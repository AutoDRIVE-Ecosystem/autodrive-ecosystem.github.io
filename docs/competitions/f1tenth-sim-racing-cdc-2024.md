# F1TENTH Sim Racing League @ CDC 2024

![F1TENTH Sim Racing League @ CDC 2024](../assets/images/banners/F1TENTH Sim Racing @ CDC 2024.png)

## About

<p align="justify">
<b>F1TENTH Autonomous Racing</b> is a semi-regular competition organized by an international community of researchers, engineers, and autonomous systems enthusiasts. The teams participating in the <b>22nd F1TENTH Autonomous Grand Prix</b> at <a href="https://cdc2024.ieeecss.org">CDC 2024</a> will write software for a 1:10 scaled autonomous racecar to fulfill the objectives of the competition: <b><i>drive fast but don’t crash!</i></b>
</p>

<p align="justify">
This time, we are organizing the second <b>F1TENTH Sim Racing League</b>, which leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an F1TENTH racecar within a virtual racetrack. Please see the accompanying video for a glimpse of the F1TENTH digital twins in action.
</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rq7Wwcwn1uk?si=ngvop2-SfJJOIjWJ" title="Digital Twin of F1TENTH in AutoDRIVE Simulator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p align="justify">
The main focus of the Sim Racing League is a virtual competition with simulated cars and environments, which is accessible to everyone across the globe. For the <a href="https://cdc2024.ieeecss.org">CDC 2024</a> competition, each team will be provided with a standardized simulation setup (in the form of a digital twin of the F1TENTH vehicle, and a digital twin of the Porto racetrack) within the high-fidelity <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a>. Additionally, teams will also be provided with a working implementation of the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a> to get started with developing their autonomy algorithms. Teams will have to develop perception, planning, and control algorithms to parse the real-time sensor data streamed from the simulator and generate control commands to be fed back to the simulated vehicle.
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
    If you are interested in autonomously racing physical F1TENTH vehicles, please check out the website for [22nd F1TENTH Autonomous Grand Prix](https://cdc2024-race.f1tenth.org), which will be held in person at <a href="https://cdc2024.ieeecss.org">CDC 2024</a>. You can always register and compete in both physical and virtual competitions!

## Organizers

| <img src="/../assets/images/people/Rahul Mangharam.png" width="125"> | <img src="/../assets/images/people/Venkat Krovi.png" width="125"> | <img src="/../assets/images/people/Johannes Betz.png" width="125"> | <img src="/../assets/images/people/Chinmay Samak.png" width="125"> | <img src="/../assets/images/people/Tanmay Samak.png" width="125"> |
|:------------------:|:-------------------:|:-------------------:|:-------------------:|:-------------------:|
| [**Dr. Rahul Mangharam**](mailto:rahulm@seas.upenn.edu) | [**Dr. Venkat Krovi**](mailto:vkrovi@clemson.edu) | [**Dr. Johannes Betz**](mailto:johannes.betz@tum.de) | [**Chinmay Samak**](mailto:csamak@clemson.edu) | [**Tanmay Samak**](mailto:tsamak@clemson.edu) |
| <img src="/../assets/images/people/Ahmad Amine.png" width="125"> | <img src="/../assets/images/people/Paolo Burgio.png" width="125"> | <img src="/../assets/images/people/Maria Prandini.png" width="125"> | <img src="/../assets/images/people/Martina Maggio.png" width="125"> | <img src="/../assets/images/people/Alessio Masola.png" width="125"> |
| [**Ahmad Amine**](mailto:aminea@seas.upenn.edu) | [**Dr. Paolo Burgio**](mailto:paolo.burgio@unimore.it) | [**Dr. Maria Prandini**](mailto:maria.prandini@polimi.it) | [**Dr. Martina Maggio**](mailto:maggio@cs.uni-saarland.de) | [**Dr. Alessio Masola**](mailto:alessio.masola@unimore.it) |
| <img src="/../assets/images/people/Filippo Muzzini.png" width="125"> | <img src="/../assets/images/people/Federico Gavioli.png" width="125"> | <img src="/../assets/images/people/Antonio Russo.png" width="125"> | <img src="/../assets/images/people/Enrico Mannocci.png" width="125"> |
| [**Dr. Filippo Muzzini**](mailto:filippo.muzzini@unimore.it) | [**Dr. Federico Gavioli**](mailto:224833@studenti.unimore.it) | [**Antonio Russo**](mailto:270201@studenti.unimore.it) | [**Enrico Mannocci**](mailto:enrico.mannocci3@unibo.it) |

## Timeline

!!! warning
    Timeline is subject to change. Please keep checking this page for any updates.

| DATE                              | EVENT                          |
|:----------------------------------|:-------------------------------|
| Aug 01, 2024                      | Registration Opens             |
| Oct 31, 2024                      | Registration Closes            |
| Oct 22, 2024 (5:30 – 6:30 PM EDT) | Online Orientation 1           |
| Nov 19, 2024 (5:30 – 6:30 PM EDT) | Online Orientation 2           |
| Nov 30 – Dec 01, 2024             | Qualification Round            |
| Dec 02, 2024                      | Qualification Results Declared |
| Dec 06, 2024                      | Competition Track Released     |
| Dec 07 – Dec 08, 2024             | Final Race                     |
| Dec 09, 2024                      | Competition Results Declared   |

<p align="justify">
Following is a brief summary of each event:
</p>

<ul class="justify-list">
  <li><b>Registration:</b> Interested teams will register for the Sim Racing League.</li>
  <li><b>Online Orientation 1:</b> Organizers will explain the competition rules and guidelines, and demonstrate how to use the simulation framework.</li>
  <li><b>Online Orientation 2:</b> Organizers will check progress of the participating teams and help with any technical difficulties.</li>
  <li><b>Qualification Round:</b> Teams will demonstrate successful completion of 10 laps around the practice track provided ahead of time.</li>
  <li><b>Qualification Results Declared:</b> Standings of all the qualified teams will be released.</li>
  <li><b>Competition Track Released:</b> Organizers will release the actual "competition track", which will be used for the final race. This track may be replicated in the physical race as well.</li>
  <li><b>Final Race:</b> Organizers will collect containerized algorithms from each team and connect them with the containerized simulator. Performance metrics of each team will be recorded.</li>
  <li><b>Competition Results Declared:</b> Standings of all the teams for the final race will be released.</li>
</ul>

!!! info
    The F1TENTH Sim Racing League will be held approximately 1 week ahead of <a href="https://cdc2024.ieeecss.org">CDC 2024</a> and the performance metrics will be made available to the teams. Discussions are underway with the CDC organizing team to allow teams to analyze and present their approach/results in a short (~10 min) presentation in a special session at <a href="https://cdc2024.ieeecss.org">CDC 2024</a>.

## Resources

<img src="/../assets/images/logos/AutoDRIVE Logo.png" width="24.5%" align="left"/>
<p align="justify">
<a href="https://autodrive-ecosystem.github.io/">AutoDRIVE</a> is envisioned to be an open, comprehensive, flexible and integrated cyber-physical ecosystem for enhancing autonomous driving research and education. It bridges the gap between software simulation and hardware deployment by providing the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a> and <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Testbed">AutoDRIVE Testbed</a>, a well-suited duo for real2sim and sim2real transfer targeting vehicles and environments of varying scales and operational design domains. It also offers <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a>, a developer's kit for rapid and flexible development of autonomy algorithms using a variety of programming languages and software frameworks. For the Sim Racing League, teams will develop their autonomous racing algorithms using the AutoDRIVE Devkit to interface with the AutoDRIVE Simulator in real-time.
</p>

<img src="/../assets/images/logos/F1TENTH Logo.png" width="24.5%" align="right"/>
<p align="justify">
<a href="https://f1tenth.org/">F1TENTH</a> is an <a href="https://f1tenth.org/about.html">international community</a> of researchers, engineers, and autonomous systems enthusiasts. It is centered around the idea of converting a 1:10 scale RC car into an autonomous vehicle for research and education; check out the <a href="https://f1tenth.org/build.html">documentation</a> to build your own F1TENTH autonomous racecar. Additionally, if you are new to the field of autonomous racing, you can refer to the complete <a href="https://f1tenth.org/learn.html">course material</a>, which is open sourced. If you already have some experience with autonomous racing, feel free to delve deeper into the <a href="https://f1tenth.org/research.html">research</a> enabled by F1TENTH. Lastly, you can also check out the physical <a href="https://f1tenth.org/race.html">F1TENTH races</a> that are being organized all around the world. For the Sim Racing League, teams will not require a physical F1TENTH vehicle; however, the learning resources can certainly be useful to get your autonomous racing fundamentals right!
</p>

<p align="justify">
We recommend all the teams interested in participating in the F1TENTH Sim Racing League to get accustomed with the competition. Following are a few resources to get you started:
</p>

<div class="grid cards" markdown>

-   :material-file-document:{ .lg .middle } __Competition Documents__

    ---

    Learn about the competition rules and technical aspects of the framework.

    [:material-open-in-new: Competition Rules](../f1tenth-sim-racing-rules)

    [:material-open-in-new: Technical Guide](../f1tenth-sim-racing-guide)

-   :material-docker:{ .lg .middle } __Docker Containers__

    ---

    Download base container images for the competition and start developing your algorithms.

    [:octicons-download-16: AutoDRIVE Simulator Container](https://hub.docker.com/r/autodriveecosystem/autodrive_f1tenth_sim)

    [:octicons-download-16: AutoDRIVE Devkit Container](https://hub.docker.com/r/autodriveecosystem/autodrive_f1tenth_api)

-   :material-monitor:{ .lg .middle } __Local Resources__

    ---

    Get started with the competition framework locally, and worry about containerization later. 

    **AutoDRIVE Simulator:**
    
    `explore`&nbsp;&nbsp;&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc-practice/autodrive_simulator_explore_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc-practice/autodrive_simulator_explore_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc-practice/autodrive_simulator_explore_macos.zip)

    `practice`&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc-practice/autodrive_simulator_practice_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc-practice/autodrive_simulator_practice_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc-practice/autodrive_simulator_practice_macos.zip)

    `compete`&nbsp;&nbsp;&nbsp; :simple-linux: Linux | :material-microsoft: Windows | :simple-apple: macOS

    **AutoDRIVE Devkit:**
    
    [:simple-ros: ROS 2](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc-practice/autodrive_devkit.zip)

-   :fontawesome-solid-users:{ .lg .middle } __Orientation Resources__

    ---

    Join the online orientation sessions or review what we covered there.

    **Orientation 1:**
    
    Meeting Link: :fontawesome-solid-video: Zoom
    
    Review Links: :octicons-video-16: Recording | :material-projector-screen-outline: Slides

    **Orientation 2:**
    
    Meeting Link: :fontawesome-solid-video: Zoom
    
    Review Links: :octicons-video-16: Recording | :material-projector-screen-outline: Slides
</div>

!!! question
    You can post general questions on the [:material-slack: AutoDRIVE Slack](https://join.slack.com/t/autodrive-ecosystem/shared_invite/zt-2oeg2hce8-0JvasvnBM1M_wUdDTWRuKw) workspace; this is the preferred modality. Technical questions can be also posted as [:material-github: GitHub Issues](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/issues) or [:material-github: GitHub Discussions](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/discussions). For any other questions or concerns that cannot be posted publicly, please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu).

## Registration

<p align="justify">
This competition is open to everyone around the world - students, researchers, hobbyists, professionals, or anyone else who is interested. A team can consist of multiple teammates. Teams with only one person are also allowed.
</p>

<center>
[:material-file-document-edit: Registration Form](https://forms.gle/D6X2C5PMwmDWEWbo9){.md-button}
</center>

<p align="justify">
Registration for the Sim Racing League is free of cost and separate from the Physical Racing League and the conference registrations themselves. The above form signs you up only for the Sim Racing League, and for its orientation and information sessions. Although you can participate in the Sim Racing League without attending the conference, we strongly encourage all competition participants to attend the conference in person. This will help you connect with the broader AutoDRIVE and F1TENTH communities, and you can also witness/participate in the physical F1TENTH autonomous racing competition!
</p>

<p align="justify">
Registered teams are added to the following table:
</p>

| SR. NO. | TEAM NAME                 | TEAM MEMBERS                  | ORGANIZATION                              |
|:--------|:--------------------------|:------------------------------|:------------------------------------------|
| 01      | Beryllium                 | Ronnie Romman                 | Personal                                  |
| 02      | AERObotics                | Arif Anjum<br/>Muhammed Sharjil | AEROBOTICS                              |
| 03      | Pharst Laps               | Olivia Dry<br/>Tian Zhao<br/>Yitian Chen<br/>Amir Ali Farzin | Australian National University |
| 04      | SeDriCa-UMIC              | Kshitij Vaidya<br/>Yash Gupta<br/>Manav Jain<br/>Parth Agrawal<br/>Sahil Kukreja<br/>Johan Biju<br/>Paawan Nenwani<br/>Shivam Yadav | Indian Institute of Technology, Bombay |
| 05      | Unimelb F1Tenth Racing    | Henry Yapeter<br/>Matthew Freeman<br/>Nathan Ruslim<br/>Harry Tauber | The University of Melbourne |
| 06      | Donatello                 | Rahil Bhowal                  | Personal                                  |
| 07      | VAUL                      | Tommy Bouchard-Lebrun<br/>William Fecteau<br/>Nicolas Lauzon | Laval University |
| 08      | TUM Phoenix               | Dean Mercer<br/>Zara Zhotabayeva | Technische Universität München         |
| 09      | Autonomous Motorsports Purdue | Manav Gagvani             | Purdue University                         |
| 10      | Pegasus                   | Zeyuan Wang<br/>Chao Wang     | Personal                                  |
| 11      | ARCLab                    | William Akuffo<br/>Joshua Nti<br/>Reginald Andrew Sai-Obodai<br/>Baron Afutu<br/>Joel Osei-Asamoah | Ashesi University |
| 12      | YTU AESK                  | Mahmut Demir<br/>Ahmet Çelik<br/>İlayda Sena Şahin<br/>Furkan Erdoğan<br/>Alper Yılmaz<br/>Enes Talha Günay<br/>Taha İlter Akar<br/>Hilal Horasan | Yıldız Technical University Alternative Energy Systems Society |
| 13      | MMS Autonomous            | Yousef Asal<br/>Zaynap Ahmad<br/>Omar Ashraf<br/>Omar Elsharabasy<br/>Abdallah Nabil<br/>Ahmed ElShaboury | Mansoura University |
| 14      | HUN-REN SZTAKI            | Csanád Budai<br/>Tamás Széles | HUN-REN SZTAKI                            |
| 15      | bracaai                   | Luis Bracamontes              | Personal                                  |

!!! note
    The above table will be updated with newly registered teams within a few days of registration. Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you do not see your team entry for more than 7 days after registering.

## Results

**Phase 1: Qualification**

<p align="justify">
To be announced on Dec 02, 2024.
</p>

**Phase 2: Competition**

<p align="justify">
To be announced on Dec 09, 2024.
</p>