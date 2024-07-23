# F1TENTH Sim Racing League @ CDC 2024

![F1TENTH Sim Racing League @ CDC 2024](../assets/images/F1TENTH-Sim-Racing-League-CDC-2024.png)

## About

<p align="justify">
<b>F1TENTH Autonomous Racing</b> is a semi-regular competition organized by an international community of researchers, engineers, and autonomous systems enthusiasts. The teams participating in the <b>22nd F1TENTH Autonomous Grand Prix</b> at CDC 2024 will write software for a 1:10 scaled autonomous racecar to fulfill the objectives of the competition: <b><i>drive fast but don’t crash!</i></b>
</p>

<!-- <div class="grid" markdown> -->
<p align="justify">
This time, we are organizing the second <b>F1TENTH Sim Racing League</b>, which leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an F1TENTH racecar within a virtual racetrack. Please see the accompanying video for more details. The main focus of the Sim Racing League is a virtual competition with simulated cars and environments.

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/Rq7Wwcwn1uk?si=ngvop2-SfJJOIjWJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div> -->
</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Rq7Wwcwn1uk?si=ngvop2-SfJJOIjWJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<p align="justify">
For the CDC 2024 competition, each team will be provided with a standardized simulation setup (in the form of a digital twin of the F1TENTH vehicle, and a digital twin of the Porto racetrack) within the high-fidelity (physically and graphically accurate) <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a>. Additionally, teams will also be provided with a working implementation of the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a> to get started with developing their autonomy algorithms. Teams will have to develop software control algorithms to use the "standardized" real-time sensor-data streamed from the simulator and generate control-commands to be fed-back to the simulated vehicle.
</p>
<p align="justify">
The competition will take place in 2 stages:
<ul>
<li><b>Qualification Session:</b> Teams will demonstrate their ability to complete multiple laps without colliding with the practice-track bounds at run time.</li>
<li><b>Time-Attack Session:</b> Teams will compete against the clock, on a previously unseen racetrack, to secure a position on the leaderboard on a brand-new (unseen) track. Since the vehicle, the environment, the simulator, and the devkit are standardized, teams must develop robust perception, planning, and control algorithms that can deal with the uncertainties of a new track.</li>
</ul>
</p>
<p align="justify">
Since vehicles and simulator are standardized, teams must develop robust perception, planning, and control algorithms that can deal with the uncertainties of a new track.
</p>

!!! Tip
    If you are interested in autonomously racing physical F1TENTH vehicles, please check out the website for [22nd F1TENTH Autonomous Grand Prix](https://cdc2024-race.f1tenth.org/), which will be held in person at CDC 2024. You can always register and compete in both physical and virtual competitions!

## Organizers

- Venkat Krovi
- Rahul Mangharam
- Chinmay Samak
- Tanmay Samak
- Ahmad Amine

## Timeline

!!! warning
    Timeline is subject to change. Please keep checking this page for any updates.

| DATE                  | EVENT                      |
|:----------------------|:---------------------------|
| Aug 01, 2024          | Registration Opens         |
| Oct 30, 2024          | Registration Closes        |
| Oct 22, 2024          | Online Orientation 1       |
| Nov 19, 2024          | Online Orientation 2       |
| Nov 30 – Dec 01, 2024 | Qualification Round        |
| Dec 02, 2024          | Competition Track Released |
| Dec 07 – Dec 08, 2024 | Final Race                 |
| Dec 09, 2024          | Results Declared           |

-	**Registration:** Interested teams will register for the sim racing league.
-	**Online Orientation 1:** Organizers will explain the competition rules and guidelines, and demonstrate how to use the simulation framework.
-	**Online Orientation 2:** Organizers will check progress of the participating teams and help with any technical difficulties.
-	**Qualification Round:** Teams will demonstrate successful completion of 10 laps around the practice track provided ahead of time.
-	**Competition Track Released:** Organizers will release the actual "competition track", which will be used for the final race. This track may be replicated in the physical race as well.
-	**Final Race:** Organizers will collect containerized algorithms from each team and connect them with the containerized simulator. Performance metrics of each team will be recorded.
-	**Results Declared:** Standings of all the teams will be released.

## Resources

AutoDRIVE is envisioned to be an open, comprehensive, flexible and integrated cyber-physical ecosystem for enhancing autonomous driving research and education. It bridges the gap between software simulation and hardware deployment by providing the AutoDRIVE Simulator and AutoDRIVE Testbed, a well-suited duo for sim2real applications. It also offers AutoDRIVE Devkit, a developer's kit for rapid and flexible development of autonomy algorithms in a variety of software frameworks. Although the ecosystem is primarily targeted towards autonomous driving, it also supports the development of smart-city solutions for managing the traffic flow.

<div class="grid" markdown>
<img src="/../assets/images/AutoDRIVE Overview - Light.png">

<img src="/../assets/images/Vehicle-DT.png">
</div>

**Details of this framework are available from:**

1. Samak T.V., Samak C.V., Kandhasamy S., Krovi V.N., Xie M., "AutoDRIVE: A Comprehensive, Flexible and Integrated Digital Twin Ecosystem for Autonomous Driving Research & Education," Robotics, 2023, 12(3):77, doi: https://doi.org/10.3390/robotics12030077

2. Samak T.V., Samak C.V., and Xie M., "AutoDRIVE Simulator: A Simulator for Scaled Autonomous Vehicle Research and Education," in Proceedings of the 2021 2nd International Conference on Control, Robotics and Intelligent System (CCRIS), Association for Computing Machinery (ACM), 2021, New York, NY, USA, pp. 1–5, doi: https://doi.org/10.1145/3483845.3483846

3. Other related publications are available at: https://autodrive-ecosystem.github.io/#publications

**Next Steps:** Early familiarization with the competition framework

- [Download Simulator Container](https://hub.docker.com/r/autodriveecosystem/autodrive_f1tenth_sim)

- [Download Devkit Container](https://hub.docker.com/r/autodriveecosystem/autodrive_f1tenth_api)

**N.B.** The F1TENTH Sim Racing League will be held approximately 1 week before the CDC and the resulting ROS Bags will be made available back to the teams. Discussions are underway with the CDC2024 Organizing Team to permit teams to analyze/present/showcase their approach/results in a short (~10 min) presentation in a special session at CDC 2024.

## Registration

Opens on Aug 01, 2024.

## Results

To be announced on Dec 09, 2024.