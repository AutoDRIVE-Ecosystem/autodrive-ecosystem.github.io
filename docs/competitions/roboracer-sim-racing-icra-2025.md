# RoboRacer Sim Racing League @ ICRA 2025

![RoboRacer Sim Racing League @ ICRA 2025](../assets/images/banners/RoboRacer Sim Racing @ ICRA 2025.png)

## About

<p align="justify">
<b>RoboRacer Autonomous Racing</b> is a semi-regular competition organized by an international community of researchers, engineers, and autonomous systems enthusiasts. The teams participating in the <b>24th RoboRacer Autonomous Racing Competition</b> at <a href="https://2025.ieee-icra.org">ICRA 2025</a> will write software for a 1:10 scaled autonomous racecar to fulfill the objectives of the competition: <b><i>drive fast but don’t crash!</i></b>
</p>

<p align="justify">
This time, we are organizing the third <b>RoboRacer Sim Racing League</b>, which leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an RoboRacer racecar within a virtual racetrack. Please see the accompanying video for a glimpse of the RoboRacer digital twins in action.
</p>

<center>
<div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/9; width: 100% !important;" src="https://www.youtube.com/embed/Rq7Wwcwn1uk?si=ngvop2-SfJJOIjWJ" title="Digital Twin of RoboRacer in AutoDRIVE Simulator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
</center>

<p align="justify">
The main focus of the Sim Racing League is a virtual competition with simulated cars and environments, which is accessible to everyone across the globe. For the <a href="https://2025.ieee-icra.org">ICRA 2025</a> competition, each team will be provided with a standardized simulation setup (in the form of a digital twin of the RoboRacer vehicle, and a digital twin of the Porto racetrack) within the high-fidelity <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a>. Additionally, teams will also be provided with a working implementation of the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a> to get started with developing their autonomy algorithms. Teams will have to develop perception, planning, and control algorithms to parse the real-time sensor data streamed from the simulator and generate control commands to be fed back to the simulated vehicle.
</p>

<p align="justify">
The competition will take place in 2 stages:
</p>

<ul class="justify-list">
  <li><b>Qualification Race:</b> Teams will demonstrate their ability to complete multiple laps around the practice track without colliding with the track bounds at run time.</li>
  <li><b>Time-Attack Race:</b> Teams will compete against the clock, on a previously unseen racetrack, to secure a position on the leaderboard.</li>
</ul>

<p align="justify">
Since the vehicle, the sensors, the simulator, and the devkit are standardized, teams must develop robust racing algorithms that can deal with the uncertainties of an unseen racetrack.
</p>

!!! Tip
    If you are interested in autonomously racing physical RoboRacer vehicles, please check out the website for [24th RoboRacer Autonomous Racing Competition](https://icra2025-race.roboracer.ai), which will be held in person at <a href="https://2025.ieee-icra.org">ICRA 2025</a>. You can always register and compete in both physical and virtual competitions!

## Organizers

| <img src="/../assets/images/people/Rahul Mangharam.png" width="125"> | <img src="/../assets/images/people/Venkat Krovi.png" width="125"> | <img src="/../assets/images/people/Johannes Betz.png" width="125"> |
|:------------------:|:-------------------:|:-------------------:|
| [**Dr. Rahul Mangharam**](mailto:rahulm@seas.upenn.edu) | [**Dr. Venkat Krovi**](mailto:vkrovi@clemson.edu) | [**Dr. Johannes Betz**](mailto:johannes.betz@tum.de) |
| <img src="/../assets/images/people/Chinmay Samak.png" width="125"> | <img src="/../assets/images/people/Tanmay Samak.png" width="125"> | <img src="/../assets/images/people/Ahmad Amine.png" width="125"> |
| [**Chinmay Samak**](mailto:csamak@clemson.edu) | [**Tanmay Samak**](mailto:tsamak@clemson.edu) | [**Ahmad Amine**](mailto:aminea@seas.upenn.edu) |

## Timeline

!!! warning
    Timeline is subject to change. Please keep checking this page for any updates.

| DATE                              | EVENT                          |
|:----------------------------------|:-------------------------------|
| Feb 20, 2025                      | Registration Opens             |
| Apr 15, 2025                      | Registration Closes            |
| Apr 16, 2025 (5:30 – 6:30 PM EST) | Online Orientation             |
| May 03 – May 04, 2025             | Qualification Round            |
| May 05, 2025                      | Qualification Results Declared |
| May 08, 2025                      | Competition Track Released     |
| May 10 – May 11, 2025             | Final Race                     |
| May 12, 2025                      | Competition Results Declared   |

<p align="justify">
Following is a brief summary of each event:
</p>

<ul class="justify-list">
  <li><b>Registration:</b> Interested teams will register for the Sim Racing League.</li>
  <li><b>Online Orientation:</b> Organizers will explain the competition rules and guidelines, and demonstrate how to use the simulation framework.</li>
  <li><b>Qualification Round:</b> Teams will demonstrate successful completion of 10 laps around the practice track provided ahead of time.</li>
  <li><b>Qualification Results Declared:</b> Standings of all the qualified teams will be released.</li>
  <li><b>Competition Track Released:</b> Organizers will release the actual "competition track", which will be used for the final race. This track may be replicated in the physical race as well.</li>
  <li><b>Final Race:</b> Organizers will collect containerized algorithms from each team and connect them with the containerized simulator. Performance metrics of each team will be recorded.</li>
  <li><b>Competition Results Declared:</b> Standings of all the teams for the final race will be released.</li>
</ul>

!!! info
    The RoboRacer Sim Racing League will be held approximately 1 week ahead of <a href="https://2025.ieee-icra.org">ICRA 2025</a> and the performance metrics will be made available to the teams. Discussions are underway with the ICRA organizing team to allow teams to analyze and present their approach/results in a short (~10 min) presentation in a special session at <a href="https://2025.ieee-icra.org">ICRA 2025</a>.

## Resources

<img src="/../assets/images/logos/AutoDRIVE Logo.png" width="24.5%" align="left"/>
<p align="justify">
<a href="https://autodrive-ecosystem.github.io/">AutoDRIVE</a> is envisioned to be an open, comprehensive, flexible and integrated cyber-physical ecosystem for enhancing autonomous driving research and education. It bridges the gap between software simulation and hardware deployment by providing the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a> and <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Testbed">AutoDRIVE Testbed</a>, a well-suited duo for real2sim and sim2real transfer targeting vehicles and environments of varying scales and operational design domains. It also offers <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a>, a developer's kit for rapid and flexible development of autonomy algorithms using a variety of programming languages and software frameworks. For the Sim Racing League, teams will develop their autonomous racing algorithms using the AutoDRIVE Devkit to interface with the AutoDRIVE Simulator in real-time.
</p>

<img src="/../assets/images/logos/RoboRacer Logo.png" width="24.5%" align="right"/>
<p align="justify">
<a href="https://roboracer.ai">RoboRacer</a> is an <a href="https://roboracer.ai/about.html">international community</a> of researchers, engineers, and autonomous systems enthusiasts. It is centered around the idea of converting a 1:10 scale RC car into an autonomous vehicle for research and education; check out the <a href="https://roboracer.ai/build.html">documentation</a> to build your own RoboRacer autonomous racecar. Additionally, if you are new to the field of autonomous racing, you can refer to the complete <a href="https://roboracer.ai/learn.html">course material</a>, which is open sourced. If you already have some experience with autonomous racing, feel free to delve deeper into the <a href="https://roboracer.ai/research.html">research</a> enabled by RoboRacer. Lastly, you can also check out the physical <a href="https://roboracer.ai/race.html">RoboRacer races</a> that are being organized all around the world. For the Sim Racing League, teams will not require a physical RoboRacer vehicle; however, the learning resources can certainly be useful to get your autonomous racing fundamentals right!
</p>

<p align="justify">
We recommend all the teams interested in participating in the RoboRacer Sim Racing League to get accustomed with the competition. Following are a few resources to get you started:
</p>

<div class="grid cards" markdown>

-   :material-file-document:{ .lg .middle } __Competition Documents__

    ---

    Learn about the competition rules and technical aspects of the framework.

    [:material-open-in-new: **Competition Rules**](../roboracer-sim-racing-rules)

    [:material-open-in-new: **Technical Guide**](../roboracer-sim-racing-guide)

-   :material-docker:{ .lg .middle } __Docker Containers__

    ---

    Download base container images for the competition and start developing your algorithms.

    :material-open-in-new: **AutoDRIVE Simulator:** `explore` | `practice` | `compete`

    :material-open-in-new: **AutoDRIVE Devkit:** `explore` | `practice` | `compete`

-   :material-monitor:{ .lg .middle } __Local Resources__

    ---

    Get started with the competition framework locally, and worry about containerization later. 

    **AutoDRIVE Simulator:**
    
    `explore`&nbsp;&nbsp;&nbsp; :simple-linux: Linux | :material-microsoft: Windows | :simple-apple: macOS

    `practice`&nbsp; :simple-linux: Linux | :material-microsoft: Windows | :simple-apple: macOS

    `compete`&nbsp;&nbsp;&nbsp; :simple-linux: Linux | :material-microsoft: Windows | :simple-apple: macOS

    **AutoDRIVE Devkit:**
    
    :simple-ros: ROS 2

-   :octicons-link-16:{ .lg .middle } __Quick Links__

    ---

    Links to be kept at your fingertips, for a smooth ride throughout the competition.

    **Schedule:** [:material-calendar-clock: Timeline](#timeline)

    **Registration:** [:material-file-document-edit: Form](https://forms.gle/zjj5dLDajUhnuTdL9)
    
    **Orientation:** :fontawesome-solid-video: Zoom | :octicons-video-16: Recording | :material-projector-screen-outline: Slides

    **Communication:** [:material-slack: Slack](https://join.slack.com/t/autodrive-ecosystem/shared_invite/zt-2oeg2hce8-0JvasvnBM1M_wUdDTWRuKw)

    **Submission:** [:material-file-document-edit: Phase 1]() | [:material-file-document-edit: Phase 2]()

    **Results:** [:fontawesome-solid-trophy: Phase 1]() | [:fontawesome-solid-trophy: Phase 2]()
</div>

!!! question
    You can post general questions on the [:material-slack: AutoDRIVE Slack](https://join.slack.com/t/autodrive-ecosystem/shared_invite/zt-2oeg2hce8-0JvasvnBM1M_wUdDTWRuKw) workspace; this is the preferred modality. Technical questions can be also posted as [:material-github: GitHub Issues](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/issues) or [:material-github: GitHub Discussions](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/discussions). For any other questions or concerns that cannot be posted publicly, please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu).

## Registration

<p align="justify">
This competition is open to everyone around the world - students, researchers, hobbyists, professionals, or anyone else who is interested. A team can consist of multiple teammates. Teams with only one person are also allowed.
</p>

<center>
[:material-file-document-edit: Registration Form](https://forms.gle/zjj5dLDajUhnuTdL9){.md-button}
</center>

<p align="justify">
Registration for the Sim Racing League is free of cost and separate from the Physical Racing League and the conference registrations themselves. The above form signs you up only for the Sim Racing League, and for its orientation and information sessions. Although you can participate in the Sim Racing League without attending the conference, we strongly encourage all competition participants to attend the conference in person. This will help you connect with the broader AutoDRIVE and RoboRacer communities, and you can also witness/participate in the physical RoboRacer autonomous racing competition!
</p>

<p align="justify">
Registered teams are added to the following table:
</p>

| SR. NO. | TEAM NAME                 | TEAM MEMBERS                  | ORGANIZATION                              |
|:--------|:--------------------------|:------------------------------|:------------------------------------------|
| 01      | fsociety                  | Ritesh Gole<br/>Kartikeya Gupta<br/>Raj Shah<br/>Goutham Jyothilal | Personal |

!!! note
    The above table will be updated with newly registered teams within a few days of registration. Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you do not see your team entry for more than 7 days after registering.

## Submission

<p align="justify">
Use the secure form below to make your team's submission for Phase 1 (Qualification Round) of the RoboRacer Sim Racing League. Please fill in your team's name and add the link to your team's DockerHub repository containing the autonomous racing stack. If you are using a private repository, make sure to add <a href="https://hub.docker.com/u/autodriveecosystem">autodriveecosystem</a> as a <a href="https://docs.docker.com/docker-hub/repos/access">collaborator to your repository</a>.
</p>

<center>
[:material-file-document-edit: Phase 1 Submission Form](){.md-button}
</center>

!!! warning
    Phase 1 submission window will close on May 03, 2025 (anywhere on earth). Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you have any questions.

<p align="justify">
Use the secure form below to make your team's submission for Phase 2 (Final Race) of the RoboRacer Sim Racing League. Please fill in your team's name and add the link to your team's DockerHub repository containing the autonomous racing stack. If you are using a private repository, make sure to add <a href="https://hub.docker.com/u/autodriveecosystem">autodriveecosystem</a> as a <a href="https://docs.docker.com/docker-hub/repos/access">collaborator to your repository</a>.
</p>

<center>
[:material-file-document-edit: Phase 2 Submission Form](){.md-button}
</center>

!!! warning
    Phase 2 submission window will close on May 10, 2025 (anywhere on earth). Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you have any questions.

## Results

**Phase 1: Qualification**

<p align="justify">
To be announced on May 05, 2025.
</p>

**Phase 2: Competition**

<p align="justify">
To be announced on May 12, 2025.
</p>