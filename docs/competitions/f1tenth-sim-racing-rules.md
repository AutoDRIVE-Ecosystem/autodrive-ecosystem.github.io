# Competition Rulebook

![F1TENTH Sim Racing](../assets/images/banners/F1TENTH Sim Racing.png)

<p align="justify">
This document describes the rules and regulations for the F1TENTH Sim Racing League. It goes over the definitions, requirements and evaluation criteria as well as general dos and don'ts for the competition.
</p>

!!! warning
    Rules are subject to change. Organizers reserve the right to ammend existing rules and, if situation demands, create new rules on the go.

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

The competition will take place in 2 stages:

- **Qualification Session:** Teams will demonstrate their ability to complete multiple laps around the practice track without colliding with the track bounds at run time.
- **Time-Attack Race:** Teams will compete against the clock, on a previously unseen racetrack, to secure a position on the leaderboard.

<p align="justify">
Following is a brief summary of the main events of the competition:
</p>

- **Registration:** Interested teams will register for the Sim Racing League.
- **Online Orientation 1:** Organizers will explain the competition rules and guidelines, and demonstrate how to use the simulation framework.
- **Online Orientation 2:** Organizers will check progress of the participating teams and help with any technical difficulties.
- **Qualification Round:** Teams will demonstrate successful completion of 10 autonomous laps around the practice track provided ahead of time.
- **Competition Track Released:** Organizers will release the actual "competition track", which will be used for the final race. This track may be replicated in the physical race as well.
- **Final Race:** Organizers will collect containerized algorithms from each team and connect them with the containerized simulator. Performance metrics of each team will be recorded.
- **Results Declared:** Standings of all the teams will be released.

### 1.4. Competition Requirements

<p align="justify">
Following are the requirements to progress along each phase of the competition:
</p>

- **Registration:** Interested teams must register for the competition before the deadline. Organizers may extend registration deadlines in certain cases; however, direct requests for deadline extension from any team(s) will not be entertained. It is recommended to register your team well in advance to avoid last-minute rush.
- **Orientations:** It is highly recommended for all teams to attend the online orientation sessions to understand the competition code-of-conduct and get familiar with the simulation framework. These events can also be used to get some of your doubts clarified!
- **Qualification:** Teams will have to demonstrate successful completion of 10 autonomous laps around the practice track provided ahead of time. During this phase, speed is not very important, but failure to complete 10 consecutive autonomous laps without exceeding the collision count tolerance will result in disqualification of that team. Passing the qualification session entitles a team for the final race.
- **Competition:** Teams will have to pass the qualification session to be entitled to compete in the final race. During this phase, the clock will be ticking and the objective would be to complete 10 consecutive autonomous laps as fast as possible without exceeding the collision count tolerance. Failure to respect the collision count tolerance will result in disqualification of that team. Teams will be ranked on a leaderboard in ascending order of their time to completion of the autonomous race (10 laps).

## Competition Guidelines

<p align="justify">
F1TENTH Sim Racing League will take place in two stages. Teams will first enter a qualification round, where they will demonstrate their ability to complete multiple laps around the practice track without colliding with the track bounds at run time. Qualified teams will then compete against the clock, on a previously unseen racetrack, to secure a position on the leaderboard.
</p>

### Vehicle

### Environment

### Racing Event

This competition will adhere to the <b>time-attack racing</b> format, wherein each team will compete against the clock independently, on the same racetrack. Each race (qualification/cometition) will comprise a total of 12 laps: the vehicles will start with a warm-up lap, followed by 10 race laps, and finally a cool-down lap.

- Collision: Any contact between the colliders of the simulated vehicle and the racetrack bounds (except the wheels touching the ground) is considered a collision. A collision will incur a compounded penalty of 10 seconds (i.e. 10 seconds for first collision, 20 seconds for the second, 30 seconds for the third, and so on). Colliding more than 5 times in a single racing event will lead to disqualification. Each collision will reset the vehicle to the nearest checkpoint (your localization algorithm will have to be robust against this re-setting action).
- Warm-Up Lap: This is the first lap of a race. The time or collisions of the warm-up lap will not be considered.
- Race Laps: These are a set of 10 laps immediately following the warm-up lap. The race laps start as soon as the vehicle crosses the finish lap in the warm-up lap. The time and collisions of the race laps will be considered.
- Cool-Down Lap: This is the last lap of a race. The time or collisions of the cool-down lap will not be considered.
- Lap Time: This is the amount of time that the vehicle takes to complete one full lap around the racetrack. The timer starts as soon as the previous lap ends and stops aafter the current lap ends.
- Race Time: This is the cumulative time that the vehicle takes to complete 10 race laps around the racetrack. The timer starts as soon as the warm-up lap ends and stops after the 10th race lap ends.
- Best Lap Time: This is the amount of time that the vehicle took to complete the fastest race lap around the racetrack. This is the minimum lap time across all the race laps.
- Average Lap Time: This is the average time that the vehicle took to complete 10 race laps around the racetrack. This is the statistical mean of all the race lap times.

### Inspection Rules

Organizers reserve the right to reject any submission that they deem illegal due to circumstances such as exploiting the simulation framework. Therefore their source code submission will be examined by the race referees before the race.

### Evaluation Criteria

!!! tip
    Race referee's decision is final!

- The ultimate evaluation criteria for the race is <b>total race time.</b> However, best lap time and/or average lap time metrics may be used in case of a tie.
- The maximim number of collisions permissible for qualification round is 
- The maximim number of collisions permissible for qualification round is 

## Submission Guidelines

<p align="justify">
Each team is expected to submit a Docker container image of their autonomous racing software stack. This container <b>MUST</b> be based on the official AutoDRIVE Devkit container released for the competition.

Teams are permitted to add/modify ROS 2 package(s) within the provided AutoDRIVE Devkit container for implementing their autonomous racing algorithm(s). However, any modifications to the existing container elements are strictly off the limits.
</p>

Code privacy

Restricted topics

Custom racetracks

