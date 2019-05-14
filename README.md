# SelfDrivingVehicle_AutonomousNavigation

An Implementation of Autonomous Navigation for a Self Driving Car on CARLA Simulator (Built on Unreal Engine) for the Course Introduction to Self Driving Cars (Coursera)

Carla Simulator Link: https://github.com/carla-simulator/carla

DESCRIPTION:
===========

Implemention of Longitudinal and Lateral control to autonomously navigate a car through a set of given way points using Stanley Control for Lateral Control and PID control for Longitudinal Control.

- Input to the system is given **waypoints** in the form of a text file which specifiy the desired position and velocity along the path.

- Output is **throttle_output (betwwen 0 and 1), steer output (between -1.22 and 1.22 and brake_output(between 0 and 1)**


CARLA SIMULATION & RACETRACK :
---------
![RACETRACK_1](https://user-images.githubusercontent.com/32943733/57668369-160dd580-75d5-11e9-8465-908dadc83057.png)


SOLUTION:
========
![results](https://user-images.githubusercontent.com/32943733/57667912-713ec880-75d3-11e9-920e-aa3d0ca166c4.png)


Dependencies:
=============

1) CARLA Simulator Installation

Download and install Carla Simulator from the following link:
https://www.coursera.org/learn/intro-self-driving-cars/supplement/pGdcu/carla-installation-guide

2) Python 3.5 or 3.6

Running Autonomous Control:
==========================

Once you have installed the dependencies, clone this repository in the Python Client Folder. 

Open Command Prompt / Terminal and go to the Carla Simulator and run the simulator using the following Commands:

For Ubuntu: ./CarlaUE4.sh /Game/Maps/RaceTrack -windowed -carla-server -benchmark -fps=30
For Windows: CarlaUE4.exe /Game/Maps/RaceTrack -windowed -carla-server -benchmark -fps=30

Open another Command Prompt / Terminal and go to the Course1Project Folder and enter the following command

For Ubuntu: python3 module_7.py
For Windows: python module_7.py

Implement your own controller:
--------------------------

To implement your own controller, make changes to the **controller2d.py** file and follow the comment blocks


