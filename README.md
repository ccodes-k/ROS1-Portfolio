# ROS1-Portfolio


## Overview

ROS 1 (Robot Operating System) is a modular open-source middleware used to develop, simulate, and control robotic systems. This repository demonstrates ROS capabilities through projects like TurtleBot navigation and Gazebo simulations. In this project, Limo Robot uses ROS and its features to navigate through obstacles in the arena with varying complexities.

### Contents

- Source code for ROS 1 projects
- Limo Robot usage
- ROS Navigation
- Arena Creation

## Limo Robot

- LiDAR and depth vision-based sensing (YDLIDAR XL2 & Orbbec Dabai)
- RViz visualization
- Nvidia Jetson Nano
<br>
The usage of the limo robot with its features such as a LiDAR and depth sensing camera helps with its own survival and reaching a specific goal.

## ROS Navigation

When first mapping the surroundings, we need to launch the camera and LiDAR sensor in the Limo Robot. Next, we need to launch orbbec to able to save the map. After saving, we can proceed with telling the limo where we want the goal to be.

![photo_2025-07-18_22-53-16](https://github.com/user-attachments/assets/8a10a491-864b-4765-a0ba-12794102c0b0)
![ph![photo_2025-07-18_22-53-35](https://github.com/user-attachments/assets/8fd0f6b8-9c90-4fb2-b808-d83e9ad269f7)
oto_2025-07-18_22-53-26](https://github.com/user-attachments/assets/ba4e3073-527f-42fd-b9cd-c7b0edcb75eb)
<br>
Examples of waypoint coordinates in the arena to be saved into the Limo Robot as our goal for arena navigation.

How is Systems Approach applied to mapping?
1. Identifying & Understanding Problems and Opportunities<br>
&nbsp;The identified problem is which mapping method is best fit for our use. Gmapping, Cartographer or Rtabmap. This gives us our 3 opportunities which is the 3 methods.

2. Synthesizing Possible Solutions
&nbsp;We start to test the 3 methods see which is best for us.

3. Analysis & Selection between Alternative Solutions<br>
&nbsp;We do trade offs between the 3 methods. What is the pros and cons of each of the mapping. In conclusion, we feel that Rtabmap is the best for our use.

4. Implementing and Proving a Solution<br>
&nbsp;We use Rtabmap to prove that this mapping method helps to best navigate the arenas by testing in our own arena.

6. Deploying, Using, & Sustaining Systems to Solve Problems<br>
&nbsp;When we are able to complete navigating thorugh our arena, we use to solve the other arenas made by other teams.


## Arena Creation

![photo_2025-07-17_21-53-38](https://github.com/user-attachments/assets/6cbf3fc7-dd59-4011-8611-28bc11c26d71)

### How Systems Approach can be applied into creating the arena
1. Identifying & Understanding Problems and Opportunities<br>
    &nbsp;Application to Arena Creation:<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Define the purpose of the arena (e.g., testing robot navigation, obstacle avoidance, SLAM).<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Identify requirements from stakeholders (e.g., researchers, students, engineers).<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Recognize constraints like space availability, budget, safety, and types of robots.<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Example: The robot struggles with uneven surfaces or tight corners—highlighting a need to include such elements in the arena for better testing.<br>

2. Synthesizing Possible Solutions<br>
    &nbsp;Application to Arena Creation:<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Brainstorm different layouts and obstacle types (ramps, tunnels, rough terrain, markers).<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Consider materials for construction (wood, foam, 3D-printed parts).<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Think about how to make the arena modular or reconfigurable for different tests.<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Example: Propose zones with different difficulty levels—basic navigation, dynamic obstacles, or line following.<br>

3. Analysis & Selection between Alternative Solutions<br>
   &nbsp;Application to Arena Creation:<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Evaluate each proposed layout for cost, realism, challenge level, safety, and learning objectives.<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Use simulations or scaled models to test how effective each design is for robot tasks.<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Choose the design that offers the best balance between challenge and feasibility.<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Example: Select a hexagonal layout over a linear one because it allows for more complex path planning.<br>

4. Implementing and Proving a Solution<br>
    &nbsp;Application to Arena Creation:<br>
        &nbsp;&nbsp;Build the physical arena based on the chosen design.<br>
        &nbsp;&nbsp;Test it with mobile robots to ensure it meets goals (e.g., robot can map the area, avoid obstacles, and return to start).<br>
        &nbsp;&nbsp;Fix construction issues or robot interaction problems during test runs.<br>
        &nbsp;&nbsp;Example: Adjust obstacle height if robots consistently fail to detect them.<br>

5. Deploying, Using, & Sustaining Systems to Solve Problems<br>
    &nbsp;Application to Arena Creation:<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Begin regular use of the arena for training, experimentation, or competitions.<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Collect feedback from users and iterate the design (e.g., add moving obstacles or tracking cameras).<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Develop a maintenance plan to keep the arena in good condition.<br>
        &nbsp;&nbsp;&nbsp;&nbsp;Example: Replace worn floor markings or update the layout for new robot capabilities.<br>


## Socials

Linkedin: https://www.linkedin.com/in/jarvisleow/
