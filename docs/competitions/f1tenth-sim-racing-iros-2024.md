# F1TENTH Sim Racing League @ IROS 2024

![F1TENTH Sim Racing League @ IROS 2024](../assets/images/banners/F1TENTH Sim Racing @ IROS 2024.png)

## About

<p align="justify">
<b>F1TENTH Autonomous Racing</b> is a semi-regular competition organized by an international community of researchers, engineers, and autonomous systems enthusiasts. The teams participating in the <b>21st F1TENTH Autonomous Grand Prix</b> at IROS 2024 will write software for a 1:10 scaled autonomous race car to fulfill the objectives for the competition: <b><i>drive fast but don’t crash!</i></b>
</p>

<p align="justify">
This time, we are organizing the first ever <b>F1TENTH Sim Racing League</b>, which leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an F1TENTH racecar within a virtual racetrack. Please see the accompanying video for a glimpse of the F1TENTH digital twins in action.
</p>

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rq7Wwcwn1uk?si=ngvop2-SfJJOIjWJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

<p align="justify">
The main focus of the Sim Racing League is a virtual competition with simulated cars and environments, which is accessible to everyone across the globe. For the IROS 2024 competition, each team will be provided with a standardized simulation setup (in the form of a digital twin of the F1TENTH vehicle, and a digital twin of the Porto racetrack) within the high-fidelity <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a>. Additionally, teams will also be provided with a working implementation of the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a> to get started with developing their autonomy algorithms. Teams will have to develop perception, planning, and control algorithms to parse the real-time sensor data streamed from the simulator and generate control commands to be fed back to the simulated vehicle.
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
    If you are interested in autonomously racing physical F1TENTH vehicles, please check out the website for [21st F1TENTH Autonomous Grand Prix](https://iros2024-race.f1tenth.org), which will be held in person at IROS 2024. You can always register and compete in both physical and virtual competitions!

## Organizers

| <img src="/../assets/images/people/Rahul Mangharam.png" width="125"> | <img src="/../assets/images/people/Venkat Krovi.png" width="125"> | <img src="/../assets/images/people/Johannes Betz.png" width="125"> | <img src="/../assets/images/people/Chinmay Samak.png" width="125"> | <img src="/../assets/images/people/Tanmay Samak.png" width="125"> |
|:------------------:|:-------------------:|:-------------------:|:-------------------:|:-------------------:|
| [**Dr. Rahul Mangharam**](mailto:rahulm@seas.upenn.edu) | [**Dr. Venkat Krovi**](mailto:vkrovi@clemson.edu) | [**Dr. Johannes Betz**](mailto:johannes.betz@tum.de) | [**Chinmay Samak**](mailto:csamak@clemson.edu) | [**Tanmay Samak**](mailto:tsamak@clemson.edu) |
| <img src="/../assets/images/people/Ahmad Amine.png" width="125"> | <img src="/../assets/images/people/Hongrui Zeng.png" width="125"> | <img src="/../assets/images/people/Fabio Bonsignorio.png" width="125"> | <img src="/../assets/images/people/Enrica Zereik.png" width="125"> | <img src="/../assets/images/people/Bilal Hassan.png" width="125"> |
| [**Ahmad Amine**](mailto:aminea@seas.upenn.edu) | [**Hongrui Zheng**](mailto:hongruiz@seas.upnn.edu) | [**Dr. Fabio Bonsignorio**](mailto:fabio.bonsignorio@fer.unizg.hr) | [**Dr. Enrica Zereik**](mailto:enrica.zereik@cnr.it) | [**Dr. Bilal Hassan**](mailto:bilal.hassan@ku.ac.ae) |
| <img src="/../assets/images/people/Bushra Alshehhi.png" width="125"> | <img src="/../assets/images/people/Fady Alnajjar.png" width="125"> | <img src="/../assets/images/people/Majd Khonji.png" width="125"> | <img src="/../assets/images/people/Hamad Karaki.png" width="125"> | <img src="/../assets/images/people/Pedro Lima.png" width="125"> |
| [**Bushra Alshehhi**](mailto:100050085@ku.ac.ae) | [**Dr. Fady Alnajjar**](mailto:fady.alnajjar@uaeu.ac.ae) | [**Dr. Majid Khonji**](mailto:majid.khonji@ku.ac.ae) | [**Dr. Hamad Karaki**](mailto:hamad.karki@ku.ac.ae) | [**Dr. Pedro Lima**](mailto:tp.aobsilu.ocincet@amil.ordep) |

## Timeline
    
!!! warning
    Timeline is subject to change. Please keep checking this page for any updates.

| DATE                  | EVENT                      |
|:----------------------|:---------------------------|
| Jul 22, 2024          | Registration Opens         |
| Aug 31, 2024          | Registration Closes        |
| Sep 02, 2024          | Online Orientation 1       |
| Sep 17, 2024          | Online Orientation 2       |
| Sep 28 – Sep 29, 2024 | Qualification Round        |
| Oct 04, 2024          | Competition Track Released |
| Oct 05 – Oct 06, 2024 | Final Race                 |
| Oct 07, 2024          | Results Declared           |

<p align="justify">
Following is a brief summary of each event:
</p>

<ul class="justify-list">
  <li><b>Registration:</b> Interested teams will register for the Sim Racing League.</li>
  <li><b>Online Orientation 1:</b> Organizers will explain the competition rules and guidelines, and demonstrate how to use the simulation framework.</li>
  <li><b>Online Orientation 2:</b> Organizers will check progress of the participating teams and help with any technical difficulties.</li>
  <li><b>Qualification Round:</b> Teams will demonstrate successful completion of 10 laps around the practice track provided ahead of time.</li>
  <li><b>Competition Track Released:</b> Organizers will release the actual "competition track", which will be used for the final race. This track may be replicated in the physical race as well.</li>
  <li><b>Final Race:</b> Organizers will collect containerized algorithms from each team and connect them with the containerized simulator. Performance metrics of each team will be recorded.</li>
  <li><b>Results Declared:</b> Standings of all the teams will be released.</li>
</ul>

!!! info
    The F1TENTH Sim Racing League will be held approximately 1 week ahead of IROS 2024 and the performance metrics will be made available to the teams. Discussions are underway with the IROS organizing team to allow teams to analyze and present their approach/results in a short (~10 min) presentation in a special session at IROS 2024.

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

    **AutoDRIVE Simulator:** [:simple-linux: Linux](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-iros-practice/autodrive_simulator_linux.zip) | [:material-microsoft: Windows](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-iros-practice/autodrive_simulator_windows.zip) | [:simple-apple: macOS](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-iros-practice/autodrive_simulator_macos.zip)

    **AutoDRIVE Devkit:** [:simple-ros: ROS 2](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/releases/download/2024-iros-practice/autodrive_devkit.zip)

-   :fontawesome-solid-users:{ .lg .middle } __Orientation Resources__

    ---

    Join the online orientation sessions or review what we covered there.

    **Orientation 1:** [:fontawesome-solid-video: Zoom](https://clemson.zoom.us/s/96939189458) | :octicons-video-24: Recording | :material-microsoft-powerpoint: Slides

    **Orientation 2:** :fontawesome-solid-video: Zoom | :octicons-video-24: Recording | :material-microsoft-powerpoint: Slides

</div>

!!! question
    You can post general questions on the [AutoDRIVE Slack](https://join.slack.com/t/autodrive-ecosystem/shared_invite/zt-2oeg2hce8-0JvasvnBM1M_wUdDTWRuKw) workspace; this is the preferred modality. Technical questions can be also posted as [GitHub Issues](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/issues) or [GitHub Discussions](https://github.com/AutoDRIVE-Ecosystem/AutoDRIVE-F1TENTH-Sim-Racing/discussions). For any other questions or concerns that cannot be posted publicly, please contact [Chinmay Samak](mailto:csamak@clemson.edu) or [Tanmay Samak](mailto:tsamak@clemson.edu).

## Registration

<p align="justify">
This competition is open for everyone around the world - students, researchers, hobbyists, professionals, or anyone else who is interested. A team can consist of multiple teammates. Teams with only one person are also allowed.
</p>

<center>
[:material-file-document-edit: Registration Form](https://forms.gle/hBCctUaHcvFoB9zHA){.md-button}
</center>

<p align="justify">
Registration for the Sim Racing League is free of cost and separate from the Physical Racing League and the conference registrations themselves. The above form signs you up only for the Sim Racing League, and for its orientation and information sessions. Although you can participate in the Sim Racing League without attending the conference, we strongly encourage all competition participants to attend the conference in person. This will help you connect with the broader AutoDRIVE and F1TENTH communities, and you can also witness/participate in the physical F1TENTH autonomous racing competition!
</p>

<p align="justify">
Registered teams are added to the following table:
</p>

| SR. NO. | TEAM NAME                 | TEAM MEMBERS                  | ORGANIZATION                              |
|:--------|:--------------------------|:------------------------------|:------------------------------------------|
| 01      | SAGOL                     | JoonCheol Park                | Personal                                  |
| 02      | Solo                      | Abdul Rahman Khader           | Khalifa University                        |
| 03      | OptimusPrime              | Sahruday Patti                | University of Maryland, College Park      |
| 04      | Velizar Zlatev            | Velizar Zlatev                | University of Bristol                     |
| 05      | Beryllium                 | Ronnie Romman                 | Personal                                  |
| 06      | Cornell Electric Vehicles | Jason Klein<br/>Eric Marchetti<br/>Zach Chosed<br/>Utku Melemetci<br/>Sidharth Rao<br/>Myles Pasetsky<br/>Zephan Sanghani<br/>Sia Chitnis<br/>Nicole Sin | Cornell University |
| 07      | Robotisim Dev             | Muhammad Luqman<br/>Yusuf Butt | Robotisim                                |
| 08      | Log Robotics              | Logesh G                      | Bannari Amman Institute of Technology     |
| 09      | Lone Rider                | Akshay Laddha                 | Indian Institute of Technology, Bombay    |
| 10      | Atlas 2.0                 | Manav Gagvani                 | Purdue University                         |
| 11      | The Buttowskis            | Kalash Jain                   | Pandit Deendayal Energy University        |
| 12      | Hanuman Parakram          | Dheeraj Bhurewar<br/>Vaibhav Wanere | Personal                            |
| 13      | Pallas                    | Haris Khan                    | Skoltech                                  |
| 14      | Gopher Speedsters         | Sujeendra Ramesh              | University of Minnesota, Twin Cities      |
| 15      | Autopilots                | Nouf Aljaberi<br/>Amna Muhammad<br/>Hajar Alnaqbi<br/>Shouq Zanki<br/>Sara Almessabie<br/> | United Arab Emirates University |
| 16      | i3                        | Pranav Kallem                 | Personal                                  |
| 17      | RobotX & More             | Oussama Errouji<br/>Imad-Eddine NACIRI | Euro Mediterranean University of Fez |
| 18      | IEEE Zagazig SB           | Abdulrahman Omar<br/>Hossam Elsherbiny<br/>Essam Shenhab<br/>Eman Abdelhamed<br/>Abdullah Elmasry<br/>Salma Swailem<br/>Merna Atef<br/>Amr Yasser<br/>Mahmoud Samy<br/>Mostafa Asaad<br/>Menna Gamal<br/>Ahmed Medhat   | Zagazig University |
| 19      | AMUGAE                    | Kim Amugae                    | Personal                                  |
| 20      | TURTLEBOT                 | Jit Ern Lim                   | Personal                                  |
| 21      | Byte Benders              | Bhajneet Singh Bedi           | Personal                                  |
| 22      | KGX                       | Hareesh R<br/>Raja Rajan K<br/>Ramesh Patel D<br/>Marudhu Paandian K<br/>Bhuvaneshwari Kanagaraj | KGISL Institute of technology |
| 23      | NaN                       | Hariharan Ravichandran<br/>Siva Vignesh Krishnan Chidambaram | Personal   |
| 24      | Vortex                    | Chinmay K                     | National Institute of Technology, Karnataka |
| 25      | bracaai                   | Luis M Bracamontes<br/>Luis Bracamontes | Braca Vision                    |
| 26      | ASU Racing Team           | Abdallah Ismail<br/>Mahmoud Omar<br/>Hussien Algendy<br/>Serag Abdelmohsen<br/>Ammar Ahmed<br/>Ahmed Sallam<br/>Malk Hany | Ain Shams University |
| 27      | TurboX                    | Dheeraj Bhogisetty            | Personal                                  |
| 28      | TractionX                 | Ameya Bagal<br/>Ananya Das<br/>Amizhthni PRK<br/>Aayush Ranawat | Indian Institute of Technology, Madras |
| 29      | Urban AI                  | Adham Fayad<br/>Abdulrahman Ahmed<br/>Nabil Fouda<br/>George Welson<br/>Muhab Muhammed<br/>Mostafa Samy | Ain Shams University |
| 30      | fstMINI                   | José Mateus<br/>Duarte Domingues | Instituto Superior Técnico             |
| 31      | Buggy Coders              | Cody Uehara                   | Personal                                  |
| 32      | AutoVision                | Luis Bracamontes              | Personal                                  |
| 33      | Autobots                  | Shubham Barge<br/>Anshuman Jena | Personal                                |
| 34      | Kyber-Kabs                | Aditya Jambhale               | SRM Institute of Science and Technology   |
| 35      | Shoubra Racing Team       | Mazen Khaled<br/>Hazem Abuelanin<br/>Hana Ahmed<br/>Mohamed Alaa<br/>Abdelghafar Mohamad<br/>Abdelrahman Salah<br/>Malak Mounir<br/>Razan Ahmed<br/>Mohamed Hamdy<br/>Abdelrahman Osama | Benha University |
| 36      | SUST AutoDrive            | Abul Bashar Raz<br/>Ad-Deen Mahbub<br/>Shafi Abdullah<br/>Fardeen Mosharraf<br/>Redwan Hassan<br/>Taj Ahmed | Shahjalal University of Science and Technology |
| 37      | VersusAI                  | Junior Jesus<br/>Alisson Kolling<br/>Pedro Pinheiro<br/>Victor Kich | Universidade Federal do Rio Grande |
| 38      | vijAYAM                   | Adarsh Baburaj                | Manipal University (MU), Dubai |
| 39      | OutRunner                 | Nihad Jifri<br/>Arif Sidhiequ<br/>Midhun Manoharan | Personal             |
| 40      | simracer                  | Vinura Wanniarachchi          | Personal                                  |
| 41      | Phoenix                   | Aman Kumar Singh<br/>Lakshmikanth Nageswar<br/>Kandregula Abhinav<br/>Suchi Sharma | Personal |
| 42      | KU F1TENTH                | Riley Anderson<br/>Jackson Yanek | The University of Kansas               |
| 43      | Void                      | Gonna Yaswanth<br/>Prajyot Jadhav | Personal                              |
| 44      | Aztec Autonomous Racing Team (AART) | Hyunjong Choi<br/>Pascal Reich<br/>Hyunhee Kwak | San Diego State University |
| 45      | IDEA_LAB                  | Myeongjun Kim<br/>Ji-hong Park<br/>Juyoung Kim<br/>Sunwoong Moon<br/>Gyuhyeok Lee<br/>Sujin Park | Gyeongsang National University |
| 46      | Aumechtron                | Siddhant Diwaker<br/>Aryan Iyer | SRM Institute of Science and Technology |
| 47      | UJI                       | Enric Cervera                 | Universitat Jaume-I                       |
| 48      | TurboTrack AI             | Swapneel Dhananjay Wagholikar | Personal                                  |
| 49      | InDIGo                    | Nikolaos Sarantinoudis        | Technical University of Crete             |
| 50      | Shelby                    | S Srikaanth<br/>S A Gogulnath | Sastra Deemed University                  |
| 51      | Noyma                     | Roni Emad<br/>Youssef Karam<br/>Ahmed Khalifa<br/>John Maged<br/>Mina Sameh<br/>Andrew Bahaa<br/>Marise Nachaat<br/>Mark Medhat | Personal |
| 52      | BREATH                    | Wonbin Lee<br/>Sechan Park<br/>Sunhwan Lee | Handong Global University    |
| 53      | SNAIL                     | Minsu Kim<br/>Minyoung Song<br/>Sieun Park | Handong Global University    |
| 54      | Shoubra Racing Team       | Ahmed Elmasry<br/>Mohamed Alaa<br/>Hana Ahmed<br/>Hazem Abuelanin | Benha University - Shoubra Faculty of Engineering |
| 55      | Kanka                     | Goktug Poyrazoglu<br/>Volkan Isler<br/>Yukang Cao<br/>Burak Mert Gonultas<br/>Qingyuan Jiang<br/>Burak Susam<br/>William Chastek | University of Minnesota |
| 56      | Kılavuz-Mekatronom        | Mehmet Baha Dursun<br/>Mustafa Kurban<br/>Hüseyin Ayvacı<br/>Cihat Kurtuluş Altıparmak | Saha Robotik |
| 57      | AA Lab                    | Taha Kocyigit                 | Bogazici University                       |
| 58      | Cognitron                 | Abhinav Pillai<br/>Abid Ansari<br/>Muhamed Shijas<br/>Safa N<br/>Razeen Rasheed | Indian Institute of Technology, Kharagpur |

!!! note
    The above table will be updated with newly registered teams within a few days of registration. Please contact [Chinmay Samak](mailto:csamak@clemson.edu) or [Tanmay Samak](mailto:tsamak@clemson.edu) if you do not see your team entry for more than 7 days after registering.

## Results

<p align="justify">
To be announced on Oct 07, 2024.
</p>