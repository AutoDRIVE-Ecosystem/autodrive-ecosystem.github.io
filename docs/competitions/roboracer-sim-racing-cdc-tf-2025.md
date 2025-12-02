# RoboRacer Sim Racing League @ CDC 2025 and Techfest 2025

![RoboRacer Sim Racing League @ CDC Techfest 2025](../assets/images/banners/RoboRacer Sim Racing @ CDC Techfest 2025.png)

## About

<p align="justify">
<b>RoboRacer Autonomous Racing</b> is a semi-regular competition organized by an international community of researchers, engineers, and autonomous systems enthusiasts. The teams participating in the <b>25th and 26th RoboRacer Autonomous Racing Competitions</b> at <a href="https://cdc2025.ieeecss.org">CDC 2025</a> and <a href="https://techfest.org">Techfest 2025</a> will write software for a 1:10 scaled autonomous racecar to fulfill the objectives of the competition: <b><i>drive fast but don’t crash!</i></b>
</p>

<p align="justify">
This time, we are organizing the fourth <b>RoboRacer Sim Racing League</b>, which leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an RoboRacer racecar within a virtual racetrack. Please see the accompanying video for a glimpse of the RoboRacer digital twins in action.
</p>

<div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/9; width: 100% !important;" src="https://www.youtube.com/embed/Rq7Wwcwn1uk?si=ngvop2-SfJJOIjWJ" title="Digital Twin of RoboRacer in AutoDRIVE Simulator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<p align="justify">
The main focus of the Sim Racing League is a virtual competition with simulated cars and environments, which is accessible to everyone across the globe. For the combined <a href="https://cdc2025.ieeecss.org">CDC 2025</a> and <a href="https://techfest.org">Techfest 2025</a> competition, each team will be provided with a standardized simulation setup (in the form of a digital twin of the RoboRacer vehicle, and a digital twin of the Porto racetrack) within the high-fidelity <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a>. Additionally, teams will also be provided with a working implementation of the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a> to get started with developing their autonomy algorithms. Teams will have to develop perception, planning, and control algorithms to parse the real-time sensor data streamed from the simulator and generate control commands to be fed back to the simulated vehicle.
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
    If you are interested in autonomously racing physical RoboRacer vehicles, please check out the websites for [25th RoboRacer Autonomous Racing Competition](https://cdc2025-race.roboracer.ai) and [26th RoboRacer Autonomous Racing Competition](https://techfest.org/competitions/Roboracer), which will be held in person at <a href="https://cdc2025.ieeecss.org">CDC 2025</a> and <a href="https://techfest.org">Techfest 2025</a>, respectively. You can always register and compete in both physical and virtual competitions!

## Organizers

| <img src="/../assets/images/people/Rahul Mangharam.png" width="125"> | <img src="/../assets/images/people/Venkat Krovi.png" width="125"> | <img src="/../assets/images/people/Archak Mittal.png" width="125"> | <img src="/../assets/images/people/Johannes Betz.png" width="125"> |
|:------------------:|:-------------------:|:-------------------:|:-------------------:|
| [**Dr. Rahul Mangharam**](mailto:rahulm@seas.upenn.edu) | [**Dr. Venkat Krovi**](mailto:vkrovi@clemson.edu) | [**Dr. Archak Mittal**](mailto:archak@iitb.ac.in) | [**Dr. Johannes Betz**](mailto:johannes.betz@tum.de) |
| <img src="/../assets/images/people/Chinmay Samak.png" width="125"> | <img src="/../assets/images/people/Tanmay Samak.png" width="125"> | <img src="/../assets/images/people/Ahmad Amine.png" width="125"> | <img src="/../assets/images/people/Michael Coraluzzi.png" width="125"> |
| [**Chinmay Samak**](mailto:csamak@clemson.edu) | [**Tanmay Samak**](mailto:tsamak@clemson.edu) | [**Ahmad Amine**](mailto:aminea@seas.upenn.edu) | [**Michael Coraluzzi**](mailto:mike.coraluzzi@roboracer.ai) |

## Timeline

!!! warning
    Timeline is subject to change. Please keep checking this page for any updates.

| DATE                              | EVENT                          |
|:----------------------------------|:-------------------------------|
| Nov 01, 2025                      | Registration Opens             |
| Nov 28, 2025                      | Registration Closes            |
| Nov 29 – Nov 30, 2025             | Qualification Round            |
| Dec 01, 2025                      | Qualification Results Declared |
| Dec 02, 2025                      | Competition Track Released     |
| Dec 06 – Dec 07, 2025             | Final Race                     |
| Dec 08, 2025                      | Competition Results Declared   |

<p align="justify">
Following is a brief summary of each event:
</p>

<ul class="justify-list">
  <li><b>Registration:</b> Interested teams will register for the Sim Racing League.</li>
  <li><b>Qualification Round:</b> Teams will demonstrate successful completion of 10 laps around the practice track provided ahead of time.</li>
  <li><b>Qualification Results Declared:</b> Standings of all the qualified teams will be released.</li>
  <li><b>Competition Track Released:</b> Organizers will release the actual "competition track", which will be used for the final race. This track may be replicated in the physical race as well.</li>
  <li><b>Final Race:</b> Organizers will collect containerized algorithms from each team and connect them with the containerized simulator. Performance metrics of each team will be recorded.</li>
  <li><b>Competition Results Declared:</b> Standings of all the teams for the final race will be released.</li>
</ul>

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

    [:material-open-in-new: **Competition Rules**](../roboracer-sim-racing-rules-2025)

    [:material-open-in-new: **Technical Guide**](../roboracer-sim-racing-guide-2025)

-   :material-docker:{ .lg .middle } __Docker Containers__

    ---

    Download base container images for the competition and start developing your algorithms.

    [:material-open-in-new: **AutoDRIVE Simulator:**](https://hub.docker.com/r/autodriveecosystem/autodrive_roboracer_sim) [`explore`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_sim/2025-cdc-tf-explore/images/sha256-72887f78aaa12cf54913f77b41d4d057e8a98e5810b69c203b3653850b38f6c5) | [`practice`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_sim/2025-cdc-tf-practice/images/sha256-c4cf1b17646b85036c008c5e1994e4f53a0e340a675fd05ec18c5e03c07f4c0d) | `compete`

    [:material-open-in-new: **AutoDRIVE Devkit:**](https://hub.docker.com/r/autodriveecosystem/autodrive_roboracer_api) [`explore`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_api/2025-cdc-tf-explore/images/sha256-15a51f3b7b75085ff1d5a36f3c9b13343cc35c3aa3026afbce8e378c5c8c23b2) | [`practice`](https://hub.docker.com/layers/autodriveecosystem/autodrive_roboracer_api/2025-cdc-tf-practice/images/sha256-f0e47bc1e694a366cc1e8fe7e0df9bb2ef77d1cce6b724af90f250ddeb83f395) | `compete`

-   :material-monitor:{ .lg .middle } __Local Resources__

    ---

    Get started with the competition framework locally, and worry about containerization later. 

    **AutoDRIVE Simulator:**
    
    `explore`&nbsp;&nbsp;&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_explore_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_explore_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_explore_macos.zip)

    `practice`&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_practice_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_practice_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_practice_macos.zip)

    `compete`&nbsp;&nbsp;&nbsp; [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_compete_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_compete_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_simulator_compete_macos.zip)

    **AutoDRIVE Devkit:**
    
    [:simple-ros: ROS 2](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/releases/download/2025-cdc-tf/autodrive_devkit.zip)

-   :octicons-link-16:{ .lg .middle } __Quick Links__

    ---

    Links to be kept at your fingertips, for a smooth ride throughout the competition.

    **Schedule:** [:material-calendar-clock: Timeline](#timeline)

    **Registration:** [:material-file-document-edit: Form](https://forms.gle/wGQYoxS1ddevHMcu7)
    
    **Documentation:** [:material-file-document: Rule Book](../roboracer-sim-racing-rules-2025) | [:material-file-document: Tech Guide](../roboracer-sim-racing-guide-2025)

    **Communication:** [:material-slack: Slack](https://join.slack.com/t/autodrive-ecosystem/shared_invite/zt-2oeg2hce8-0JvasvnBM1M_wUdDTWRuKw)

    **Submission:** [:material-file-document-edit: Phase 1](https://forms.gle/X3aaPGwkR9zQTKqm7) | [:material-file-document-edit: Phase 2]()

    **Results:** [:fontawesome-solid-trophy: Phase 1](#results) | [:fontawesome-solid-trophy: Phase 2](#results)
</div>

!!! question
    You can post general questions on the [:material-slack: AutoDRIVE Slack](https://join.slack.com/t/autodrive-ecosystem/shared_invite/zt-2oeg2hce8-0JvasvnBM1M_wUdDTWRuKw) workspace; this is the preferred modality. Technical questions can be also posted as [:material-github: GitHub Issues](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/issues) or [:material-github: GitHub Discussions](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-RoboRacer-Sim-Racing/discussions). For any other questions or concerns that cannot be posted publicly, please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu).

## Registration

<p align="justify">
This competition is open to everyone around the world - students, researchers, hobbyists, professionals, or anyone else who is interested. A team can consist of multiple teammates. Teams with only one person are also allowed. However, a person cannot be a part of more than one team.
</p>

<div style="display: flex; justify-content: center;">
<a class="md-button" href="https://forms.gle/wGQYoxS1ddevHMcu7"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Registration Form</a>
</div>

<p align="justify">
Registration for the Sim Racing League is free of cost and separate from the Physical Racing League and the conference/event registrations themselves. The above form signs you up only for the Sim Racing League. Although you can participate in the Sim Racing League without attending the conference/event, we strongly encourage all competition participants to attend the conference/event in person. This will help you connect with the broader AutoDRIVE and RoboRacer communities, and you can also witness/participate in the physical RoboRacer autonomous racing competition!
</p>

<p align="justify">
Registered teams are added to the following table:
</p>

| SR. NO. | TEAM NAME                 | TEAM MEMBERS                  | ORGANIZATION                              | COUNTRY                              |
|:--------|:--------------------------|:------------------------------|:------------------------------------------|:-------------------------------------|
| 01      | 魔法师大大                 | Chen Zexiang                  | Personal                                  | China                                |
| 02      | Mamba                     | Hariharan Ravichandran        | Personal                                  | United States of America (USA)       |
| 03      | Finding Theta             | Michael Kudlaty               | Personal                                  | United States of America (USA)       |
| 04      | Devrim                    | Melih Akay                    | Middle East Technical University          | Republic of Türkiye                  |
| 05      | Khepa_BobCats             | MdSakifUddin Khan<br/>KaziSifatul Islam<br/>Rashedul Hasan<br/>Sayan Paul | Personal | United States of America (USA) |
| 06      | MIA                       | Srivardhini Veeraragavan<br/>Krishna Vihaan Mokkapaty<br/>Souptik Sinha<br/>Siddarth Menon<br/>Aparna Asokan | Personal | Malaysia |
| 07      | Pathline                  | Albert Sagré                  | Personal                                  | Spain                                |
| 08      | MonacoF1                  | Gerardo Puga<br/>Ariel Lowy<br/>Diego Palma<br/>Emiliano Alban<br/>Enrique Abramzon<br/>Florencia Battocchia<br/>Juan Manuel Carosella<br/>Juan Manuel Gomez Vasquez<br/>Michel Hidalgo<br/>Nicolás de Lima | Ekumen | Argentina, Colombia, Ecuador, Peru |
| 09      | ESL                       | Nico Martin<br/>Christopher Flood | Stellenbosch University               | South Africa                         |
| 10      | bracavisionai             | Luis Bracamontes              | Personal                                  | Mexico                               |
| 11      | Gator Autonomous Racing   | Christopher Oeltjon<br/>Jackie Wang<br/>Gabrielle Cammarata<br/>Trevor Turnquist | University of Florida | United States of America (USA) |
| 12      | E-Rally                   | Morad Singer<br/>Ahmed Mohammed<br/>Abdelhamid Raafat<br/>Ramiz Sayed | Helwan University | Egypt                |
| 13      | IrohazakaJump             | Fritz Andrew Graciano<br/>Gede Bagus Wirayasa<br/>Kelvin Pratama | National Dong Hwa University | Indonesia      |
| 14      | VAUL - Old but Gold       | William Fecteau<br/>Nicolas Lauzon<br/>Tommy Bouchard-Lebrun | Laval University | Canada                         |
| 15      | VAUL - Young Guns         | Mohamed Billo Barry<br/>Achy Chris Yohann Ekissi<br/>Rahul Iyer<br/>Jayson Poirier<br/>Alissa Audet<br/>Teddy Emmanuel Kana Boumkwo II | Laval University | Canada |
| 16      | Raga Racing               | VaishnavaHari Seenivasan      | Personal                                  | Germany                              |
| 17      | RoboCORE                  | Mahdis Rabbani<br/>Armin Abdolmohammadi<br/>Mohammad Abtahi<br/>Farhang Motallebiaraghi<br/>Navid Mojahed<br/>Shima Nazari | University of California, Davis | United States of America (USA) |
| 18      | Element                   | Sree Penisetty                | Personal                                  | India                                |
| 19      | RAPTOR                    | Jisu Lee                      | Hanyang University                        | South Korea                          |
| 20      | EPIIBOTS                  | Leandro Henrique Vidigal Sousa<br/>Elias José de Rezende Freitas<br/>Christyan Ribeiro de Amorim Honorato<br/>Raissa Rúbia Braga Gonçalves<br/>Luciano Cunha de Araújo Pimenta | Instituto Federal de Minas Gerais | Brazil |
| 21      | Phoenix Racing            | Harun Teper<br/>Utku Pazarci<br/>Adem Jabri<br/>Tim Gliemann<br/>Louis Radtke<br/>Nico Koltermann | TU Dortmund University | Germany |
| 22      | RUN-RUN-ChuraTaro         | Soya Aoki                     | Chura DATA Inc.                           | Japan                                |
| 23      | UO Astur Martin           | Pablo Suárez<br/>Pedro Martín<br/>Mateo Cobo<br/>Álvaro Tamargo | University of Oviedo | Spain                   |
| 24      | Assiut Motorsport         | Mohamed Emadeldeen<br/>Doaa Essam<br/>Ahmed Nadi<br/>Mina Waheed<br/>Shams Sabry<br/>Kareem Salah<br/>Abdallah Elkashef<br/>Habiba Sayed<br/>Moataz Hesham<br/>Mohamed Mostafa | Assiut University | Egypt |
| 25      | F1tenth@UCI               | Alistair Keiller<br/>Daniel Huynh<br/>Allen Dai<br/>Bradley Chu<br/>Jeffery Lee<br/>George Rajamachvili<br/>Arthur Chung | University Of California, Irvine | United States of America (USA) |
| 26      | YTU AESK                  | Atahan Taşal<br/>Mahmut Esat Baydaş<br/>Rabia Hanne Akyüz<br/>Efe Erbağ<br/>Kubilay Kayra Kivrak<br/>Berke Sinan Yetkin | Yildiz Technical University | Republic of Türkiye | 
| 27      | YTU-AESK-RL               | Burak Hazır<br/>Berdan Fırat Doğan<br/>Efe Pehlivan<br/>Selinay Dikdere<br/>Muhammet Yusuf Oral | Yildiz Technical University | Republic of Türkiye |
| 28      | Solo-Drive                | Mohammed Ibrahim              | Heriot-Watt University                    | United Arab Emirates (UAE)           |
| 29      | Autonomous Ground Vehicle | Akshit Goyal<br/>Utsab Karan<br/>Rohan Singh<br/>Sandip Das<br/>Ninaad Desai<br/>Theyanesh E R<br/>Jinansh Dalal<br/>Tanishq Saxena<br/>Yug Bargaway<br/>Mahin Sanklecha<br/>Shrey Nayakpara<br/>Satyam Chakravorty<br/>Aneesh Lade<br/>Gokul Vemuri<br/>Akshat Shukla<br/>Netra Nandankar | Indian Institute of Technology, Kharagpur | India           |
| 30      | Jarvis                    | Muhilan M<br/>Rohit Balaji<br/>Chaitanya Bhatia<br/>Sujal Choudhary<br/>Asvithh Sivakumar<br/>Akash Kandasamy<br/>Devanand P | SRM Institute of Science and Technology | India |
| 31      | SART                      | Seyyed Ali Kakaei<br/>Siavash Sepahi<br/>Abdolreza Pasharavesh | Sharif University of Technology | Iran          |
| 32      | Meteoritonomous           | Seif Ashraf Mohammed Hussein<br/>Omar Mostafa<br/>Shrouq Hamdy<br/>Abdelbadee Yehia<br/>Abdelrahman Talaat<br/>Abdelrahman Ehab<br/>Abdelrahman Hamouda<br/>Ahmed Hazem<br/>Ahmed M. Khalafallah<br/>Fagr Ahmed<br/>Hatem Safwat<br/>Jana Mohamed<br/>Khalid Ashraf<br/>MIna Rushdy Rady<br/>Mohamed Fouad<br/>Mohamed Shaaban<br/>Mohamed Abdelatif<br/>Abdelrahman Hatem<br/>Eman Mohamed<br/>Nourhan Anter<br/>Sajda Mohamed<br/>Sama Ahmed<br/>Sama Mohamed | Sohag University | Egypt                              |
| 33      | Fifty Four                | Anonymous                     | Personal                                  | Egypt                                |
| 34      | BlindRacer                | Kamallesh Umasankar           | Personal                                  | India                                |
| 35      | HumbleOps                 | Ayush David<br/>Cyril Jacob<br/>Basil Shaji | Karunya University          | India                                |
| 36      | SKG                       | Anvesh SK<br/>Subhash G       | Personal                                  | India                                |
| 37      | Al-Jazari                 | Taha Koçyiğit                 | The Institute for Data Science & Artificial Intelligence at Boğaziçi University | Republic of Türkiye |
| 38      | PARCar                    | Pranav Bhatt                  | University of California, Berkeley        | United States of America (USA)       |
| 39      | Hero Comes Last           | Omar Abdelrady                | Schmalkalden Applied science university   | Germany                              |
| 40      | 321GO                     | Ashwin Pandey                 | Personal                                  | India                                |

!!! note
    The above table will be updated with newly registered teams within a few days of registration. Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you do not see your team entry for more than 7 days after registering.

<!-- <div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/8; width: 100% !important;" src="/../assets/images/competitions/2025 icra roboracer sim racing league/Map.html" title="Global Participation Map"  frameborder="0"></iframe>
</div>

<div style="display: flex; justify-content: center;">
<img src="/../assets/images/competitions/2025 icra roboracer sim racing league/Collage.png" title="Participating Organizations">
</div> -->

## Submission

<p align="justify">
Use the secure form below to make your team's submission for Phase 1 (Qualification Round) of the RoboRacer Sim Racing League. Please fill in your team's name and add the link to your team's DockerHub repository containing the autonomous racing stack. If you are using a private repository, make sure to add <a href="https://hub.docker.com/u/autodriveecosystem">autodriveecosystem</a> as a <a href="https://docs.docker.com/docker-hub/repos/access">collaborator to your repository</a>.
</p>

<div style="display: flex; justify-content: center;">
<a class="md-button" href="https://forms.gle/X3aaPGwkR9zQTKqm7"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Phase 1 Submission Form</a>
</div>

!!! warning
    Phase 1 submission window will close on Nov 29, 2025 (anywhere on Earth). Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you have any questions.

<p align="justify">
Use the secure form below to make your team's submission for Phase 2 (Final Race) of the RoboRacer Sim Racing League. Please fill in your team's name and add the link to your team's DockerHub repository containing the autonomous racing stack. If you are using a private repository, make sure to add <a href="https://hub.docker.com/u/autodriveecosystem">autodriveecosystem</a> as a <a href="https://docs.docker.com/docker-hub/repos/access">collaborator to your repository</a>.
</p>

<div style="display: flex; justify-content: center;">
<a class="md-button" href=""><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6 2c-1.11 0-2 .89-2 2v16a2 2 0 0 0 2 2h4v-1.91L12.09 18H6v-2h8.09l2-2H6v-2h12.09L20 10.09V8l-6-6H6m7 1.5L18.5 9H13V3.5m7.15 9.5a.55.55 0 0 0-.4.16l-1.02 1.02 2.09 2.08 1.02-1.01c.21-.22.21-.58 0-.79l-1.3-1.3a.544.544 0 0 0-.39-.16m-2.01 1.77L12 20.92V23h2.08l6.15-6.15-2.09-2.08Z"/></svg></span> Phase 2 Submission Form</a>
</div>

!!! warning
    Phase 2 submission window will close on Dec 06, 2025 (anywhere on Earth). Please contact [:material-email: Chinmay Samak](mailto:csamak@clemson.edu) or [:material-email: Tanmay Samak](mailto:tsamak@clemson.edu) if you have any questions.

## Results

**Phase 1: Qualification**

<p align="justify">
The following teams have qualified for the final time-attack race. Here are the official standings:
</p>

| RANK    | TEAM NAME                       | RACE TIME       | COLLISION COUNT | ADJUSTED RACE TIME | BEST LAP TIME | VIDEO                                                                     |
|:--------|:--------------------------------|:----------------|:----------------|:-------------------|:--------------|:--------------------------------------------------------------------------|
| 01      | 👏 Mamba                       	| 65.41 s         | 0               | 65.41 s            | 6.53 s        |                                                                           |
| 02      | 👏 VAUL - Old but Gold         	| 65.65 s         | 0               | 65.65 s            | 6.49 s        |                                                                           |
| 03      | 👏 Phoenix Racing             	| 70.35 s         | 0               | 70.35 s            | 7.00 s        |                                                                           |
| 04      | 👏 Solo-Drive                 	| 71.42 s         | 0               | 71.42 s            | 7.11 s        |                                                                           |
| 05      | 👏 Autonomous Ground Vehicle	| 80.44 s         | 0               | 80.44 s            | 7.99 s        |                                                                           |
| 06      | 👏 RUN-RUN-ChuraTaro           	| 84.33 s         | 0               | 84.33 s            | 8.37 s        |                                                                           |
| 07      | 👏 IrohazakaJump               	| 85.38 s         | 0               | 85.38 s            | 8.51 s        |                                                                           |
| 08      | 👏 YTU-AESK-RL                 	| 94.96 s         | 0               | 94.96 s            | 8.98 s        |                                                                           |
| 09      | 👏 MonacoF1                    	| 98.69 s         | 0               | 98.69 s            | 9.81 s        |                                                                           |
| 10      | 👏 PARCar                      	| 113.30 s        | 0               | 113.30 s           | 11.32 s       |                                                                           |
| 11      | 👏 Jarvis                      	| 118.37 s        | 0               | 118.37 s           | 11.83 s       |                                                                           |
| 12      | 👏 VAUL - Young Guns           	| 118.40 s        | 0               | 118.40 s           | 11.84 s       |                                                                           |
| 13      | 👏 Assiut Motorsport	        | 118.83 s        | 0               | 118.83 s           | 11.85 s       |                                                                           |
| 14      | 👏 UO Astur Martin             	| 120.42 s        | 0               | 120.42 s           | 12.04 s       |                                                                           |
| 15      | 👏 E-Rally                  	| 124.30 s        | 0               | 124.30 s           | 12.41 s       |                                                                           |
| 16      | 👏 YTU AESK                    	| 123.39 s        | 1               | 133.39 s           | 12.19 s       |                                                                           |
| 17      | 👏 RoboCORE                    	| 162.99 s        | 0               | 162.99 s           | 16.18 s       |                                                                           |
| 18      | 👏 bracavisionai            	| 185.69 s        | 0               | 185.69 s           | 18.48 s       |                                                                           |
| 19      | 👏 Gator Autonomous Racing     	| 225.60 s        | 0               | 225.60 s           | 22.55 s       |                                                                           |
| 20      | 👏 Hero Comes Last           	| 301.73 s        | 0               | 301.73 s           | 30.02 s       |                                                                           |

**Phase 2: Competition**

<p align="justify">
Competition results will be declared on Dec 08, 2025.
</p>

<!-- <p align="justify">
The following teams successfully finished the final time-attack race. Here are the official standings:
</p> -->

| RANK    | TEAM NAME                       | RACE TIME       | COLLISION COUNT | ADJUSTED RACE TIME | BEST LAP TIME | VIDEO                                                                     |
|:--------|:--------------------------------|:----------------|:----------------|:-------------------|:--------------|:--------------------------------------------------------------------------|

## Summary

<p align="justify">
A summary video will be posted here after the competition.
</p>

<!-- <div style="display: flex; justify-content: center;">
<iframe style="aspect-ratio: 16/9; width: 100% !important;" src="https://www.youtube.com/embed/oObgg_MCU4U?si=PoG8ilw_ovGh71Dj" title="RoboRacer Sim Racing League @ ICRA 2025" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div> -->
