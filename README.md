# spidyproject
![version](https://badge.fury.io/gh/didix21%2Fspidyproject.svg)
![travis-build](https://travis-ci.org/didix21/spidyproject.svg?branch=master)
[![HitCount](http://hits.dwyl.io/didix21/spidyproject.svg)](http://hits.dwyl.io/didix21/spidyproject)
## About it
This repository is the collection of the different parts used in the Spidy Project. Spidy is a six leg robot which is controlled with and Arduino, connected to the computer using a Raspberry and ROS. 
The obejctive of the project is to make an algorithm where the robot is able to learn to walk using a Machine Learning Algorithm.
Based on the robot: [Funny six feet + Myo](http://www.thingiverse.com/thing:1201161/#files)

# Characteristics
## Hardware
 * Plastic chasis.
 * Arduino.
 * 16 channels pwm controller.
 * 13 servo motors SG90.
 * Ultrasonic sensor.
 * MPU-6050 3 Axis Acceleration + Gyroscope / 6 Axis Attitude Module.
 * Raspberry Pi 2.0. (Optional for controll it manually)
 
 ## Firmware
 * spidyfirmware

 ## ROS
 * Simulation and model of the robot in Gazebo
 * Connection with the real robot using ROS and Python
 
 ## NEAT Algorithm
 * C++ Implementation of the NEAT Algorithm (http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf)

## Contributors

- [XMabbX](https://github.com/XMabbX)
  - Implementation of the NEAT algorithm in C++. 
  - ROS project coding.
  - Gazebo simulation.
  
- [Sxubach](https://github.com/sxubach)
  - Communication between a PC, the Raspberry Pi 3.0 and Arduino MEGA. 

- [didix21](https://github.com/didix21)
  - Robot and Hardware. 
  - Firmware which allows to control the servos, obtain IMU's and Ultrasonics sensor data.

