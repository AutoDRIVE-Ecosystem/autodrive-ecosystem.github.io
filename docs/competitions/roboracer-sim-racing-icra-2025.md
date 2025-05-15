# RoboRacer Sim Racing League @ ICRA 2025

![RoboRacer Sim Racing League @ ICRA 2025](../assets/images/banners/RoboRacer Sim Racing @ ICRA 2025.png)

## About

<p align="justify">
<b>RoboRacer Autonomous Racing</b> is a semi-regular competition organized by an international community of researchers, engineers, and autonomous systems enthusiasts. The teams participating in the <b>24th RoboRacer Autonomous Racing Competition</b> at <a href="https://2025.ieee-icra.org">ICRA 2025</a> will write software for a 1:10 scaled autonomous racecar to fulfill the objectives of the competition: <b><i>drive fast but don’t crash!</i></b>
</p>

<p align="justify">
This time, we are organizing the third <b>RoboRacer Sim Racing League</b>, which leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an RoboRacer racecar within a virtual racetrack. Please see the accompanying video for a glimpse of the RoboRacer digital twins in action.
</p>

<div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/9; width: 100% !important;" src="https://www.youtube.com/embed/Rq7Wwcwn1uk?si=ngvop2-SfJJOIjWJ" title="Digital Twin of RoboRacer in AutoDRIVE Simulator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

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
| Apr 16, 2025 (5:30 – 6:30 PM EDT) | [Online Orientation](https://clemson.zoom.us/j/94807115758) |
| May 03 – May 05, 2025             | Qualification Round            |
| May 06, 2025                      | Qualification Results Declared |
| May 08, 2025                      | Competition Track Released     |
| May 11 – May 13, 2025             | Final Race                     |
| May 14, 2025                      | Competition Results Declared   |

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

    [:material-open-in-new: **AutoDRIVE Simulator:**](https://hub.docker.com/r/autodriveecosystem/autodrive_roboracer_sim) [`explore`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_sim/2025-icra-explore/images/sha256-71556ca735c7d3726150495bae8ffe2093b4c3e6441420d595906f076422bb58) | [`practice`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_sim/2025-icra-practice/images/sha256-b047b7345d9dd81ef4c1faf86a94dd62f4022c78cc8c1693aee39abda0f6208c) | [`compete`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_sim/2025-icra-compete/images/sha256-00a15bc00d60f67e321391b1a8fc0767a0eadf30b50fe07c399e95670111a791)

    [:material-open-in-new: **AutoDRIVE Devkit:**](https://hub.docker.com/r/autodriveecosystem/autodrive_roboracer_api) [`explore`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_api/2025-icra-explore/images/sha256-5cca86a81db106773685b41b42301adeeb7721c91cde3cf39e9cf9537b1bdcfe) | [`practice`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_api/2025-icra-practice/images/sha256-d086c01fa7f6025da18a6b73295e98b62bb6b6ceb9c86fa07a172135c3ceddce) | [`compete`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_api/2025-icra-compete/images/sha256-98962da9647b124c61176b531e3c788b1c50a77bcb7d5ae44ef5c69034d87b71)

-   :material-monitor:{ .lg .middle } __Local Resources__

    ---

    Get started with the competition framework locally, and worry about containerization later. 

    **AutoDRIVE Simulator:**
    
    `explore`&nbsp;&nbsp;&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_explore_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_explore_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_explore_macos.zip)

    `practice`&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_practice_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_practice_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_practice_macos.zip)

    `compete`&nbsp;&nbsp;&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_compete_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_compete_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_simulator_compete_macos.zip)

    **AutoDRIVE Devkit:**
    
    [:simple-ros: ROS 2](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/autodrive_devkit.zip)

-   :octicons-link-16:{ .lg .middle } __Quick Links__

    ---

    Links to be kept at your fingertips, for a smooth ride throughout the competition.

    **Schedule:** [:material-calendar-clock: Timeline](#timeline)

    **Registration:** [:material-file-document-edit: Form](https://forms.gle/zjj5dLDajUhnuTdL9)
    
    **Orientation:** [:fontawesome-solid-video: Zoom](https://clemson.zoom.us/j/94807115758) | [:octicons-video-16: Recording](https://youtu.be/Mit9c8B-06o) | [:material-projector-screen-outline: Slides](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-icra/orientation_slides.zip)

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

<div style="display: flex; justify-content: center;">
<a class="md-button" href="https://forms.gle/zjj5dLDajUhnuTdL9"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Registration Form</a>
</div>

<p align="justify">
Registration for the Sim Racing League is free of cost and separate from the Physical Racing League and the conference registrations themselves. The above form signs you up only for the Sim Racing League, and for its orientation and information sessions. Although you can participate in the Sim Racing League without attending the conference, we strongly encourage all competition participants to attend the conference in person. This will help you connect with the broader AutoDRIVE and RoboRacer communities, and you can also witness/participate in the physical RoboRacer autonomous racing competition!
</p>

<p align="justify">
Registered teams are added to the following table:
</p>

| SR. NO. | TEAM NAME                 | TEAM MEMBERS                  | ORGANIZATION                              | COUNTRY                              |
|:--------|:--------------------------|:------------------------------|:------------------------------------------|:-------------------------------------|
| 01      | fsociety                  | Ritesh Gole<br/>Kartikeya Gupta<br/>Raj Shah<br/>Goutham Jyothilal | Personal | India                            |
| 02      | Chasing Cop Car           | Jaihind J<br/>Aditya Ravichander | Personal                               | India                                |
| 03      | Alp Autonomous            | Ble Auriol                    | Alpha Space Robotics                      | Côte d'Ivoire                        |
| 04      | Bushra AlShehhi           | Bushra AlShehhi               | Khalifa University                        | United Arab Emirates (UAE)           |
| 05      | Technion F1TENTH Team     | Andrés Kaminker               | Technion                                  | Israel                               |
| 06      | bracavisionai             | Luis Bracamontes              | Personal                                  | Mexico                               |
| 07      | Finding Theta             | Michael Kudlaty               | Personal                                  | United States of America (USA)       |
| 08      | Team                      | Rajdeep Singh                 | Personal                                  | India                                |
| 09      | Mostafa Ahmed Sayed       | Mostafa Hassan                | Personal                                  | Egypt                                |
| 10      | Invincibles               | Elyas Saeed<br/>Ahmad Aljallaf<br/>Ali Asaad Al-Behadili<br/>Abdelrahman Zidan | Khalifa University | United Arab Emirates (UAE) |
| 11      | FuzzyGreenBlurs           | Akhil Sankar                  | Rutgers University                        | United States of America (USA)       |
| 12      | CarGoesVroom              | WenYang Lim                   | Personal                                  | Malaysia                             |
| 13      | Autobots                  | Shubham Barge<br/>Anshuman Jena<br/>Saivamshi Jilla | Personal            | India                                |
| 14      | Baby Driver               | Mason Notz<br/>Pallavi Kulkarni | Personal                                | United States of America (USA)       |
| 15      | TURTLEBOT                 | Jit Ern Lim<br/>Dustin Lim    | Personal                                  | Malaysia, Indonesia                  |
| 16      | Cair's                    | Siddhant Diwaker<br/>Chirag Makwana | Personal                            | India                                |
| 17      | BONG_RACERS               | Srinjoy Ganguly<br/>Pritish Saha<br/>Srijit Das | Personal                | India                                |
| 18      | AA Lab                    | Taha Kocyigit<br/>Omer Geyikci | Bogazici University                      | Turkiye                              |
| 19      | SUST Autodrive            | Abul Bashar Raz               | Shahjalal University of Science and Technology | Bangladesh                      |
| 20      | Beep Beep                 | Jeremy Seyssaud               | Personal                                  | France                               |
| 21      | Circuit Breakers          | Thanushraam Suresh Kumar<br/>Dhruv Pathak<br/>Atharva Patil | University of Colorado, Boulder | United States of America (USA) |
| 22      | Mamba                     | Hariharan Ravichandran        | Personal                                  | United States of America (USA)       |
| 23      | Racer X                   | Jonathan Nixon<br/>Roberto Ligeralde | Autonomous Racing at Penn          | United States of America (USA)       |
| 24      | IDEA_LAB                  | Ji-Hong Park<br/>Kim Ju-Young<br/>Chanki Kim<br/>Sujin Park<br/>Se Yeon Lee | Gyeongsang National University | South Korea |
| 25      | Abdulrahman Mahmoud       | Abdulrahman Mahmoud           | Personal                                  | Egypt                                |
| 26      | ESL                       | Christopher Flood<br/>Nico Martin<br/>JC Schoeman | Stellenbosch University | South Africa                       |
| 27      | VAUL                      | William Fecteau<br/>Nicolas Lauzon<br/>Tommy Bouchard-Lebrun | Laval University | Canada                         |
| 28      | Wall-E                    | Vinura Wanniarachchi          | Personal                                  | Sri Lanka                            |
| 29      | SoloDriver                | Hana Nabhan                   | Personal                                  | Egypt                                |
| 30      | Robotikusu                | Ananay Shiv                   | Indian Institute of Technology, Kharagpur | India                                |
| 31      | Shelby                    | S. Srikaanth<br/>S. Vignesh<br/>S. A. Gogulnath | Personal                | India                                |
| 32      | MMS Autonomous            | Osama Helal<br/>Ahmed Mwafy<br/>Abdelrahman Arafa<br/>Kirellos Youssef<br/>Kareem El Zahaby | Mansoura University | Egypt |
| 33      | Escuderia Poliposition    | Fernando Zolubas Preto<br/>Antonio Colombini Neto<br/>Carlos Alberto Arronte Delgado<br/>Gabriel Stephano Santos<br/>Luccas Barsotti<br/>Francisco Rodrigues Marazia<br/>Amanda Spagolla | Polytechnic School of the University of São Paulo | Brazil |
| 34      | Raptor                    | Ji Su Lee                     | Personal                                  | South Korea                          |
| 35      | Humble-CV                 | Ayush David<br/>Basil Shaji<br/>Cyril Jacob | Karunya Institute of Technology and Sciences | India               |
| 36      | Zancle E-Drive            | Gaetano Pio Pispisa<br/>Giovanni Lombardo<br/>Simone Castorino<br/>Gabriele Rinaldi<br/>Andrea Ferdinando Longoni | University of Messina | Italy  |
| 37      |Riverside Racers           | Alexander Totah<br/>Marcus Hsieh<br/>Amber Lin<br/>James Liu<br/>Hang Qiu | University of California, Riverside | United States of America (USA) |
| 38      | IslandDriver              | Eunhye Lee | Stony Brook University                                       | United States of America (USA)       |
| 39      | ICPS                      | Juan Tique<br/>Donovan Ho<br/>Andrew Mitchell | iCPS Lab, University of Central Florida | United States of America (USA) |
| 40      | Kanka                     | Yukang Cao<br/>Goktug Poyrazoglu | University of Minnesota                | United States of America (USA) |
| 41      | Ctrl+Drift                | Aditya Jambhale<br/>Chaitanya Bhatia<br/>Kaustubh Krishna<br/>Akshat Tambi<br/>Prerna Sharma<br/>Yashowardhan Singh | SRM Institute of Science and Technology | India |
| 42      | Overtechnologia           | Aditya Paul                   | Personal                                  | India                                |
| 43      | Autonomous Ground Vehicle | Swaminathan S K<br/>Shreyansh Kansal<br/>Daksh Yadav<br/>Ninaad Desai<br/>Rohan Singh<br/>Sandip Das<br/>Utsab Karan<br/>Varun Thirupathy<br/>Aditya Srivastava<br/>Sreyas Venkataraman<br/>Theyanesh E R | Indian Institute of Technology, Kharagpur | India |
| 44      | CAVREL-UCF                | Israel Charles<br/>Babak Soorchaei<br/>Devin Hunter<br/>Yaser Fallah | University of Central Florida | United States of America (USA) |
| 45      | Autoware Aces             | Po-Jen Wang<br/>Tran Huu Nhat Huy<br/>Alexander Kalmykov<br/>Atanasko Boris Mitrev | Autoware Foundation | United States of America (USA), Japan, Russia, North Macedonia |
| 46      | Ashesi ARCLab             | Emmanuel Korankye<br/>William Akuffo<br/>Joshua Nti<br/>Reginald Andrew Sai-Obadai<br/>Baron Afutu<br/>Joel Osei-Asamoah<br/>Kobena Enyam<br/>Samuel Akwensivie<br/>Appenteng Adjepong<br/>Desmond Hammond | Ashesi University | Ghana |
| 47      | QuillKraft                | Aryan Iyer                    | Indian Institute of Technology, Bombay    | India                                |
| 48      | PowerZero                 | Ramana Botta<br/>Venkat Prasad | Personal                                 | India                                |
| 49      | WARRacing                 | Dominik Schneider<br/>Danit Niwattananan<br/>Parham Rahimi | Personal     | Germany                              |
| 50      | The Impressionists        | Tanay Shah                    | Personal                                  | India                                |
| 51      | WATonomous                | Rodney Dong<br/>Mark Do<br/>Harsharan Rakhra<br/>Manjot Dola | University of Waterloo WATonomous Design Team | Canada |
| 52      | UO Autonomous Drive       | David Miranda<br/>Lucía Sánchez<br/>Miguel Santamaría | University of Oviedo | Spain                             |
| 53      | Smirnov Racing            | Kirill Smirnov                | K. Smirnov Robotics Ltd.                  | Cyprus                               |
| 54      | RUN-RUN-ChuraTaro         | Soya Aoki                     | Chura DATA Inc.                           | Japan                                |
| 55      | Arcanine                  | Shreyas Raorane               | University of Pennslvania                 | United States of America (USA)       |
| 56      | orangetongue              | Vittorio Cataffo<br/>Francesca Cataffo<br/>Federica Cataffo | Personal    | Italy                                |
| 57      | AsTenth Martin            | Ajay Shankar Sriram           | Chura DATA Inc.                           | United States of America (USA)       |
| 58      | PITT                      | Aragya Goyal<br/>Robert Exley | University of Pittsburgh                  | United States of America (USA)       |

!!! note
    The above table will be updated with newly registered teams within a few days of registration. Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you do not see your team entry for more than 7 days after registering.

<div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/8; width: 100% !important;" src="/../assets/images/competitions/2025 icra roboracer sim racing league/Map.html" title="Global Participation Map"  frameborder="0"></iframe>
</div>

<div style="display: flex; justify-content: center;">
<img src="/../assets/images/competitions/2025 icra roboracer sim racing league/Collage.png" title="Participating Organizations">
</div>

## Submission

<p align="justify">
Use the secure form below to make your team's submission for Phase 1 (Qualification Round) of the RoboRacer Sim Racing League. Please fill in your team's name and add the link to your team's DockerHub repository containing the autonomous racing stack. If you are using a private repository, make sure to add <a href="https://hub.docker.com/u/autodriveecosystem">autodriveecosystem</a> as a <a href="https://docs.docker.com/docker-hub/repos/access">collaborator to your repository</a>.
</p>

<div style="display: flex; justify-content: center;">
<a class="md-button" href="https://forms.gle/ioZy5SXYrA6DCnhG6"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Phase 1 Submission Form</a>
</div>

!!! warning
    Phase 1 submission window will close on May 03, 2025 (anywhere on Earth). Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you have any questions.

<p align="justify">
Use the secure form below to make your team's submission for Phase 2 (Final Race) of the RoboRacer Sim Racing League. Please fill in your team's name and add the link to your team's DockerHub repository containing the autonomous racing stack. If you are using a private repository, make sure to add <a href="https://hub.docker.com/u/autodriveecosystem">autodriveecosystem</a> as a <a href="https://docs.docker.com/docker-hub/repos/access">collaborator to your repository</a>.
</p>

<div style="display: flex; justify-content: center;">
<a class="md-button" href="https://forms.gle/MMVAPszcowRppESw9"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Phase 2 Submission Form</a>
</div>

!!! warning
    Phase 2 submission window will close on May 11, 2025 (anywhere on Earth). Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you have any questions.

## Results

**Phase 1: Qualification**

<p align="justify">
The following teams have qualified for the final time-attack race. Here are the official standings:
</p>

| RANK    | TEAM NAME                       | RACE TIME       | COLLISION COUNT | ADJUSTED RACE TIME | BEST LAP TIME |
|:--------|:--------------------------------|:----------------|:----------------|:-------------------|:--------------|
| 01      | 👏 Autonomous Ground Vehicle    | 67.86 s         | 0               | 67.86 s            | 6.77 s        |
| 02      | 👏 VAUL                         | 71.30 s         | 0               | 71.30 s            | 7.06 s        |
| 03      | 👏 Ctrl+Drift                   | 81.32 s         | 0               | 81.32 s            | 8.03 s        |
| 04      | 👏 Ashesi ARCLab                | 82.02 s         | 0               | 82.02 s            | 8.12 s        |
| 05      | 👏 ICPS                         | 82.70 s         | 0               | 82.70 s            | 8.24 s        |
| 06      | 👏 Escuderia Poliposition       | 75.18 s         | 1               | 85.18 s            | 7.40 s        |
| 07      | 👏 TURTLEBOT                    | 84.48 s         | 1               | 94.48 s            | 8.03 s        |
| 08      | 👏 IDEA_LAB                     | 95.12 s         | 0               | 95.12 s            | 9.35 s        |
| 09      | 👏 UO Autonomous Drive          | 81.37 s         | 2               | 101.37 s           | 8.01 s        |
| 10      | 👏 Chasing Cop Car              | 90.97 s         | 2               | 110.97 s           | 9.04 s        |
| 11      | 👏 Mamba                        | 118.15 s        | 0               | 118.15 s           | 11.79 s       |
| 12      | 👏 Racer X                      | 97.65 s         | 3               | 127.65 s           | 9.57 s        |
| 13      | 👏 Zancle E-Drive               | 128.71 s        | 0               | 128.71 s           | 12.69 s       |
| 14      | 👏 WARRacing                    | 128.76 s        | 1               | 138.76 s           | 12.79 s       |
| 15      | 👏 MMS Autonomous               | 120.25 s        | 3               | 150.25 s           | 11.74 s       |
| 16      | 👏 RUN-RUN-ChuraTaro            | 94.35 s         | 6               | 154.35 s           | 8.89 s        |
| 17      | 👏 Kanka                        | 141.43 s        | 2               | 161.43 s           | 13.86 s       |
| 18      | 👏 Autoware Aces                | 71.14 s         | 10              | 171.14 s           | 6.89 s        |
| 19      | 👏 bracavisionai                | 187.69 s        | 1               | 197.69 s           | 18.56 s       |
| 20      | 👏 Bushra AlShehhi              | 226.40 s        | 1               | 236.40 s           | 22.26 s       |
| 21      | 👏 ESL                          | 290.78 s        | 1               | 300.78 s           | 28.97 s       |

**Phase 2: Competition**

<p align="justify">
The following teams successfully finished the final time-attack race. Here are the official standings:
</p>

| RANK    | TEAM NAME                       | RACE TIME       | COLLISION COUNT | ADJUSTED RACE TIME | BEST LAP TIME |
|:--------|:--------------------------------|:----------------|:----------------|:-------------------|:--------------|
| 01      | 🥇 VAUL                         | 111.46 s        | 0               | 111.46 s           | 11.28 s       |
| 02      | 🥈 Autoware Aces                | 122.16 s        | 0               | 122.16 s           | 12.08 s       |
| 03      | 🥉 Kanka                        | 129.28 s        | 0               | 129.28 s           | 12.76 s       |
| 04      | 👏 UO Autonomous Drive          | 137.42 s        | 0               | 137.42 s           | 13.70 s       |
| 05      | 👏 ESL                          | 155.81 s        | 0               | 155.81 s           | 15.52 s       |
| 06      | 👏 IDEA_LAB                     | 193.24 s        | 0               | 193.24 s           | 18.33 s       |
| 07      | 👏 Ashesi ARCLab                | 188.67 s        | 2               | 208.67 s           | 18.67 s       |
| 08      | 👏 bracavisionai                | 221.03 s        | 0               | 221.03 s           | 22.06 s       |
| 09      | 👏 Autonomous Ground Vehicle    | 226.71 s        | 0               | 226.71 s           | 22.54 s       |
| 10      | 👏 Zancle E-Drive               | 149.19 s        | 10              | 249.19 s           | 14.81 s       |
| 10      | 👏 RUN-RUN-ChuraTaro            | 275.71 s        | 0               | 275.71 s           | 27.36 s       |
| 12      | 👏 Escuderia Poliposition       | 191.05 s        | 10              | 291.05 s           | 19.05 s       |
| 13      | 👏 ICPS                         | 297.31 s        | 4               | 337.31 s           | 29.02 s       |
| 14      | 👏 Ctrl+Drift                   | 287.98 s        | 10              | 387.98 s           | 28.74 s       |
| 15      | 👏 Bushra AlShehhi              | 395.36 s        | 1               | 405.36 s           | 37.76 s       |