# Self-Balancing Robot

## Overview
This project demonstrates the design and implementation of a two-wheeled self-balancing robot based on inverted pendulum dynamics. The system maintains stability using feedback control and real-time sensor data.

## Objective
To develop a robot capable of maintaining balance by continuously correcting its tilt using sensor feedback and motor control.

## Key Concepts
- Inverted pendulum system  
- Closed-loop control (PID)  
- Sensor fusion using MPU6050  

## Hardware Components
- Arduino Uno  
- MPU6050 (Accelerometer + Gyroscope)  
- L298N Motor Driver  
- DC Gear Motors  
- Battery supply  
- MOSFET (for controlled power switching)

## Working Principle
The MPU6050 measures the tilt angle of the robot using accelerometer and gyroscope data.  
A control algorithm processes this data and adjusts motor speeds accordingly to maintain balance.  
The system continuously corrects deviations caused by disturbances.

## Features
- Real-time stabilization  
- Feedback-based control  
- Sensor noise handling  
- Optimized center of mass design  

## Results
- Achieved stable balancing under small disturbances  
- Observed sensitivity to control parameters and sensor noise  

## Challenges
- IMU drift and noise  
- PID tuning  
- Maintaining stability on real surfaces  

## Conclusion
This project demonstrates the integration of mechanical design and control systems to stabilize an inherently unstable system.

## Future Improvements
- Implement advanced filtering (Kalman filter)  
- Improve control algorithm tuning  
- Optimize mechanical design for better stability  

## Author
Aditya Singh
