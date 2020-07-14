---
title: "OLLY"
excerpt: "Robotic platform for collaborative heavy load transportation and obstacle avoidance<br/><img src='/images/olly_labeled_500.png'>"
collection: portfolio
---

Project OLLY is a custom robotic platform developed from the ground up by a team of 6 seniors for our capstone mechatronics/robotics project. OLLY stands for Oversized Load Lifting and Yielding, and serves as a scaled down robotic solution to the lifting and transportation of large, extended payloads. The project features dual holonomic robots:
1. MOLLY: The Master OLLY robot - teleop controlled via an XBOX controller
2. FOLLY: The Follower OLLY robot - autonomously tracks MOLLY, maintaining fixed payload distance and maneuvering around path constraints/obstacles


For more information, the full project report can be downloaded [here](http://benchang.us/files/Project_Olly_final_report.pdf).


Hardware:
---------
The robot hardware platform was designed and manufactured from the ground up, with identical designs across both MOLLY and FOLLY.

Show image gallery:

## Mechanical:
1. Chassis:
	* Holonomic Drivetrain: 3 omnidirectional wheels actuated by NEMA 17 stepper motors allow simple open loop control and full actuation in all 3 planar degrees of freedom
	* Sensor & Electronics Integration: all in one baseplate design allows careful and precise mounting of all sensors and electronics
![CAD](/images/olly_cad.jpg)

2. Tophat: 
	* Gripper: interchangable gripper system with modular peg board design securely fastens loads to robot
	* Compliance: rotational and translation compliance built in to eliminate payload stresses due to control errors 
![CAD](/images/olly_cad.jpg)

## Electrical:
1. Raspberry Pi
2. Arduino Mega
3. RPLiDAR A2
4. Indoor GPS + IMU (localization via LiDAR sufficient, so these sensors are unused for final demo)


The power distribution system delivers power to all of the sensors, actuators, and microprocessors on the robots.
![Power Distribution](/images/olly_power.jpg)


Software:
---------
![ROS System Architecture](/images/olly_system.jpg)


Demo:
-----
![OLLY Demo Video](youtube_vid_link)


Team:
-----
![OLLY Team](/images/olly_team.jpg)

From left to right: Rachel Lim, Jason Anderson, Sam Kruger, Rohan Sinha, Ben Chang, and Ryan Cosner