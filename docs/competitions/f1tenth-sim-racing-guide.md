# Technical Guide

![F1TENTH Sim Racing](../assets/images/banners/F1TENTH Sim Racing.png)

<p align="justify">
This document describes the technical details of the competition framework for the F1TENTH Sim Racing League. It goes over the details pertaining to the simulator and devkit, as well as some important aspects of the submission system, process and evaluation. Some good-to-know tips and "best practices" are thrown asynchronously to smoothen the process and workflow for the participants.
</p>

!!! warning
    It expected that teams have sufficient background knowlege pertaining to autonomous racing (concepts, methods, and algorithms), programming languages (Python, C++, etc.) and frameworks (ROS 2), containerization (Docker) and version control (Git), etc. In order to be fair to all teams and keep the competition on schedule, extensive technical support/help cannot be provided by the organizers to any team. However, legitimate requests may be entertained at the discretion of the organizers.

!!! note
    Although AutoDRIVE Ecosystem supports many vehicles across different scales and operational design domains (ODDs), the **ONLY** vehicle allowed for this competition is **F1TENTH**. Similarly, although AutoDRIVE Ecosystem supports multiple application programming interfaces (APIs), the **ONLY** API allowed for this competition is **ROS 2**.

## 1. AutoDRIVE Simulator

<p align="justify">
AutoDRIVE Simulator (part of the larger <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a>) is an autonomy oriented tool designed to model and simulate vehicle and environment digital twins. It equally prioritizes backend physics and frontend graphics to achieve high-fidelity simulation in realtime. From a computing perspective, the simulation framework is completely modular owing to its object-oriented programming (OOP) constructs. Additionally, the simulator can take advantage of CPU multi-threading as well as GPU instancing (only if available) to efficiently parallelize various simulation objects and processes, with cross-platform support.
</p>

<p align="justify">
For the F1TENTH Sim Racing League, each team will be provided with a standardized simulation setup (in the form of a digital twin of the F1TENTH vehicle, and a digital twin of the Porto racetrack) within the high-fidelity <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a>. This would help make this competition and exploration of autonomous racing in general accessible to everyone across the globe.
</p>

### 1.1. System Requirements

<p align="justify">
  <b>Minimum Requirements:</b>
</p>
<ul class="justify-list">
  <li><b>Platform:</b> Ubuntu 20.04+, Windows 10+, macOS 10.14+ (simulator has cross-platform compatibility)</li>
  <li><b>Processor:</b> Quad-core CPU (e.g., Intel Core i5 or AMD Ryzen 5)</li>
  <li><b>Memory:</b> 8 GB RAM</li>
  <li><b>Graphics:</b> Integrated graphics or a low-end discrete GPU (e.g., NVIDIA GeForce GTX 1050) with at least 2 GB of VRAM</li>
  <li><b>Storage:</b> 10 GB free disk space (for Docker images, simulator application and data)</li>
  <li><b>Network:</b> Internet connection for pulling Docker images, and downloading updates on demand</li>
</ul>

<p align="justify">
  <b>Recommended Requirements:</b>
</p>
<ul class="justify-list">
  <li><b>Platform:</b> Ubuntu 20.04/22.04, Windows 10/11 (simulator has been extensively tested on these platforms)</li>
  <li><b>Processor:</b> Six-core CPU (e.g., Intel Core i7 or AMD Ryzen 7)</li>
  <li><b>Memory:</b> 16 GB RAM</li>
  <li><b>Graphics:</b> Mid-range discrete GPU (e.g., NVIDIA GeForce GTX 1660 or RTX 2060) with 4 GB or more VRAM</li>
  <li><b>Storage:</b> 20 GB free disk space (to accommodate multiple Docker images, additional data, and logs)</li>
  <li><b>Network:</b> Stable internet connection for pulling Docker images, and downloading updates on the fly</li>
</ul>

!!! info
    Note that the organizers will execute the competition framework on a workstation incorporating Intel Core i9 14th Gen 14900K CPU, NVIDIA GeForce RTX 4090 GPU, and 64 GB RAM (or a similar configuration). However, this machine will be simultaneously running the simulator container, screen recorder and data logger in addition to the devkit container. Kindly develop your algorithms while considering their computational requirements.

### 1.2. Graphical User Interface (GUI)

<center>
<img src="/../assets/images/documentation/f1tenth sim racing league/Simulator.png">
</center>

<p align="justify">
Apart from the visualization of autonomous vehicle(s) and their operating environments, AutoDRIVE Simulator GUI consists of a toolbar encompassing two panels for observing and interacting with key aspects of the simulator in real-time, namely <b>Menu</b> and <b>Heads-Up Display (HUD)</b>. Both the panels can be enabled or disabled using buttons provided on the toolbar, the figure above illustrates both GUI panels being enabled. The menu panel on the left hand side helps configure and control some important aspects of the simulation with just a few clicks. The HUD panel on the right hand side helps visualize prominent simulation parameters along with vehicle status and sensory data, while hosting a time-synchronized data recording functionality that can be used to export simulation data for a specific run.
</p>

#### 1.2.1. Menu Panel

<ul class="justify-list">
  <li><b>IP Address Field:</b> Input field to specify IP address for the machine running the devkit (default is 127.0.0.1, i.e., standard address for IPv4 loopback traffic).
  <li><b>Port Number Field:</b> Input field to specify port number for the machine running the devkit (default is 4567, observed to be usually unoccupied).
  <li><b>Connection Button:</b> Button to establish connection with the devkit, which acts as the server with simulator being the client (the button is disabled once the connection is established). The status of bridge connection (i.e., Connected or Disconnected) is displayed besides this button.
  <li><b>Driving Mode Button:</b> Button to toggle the driving mode of the vehicle between Manual and Autonomous (default is Manual). The selected driving mode is displayed besides this button.
  <li><b>Camera View Button:</b> Button to toggle the scene camera view between Driver’s Eye, Bird’s Eye and God’s Eye (default is Driver’s Eye). The selected view is displayed besides this button.
  <li><b>Graphics Quality Button:</b> Button to toggle the graphics quality view between Low, High and Ultra (default is Low). The selected quality is displayed besides this button.
  <li><b>Scene Light Button:</b> Button to enable/disable the environmental lighting (default is enabled).
  <li><b>Reset Button:</b> Button to reset the simulator to initial conditions.
  <li><b>Quit Button:</b> Button to quit the simulator application.
</ul>

#### 1.2.2. HUD Panel

<ul class="justify-list">
  <li><b> Simulation Time:</b> The time (HH:MM:SS) since start of the simulation. Reset button resets the simulation time.
  <li><b> Frame Rate:</b> Running average of the FPS value (Hz).
  <li><b> Driving Mode:</b> Driving mode of the ego-vehicle (Manual or Autonomous).
  <li><b> Gear:</b> Drive gear of the vehicle, either Drive (D) or Reverse (R).
  <li><b> Speed:</b> Magnitude of forward velocity of the vehicle (m/s).
  <li><b> Throttle:</b> Instantaneous throttle input of the vehicle (%).
  <li><b> Steering:</b> Instantaneous steering angle of the vehicle (rad).
  <li><b> Encoder Ticks:</b> Ticks (counts) of the rear-left and rear-right incremental encoders of the vehicle represented using a 1D array of 2 elements [left_ticks, right_ticks].
  <li><b> IPS Data:</b> Position (m) of the vehicle within the environment represented using a 1D vector [x, y, z].
  <li><b> IMU Data:</b> Orientation [x, y, z] rad, angular velocity [x, y, z] rad/s, and linear acceleration [x, y, z] m/s<sup>2</sup> of the ego-vehicle w.r.t. body frame of reference.
  <li><b> LIDAR Measurement:</b> Instantaneous ranging measurement (m) of the 270&deg FOV 2D LIDAR on the vehicle.
  <li><b> Camera Preview:</b> Instantaneous raw image from the front camera of the vehicle.
  <li><b> Race Telemetry:</b> Current elapsed lap time (s), last lap time (s), overall best lap time (s) as well as total lap count data.
  <li><b> Data Recorder:</b> Save time-synchronized simulation data for a specific simulation run.
</ul>

### 1.3. Vehicle
#### 1.3.1. Frames of Reference (TF)
#### 1.3.2. Vehicle Dynamics
#### 1.3.3. Actuator Dynamics
#### 1.3.4. Sensor Characteristics
#### 1.3.5. Variability (noise in sensor/actuator/system characteristics)
#### 1.3.6. Multiple Vehicles

### 1.4. Environment
#### 1.4.1. Size and Structure

!!! warning
    The racetrack is subject to change across different stages of the competition (i.e., practice or race) with prior notice.

#### 1.4.2. Features (straight, chicane, bifurcation, etc.)
#### 1.4.3. Obstacles (static/dynamic)
#### 1.4.4. Frame(s) of Reference (TF)

- world
    - f1tenth_1
        - front_camera
        - front_left_wheel
        - front_right_wheel
        - imu
        - ips
        - left_encoder
        - lidar
        - rear_left_wheel
        - rear_right_wheel
        - right_encoder

!!! warning
    Since racetrack is subject to change, the fixed environmental frame of reference may be different depending the racetrack.

#### 1.4.5. Custom Racetracks
#### 1.4.6. Environmental Variability (time, weather, wind, lighting, friction, etc.)


## 2. AutoDRIVE Devkit

<center>
<img src="/../assets/images/documentation/f1tenth sim racing league/Devkit.png">
</center>

<p align="justify">
AutoDRIVE Devkit (part of the larger <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a>) is a collection of application programming interfaces (APIs), human-machine interfaces (HMIs), programming languages, libraries, frameworks, packages and tools, which enables the flexible development of on-road and off-road autonomous driving algorithms, as well as smart city traffic management algorithms. It allows targeting the devised algorithms to the simulator as well as the testbed, seamlessly. It supports both local as well as distributed computing, thereby facilitating the development of both centralized and decentralized autonomy algorithms.
</p>

<p align="justify">
For the F1TENTH Sim Racing League, each team will be provided with a standardized working implementation of the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a> (in the form of ROS 2 API for the the F1TENTH digital twin within AutoDRIVE Simulator) to get started with developing their autonomy algorithms. Teams will have to develop perception, planning, and control algorithms to parse the real-time sensor data streamed from the simulator and generate control commands to be fed back to the simulated vehicle. Since the vehicle, the sensors, the simulator, and the devkit are standardized, teams must develop robust racing algorithms that can deal with the uncertainties of an unseen racetrack.
</p>

### 2.1. System Requirements

<p align="justify">
  <b>Minimum Requirements:</b>
</p>
<ul class="justify-list">
  <li><b>Platform:</b> Ubuntu 20.04, Windows 10, macOS 10.14 (simulator has cross-platform compatibility)</li>
  <li><b>Processor:</b> Dual-core CPU (e.g., Intel Core i3 or AMD Ryzen 3)</li>
  <li><b>Memory:</b> 4 GB RAM</li>
  <li><b>Graphics:</b> Integrated graphics (e.g., Intel HD Graphics) or a low-end discrete GPU (e.g., NVIDIA GeForce GT 1030)</li>
  <li><b>Storage:</b> 5 GB free disk space (for Docker images, API files, and temporary data)</li>
  <li><b>Network:</b> Internet connection for pulling and pushing Docker images, and downloading updates on demand</li>
</ul>

<p align="justify">
  <b>Recommended Requirements:</b>
</p>
<ul class="justify-list">
  <li><b>Platform:</b> Ubuntu 20.04 (devkit has been extensively tested on this platform)</li>
  <li><b>Processor:</b> Quad-core CPU (e.g., Intel Core i5 or AMD Ryzen 5)</li>
  <li><b>Memory:</b> 8 GB RAM</li>
  <li><b>Graphics:</b> Mid-range discrete GPU (e.g., NVIDIA GeForce GTX 1050 or RTX 2060) with at least 2 GB of VRAM (optional, depending on whether the development kit includes graphical components)</li>
  <li><b>Storage:</b> 10 GB free disk space (to accommodate multiple Docker images, additional data, and logs)</li>
  <li><b>Network:</b> Stable internet connection for pulling and pushing Docker images, and downloading updates on the fly</li>
</ul>

!!! info
    Note that the organizers will execute the competition framework on a workstation incorporating Intel Core i9 14th Gen 14900K CPU, NVIDIA GeForce RTX 4090 GPU, and 64 GB RAM (or a similar configuration). However, this machine will be simultaneously running the simulator container, screen recorder and data logger in addition to the devkit container. Kindly develop your algorithms while considering their computational requirements.

### 2.2. Package Structure

### 2.3. Data Streams

| TOPIC                                   | TYPE        | MESSAGE                      | ACCESS             |
|:----------------------------------------|:------------|:-----------------------------|:-------------------|
`/autodrive/f1tenth_1/best_lap_time`      | Debugging   | `std_msgs/msg/Float32`       | Restricted         |
`/autodrive/f1tenth_1/collision_count`    | Debugging   | `std_msgs/msg/Int32`         | Restricted         |
`/autodrive/f1tenth_1/front_camera`       | Sensor      | `sensor_msgs/msg/Image`      | Input              |
`/autodrive/f1tenth_1/imu`                | Sensor      | `sensor_msgs/msg/Imu`        | Input              |
`/autodrive/f1tenth_1/ips`                | Sensor      | `geometry_msgs/msg/Point`    | Input (Restricted) |
`/autodrive/f1tenth_1/lap_count`          | Debugging   | `std_msgs/msg/Int32`         | Restricted         |
`/autodrive/f1tenth_1/lap_time`           | Debugging   | `std_msgs/msg/Float32`       | Restricted         |
`/autodrive/f1tenth_1/last_lap_time`      | Debugging   | `std_msgs/msg/Float32`       | Restricted         |
`/autodrive/f1tenth_1/left_encoder`       | Sensor      | `sensor_msgs/msg/JointState` | Input              |
`/autodrive/f1tenth_1/lidar`              | Sensor      | `sensor_msgs/msg/LaserScan`  | Input              |
`/autodrive/f1tenth_1/right_encoder`      | Sensor      | `sensor_msgs/msg/JointState` | Input              |
`/autodrive/f1tenth_1/speed`              | Debugging   | `std_msgs/msg/Float32`       | Restricted         |
`/autodrive/f1tenth_1/steering`           | Sensor      | `std_msgs/msg/Float32`       | Input              |
`/autodrive/f1tenth_1/steering_command`   | Actuator    | `std_msgs/msg/Float32`       | Output             |
`/autodrive/f1tenth_1/throttle`           | Sensor      | `std_msgs/msg/Float32`       | Input              |
`/autodrive/f1tenth_1/throttle_command`   | Actuator    | `std_msgs/msg/Float32`       | Output             |
`/tf`                                     | Debugging   | `tf2_msgs/msg/TFMessage`     | Restricted         |

!!! note
    You may use the restricted topics for debugging, training AI models, etc. However, these topics should not be used during the deployment/inference stage (i.e., while autonomously racing at run-time).

## 3. Competition Submission
<p align="justify">
F1TENTH Sim Racing League is a virtual competition, which accompanies the physical F1TENTH Autonomous Racing Competition. It leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an F1TENTH racecar within a virtual racetrack. The main goal of this competition is to make autonomous racing accessible to everyone across the globe.
</p>

### 3.1. Submission Preparation

#### 3.1.1. Setup

1. Install [Docker](https://docs.docker.com/engine/install) is installed.
2. Since the Docker container is to take advantage of an NVIDIA GPU, the host machine has to be properly configured by installing the necessary NVIDIA GPU Drivers and the [NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/index.html).
3. Pull [AutoDRIVE Simulator docker image](https://hub.docker.com/repository/docker/autodriveecosystem/autodrive_f1tenth_sim) from DockerHub.
   ```bash
   docker pull autodriveecosystem/autodrive_f1tenth_sim:<TAG>
   ```
4. Pull [AutoDRIVE Devkit docker image](https://hub.docker.com/repository/docker/autodriveecosystem/autodrive_f1tenth_api) from DockerHub.
   ```bash
   docker pull autodriveecosystem/autodrive_f1tenth_api:<TAG>
   ```

#### 3.1.2. Execute

1. Enable display forwarding for simulator:
    ```bash
    xhost local:root
    ```
2. Run the simulator container at `entrypoint`:
    ```bash
    docker run --name autodrive_f1tenth_sim --rm -it --network=host --ipc=host -v /tmp/.X11-unix:/tmp.X11-umix:rw --env DISPLAY --privileged --gpus all autodriveecosystem/autodrive_f1tenth_sim
    ```
3. [OPTIONAL] Start additional bash session(s) within the simulator container (each in a new terminal window):
    ```bash
    docker exec -it autodrive_f1tenth_sim bash
    ```
4. Enable display forwarding for devkit:
    ```bash
    xhost local:root
    ```
5. Run the devkit container at `entrypoint`:
    ```bash
    docker run --name autodrive_f1tenth_api --rm -it --network=host --ipc=host -v /tmp/.X11-unix:/tmp.X11-umix:rw --env DISPLAY --privileged --gpus all autodriveecosystem/autodrive_f1tenth_api
    ```
6. [OPTIONAL] Start additional bash session(s) within the devkit container (each in a new terminal window):
    ```bash
    docker exec -it autodrive_f1tenth_api bash
    ```
7. Using the simulator GUI, configure the following:
   
   7.1 Enter the IP address of the machine running the devkit container. If both containers are running on the same machine, leave the default loopback IP.
   
   7.2 Hit the `Connection` button and note the status next to it.

   7.3 Once the connection has been established, hit the `Driving Mode` to engage the vehicle in `Autonomous` mode.

!!! tip
    In certain cases, GPUs and Docker do not work very well and can cause problems in running the simulator container. In such cases, you can download and run the simulator locally (it should be easier to access the GPU this way). You can then run only the devkit within a container. Everything else will work just fine, only that the simulator will not be running inside a container. This shouldn’t matter, since you will have to submit only the container for your algorithms (i.e., devkit) and not the simulator. We will run the containerized simulator on our side for the evaluation of all submissions.

#### 3.1.3. Develop

Teams will have to create their packages or meta-packages for autonomous racing within the devkit container **separate** from the provided `autodrive_f1tenth` package (i.e., without making any modifications to the `autodrive_f1tenth` package itself).

Please make a note of the data streams mentioned above (along with their access restrictions) to help with the development process.

!!! tip
    If working with containers is overwhelming, you can download and run the devkit locally while developing and testing your autonomous racing algorithms. You can then containerize the finalized algorithms, test them one last time, and push them to the container registry.

#### 3.1.4. Submit

1. Run the image you created in the previous step inside a container:
```bash
xhost local:root
docker run --name autodrive_f1tenth_api --rm -it --network=host --ipc=host -v /tmp/.X11-unix:/tmp.X11-umix:rw --env DISPLAY --privileged --gpus all autodriveecosystem/autodrive_f1tenth_api:<TAG>
```
2. In a new terminal window, list all containers and make a note of the desired `CONTAINER ID`:
```bash
docker ps -a
```
3. Commit changes to DockerHub:
```bash
docker commit -m "<Sample commit message>" -a "<USERNAME>" <CONTAINER ID> <username>/<image_name>:<TAG>
```
4. Login to DockerHub:
```bash
docker login
```
5. Push the container to DockerHub, once done, you should be able to see your repository on DockerHub:
```bash
docker push <username>/<image_name>:<TAG>
```
6. Submit the link to your team's DockerHub repository via a secure Google Form.

#### 3.1.5. Troubleshooting

1. To access the container while it is running, execute the following command in a new terminal window to start a new bash session inside the container:
```bash
docker exec -it <CONTAINER NAME> bash
```
2. To exit the bash session(s), simply execute:
```bash
exit
```
3. To kill the container, execute the following command:
```bash
docker kill <CONTAINER NAME>
```
4. To remove the container, simply execute:
```bash
docker rm <CONTAINER NAME>
```
5. Running or caching multiple docker images, containers, volumes, and networks can quickly consume a lot of disk space. Hence, it is always a good idea to frequently check Docker disk utilization:
```bash
docker system df
```
6. To avoid utilizing a lot of disk space, it is a good idea to frequently purge docker resources such as images, containers, volumes, and networks that are unused or dangling (i.e. not tagged or associated with a container). There are several ways with many options to achieve this, please refer to appropriate documentation. The easiest way (but a potentially dangerous one) is to use a single command to clean up all the docker resources (dangling or otherwise):
```bash
docker system prune -a
```

!!! tip
    For additional help on containerization, visit [docker.com](https://www.docker.com). Specifically, the [documentation](https://docs.docker.com/?_gl=1*1xv75eh*_gcl_au*MTA2MDkwMzgxMC4xNzI0NzEzMDY3*_ga*NjgyMTY2Njc2LjE2OTc0MjMwNzQ.*_ga_XJWPQMJYHQ*MTcyNDcxMzA3Mi4zOS4xLjE3MjQ3MTMyODAuNTMuMC4w) and [get started](https://www.docker.com/get-started) pages would be of significant help for the beginners. Also, the [cheatsheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf?_gl=1*l3zebg*_gcl_au*MTA2MDkwMzgxMC4xNzI0NzEzMDY3*_ga*NjgyMTY2Njc2LjE2OTc0MjMwNzQ.*_ga_XJWPQMJYHQ*MTcyNDcxMzA3Mi4zOS4xLjE3MjQ3MTM1NzIuOS4wLjA.) could be a very handy reference for all important Docker CLI commands.

### 3.2. Evaluation Architecture

figure with explanation

### 3.3. Execution Sequence

How will the evaluation process of a team's submission be conducted?

### 3.4. Scoring & Evaluation

Exact scoring, penalties, ranking, tie-breaker, etc. - quantitative details

### 4. Citation

We encourage you to read and cite the following papers if you use any part of this project for your research:

#### [AutoDRIVE: A Comprehensive, Flexible and Integrated Digital Twin Ecosystem for Enhancing Autonomous Driving Research and Education](https://arxiv.org/abs/2212.05241)
```bibtex
@article{AutoDRIVE-Ecosystem-2023,
author = {Samak, Tanmay and Samak, Chinmay and Kandhasamy, Sivanathan and Krovi, Venkat and Xie, Ming},
title = {AutoDRIVE: A Comprehensive, Flexible and Integrated Digital Twin Ecosystem for Autonomous Driving Research &amp; Education},
journal = {Robotics},
volume = {12},
year = {2023},
number = {3},
article-number = {77},
url = {https://www.mdpi.com/2218-6581/12/3/77},
issn = {2218-6581},
doi = {10.3390/robotics12030077}
}
```
This work has been published in **MDPI Robotics.** The open-access publication can be found on [MDPI](https://doi.org/10.3390/robotics12030077).

#### [AutoDRIVE Simulator: A Simulator for Scaled Autonomous Vehicle Research and Education](https://arxiv.org/abs/2103.10030)
```bibtex
@inproceedings{AutoDRIVE-Simulator-2021,
author = {Samak, Tanmay Vilas and Samak, Chinmay Vilas and Xie, Ming},
title = {AutoDRIVE Simulator: A Simulator for Scaled Autonomous Vehicle Research and Education},
year = {2021},
isbn = {9781450390453},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3483845.3483846},
doi = {10.1145/3483845.3483846},
booktitle = {2021 2nd International Conference on Control, Robotics and Intelligent System},
pages = {1–5},
numpages = {5},
location = {Qingdao, China},
series = {CCRIS'21}
}
```
This work has been published at **2021 International Conference on Control, Robotics and Intelligent System (CCRIS).** The publication can be found on [ACM Digital Library](https://dl.acm.org/doi/abs/10.1145/3483845.3483846).
