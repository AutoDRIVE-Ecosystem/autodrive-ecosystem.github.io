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
  <li>Platform: Ubuntu, Windows, macOS (simulator has cross-platform compatibility)</li>
  <li>Processor: Quad-core CPU (e.g., Intel Core i5 or AMD Ryzen 5)</li>
  <li>Memory: 8 GB RAM</li>
  <li>Graphics: Integrated graphics or a low-end discrete GPU (e.g., NVIDIA GeForce GTX 1050) with at least 2 GB of VRAM</li>
  <li>Storage: 10 GB free disk space (for Docker images, simulator application and data)</li>
  <li>Network: Internet connection for pulling Docker images, and downloading updates</li>
</ul>

<p align="justify">
  <b>Recommended Requirements:</b>
</p>
<ul class="justify-list">
  <li>Platform: Ubuntu, Windows (simulator has been extensively tested on these platforms)</li>
  <li>Processor: Six-core CPU (e.g., Intel Core i7 or AMD Ryzen 7)</li>
  <li>Memory: 16 GB RAM</li>
  <li>Graphics: Mid-range discrete GPU (e.g., NVIDIA GeForce GTX 1660 or RTX 2060) with 4 GB or more VRAM</li>
  <li>Storage: 20 GB free disk space (to accommodate multiple Docker images, additional data, and logs)</li>
  <li>Network: Stable internet connection for pulling Docker images, and downloading updates</li>
</ul>

!!! info
    Note that the organizers will execute the competition framework on a workstation incorporating Intel Core i9 14th Gen 14900K CPU, NVIDIA GeForce RTX 4090 GPU, and 64 GB RAM (or a similar configuration). However, this machine will be simultaneously running the simulator container, screen recorder and data logger in addition to the devkit container. Kindly develop your algorithms while considering their computational requirements.

### 1.2. Graphical User Interface (GUI)

<center>
<img src="/../assets/images/AutoDRIVE-SImulator.png">
</center>

<p align="justify">
Apart from the visualization of autonomous vehicle(s) and their operating environments, AutoDRIVE Simulator GUI consists of a toolbar encompassing two panels for observing and interacting with key aspects of the simulator in real-time, namely <b>Menu</b> and <b>Heads-Up Display (HUD)</b>. Both the panels can be enabled or disabled using buttons provided on the toolbar, the figure above illustrates both GUI panels being enabled. The menu panel on the left hand side helps configure and control some important aspects of the simulation with just a few clicks. The HUD panel on the right hand side helps visualize prominent simulation parameters along with vehicle status and sensory data, while hosting a time-synchronized data recording functionality that can be used to export vehicle as well as infrastructure data for a specific run.
</p>

#### 1.2.1 Menu Panel

<ul class="justify-list">
  <li><b>IP Address Field:</b> Input field to specify IP address for the communication bridge (default is 127.0.0.1, i.e. standard address for IPv4 loopback traffic).
  <li><b>Port Number Field:</b> Input field to specify port number for the communication bridge (default is 4567).
  <li><b>Connection Button:</b> Button to establish connection with the server (the button is disabled once the connection is established). The status of bridge connection (i.e. Connected or Disconnected) is displayed besides this button.
  <li><b>Driving Mode Button:</b> Button to toggle the driving mode of the vehicle between Manual and Autonomous (default is Manual). The selected driving mode is displayed besides this button.
  <li><b>Camera View Button:</b> Button to toggle the scene camera view between Driver’s Eye, Bird’s Eye and God’s Eye (default is Driver’s Eye). The selected view is displayed besides this button.
  <li><b>Graphics Quality Button:</b> Button to toggle the graphics quality view between Low, High and Ultra (default is Low). The selected quality is displayed besides this button.
  <li><b>Scene Light Button:</b> Button to enable/disable the scene light (default is enabled).
  <li><b>Reset Button:</b> Button to reset the simulator to initial conditions.
  <li><b>Quit Button:</b> Button to quit the simulator application.
</ul>

#### 1.2.2 HUD Panel

<ul class="justify-list">
  <li><b> Simulation Time:</b> The time (HH:MM:SS) since start of the simulation. Reset button resets the simulation time.
  <li><b> Frame Rate:</b> Running average of the FPS value (Hz).
  <li><b> Driving Mode:</b> Driving mode of the ego-vehicle (Manual or Autonomous).
  <li><b> Gear:</b> Drive direction of the vehicle; either Drive (D) or Reverse (R).
  <li><b> Speed:</b> Magnitude of forward velocity of the vehicle (m/s).
  <li><b> Throttle:</b> Instantaneous throttle input of the vehicle (%).
  <li><b> Steering:</b> Instantaneous steering angle of the vehicle (rad).
  <li><b> Encoder Ticks:</b> Ticks (counts) of the left and right incremental encoders of the vehicle represented using a 1D array of 2 elements [left_ticks, right_ticks].
  <li><b> IPS Data:</b> Position(m)ofvehiclewithinthemaprepresented using a vector [x, y, z].
  <li><b> IMU Data:</b> Orientation [x, y, z] rad, angular velocity [x, y, z] rad/s, and linear acceleration [x, y, z] m/s2 of the ego-vehicle about its local axes.
  <li><b> LIDAR Measurement:</b> Instantaneous ranging measurement (m) of the LIDAR on the vehicle.
  <li><b> Camera Preview:</b> Instantaneous raw image from the front camera of the vehicle.
  <li><b> Data Recorder:</b> Save time-synchronized vehicle as well as infrastructure data for a specific simulation run.
</ul>

### 1.3. Vehicle
#### 1.3.1 Frames of Reference (TF)
#### 1.3.2 Vehicle Dynamics
#### 1.3.3 Actuator Dynamics
#### 1.3.4 Sensor Characteristics
#### 1.3.5 Variability (noise in sensor/actuator/system characteristics)
#### 1.3.6 Multiple Vehicles

### 1.4. Environment
#### 1.4.1 Size and Structure
#### 1.4.2 Features (straight, chicane, bifurcation, etc.)
#### 1.4.3 Obstacles (static/dynamic)
#### 1.4.4 Frame(s) of Reference (TF)
#### 1.4.5 Custom Racetracks
#### 1.4.6 Environmental Variability (time, weather, wind, lighting, friction, etc.)


## 2. AutoDRIVE Devkit

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
  <li>Platform: Ubuntu 20.04, Windows 10, macOS 10.14 (simulator has cross-platform compatibility)</li>
  <li>Processor: Dual-core CPU (e.g., Intel Core i3 or AMD Ryzen 3)</li>
  <li>Memory: 4 GB RAM</li>
  <li>Graphics: Integrated graphics (e.g., Intel HD Graphics) or a low-end discrete GPU (e.g., NVIDIA GeForce GT 1030)</li>
  <li>Storage: 5 GB free disk space (for Docker images, API files, and temporary data)</li>
  <li>Network: Internet connection for pulling and pushing Docker images, and downloading updates</li>
</ul>

<p align="justify">
  <b>Recommended Requirements:</b>
</p>
<ul class="justify-list">
  <li>Platform: Ubuntu 20.04 (devkit has been extensively tested on this platform)</li>
  <li>Processor: Quad-core CPU (e.g., Intel Core i5 or AMD Ryzen 5)</li>
  <li>Memory: 8 GB RAM</li>
  <li>Graphics: Mid-range discrete GPU (e.g., NVIDIA GeForce GTX 1050 or RTX 2060) with at least 2 GB of VRAM (optional, depending on whether the development kit includes graphical components)</li>
  <li>Storage: 10 GB free disk space (to accommodate multiple Docker images, additional data, and logs)</li>
  <li>Network: Stable internet connection for pulling and pushing Docker images, and downloading updates</li>
</ul>

!!! info
    Note that the organizers will execute the competition framework on a workstation incorporating Intel Core i9 14th Gen 14900K CPU, NVIDIA GeForce RTX 4090 GPU, and 64 GB RAM (or a similar configuration). However, this machine will be simultaneously running the simulator container, screen recorder and data logger in addition to the devkit container. Kindly develop your algorithms while considering their computational requirements.

### 2.2. Package Structure

### 2.3. Data Streams

Topic | Message | Access Type | Description

- Input topics: sensor topics
- Output topics: actuator topics
- Restricted topics: debugging topics

!!! note
    You may use the restricted topics for debugging, to train AI models, etc. However, these topics should not be used during the deployment/inference stage (i.e. while autonomously racing at run-time).

## 3. Competition Submission
<p align="justify">
F1TENTH Sim Racing League is a virtual competition, which accompanies the physical F1TENTH Autonomous Racing Competition. It leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an F1TENTH racecar within a virtual racetrack. The main goal of this competition is to make autonomous racing accessible to everyone across the globe.
</p>

### 3.1. Submission Preparation

Setup - download and install dependencies, simulator and devkit
Usage - run the simulator, run the devkit, hit connection button, hit driving mode button.

!!! tip
    In certain cases, GPUs and Docker do not work very well and can cause problems in running the simulator container. In such cases, you can download and run the simulator locally (it should be easier to access the GPU this way). You can then run only the devkit within a container. Everything else will work just fine, only that the simulator will not be running inside a container. This shouldn’t matter, since you will have to submit only the container for your algorithms (i.e. devkit) and not the simulator. We will run the containerized simulator on our side for the evaluation of all submissions.

!!! tip
    If working with containers is overwhelming, you can download and run the devkit locally while developing and testing your autonomous racing algorithms. You can then containerize the finalized algorithms, test them one last time, and push them to the container registry.

### 3.2. Evaluation Architecture

figure with explaination

### 3.3. Execution Sequence

How will the evaluation process of a team's submission conducted

### 3.4. Scoring & Evaluation

Exact scoring, penalties, ranking, tie-breaker, etc. quantitative details