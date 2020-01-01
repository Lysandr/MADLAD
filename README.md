# MADLAD
Modular Algorithm Demonstration Linux Autonomous Drone (MADLAD)

## What is this?
This is meant to be an open-source drone guidance, navigation, and control platform. The board is equipped with an MPU9260 (3ax accel, 3ax gyro, 3ax mag)
as well as an IMU380ZA, a single source time-of-flight lidar, and a barometer.  It has onboard 3.3V and 5V DC/DC converters. The brain is a
pocketbeagle computer.

Upgrades will be considered at a later time, this project is currently in a get-shit-done-asap stage.


## Goals for this project
* Get the flight computer board functioning.
* Get the PREEMPT_RT thread patch functioning in debian on the pocketbeagle
* Get a decent GNC framework implemented for plug and play algorithms based on a globally defined state machine


