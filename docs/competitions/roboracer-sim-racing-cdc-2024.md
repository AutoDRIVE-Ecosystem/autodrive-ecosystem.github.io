# RoboRacer Sim Racing League @ CDC 2024

![RoboRacer Sim Racing League @ CDC 2024](../assets/images/banners/RoboRacer Sim Racing @ CDC 2024.png)

## About

<p align="justify">
<b>RoboRacer Autonomous Racing</b> is a semi-regular competition organized by an international community of researchers, engineers, and autonomous systems enthusiasts. The teams participating in the <b>22nd RoboRacer Autonomous Grand Prix</b> at <a href="https://cdc2024.ieeecss.org">CDC 2024</a> will write software for a 1:10 scaled autonomous racecar to fulfill the objectives of the competition: <b><i>drive fast but don’t crash!</i></b>
</p>

<p align="justify">
This time, we are organizing the second <b>RoboRacer Sim Racing League</b>, which leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an RoboRacer racecar within a virtual racetrack. Please see the accompanying video for a glimpse of the RoboRacer digital twins in action.
</p>

<div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/9; width: 100% !important;" src="https://www.youtube.com/embed/Rq7Wwcwn1uk?si=ngvop2-SfJJOIjWJ" title="Digital Twin of RoboRacer in AutoDRIVE Simulator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<p align="justify">
The main focus of the Sim Racing League is a virtual competition with simulated cars and environments, which is accessible to everyone across the globe. For the <a href="https://cdc2024.ieeecss.org">CDC 2024</a> competition, each team will be provided with a standardized simulation setup (in the form of a digital twin of the RoboRacer vehicle, and a digital twin of the Porto racetrack) within the high-fidelity <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a>. Additionally, teams will also be provided with a working implementation of the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a> to get started with developing their autonomy algorithms. Teams will have to develop perception, planning, and control algorithms to parse the real-time sensor data streamed from the simulator and generate control commands to be fed back to the simulated vehicle.
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
    If you are interested in autonomously racing physical RoboRacer vehicles, please check out the website for [22nd RoboRacer Autonomous Racing Competition](https://cdc2024-race.f1tenth.org), which will be held in person at <a href="https://cdc2024.ieeecss.org">CDC 2024</a>. You can always register and compete in both physical and virtual competitions!

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
| Nov 08, 2024 (5:30 – 6:30 PM EST) | [Online Orientation 1](https://clemson.zoom.us/j/92399406829) |
| Nov 23, 2024 (1:00 – 2:00 PM EST) | [Online Orientation 2](https://clemson.zoom.us/j/98938663143) |
| Nov 30 – Dec 01, 2024             | Qualification Round            |
| Dec 02, 2024                      | Qualification Results Declared |
| Dec 04, 2024                      | Competition Track Released     |
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
    The RoboRacer Sim Racing League will be held approximately 1 week ahead of <a href="https://cdc2024.ieeecss.org">CDC 2024</a> and the performance metrics will be made available to the teams. We have also been able to organize a <a href="https://css.paperplaza.net/conferences/conferences/CDC24/program/CDC24_ContentListWeb_1.html#moevsp1_01">special session</a> for <a href="https://cdc2024.ieeecss.org/program/competitions#session-10-44">RoboRacer Sim Racing League Celebration</a> on Monday (Dec 16), 18:00-19:00 CET with the help of the CDC organizing committee. Join the celebration event to relive the nail-biting races, hear the top teams brag about their winning strategies (~5 min presentations), and start your engines for the physical competition.

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

    [:material-open-in-new: **Competition Rules**](../roboracer-sim-racing-rules-2024)

    [:material-open-in-new: **Technical Guide**](../roboracer-sim-racing-guide-2024)

-   :material-docker:{ .lg .middle } __Docker Containers__

    ---

    Download base container images for the competition and start developing your algorithms.

    [:material-open-in-new: **AutoDRIVE Simulator:**](https://hub.docker.com/r/autodriveecosystem/autodrive_f1tenth_sim) [`explore`](https://hub.docker.com/layers/autodriveecosystem/autodrive_f1tenth_sim/2024-cdc-explore/images/sha256-6a4a9aab20e5deafdcf1a8318b4f270d409b557ba198888fd701eb56506760c7) | [`practice`](https://hub.docker.com/layers/autodriveecosystem/autodrive_f1tenth_sim/2024-cdc-practice/images/sha256-07126b3b4bcf7d6ff43a7d76f9ba84412b2553784026d27b7e4ebdab269c4c6f) | [`compete`](https://hub.docker.com/layers/autodriveecosystem/autodrive_f1tenth_sim/2024-cdc-compete/images/sha256-e0b511807cdc5597e9da3e3c1f630750476dd9a6a56f14187f79ca15ad72ad5e)

    [:material-open-in-new: **AutoDRIVE Devkit:**](https://hub.docker.com/r/autodriveecosystem/autodrive_f1tenth_api) [`explore`](https://hub.docker.com/layers/autodriveecosystem/autodrive_f1tenth_api/2024-cdc-explore/images/sha256-221ab09c92720fc9ed324839ec81da6aceb4c5c12ae1e46b8733c2275cb000f1) | [`practice`](https://hub.docker.com/layers/autodriveecosystem/autodrive_f1tenth_api/2024-cdc-practice/images/sha256-d3fd68b51ec6934d8de283c14be5d5b5d8e3c536599eeeef652a16f47cce103d) | [`compete`](https://hub.docker.com/layers/autodriveecosystem/autodrive_f1tenth_api/2024-cdc-compete/images/sha256-6596fa4eed9521f61d2fb3dc43c52bb0affbf3e7e2a197e1afb6ef03894694a7)

-   :material-monitor:{ .lg .middle } __Local Resources__

    ---

    Get started with the competition framework locally, and worry about containerization later. 

    **AutoDRIVE Simulator:**
    
    `explore`&nbsp;&nbsp;&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_explore_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_explore_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_explore_macos.zip)

    `practice`&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_practice_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_practice_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_practice_macos.zip)

    `compete`&nbsp;&nbsp;&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_compete_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_compete_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_simulator_compete_macos.zip)

    **AutoDRIVE Devkit:**
    
    [:simple-ros: ROS 2](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/autodrive_devkit.zip)

-   :fontawesome-solid-users:{ .lg .middle } __Orientation Resources__

    ---

    Join the online orientation sessions or review what we covered there.

    **Orientation 1:**
    
    Meeting Link: [:fontawesome-solid-video: Zoom](https://clemson.zoom.us/j/92399406829)
    
    Review Links: [:octicons-video-16: Recording](https://youtu.be/WQyhXQtFC0o) | [:material-projector-screen-outline: Slides](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/orientation_1_slides.zip)

    **Orientation 2:**
    
    Meeting Link: [:fontawesome-solid-video: Zoom](https://clemson.zoom.us/j/98938663143)
    
    Review Links: [:octicons-video-16: Recording](https://youtu.be/MxCDt1A4Wbo) | [:material-projector-screen-outline: Slides](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-cdc/orientation_2_slides.zip)
</div>

!!! question
    You can post general questions on the [:material-slack: AutoDRIVE Slack](https://join.slack.com/t/autodrive-ecosystem/shared_invite/zt-2oeg2hce8-0JvasvnBM1M_wUdDTWRuKw) workspace; this is the preferred modality. Technical questions can be also posted as [:material-github: GitHub Issues](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/issues) or [:material-github: GitHub Discussions](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/discussions). For any other questions or concerns that cannot be posted publicly, please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu).

## Registration

<p align="justify">
This competition is open to everyone around the world - students, researchers, hobbyists, professionals, or anyone else who is interested. A team can consist of multiple teammates. Teams with only one person are also allowed.
</p>

<div style="display: flex; justify-content: center;">
<a class="md-button" href="https://forms.gle/D6X2C5PMwmDWEWbo9"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Registration Form</a>
</div>

<p align="justify">
Registration for the Sim Racing League is free of cost and separate from the Physical Racing League and the conference registrations themselves. The above form signs you up only for the Sim Racing League, and for its orientation and information sessions. Although you can participate in the Sim Racing League without attending the conference, we strongly encourage all competition participants to attend the conference in person. This will help you connect with the broader AutoDRIVE and RoboRacer communities, and you can also witness/participate in the physical RoboRacer autonomous racing competition!
</p>

<p align="justify">
Registered teams are added to the following table:
</p>

| SR. NO. | TEAM NAME                 | TEAM MEMBERS                  | ORGANIZATION                              | COUNTRY                              |
|:--------|:--------------------------|:------------------------------|:------------------------------------------|:-------------------------------------|
| 01      | Beryllium                 | Ronnie Romman                 | Personal                                  | United States of America (USA)       |
| 02      | AERObotics                | Arif Anjum<br/>Muhammed Sharjil | AEROBOTICS                              | South Africa                         |
| 03      | Pharst Laps               | Olivia Dry<br/>Tian Zhao<br/>Yitian Chen<br/>Amir Ali Farzin | Australian National University | Australia        |
| 04      | SeDriCa-UMIC              | Kshitij Vaidya<br/>Yash Gupta<br/>Manav Jain<br/>Parth Agrawal<br/>Sahil Kukreja<br/>Johan Biju<br/>Paawan Nenwani<br/>Shivam Yadav | Indian Institute of Technology, Bombay | India |
| 05      | Unimelb F1Tenth Racing    | Henry Yapeter<br/>Matthew Freeman<br/>Nathan Ruslim<br/>Harry Tauber | The University of Melbourne |  Australia  |
| 06      | Donatello                 | Rahil Bhowal                  | Personal                                  | United States of America (USA)       |
| 07      | VAUL                      | Tommy Bouchard-Lebrun<br/>William Fecteau<br/>Nicolas Lauzon | Laval University | Canada                         |
| 08      | TUM Phoenix               | Dean Mercer<br/>Zara Zhotabayeva | Technische Universität München         | Germany                              |
| 09      | Autonomous Motorsports Purdue | Manav Gagvani<br/>Alan Kang<br/>Sivamurugan Velmurugan<br/>Rohan Potta<br/>Sangeet Mohan | Purdue University | United States of America (USA) |
| 10      | Pegasus                   | Zeyuan Wang<br/>Chao Wang     | Personal                                  | France, China                        |
| 11      | ARCLab                    | William Akuffo<br/>Joshua Nti<br/>Reginald Andrew Sai-Obodai<br/>Baron Afutu<br/>Joel Osei-Asamoah | Ashesi University | Ghana |
| 12      | YTU AESK                  | Mahmut Demir<br/>Ahmet Çelik<br/>İlayda Sena Şahin<br/>Furkan Erdoğan<br/>Alper Yılmaz<br/>Enes Talha Günay<br/>Taha İlter Akar<br/>Hilal Horasan | Yıldız Technical University Alternative Energy Systems Society | Türkiye |
| 13      | MMS Autonomous            | Yousef Asal<br/>Zaynap Ahmad<br/>Omar Ashraf<br/>Omar Elsharabasy<br/>Abdallah Nabil<br/>Ahmed ElShaboury | Mansoura University | Egypt |
| 14      | HUN-REN SZTAKI            | Csanád Budai<br/>Tamás Széles | HUN-REN SZTAKI                            | Hungary                              |
| 15      | bracaai                   | Luis Bracamontes              | Personal                                  | Mexico                               |
| 16      | Velox                     | Karun Ashok Kumar             | University of Twente                      | Netherlands                          |
| 17      | Exhausted Lion            | Mohamed Alaa                  | Personal                                  | Egypt                                |
| 18      | Sahruday Patti            | Sahruday Patti                | Personal                                  | United States of America (USA)       |
| 19      | Als F1Tenth Racing        | Auriol Ble                    | Alpha Space Robotics Lab                  | Côte d'Ivoire                        |
| 20      | SoloDriver                | Hana Nabhan                   | Personal                                  | United Arab Emirates (UAE)           |
| 21      | Daniel's RL Experiment    | Daniel Mittelman              | Georgia Institute of Technology           | United States of America (USA)       |
| 22      | TURTLEBOT                 | Jit Ern Lim                   | Personal                                  | Singapore                            |
| 23      | TractionX                 | Ameya Bagal<br/>Ananya Das<br/>Amizhthni PRK | Indian Institute of Technology, Madras | India                    |
| 24      | Awareness                 | Guodong Zhu                   | Nanjing Forest University                 | China                                |
| 25      | Byte Benders              | Bhajneet Singh Bedi<br/>Yaduraj Jagadeesan | Personal                     | India                                |
| 26      | Eigenbots                 | Shubham Barge<br/>Anshuman Jena | Personal                                | India                                |
| 27      | \_\_duronto\_\_           | Md. Jesan<br/>Muhammad Fahim Faisal<br/>Abu Nafis Mohammod Noor Rohan<br/>Rakibul Islam Rakib | BRAC University, Dhaka Residential Model College | Bangladesh |
| 28      | MV33F110                  | Vishwanath R                  | Personal                                  | India                                |
| 29      | F1NESSE - Formula 1 Neuro-Enhanced System for Smart Execution | Oscar Guerrero Rosado<br/>Joris Kranz<br/>Jan Honing<br/>Wout Laracker | Radboud University, ROC Nijmegen | Netherlands |
| 30      | Baby Driver               | Mason Notz                    | Personal                                  | United States of America (USA)       |
| 31      | Asturian Kingdom Team     | David Miranda<br/>Lucía Sánchez<br/>Miguel Santamaría | University of Oviedo | Spain                             |
| 32      | AsTenth Martin            | Ajay Shankar Sriram           | UC Irvine                                 | United States of America (USA)       |
| 33      | Ray C.E.R.S.              | Aditya Jambhale<br/>Akshat Tambi | SRM Institute of Science and Technology | India                               |
| 34      | Neutrino                  | Ahmed Elnely<br/>Abdallah Atef<br/>Mohamed Abdelmoneam<br/>Noran Mohamed<br/>Yasmin Khaled<br/>Nouran Karam | Egyptian Russian University | Egypt |
| 35      | Zancle E-Drive            | Gaetano Pio Pispisa<br/>Giovanni Lombardo<br/>Simone Castorino | University of Messina, Italy | Italy            |
| 36      | sim_goes_brrrrrr_mha      | Marzanul Momenine<br/>Maidul Islam<br/>Hironmoy Roy Rudra | Personal      | Bangladesh                           |
| 37      | Inertia                   | Mushfiqur Rahman<br/>Al Mahir Ahmed<br/>Suhail Haque Rafi<br/>Abrar Ahmed | Personal | Bangladesh                |
| 38      | Assiut Motorsport         | Omar Abbas<br/>Kareem Salah<br/>Mohamed Abd-El-Fattah<br/>Ahmed Shehata<br/>Doaa Ibrahem<br/>Eslam Mohamed<br/>Arwa Ibrahim<br/>Maotaz Refaat<br/>Fajr Mohamed<br/>Ahmed Mohamed | Assiut University | Egypt |
| 39      | SELF                      | Zhuo Ouyang<br/>Pengcheng You<br/>Chang Liu<br/>Yingzhu Liu<br/>Chengrui Qu | Peking University | China          |
| 40      | Triton AI                 | Yen-Ru Chen<br/>Winston Chou<br/>Kevin Shin<br/>Samuel Lin<br/>Surya Setty<br/>Aryan Palaskar | University of California, San Diego |  United States of America (USA) |
| 41      | Escuderia Brasileira de Veículos Autônomos | Fernando Zolubas Preto<br/>Antonio Colombini Neto<br/>Felipe Gomes de Melo D'Elia<br/>Carlos Alberto Arronte Delgado<br/>Francisco Rodrigues Marazia<br/>Luccas Barsotti<br/>Caio Victor Goveia Freitas | Polytechnic School of the University of São Paulo - Brazil | Brazil |
| 42      | Autonomous Ground Vehicle | Shreyansh Kansal<br/>Swaminathan S K<br/>Yash Sirvi<br/>Aditya Srivastava<br/>Akshit Goyal<br/>Atul Singh<br/>Rohan Singh<br/>Theyanesh E R<br/>Sandip Das<br/>Arham J Bhansali<br/>Ansh Sharma<br/>Samarth G | Indian Institute of Technology, Kharagpur | India |
| 43      | SUST Autodrive            | Abul Bashar Raz<br/>Md. Redwan Hasan<br/>Ehsanul Karim Aslam<br/>Md. Tamzid Islam Babul | Shahjalal University of Science and Technology | Bangladesh |
| 44      | Sabeq                     | Adham Waleed<br/>Abdulrahman Ahmed<br/>Nabil Fouda<br/>Mostafa Samy | Ain Shams University | Egypt               |
| 45      | RapidRabbits              | Aryan Iyer<br/>Siddhant Diwaker | Personal                                | India                                |
| 46      | Orion                     | U Skanda Aithal<br/>Aryan Agarwal<br/>Aditya Gupta<br/>Aman Kumar<br/>Lakshmikanth Nageswar | Personal | India   |
| 47      | KOU-Mekatronom            | Mehmet Baha Dursun<br/>Muvahhid Kılıç<br/>Can Ercan | Personal            | Türkiye                                |
| 48      | CLUTCH                    | Emmanuel Korankye<br/>Appenteng Adjepong<br/>Samuel Akwensivie<br/>Kobena Enyam<br/>Desmond Hammond | Personal | Ghana |
| 49      | SimRacer                  | Vinura Wanniarachchi          | Personal                                  | Sri Lanka                            |
| 50      | WaterlooF110              | Megnath Ramesh<br/>Shaswat Garg<br/>Avraiem Iskander<br/>Praneeth KVK | University of Waterloo | Canada          |
| 51      | AA LAB                    | Taha Kocyigit<br/>Taha Yigit Erdogan | Bogazici University                | Türkiye                              |

!!! note
    The above table will be updated with newly registered teams within a few days of registration. Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you do not see your team entry for more than 7 days after registering.

<div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/8; width: 100% !important;" src="/../assets/images/competitions/2024 cdc roboracer sim racing league/Map.html" title="Global Participation Map"  frameborder="0"></iframe>
</div>

<div style="display: flex; justify-content: center;">
<img src="/../assets/images/competitions/2024 cdc roboracer sim racing league/Collage.png" title="Participating Organizations">
</div>

## Submission

<p align="justify">
Use the secure form below to make your team's submission for Phase 1 (Qualification Round) of the RoboRacer Sim Racing League. Please fill in your team's name and add the link to your team's DockerHub repository containing the autonomous racing stack. If you are using a private repository, make sure to add <a href="https://hub.docker.com/u/autodriveecosystem">autodriveecosystem</a> as a <a href="https://docs.docker.com/docker-hub/repos/access">collaborator to your repository</a>.
</p>

<div style="display: flex; justify-content: center;">
<a class="md-button" href="https://forms.gle/aYPFnWwVDzf47eXS6"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Phase 1 Submission Form</a>
</div>

!!! warning
    Phase 1 submission window will close on Nov 30, 2024. Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you have any questions.

<p align="justify">
Use the secure form below to make your team's submission for Phase 2 (Final Race) of the RoboRacer Sim Racing League. Please fill in your team's name and add the link to your team's DockerHub repository containing the autonomous racing stack. If you are using a private repository, make sure to add <a href="https://hub.docker.com/u/autodriveecosystem">autodriveecosystem</a> as a <a href="https://docs.docker.com/docker-hub/repos/access">collaborator to your repository</a>.
</p>

<div style="display: flex; justify-content: center;">
<a class="md-button" href="https://forms.gle/mbrDFBU9Xww1Gp5X9"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Phase 2 Submission Form</a>
</div>

!!! warning
    Phase 2 submission window will close on Dec 07, 2024. Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you have any questions.

## Results

**Phase 1: Qualification**

<p align="justify">
The following teams have qualified for the final time-attack race. Here are the official standings:
</p>

| RANK    | TEAM NAME                                     | RACE TIME       | COLLISION COUNT | ADJUSTED RACE TIME | BEST LAP TIME | VIDEO                                                     |
|:--------|:----------------------------------------------|:----------------|:----------------|:-------------------|:--------------|:----------------------------------------------------------|
| 01      | 👏 VAUL                                       | 70.30 s         | 0               | 70.30 s            | 6.96 s        | [:material-youtube: YouTube](https://youtu.be/SDusD071cyk?feature=shared) |
| 02      | 👏 Asturian Kingdom Team                      | 75.27 s         | 0               | 75.27 s            | 7.52 s        | [:material-youtube: YouTube](https://youtu.be/MkIWWgdW_Bo?feature=shared) |
| 03      | 👏 SoloDriver                                 | 82.97 s         | 0               | 82.97 s            | 8.27 s        | [:material-youtube: YouTube](https://youtu.be/iq6XiuYi0Tc?feature=shared) |
| 04      | 👏 TURTLEBOT                                  | 90.33 s         | 0               | 90.33 s            | 8.98 s        | [:material-youtube: YouTube](https://youtu.be/tnDtR_BPtAY?feature=shared) |
| 05      | 👏 Byte Benders                               | 85.61 s         | 1               | 95.61 s            | 8.29 s        | [:material-youtube: YouTube](https://youtu.be/kcxb_3NtO-U?feature=shared) |
| 06      | 👏 AsTenth Martin                             | 92.44 s         | 1               | 102.44 s           | 9.08 s        | [:material-youtube: YouTube](https://youtu.be/KgV__0fcqr4?feature=shared) |
| 07      | 👏 Pharst Laps                                | 93.69 s         | 1               | 103.69 s           | 9.24 s        | [:material-youtube: YouTube](https://youtu.be/xDbs3ewB_f4?feature=shared) |
| 08      | 👏 Autonomous Ground Vehicle                  | 111.94 s        | 1               | 121.94 s           | 10.55 s       | [:material-youtube: YouTube](https://youtu.be/_itmR_8lQxE?feature=shared) |
| 09      | 👏 Autonomous Motorsports Purdue              | 122.34 s        | 0               | 122.34 s           | 12.22 s       | [:material-youtube: YouTube](https://youtu.be/YnLfij6H87Q?feature=shared) |
| 10      | 👏 Escuderia Brasileira de Veículos Autônomos | 114.19 s        | 1               | 124.19 s           | 11.33 s       | [:material-youtube: YouTube](https://youtu.be/VRmLx6drMko?feature=shared) |
| 11      | 👏 YTU AESK                                   | 125.14 s        | 0               | 125.14 s           | 12.47 s       | [:material-youtube: YouTube](https://youtu.be/so1HFp_kmOQ?feature=shared) |
| 12      | 👏 Zancle E-Drive                             | 126.79 s        | 0               | 126.79 s           | 12.65 s       | [:material-youtube: YouTube](https://youtu.be/-d4bYYlnBR4?feature=shared) |
| 13      | 👏 Baby Driver                                | 122.66 s        | 1               | 132.66 s           | 12.19 s       | [:material-youtube: YouTube](https://youtu.be/FHNaUfW21Rw?feature=shared) |
| 14      | 👏 Pegasus                                    | 146.82 s        | 0               | 146.82 s           | 14.65 s       | [:material-youtube: YouTube](https://youtu.be/r7Ppv0hXfwE?feature=shared) |
| 15      | 👏 MMS Autonomous                             | 113.15 s        | 5               | 163.15 s           | 10.90 s       | [:material-youtube: YouTube](https://youtu.be/HXrgM4KHC2Q?feature=shared) |
| 16      | 👏 WaterlooF110                               | 190.31 s        | 0               | 190.31 s           | 18.78 s       | [:material-youtube: YouTube](https://youtu.be/45_0Pjbd_YY?feature=shared) |
| 17      | 👏 bracaai                                    | 201.09 s        | 0               | 201.09 s           | 19.68 s       | [:material-youtube: YouTube](https://youtu.be/Rmqrl6Qaiuc?feature=shared) |
| 18      | 👏 Assiut Motorsport                          | 112.09 s        | 9               | 202.09 s           | 10.74 s       | [:material-youtube: YouTube](https://youtu.be/n9zs7wRjR7s?feature=shared) |
| 19      | 👏 SeDriCa-UMIC                               | 185.18 s        | 2               | 205.18 s           | 18.34 s       | [:material-youtube: YouTube](https://youtu.be/1008cTF6gwM?feature=shared) |
| 20      | 👏 Sabeq                                      | 128.63 s        | 10              | 228.63 s           | 12.50 s       | [:material-youtube: YouTube](https://youtu.be/Z8uZNGdLJ1A?feature=shared) |

**Phase 2: Competition**

<p align="justify">
The following teams successfully finished the final time-attack race. Here are the official standings:
</p>

| RANK    | TEAM NAME                                     | RACE TIME       | COLLISION COUNT | ADJUSTED RACE TIME | BEST LAP TIME | VIDEO                                                     |
|:--------|:----------------------------------------------|:----------------|:----------------|:-------------------|:--------------|:----------------------------------------------------------|
| 01      | 🥇 VAUL                                       | 103.84 s        | 0               | 103.84 s           | 10.35 s       | [:material-youtube: YouTube](https://youtu.be/9cGryPiPNTw?feature=shared) |
| 02      | 🥈 Baby Driver                                | 136.63 s        | 0               | 136.63 s           | 13.58 s       | [:material-youtube: YouTube](https://youtu.be/U40fX7-eqzc?feature=shared) |
| 03      | 🥉 TURTLEBOT                                  | 145.99 s        | 0               | 145.99 s           | 14.42 s       | [:material-youtube: YouTube](https://youtu.be/jo_Nhqn-IPI?feature=shared) |
| 04      | 👏 Asturian Kingdom Team                      | 150.76 s        | 1               | 160.76 s           | 14.91s        | [:material-youtube: YouTube](https://youtu.be/hDVwhqrr_x8?feature=shared) |
| 05      | 👏 Pharst Laps                                | 151.37 s        | 3               | 181.37 s           | 14.79 s       | [:material-youtube: YouTube](https://youtu.be/lDuHt5YY2rk?feature=shared) |
| 06      | 👏 bracaai                                    | 167.15 s        | 2               | 187.15 s           | 16.34 s       | [:material-youtube: YouTube](https://youtu.be/cAbo8uAQe6k?feature=shared) |
| 07      | 👏 Byte Benders                               | 195.76 s        | 2               | 215.76 s           | 18.99 s       | [:material-youtube: YouTube](https://youtu.be/1cwtYUkzGmc?feature=shared) |
| 08      | 👏 Autonomous Motorsports Purdue              | 211.76 s        | 1               | 221.76 s           | 20.48 s       | [:material-youtube: YouTube](https://youtu.be/CZvvhld03B8?feature=shared) |
| 09      | 👏 Escuderia Brasileira de Veículos Autônomos | 219.45 s        | 1               | 229.45 s           | 21.74 s       | [:material-youtube: YouTube](https://youtu.be/m1v0NSuAhTQ?feature=shared) |
| 10      | 👏 Pegasus                                    | 227.29 s        | 1               | 237.29 s           | 21.72 s       | [:material-youtube: YouTube](https://youtu.be/o7Xye3Sd2Ns?feature=shared) |
| 11      | 👏 Zancle E-Drive                             | 241.64 s        | 0               | 241.64 s           | 24.04 s       | [:material-youtube: YouTube](https://youtu.be/JFq6BRu7l8w?feature=shared) |
| 12      | 👏 MMS Autonomous                             | 155.19 s        | 9               | 245.19 s           | 15.09 s       | [:material-youtube: YouTube](https://youtu.be/nn9IYfmuXLM?feature=shared) |
| 13      | 👏 SoloDriver                                 | 259.23 s        | 1               | 269.23 s           | 24.59 s       | [:material-youtube: YouTube](https://youtu.be/nPsR5S4T-4k?feature=shared) |

**Celebration Event @ CDC 2024**

<p align="justify">
🎉 Please join us (in-person or virtually) for the <a href="https://css.paperplaza.net/conferences/conferences/CDC24/program/CDC24_ContentListWeb_1.html#moevsp1_01">celebration event</a> of the 2nd RoboRacer Sim Racing League @ CDC 2024 on Monday (Dec 16, 2024) between 18:00-19:00 CET! 🏁
</p>

<p align="justify">
<b>🎤 <i>Agenda:</i></b>
</p>

<ul class="justify-list">
  <li>Introduction & Overview (15 min) – Dr. Krovi & Dr. Mangharam</li>
  <li>Competition Insights (20 min) – Tanmay & Chinmay</li>
  <li>Words from the Winners (15 min) – 5 min for each team</li>
  <li>Concluding Remarks (10 min) – Dr. Krovi & Dr. Mangharam</li>
</ul>

<p align="justify">
<b>💻 <i>Zoom:</i></b> <a href="https://tinyurl.com/f1tenth-cdc24-virtual-race">https://tinyurl.com/f1tenth-cdc24-virtual-race</a>
</p>

<p align="justify">
🏆 Don't miss this chance to relive the thrill of the competition and hear from the champions themselves!
</p>

<div class="grid cards" markdown> 

- :material-youtube:{ .lg .middle } __Celebration Event Recording__
    
    <iframe width="640" height="268" src="https://www.youtube.com/embed/HtmRKE3Jres?si=4j6mOefsbBnGiGud" title="Celebration Event Recording" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- :material-youtube:{ .lg .middle } __Words from the Winners!__
    
    <iframe width="640" height="268" src="https://www.youtube.com/embed/-mV4k7wvUac?si=1sykHxWwryncDJFu" title="Words from the Winners!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- :material-projector-screen-outline:{ .lg .middle } __Celebration Event Slides - Part 1__
    
    <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSLHoLW0B1yny-4t3aMZe-5fzNr4C5L-VeqnEDFXdi-l1I0gR46fN9wd9yIWIE00BWGEQpyQfqeZkUA/embed?start=true&loop=true&delayms=3000" frameborder="0" width="640" height="303" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

- :material-projector-screen-outline:{ .lg .middle } __Celebration Event Slides - Part 2__
    
    <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSJVIfhhZw81-v_NYhlLYA26MjgjBjS75riYiAlLf1rb6IQKDfprxQQV917b2nY_Q/embed?start=true&loop=true&delayms=3000" frameborder="0" width="640" height="303" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

</div>

## Summary

<div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/9; width: 100% !important;" src="https://www.youtube.com/embed/Q-WTcTOld08?si=PORCUPmbj2KfHYST" title="RoboRacer Sim Racing League @ CDC 2024" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>