# ABOUT

<img src="/../assets/images/banners/AutoDRIVE Banner.png">

<p align="center">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fautodrive-ecosystem.github.io&count_bg=%23DA4848&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Hits&edge_flat=false"/>
  <img src="https://komarev.com/ghpvc/?username=AutoDRIVE-Ecosystem&label=Views&color=brightgreen">
  <img src="https://img.shields.io/github/followers/AutoDRIVE-Ecosystem?style=flat&label=Followers&color=blueviolet">
  <img src="https://badgen.net/github/stars/Tinker-Twins/AutoDRIVE?label=Stars&color=blue">
  <img src="https://badgen.net/github/forks/Tinker-Twins/AutoDRIVE?label=Forks&color=orange">
  <img alt='GitHub Clones' src='https://img.shields.io/badge/dynamic/json?color=blue&label=Clones&query=count&url=https://gist.githubusercontent.com/Tinker-Twins/e2855ef0fa018279b206045be92424cb/raw/clone.json'>
  <img src="https://img.shields.io/github/downloads/Tinker-Twins/AutoDRIVE/total?color=yellow&label=Downloads">
  <!---img src="https://img.shields.io/github/stars/AutoDRIVE-Ecosystem?label=Stars&color=blue"-->
</p>

## Project Overview

![](../assets/images/AutoDRIVE Overview - Light.png#only-light)
![](../assets/images/AutoDRIVE Overview - Dark.png#only-dark)

<p align="justify">
AutoDRIVE is envisioned to be an integrated platform for autonomous driving research and education. It bridges the gap between software simulation and hardware deployment by providing the AutoDRIVE Simulator and AutoDRIVE Testbed, a well-suited duo for sim2real applications. It also offers AutoDRIVE Devkit, a developer's kit for rapid and flexible development of autonomy algorithms. Although the platform is primarily targeted towards autonomous driving, it also supports the development of smart-city solutions for managing the traffic flow.
</p>

## AutoDRIVE Testbed

| <img src="/../assets/images/Testbed-Vehicle.png" width="500"> | <img src="/../assets/images/Testbed-Infrastructure.png" width="500"> |
|:--------:|:-------------:|
| Vehicle | Infrastructure |

<p align="justify">
AutoDRIVE Testbed is the hardware setup comprising of a scaled vehicle model (called Nigel) and a modular infrastructure development kit. The vehicle is equipped with a comprehensive sensor suite for redundant perception, a set of actuators for constrained motion control and a fully functional lighting system for illumination and signaling. It can be teleoperated (in manual mode) or self-driven (in autonomous mode). The infrastructure development kit comprises of various environment modules along with active and passive traffic elements.
</p>

- **Source Branch:** [AutoDRIVE Testbed](https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Testbed)
- **Latest Release:** [AutoDRIVE Testbed 0.2.0](https://github.com/Tinker-Twins/AutoDRIVE/releases/tag/Testbed-0.2.0)
- **Upcoming Release:** AutoDRIVE Testbed 0.3.0 is currently under development.
- **Nigel (AS) Build Documentation:** [Assembly Guide](https://github.com/Tinker-Twins/AutoDRIVE/blob/AutoDRIVE-Testbed/Documents/Nigel%20-%20Assembly%20Guide.pdf), [Assembly Animation](https://youtu.be/0wQqMQN9PJY?feature=shared) and [BOM](https://github.com/Tinker-Twins/AutoDRIVE/blob/AutoDRIVE-Testbed/Documents/BOM.pdf)
- **Nigel (4WD4WS) Build Documentation:** [Assembly Guide](https://github.com/Tinker-Twins/AutoDRIVE/blob/AutoDRIVE-Testbed/Documents/Nigel%204WD4WS%20-%20Assembly%20Guide.pdf), [Assembly Animation](https://youtu.be/PsjJeoElGiI?feature=shared) and [BOM](https://github.com/Tinker-Twins/AutoDRIVE/blob/AutoDRIVE-Testbed/Documents/BOM.pdf)

## AutoDRIVE Simulator

| <img src="/../assets/images/Simulator-Vehicle.png" width="500"> | <img src="/../assets/images/Simulator-Infrastructure.png" width="500"> |
|:--------:|:-------------:|
| Vehicle | Infrastructure |

<p align="justify">
AutoDRIVE Simulator is the digital twin of the AutoDRIVE Testbed, which enables the users to virtually prototype their algorithms either due to hardware limitations or as a part of the reiterative development cycle. It is developed atop the Unity game engine and offers a WebSocket interface for bilateral communication with the autonomy algorithms developed independently using the AutoDRIVE Devkit. The standalone simulator application is targeted at Full HD resolution (1920x1080p) with cross-platform support (Windows, macOS and Linux). It is a light-weight software application that utilizes system resources wisely. This enables deployment of the simulator application and autonomy algorithms on a single machine; nonetheless, distributed computing is also supported.
</p>

- **Source Branch:** [AutoDRIVE Simulator](https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator)
- **Latest Release:** [AutoDRIVE Simulator 0.3.0](https://github.com/Tinker-Twins/AutoDRIVE/releases/tag/Simulator-0.3.0)
- **Upcoming Release:** AutoDRIVE Simulator 0.4.0 is currently under development.

## AutoDRIVE Devkit

| <img src="/../assets/images/ADSS.png" width="500"> | <img src="/../assets/images/SCSS.png" width="500"> |
|:--------:|:-------------:|
| ADSS Toolkit | SCSS Toolkit |

<p align="justify">
AutoDRIVE Devkit is a developer's kit that enables the users to exploit AutoDRIVE Simulator or AutoDRIVE Testbed for rapid and flexible development of autonomy algorithms pertaining to autonomous driving (using ADSS Toolkit) as well as smart city management (using SCSS Toolkit). It supports local (decentralized) as well as distributed (centralized) computing and is compatible with Robot Operating System (ROS), while also offering a direct scripting support for Python and C++.
</p>

- **Source Branch:** [AutoDRIVE Devkit](https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit)
- **Latest Release:** [AutoDRIVE Devkit 0.3.0](https://github.com/Tinker-Twins/AutoDRIVE/releases/tag/Devkit-0.3.0)
- **Upcoming Release:** AutoDRIVE Devkit 0.4.0 is currently under development.

## Awards and Recognition
- [Finalist Award](https://sites.google.com/site/asmemrc/design-competition-showcase/2023-finalists#h.k763k3hc2lfu) for project "Nigel: A Mechatronically Redundant and Reconfigurable Scaled Autonomous Vehicle of AutoDRIVE Ecosystem" at ASME Student Mechanism and Robot Design Competition (SMRDC) 2023
- [Best Paper Award](http://ccris2023.net/ccris2021.html) for paper "AutoDRIVE Simulator: A Simulator for Scaled Autonomous Vehicle Research and Education" at CCRIS 2021
- [Best Project Award](https://www.youtube.com/watch?v=VUo4UFiTnd4&t=4048s) for "AutoDRIVE – An Integrated Platform for Autonomous Driving Research and Education" at National Level IEEE Project Competition 2021
- [Best Project Award](https://youtu.be/2FByDOkDxMc?t=1892) for "AutoDRIVE – An Integrated Platform for Autonomous Driving Research and Education" at SRMIST Mechatronics Department 2021
- [Gold Medal](https://arxiv.org/abs/2211.08475) for paper "AutoDRIVE – An Integrated Platform for Autonomous Driving Research and Education" at SRMIST Research Day 2021
- [Lightning Talk](https://vimeo.com/480566576) of "AutoDRIVE Simulator: A Simulator for Scaled Autonomous Vehicle Research and Education" at ROS World 2020
- [India Connect @ NTU Research Fellowship](https://arxiv.org/abs/2211.07022v2) 2020 for "AutoDRIVE Simulator"

## Resources

### Highlights

We encourage you to take a look at the following quick highlights to keep up with the recent advances in AutoDRIVE Ecosystem.

|                    |
|:------------------:|
| [<img src="/../assets/images/AutoDRIVE-Ecosystem-Pitch-Video.png">](https://youtu.be/t0CgNR_LgrQ) |
| [AutoDRIVE Ecosystem Pitch Video](https://youtu.be/t0CgNR_LgrQ) |
|                    |

|                    |                     |
|:------------------:|:-------------------:|
| [<img src="/../assets/images/AutoDRIVE-Simulator-Pitch-Video.png" width="500">](https://youtu.be/i7R79jwnqlg) | [<img src="/../assets/images/AutoDRIVE-Testbed-Pitch-Video.png" width="500">](https://youtu.be/YFQzyfXV6Rw) |
| [AutoDRIVE Simulator Pitch Video](https://youtu.be/i7R79jwnqlg) | [AutoDRIVE Testbed Pitch Video](https://youtu.be/YFQzyfXV6Rw) |
| [<img src="/../assets/images/Nigel-4WD4WS-Feature-Video.png" width="500">](https://youtu.be/UVIShZuZmpg) | [<img src="/../assets/images/F1TENTH-in-AutoDRIVE-Simulator.png" width="500">](https://youtu.be/Rq7Wwcwn1uk) |
| [Nigel 4WD4WS Feature Video](https://youtu.be/UVIShZuZmpg) | [F1TENTH in AutoDRIVE Simulator](https://youtu.be/Rq7Wwcwn1uk) |
| [<img src="/../assets/images/OpenCAV-in-AutoDRIVE-Simulator.png" width="500">](https://youtu.be/YIZz_8rLgZQ) | [<img src="/../assets/images/RZR-in-AutoDRIVE-Simulator.png" width="500">](https://youtu.be/PLW1-sYW6Hw) |
| [OpenCAV in AutoDRIVE Simulator](https://youtu.be/YIZz_8rLgZQ) | [RZR in AutoDRIVE Simulator](https://youtu.be/PLW1-sYW6Hw) |
| [<img src="/../assets/images/Parallel-RL-using-AutoDRIVE-Simulator.png" width="500">](https://youtu.be/UAIcgeZ-at8) | [<img src="/../assets/images/Deformable-Terrain-Demo.png" width="500">](https://youtu.be/N8oZdD-WGYU) |
| [Parallel RL using AutoDRIVE Simulator](https://youtu.be/UAIcgeZ-at8) | [Deformable Terrain in AutoDRIVE Simulator](https://youtu.be/N8oZdD-WGYU) |
| [<img src="/../assets/images/Nigel-Variability-Testing.png" width="500">](https://youtu.be/KtjZapz0OkE) | [<img src="/../assets/images/OpenCAV-Variability-Testing.png" width="500">](https://youtu.be/sW8Ic-XyufM) |
| [Variability Testing using Nigel](https://youtu.be/KtjZapz0OkE) | [Variability Testing using OpenCAV](https://youtu.be/sW8Ic-XyufM) |
|                    |                     |

### Demonstrations

We encourage you to take a look at the following research projects developed using the AutoDRIVE Ecosystem.

|                    |                     |
|:------------------:|:-------------------:|
| [<img src="/../assets/images/Autonomous-Parking.png" width="500">](https://youtu.be/piCyvTM2dek) | [<img src="/../assets/images/Behavioural-Cloning.png" width="500">](https://youtu.be/rejpoogaXOE) |
| [Autonomous Parking](https://youtu.be/piCyvTM2dek) | [Behavioural Cloning](https://youtu.be/rejpoogaXOE) |
| [<img src="/../assets/images/Intersection-Traversal.png" width="500">](https://youtu.be/AEFJbDzOpcM) | [<img src="/../assets/images/Smart-City-Management.png" width="500">](https://youtu.be/fnxOpV1gFXo) |
| [Intersection Traversal](https://youtu.be/AEFJbDzOpcM) | [Smart City Management](https://youtu.be/fnxOpV1gFXo) |
|                    |                     |

### Presentations

We encourage you to take a look at the following presentations to gain a better insight into the AutoDRIVE Ecosystem.

|                    |                     |
|:------------------:|:-------------------:|
| [<img src="/../assets/images/SRMIST-FYP-Viva-Voce.png" width="500">](https://youtu.be/2FByDOkDxMc) | [<img src="/../assets/images/CCRIS-2021-Presentation.png" width="500">](https://youtu.be/whTH6VyVtHE) |
| [SRMIST UG Final Year Project Viva Voce](https://youtu.be/2FByDOkDxMc) | [CCRIS 2021 Virtual Presentation](https://youtu.be/whTH6VyVtHE) |
| [<img src="/../assets/images/AutoDRIVE-Technical-Discussion.png" width="500">](https://youtu.be/nV7HuLTjUY4) | [<img src="/../assets/images/Autoware-COE-Seminar.png" width="500">](https://youtu.be/WTGOAiRX4b0) |
| [AutoDRIVE Technical Discussion @ ARMLab CU-ICAR](https://youtu.be/nV7HuLTjUY4) | [Autoware COE Seminar](https://youtu.be/WTGOAiRX4b0) |
| [<img src="/../assets/images/AIM-2023-Presentation.png" width="500">](https://youtu.be/PV9k3-N_bvc) | [<img src="/../assets/images/OpenCAV-Technical-Discussion.png" width="500">](https://youtu.be/xihFoUxU7EU) |
| [AIM 2023 Video Presentation](https://youtu.be/PV9k3-N_bvc) | [OpenCAV Technical Discussion @ ARMLab CU-ICAR](https://youtu.be/xihFoUxU7EU) |
| [<img src="/../assets/images/OpenCAV-AuE-Seminar.png" width="500">](https://youtu.be/bk7lJfD4H0s) | [<img src="/../assets/images/SMRDC-2023-Presentation.png" width="500">](https://youtu.be/R_GZ1LkMWGQ) |
| [OpenCAV CUICAR AuE Seminar](https://youtu.be/bk7lJfD4H0s) | [SMRDC 2023 Finalist Pitch](https://youtu.be/R_GZ1LkMWGQ) |
| [<img src="/../assets/images/MECC-2023-Presentation.png" width="500">](https://youtu.be/0yS1-RpqhcE) | [<img src="/../assets/images/IROS-2023-Presentation.png" width="500">](https://youtu.be/8jyCJUOaLaI) |
| [MECC 2023 Video Presentation](https://youtu.be/0yS1-RpqhcE) | [IROS 2023 Presentation](https://youtu.be/8jyCJUOaLaI) |
|                    |                     |

## Team

#### Developers

|                    |                     |
|:------------------:|:-------------------:|
| [<img src="/../assets/images/Developer-Tanmay-Samak.png" width="125">](https://www.linkedin.com/in/samaktanmay) | [<img src="/../assets/images/Developer-Chinmay-Samak.png" width="125">](https://www.linkedin.com/in/samakchinmay) |
| [Tanmay Vilas Samak](https://www.linkedin.com/in/samaktanmay) | [Chinmay Vilas Samak](https://www.linkedin.com/in/samakchinmay) |
|                    |                     |

#### Contributors

|                    |                     |                     |                     |
|:------------------:|:-------------------:|:-------------------:|:-------------------:|
| [<img src="/../assets/images/Contributor-Rohit-Ravikumar.png" width="125">](https://www.linkedin.com/in/rohitravikumar-) | [<img src="/../assets/images/Contributor-Parth-Shinde.png" width="125">](https://www.linkedin.com/in/parthshindelink) | [<img src="/../assets/images/Contributor-Joey-Binz.png" width="125">](https://www.linkedin.com/in/joey-binz) | [<img src="/../assets/images/Contributor-Giovanni-Martino.png" width="125">](https://www.linkedin.com/in/giovannimartinose) |
| [Rohit Ravikumar](https://www.linkedin.com/in/rohitravikumar-) | [Parth Shinde](https://www.linkedin.com/in/parthshindelink) | [Joey Binz](https://www.linkedin.com/in/joey-binz) | [Giovanni Martino](https://www.linkedin.com/in/giovannimartinose) |
|                    |                     |                     |                     |

#### Mentors

|                    |                     |                     |
|:------------------:|:-------------------:|:-------------------:|
| [<img src="/../assets/images/Mentor-Venkat-Krovi.png" width="125">](https://www.linkedin.com/in/venkatnkrovi) | [<img src="/../assets/images/Mentor-Sivanathan-Kandhasamy.png" width="125">](https://www.linkedin.com/in/dr-sivanathan-kandhasamy-a4703966) | [<img src="/../assets/images/Mentor-Ming-Xie.png" width="125">](https://www.linkedin.com/in/ming-xie-800a4aa1) |
| [Dr. Venkat Krovi](https://www.linkedin.com/in/venkatnkrovi) | [Dr. Sivanathan Kandhasamy](https://www.linkedin.com/in/dr-sivanathan-kandhasamy-a4703966) | [Dr. Ming Xie](https://www.linkedin.com/in/ming-xie-800a4aa1) |
|                    |                     |                     |

#### Institutions

|                    |                     |                     |
|:------------------:|:-------------------:|:-------------------:|
| [<img src="/../assets/images/Institution-CUICAR.png" width="250">](https://cuicar.com) | [<img src="/../assets/images/Institution-SRMIST.png" width="250">](https://www.srmist.edu.in/) | [<img src="/../assets/images/Institution-NTU.png" width="250">](https://www.ntu.edu.sg) |
| [CU-ICAR](https://cuicar.com) | [SRM-IST](https://www.srmist.edu.in) | [NTU](https://www.ntu.edu.sg) |
|                    |                     |                     |
