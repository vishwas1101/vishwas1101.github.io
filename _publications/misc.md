---
title: "Miscellenous stuff"
collection: publications
permalink: /publications/misc
excerpt: Other random projects that I did during my undergrad. 
date: 
venue:
---

**Abstract:**

*Operating systems course project:*
CS F372 (Operating Systems) Assignment Emulation of First Come First Serve (FCFS) and Round Robin (RR) Scheduling Algorithms in C. In this project, the resource is a single processor (we have written our program under the assumption that it will run on a uniprocessor system). The tasks in the project are multithreaded processes. Each process has two threads; the monitor thread, which communicates with the main process to monitor the execution of the task thread, which is the thread that does the actual work. The scheduler here is the main process in the program. [GitHub Repo](https://github.com/vishwas1101/cs-f372-assignment)

*Gem5 101 Solutions:*
Learnt Gem5 and tried completing the six part course which helps pick up the basics of gem5, and illustrate some common uses. Didn't complete all the parts. My solutions to the completed parts can be found [here](https://github.com/vishwas1101/gem5_101_Solutions).


*Hexacopter Simulation:*
Simulated a Hexacopter in ROS for obstacle avoidance and movement of goods in a warehouse. Implemented autonomous flight algorithms in RosPy for the control of the UAV.
Used basics of control theory in designing these algorithms. Decided the onboard electronics and control architecture of the UAV. The code and the other details regarding the course can be found in this [repository](https://github.com/vishwas1101/Hexacopter-Simulation). We participated in the Flipkart GRiD 2.0 competition and we were eliminated in Round 3 — Top 64 of 6060 Participants.


*Filters for Sensor Fusion:*
Implemented Complementary, Kalman, and Qauternion based filters for sensor fusion of accelerometer & gyroscope. More details and code can be found in the GitHub [repo](https://github.com/vishwas1101/Filters).


*SmartRoom:*
A Raspberry Pi is used along with relays to different devices. Currently, an RGB light is connected to the Raspi. As a person enters the room, the camera detects if it is a known person entering the room. If it is, it checks with an existing API (using polling) for that person's light settings (whether the light is red, green or blue, and whether the light is supposed to be on or off). The user can control his/her settings from the mobile app and they are automatically saved to the API. This enables real time switching on/off of the light and change in color of the light. To check if this recognized individual enters the room, IR sensors are used. Once they are inside the room, the light is switched on/off based on the settings. If more than one person enters the room, the lights will stay on until the last person inside the room leaves. [GitHub Repo](https://github.com/vishwas1101/SmartRoom).


*Microfluidic Devices:*
I worked on Microfluidic devices as a Summer Intern at CSIR-CEERI Pilani for 3 months. More details and reports can be found in this [GitHub repo](https://github.com/vishwas1101/Microfluidic-Devices)



