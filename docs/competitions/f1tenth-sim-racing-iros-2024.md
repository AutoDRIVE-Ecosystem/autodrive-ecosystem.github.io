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
| Aug 27, 2024          | Online Orientation 1       |
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
As the next few steps, we recommend all the teams interested in participating in the F1TENTH Sim Racing League to get accustomed with the competition framework:
</p>

<div class="grid">
  <a href="https://hub.docker.com/r/autodriveecosystem/autodrive_f1tenth_sim" class="md-button md-button"><center><div class="logo"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512"><path d="M349.9 236.3h-66.1v-59.4h66.1v59.4zm0-204.3h-66.1v60.7h66.1V32zm78.2 144.8H362v59.4h66.1v-59.4zm-156.3-72.1h-66.1v60.1h66.1v-60.1zm78.1 0h-66.1v60.1h66.1v-60.1zm276.8 100c-14.4-9.7-47.6-13.2-73.1-8.4-3.3-24-16.7-44.9-41.1-63.7l-14-9.3-9.3 14c-18.4 27.8-23.4 73.6-3.7 103.8-8.7 4.7-25.8 11.1-48.4 10.7H2.4c-8.7 50.8 5.8 116.8 44 162.1 37.1 43.9 92.7 66.2 165.4 66.2 157.4 0 273.9-72.5 328.4-204.2 21.4 .4 67.6 .1 91.3-45.2 1.5-2.5 6.6-13.2 8.5-17.1l-13.3-8.9zm-511.1-27.9h-66v59.4h66.1v-59.4zm78.1 0h-66.1v59.4h66.1v-59.4zm78.1 0h-66.1v59.4h66.1v-59.4zm-78.1-72.1h-66.1v60.1h66.1v-60.1z"/></svg></span> Download AutoDRIVE Simulator Container</div></center></a>
  <a href="https://hub.docker.com/r/autodriveecosystem/autodrive_f1tenth_api" class="md-button md-button"><center><div class="logo"><span class="twemoji"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512"><path d="M349.9 236.3h-66.1v-59.4h66.1v59.4zm0-204.3h-66.1v60.7h66.1V32zm78.2 144.8H362v59.4h66.1v-59.4zm-156.3-72.1h-66.1v60.1h66.1v-60.1zm78.1 0h-66.1v60.1h66.1v-60.1zm276.8 100c-14.4-9.7-47.6-13.2-73.1-8.4-3.3-24-16.7-44.9-41.1-63.7l-14-9.3-9.3 14c-18.4 27.8-23.4 73.6-3.7 103.8-8.7 4.7-25.8 11.1-48.4 10.7H2.4c-8.7 50.8 5.8 116.8 44 162.1 37.1 43.9 92.7 66.2 165.4 66.2 157.4 0 273.9-72.5 328.4-204.2 21.4 .4 67.6 .1 91.3-45.2 1.5-2.5 6.6-13.2 8.5-17.1l-13.3-8.9zm-511.1-27.9h-66v59.4h66.1v-59.4zm78.1 0h-66.1v59.4h66.1v-59.4zm78.1 0h-66.1v59.4h66.1v-59.4zm-78.1-72.1h-66.1v60.1h66.1v-60.1z"/></svg></span> Download AutoDRIVE Devkit Container</div></center></a>
</div>

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
| 06      | Cornell Electric Vehicles | Jason Klein<br />Eric Marchetti<br />Zach Chosed<br />Utku Melemetci<br />Sidharth Rao<br />Myles Pasetsky<br />Zephan Sanghani<br />Sia Chitnis<br />Nicole Sin | Cornell University |
| 07      | Robotisim Dev             | Muhammad Luqman<br />Yusuf Butt | Robotisim                               |
| 08      | Log Robotics              | Logesh G                      | Bannari Amman Institute of Technology     |
| 09      | Lone Rider                | Akshay Laddha                 | Indian Institute of Technology, Bombay    |
| 10      | Atlas 2.0                 | Manav Gagvani                 | Purdue University                         |
| 11      | The Buttowskis            | Kalash Jain                   | Pandit Deendayal Energy University        |
| 12      | Hanuman Parakram          | Dheeraj Bhurewar<br />Vaibhav Wanere | Personal                           |
| 13      | Pallas                    | Haris Khan                    | Skoltech                                  |
| 14      | Gopher Speedsters         | Sujeendra Ramesh              | University of Minnesota, Twin Cities      |
| 15      | Autopilots                | Nouf Aljaberi<br />Amna Muhammad<br />Hajar Alnaqbi<br />Shouq Zanki<br />Sara Almessabie<br /> | United Arab Emirates University |
| 16      | i3                        | Pranav Kallem                 | Personal                                  |
| 17      | Phoenix                   | Aman Kumar Singh<br />Lakshmikanth Nageswar | Personal                    |
| 18      | RobotX & More             | Oussama Errouji<br />Imad-Eddine NACIRI | Euro Mediterranean University of Fez |
| 19      | IEEE Zagazig SB           | Abdulrahman Omar<br />Hossam Elsherbiny<br />Essam Shenhab<br />Eman Abdelhamed<br />Abdullah Elmasry<br />Salma Swailem<br />Merna Atef<br />Amr Yasser<br />Mahmoud Samy<br />Mostafa Asaad<br />Menna Gamal<br />Ahmed Medhat   | Zagazig University                        |
| 20      | AMUGAE                    | Kim Amugae                    | Personal                                  |
| 21      | TURTLEBOT                 | Jit Ern Lim                   | Personal                                  |
| 22      | Byte Benders              | Bhajneet Singh Bedi           | Personal                                  |
| 23      | KGX                       | Hareesh R<br />Raja Rajan K<br />Ramesh Patel D<br />Marudhu Paandian K<br />Bhuvaneshwari Kanagaraj | KGISL Institute of technology |
| 24      | NaN                       | Hariharan Ravichandran<br />Siva Vignesh Krishnan Chidambaram | Personal  |
| 25      | Vortex                    | Chinmay K                     | National Institute of Technology, Karnataka |
| 26      | bracaai                   | Luis M Bracamontes<br />Luis Bracamontes | Braca Vision                   |
| 27      | ASU Racing Team           | Abdallah Ismail<br />Mahmoud Omar<br />Hussien Algendy<br />Serag Abdelmohsen<br />Ammar Ahmed<br />Ahmed Sallam<br />Malk Hany | Ain Shams University |
| 28      | TurboX                    | Dheeraj Bhogisetty            | Personal                                  |
| 29      | TractionX                 | Ameya Bagal<br />Ananya Das<br />Amizhthni PRK<br />Aayush Ranawat | Indian Institute of Technology, Madras |
| 30      | Urban AI                  | Adham Fayad<br />Abdulrahman Ahmed<br />Nabil Fouda<br />George Welson<br />Muhab Muhammed<br />Mostafa Samy | Ain Shams University |
| 31      | fstMINI                   | José Mateus<br />Duarte Domingues | Instituto Superior Técnico            |
| 32      | Buggy Coders              | Cody Uehara                   | Personal                                  |
| 33      | AutoVision                | Luis Bracamontes              | Personal                                  |
| 34      | Autobots                  | Shubham Barge<br />Anshuman Jena | Personal                               |
| 35      | SUST AutoDrive            | Abul Basar Raz<br />Ad-deen Mahbub<br />Shafi Abdullah<br />Redwan Hossen<br />Taj Ahmad | Shahjalal University of Science and Technology |

!!! note
    The above table will be updated with newly registered teams within a few days of registration. Please contact [Chinmay Samak](mailto:csamak@clemson.edu) or [Tanmay Samak](mailto:tsamak@clemson.edu) if you do not see your team entry for more than 7 days after registering.

## Results

<p align="justify">
To be announced on Oct 07, 2024.
</p>