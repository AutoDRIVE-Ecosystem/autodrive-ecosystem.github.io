# Competition Rulebook

![F1TENTH Sim Racing](../assets/images/banners/F1TENTH Sim Racing.png)

<p align="justify">
This document describes the rules and regulations for the F1TENTH Sim Racing League. It goes over the definitions, requirements and evaluation criteria as well as general dos and don'ts for the competition.
</p>

!!! warning
    Rules are subject to change. Organizers reserve the right to amend existing rules and, if situation demands, create new rules on the go.

## 1. General Guidelines

<p align="justify">
F1TENTH Sim Racing League is a virtual competition, which accompanies the physical F1TENTH Autonomous Racing Competition. It leverages <a href="https://autodrive-ecosystem.github.io">AutoDRIVE Ecosystem</a> to model and simulate the digital twin of an F1TENTH racecar within a virtual racetrack. The main goal of this competition is to make autonomous racing accessible to everyone across the globe.
</p>

### 1.1. Eligibility Criteria

<p align="justify">
This competition is open for everyone around the world - students, researchers, hobbyists, professionals, or anyone else who is interested. There are no restrictions on age, sex, nationality, profession, etc. A team can consist of single or multiple participants; however, each participant can be a member of strictly one team.
</p>

<p align="justify">
Registration for the Sim Racing League is free of cost and separate from the Physical Racing League and the conference registrations themselves. Although teams can participate in the Sim Racing League without attending the conference, we strongly encourage all competition participants to attend the conference in person. This will allow the teams to participate in competition-related events at the conference and connect with the broader community!
</p>

### 1.2. Competition Structure

<p align="justify">
Each team will be provided with a standardized simulation setup (in the form of a digital twin of the F1TENTH vehicle, and a digital twin of the Porto racetrack) within the high-fidelity <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator">AutoDRIVE Simulator</a>. Additionally, teams will also be provided with a working implementation of the <a href="https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit">AutoDRIVE Devkit</a> to get started with developing their autonomy algorithms. Teams will have to develop perception, planning, and control algorithms to parse the real-time sensor data streamed from the simulator and generate control commands to be fed back to the simulated vehicle.
</p>

### 1.3. Competition Timeline

<p align="justify">
The competition will take place in 2 stages:
</p>

<ul class="justify-list">
  <li><b>Qualification Race:</b> Teams will demonstrate their ability to complete multiple laps around the practice track without colliding with the track bounds at run time.</li>
  <li><b>Time-Attack Race:</b> Teams will compete against the clock, on a previously unseen racetrack, to secure a position on the leaderboard.</li>
</ul>

<p align="justify">
Following is a brief summary of the main events of the competition:
</p>

<ul class="justify-list">
  <li><b>Registration:</b> Interested teams will register for the Sim Racing League.</li>
  <li><b>Online Orientation 1:</b> Organizers will explain the competition rules and guidelines, and demonstrate how to use the simulation framework.</li>
  <li><b>Online Orientation 2:</b> Organizers will check progress of the participating teams and help with any technical difficulties.</li>
  <li><b>Qualification Round:</b> Teams will demonstrate successful completion of 10 autonomous laps around the practice track provided ahead of time.</li>
  <li><b>Competition Track Released:</b> Organizers will release the actual "competition track", which will be used for the final race. This track may be replicated in the physical race as well.</li>
  <li><b>Final Race:</b> Organizers will collect containerized algorithms from each team and connect them with the containerized simulator. Performance metrics of each team will be recorded.</li>
  <li><b>Results Declared:</b> Standings of all the teams will be released.</li>
</ul>

## 2. Competition Guidelines

<p align="justify">
This competition will adhere to the <b>time-attack racing</b> format, wherein each team will compete against the clock independently, on the same racetrack. Each race will comprise a total of 12 laps: the vehicles will start with a warm-up lap, followed by 10 race laps, and finally a cool-down lap.
</p>

### 2.1. Competition Requirements

<p align="justify">
Following are the requirements to progress along each phase of the competition:
</p>

<ul class="justify-list">
  <li><b>Registration:</b> Interested teams must register for the competition before the deadline. Organizers may extend registration deadlines in certain cases; however, direct requests for deadline extension from any team(s) will not be entertained. It is recommended to register your team well in advance to avoid last-minute rush.</li>
  <li><b>Orientations:</b> It is highly recommended for all teams to attend the online orientation sessions to understand the competition code-of-conduct and get familiar with the simulation framework. These events can also be used to get some of your doubts clarified!</li>
  <li><b>Qualification:</b> Teams will have to demonstrate successful completion of 10 autonomous laps around the practice track provided ahead of time. During this phase, speed is not very important, but failure to complete 10 consecutive autonomous laps without exceeding the collision count tolerance will result in disqualification of that team. Passing the qualification session entitles a team for the final race.</li>
  <li><b>Competition:</b> During this phase, the clock will be ticking and the objective would be to complete 10 consecutive autonomous laps as fast as possible without exceeding the collision count tolerance. Failure to respect the collision count tolerance will result in disqualification of that team. Teams will be ranked on a leaderboard in the ascending order of their time to completion (10 autonomous racing laps).</li>
</ul>

### 2.2. Competition Terminology

<p align="justify">
Following are the definitions of some competition terminologies:
</p>

<ul class="justify-list">
  <li><b>Collision:</b> Any contact between the colliders of the simulated vehicle and the racetrack bounds (except the wheels touching the ground) is considered a collision. A collision will incur a compounding penalty of 10 seconds (i.e. 10 seconds for first collision, 20 seconds for the second, 30 seconds for the third, and so on). Colliding more than 5 times in a single racing event will lead to disqualification. Each collision will automatically reset the vehicle to the nearest checkpoint (your localization algorithm will have to be robust against this re-setting action). Lap timer will not reset upon collision.</li>
  <li><b>Warm-Up Lap:</b> This is the first lap of a race. The time or collisions during the warm-up lap will not be considered. This lap acts as a buffer since your algorithms may take time to launch and connect with the simulator, while the lap timer is on.</li>
  <li><b>Race Laps:</b> These are a set of 10 laps immediately following the warm-up lap. The race laps start as soon as the vehicle crosses the finish line in the warm-up lap. The time and collisions of the race laps will be considered.</li>
  <li><b>Cool-Down Lap:</b> This is the last lap of a race. The time or collisions during the cool-down lap will not be considered. Completing this lap is not required for the competition, but this can be a good time to "show-off" your skills without worrying about collisions!</li>
  <li><b>Checkpoints:</b> The racetrack has several "virtual" checkpoints, spaced approximately equally along the track. These checkpoints cover the entire width of the racetrack and are triggered as the vehicle passes through them. The start/finish line is the final "special" checkpoint. The exact location of the checkpoints will not be revealed to the participants.</li>
  <li><b>Lap Time:</b> This is the amount of time that the vehicle takes to complete one full lap around the racetrack. The timer starts as soon as the previous lap ends and stops after the current lap ends. Failing to pass all the checkpoints before crossing the finish line (e.g. driving in opposite direction) will not stop the lap timer.</li>
  <li><b>Race Time:</b> This is the cumulative time that the vehicle takes to complete 10 race laps around the racetrack. The timer starts as soon as the warm-up lap ends and stops after the 10th race lap ends. Collision penalties are added separately.</li>
  <li><b>Best Lap Time:</b> This is the amount of time that the vehicle took to complete the fastest race lap around the racetrack. This is the minimum lap time across all the 10 race laps.</li>
  <li><b>Average Lap Time:</b> This is the average time that the vehicle took to complete a race laps (out of 10 race laps) around the racetrack. This is the statistical mean of all the 10 race lap times.</li>
</ul>

### 2.3. Competition Execution 

<p align="justify">
Following is a brief summary of a typical racing event:
</p>

<ul class="justify-list">
  <li><b>Inspection:</b> Race stewards will examine the team's submission according to race standards.</li>
  <li><b>Simulator:</b> Containerized AutoDRIVE Simulator will be launched. Communication bridge parameters will be set (communication channel will not be opened yet). Vehicle will be engaged in autonomous mode. Graphics quality will be set to "Ultra". </li>
  <li><b>Devkit:</b> Containerized AutoDRIVE Devkit with the team's autonomous racing algorithm submission will be launched. A new Bash session will be opened within the container to start recording a ROS 2 bag of all the available topics.</li>
  <li><b>Recording:</b> A screen recorder application as well as the ROS 2 bag recording will run in the background.</li>
  <li><b>Communication:</b> The bi-directional communication channel between simulator container and devkit container will be established. This should make all the data available on the relevant ROS 2 topics and automatically start the race.</li>
  <li><b>Race:</b> Each race will comprise a total of 12 laps: the vehicles will start with a warm-up lap, followed by 10 race laps, and finally a cool-down lap. The lap times or collisions during the warm-up and cool-down laps will not be considered, only those during the 10 race laps will be considered.</li>
  <li><b>Data:</b> Performance metrics of the team will be recorded and stored along with the screen recording of the simulator as well as the comprehensive ROS 2 bag.</li>
</ul>

### 2.4. Inspection Rules

!!! warning
    Organizers reserve the right to reject any submission that they deem illegal due to unethical exploitation of the competition framework. All submissions will be examined by the race stewards prior to the race.

!!! warning
    Teams breaching the code of conduct will face direct disqualification with a publicly visible <b>"malpractice"</b> citation on the competition website.

<p align="justify">
This competition is intended to be a <b>battle of algorithms</b>, and hence any modifications to the competition framework including (but not limited to) the simulator executable, vehicle (chassis, powertrain, sensors, etc.), environment (track, layout, ground, weather, time, etc.), communication interface (use of protocols other than WebSocket), devkit (use of APIs other than ROS 2) or the containerization approach (use of tools besides Docker, Dockerfile configuration, etc.) are strictly prohibited. Any modification to the competition framework shall result in direct disqualification of the responsible team without admission to the qualification/competition session.
</p>

<p align="justify">
Any kind of autonomous racing algorithm that makes use of raw perception data to generate control commands for the simulated vehicle is permissible - including (but not limited to) reactive planning, map-based localization, raceline optimization, deep learning, reinforcement learning as well as hybrid algorithms.
</p>

<p align="justify">
However, utilizing simulation ground truth data or controlling aspects other than the vehicle actuators is not allowed. Furthermore, exploiting the competition framework unethically (e.g. tapping into the back-end, frame-grabbing the front-end, finding loop-holes in the framework, tampering with data streaming/logging, etc.) is considered a serious malpractice.
</p>

!!! info
    Please refer to the Technical Guide for more information about permissible and restricted data streams.

### 2.5. Evaluation Criteria

<p align="justify">
Following are the evaluation criteria for the competition:
</p>

<ul class="justify-list">
  <li>The ultimate evaluation criteria for the race is <b>total race time.</b> However, best lap time and/or other metrics may be used in case of a tie.</li>
  <li>A collision will incur a compounding <b>penalty</b> of 10 seconds (i.e. 10 seconds for first collision, 20 seconds for the second, 30 seconds for the third, and so on).</li>
  <li>The maximum number of collisions permissible for a race (qualification/competition) is 5, beyond which the team will be <b>disqualified.</b></li>
  <li>Lap times or collisions during the warm-up and cool-down laps will not be considered, only those during the <b>10 race laps</b> will be considered.</li>
</ul>

!!! note
    Race referee's decision is final! In extreme cases, rebuttals with supporting evidence may be entertained at the organizers' discretion.

## 3. Submission Guidelines

<p align="justify">
Each team is expected to submit a containerized version of their autonomous racing software stack. Submissions for each phase of the competition will be done separately.
</p>

### 3.1. Submission Requirements

<p align="justify">
Following are the requirements for submitting an entry to the competition:
</p>

<ul class="justify-list">
  <li>Each team is expected to submit a Docker container image of their autonomous racing software stack.</li>
  <li>The submitted container should be self-sustainable in terms of all the dependencies and should be configured to run all the necessary commands automatically when launched.</li>
  <li>The submitted container must be based off of the official AutoDRIVE Devkit container released for the competition.</b></li>
  <li>Teams are permitted to add/modify ROS 2 package(s) within the provided AutoDRIVE Devkit container for implementing their autonomous racing algorithm(s). However, any modifications to the existing container elements are strictly off the limits.</li>
  <li>Teams do not need to submit the simulator container.</li>
</ul>

!!! tip
    Teams can test their algorithms locally before containerizing them. However, don't forget to test the containerized approach before submitting!

### 3.2. Submission Process

<p align="justify">
Following are the key milestones for submitting an entry to the competition:
</p>

<ul class="justify-list">
  <li>Teams will <b>containerize</b> their autonomous racing software stack using <a href="https://www.docker.com">Docker</a>.</li>
  <li>Teams will <b>push</b> their Docker container image to <a href="https://hub.docker.com">DockerHub</a>.</li>
  <li>Teams will <b>share</b> the link of the upstream repository with the organizers via a secure Submission Form (separate forms for each stage of the competition).</li>
</ul>

### 3.3. Submission Privacy

<p align="justify">
This is a competition, and all teams have the right to keep their source code hidden from their competitors. Here are a few strategies to keep in mind:
</p>

<ul class="justify-list">
  <li><b>Source Code:</b> Teams can host their source code in a private <a href="https://github.com">GitHub</a> repository for collaboration and version control. GitHub now allows hosting unlimited private repositories for personal accounts and organizations.</li>
  <li><b>Containers:</b> Teams can push their Docker container images to a private <a href="https://hub.docker.com">DockerHub</a> repository. As of now, DockerHub allows hosting one free private repository for each user account.</li>
  <li><b>Data:</b> Teams can store their data in an encrypted and secure cloud storage platform with link-sharing disabled. Alternatively, storing data locally (with a hard-drive backup) is also an option.</li>
</ul>

<p align="justify">
However, <b>after the competition,</b> we encourage teams to publish their source code on GitHub under an open-source license. We also encourage teams to make their Docker containers public on DockerHub. Teams can also choose to make other race data (e.g. videos, logs, reports, etc.) publicly available. This will increase the visibility of their work and increase the quality of the future competitions.
</p>