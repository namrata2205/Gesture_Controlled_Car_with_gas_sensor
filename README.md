# Gesture Controlled Car with Gas Detection

## Project Overview
This project implements a gesture-controlled robotic car using an ESP32 microcontroller and an MPU6050 motion sensor. Hand gestures are captured and converted into directional commands to control the car wirelessly.
The system also integrates an MQ-2 gas sensor to detect harmful gases in the environment and trigger an alert when the gas level exceeds a predefined threshold. The project demonstrates the integration of IoT and sensor-based technologies for smart mobility and environmental safety.

## Features
- Gesture-based vehicle control
- Wireless communication between transmitter and receiver
- Real-time gas detection using MQ-2 sensor
- Multi-directional movement (forward, backward, left, right, stop)

## Technologies Used
- ESP32 Microcontroller
- MPU6050 Motion Sensor
- MQ-2 Gas Sensor
- L298N Motor Driver
- Arduino IDE

## Hardware Components
- ESP32 (2 units)
- MPU6050 sensor
- MQ-2 gas sensor
- L298N motor driver
- DC motors and wheels
- Jumper wires
- Power supply

## Working Principle
1. The MPU6050 sensor detects hand gestures by measuring tilt and motion.
2. The transmitter ESP32 processes the motion data.
3. Commands are sent wirelessly to the receiver ESP32.
4. The receiver ESP32 controls the motors through the L298N motor driver.
5. The MQ-2 gas sensor continuously monitors gas levels and activates an alert if harmful gases are detected.

## Note
This project was originally developed earlier as part of an academic IoT project.  
The prototype worked successfully during initial testing; however, the hardware setup is currently not functional due to component damage over time. The repository is shared to document the project design, implementation approach, and system architecture.

## Author
Namrata Thorat  
B.Tech Electronics and Computer Science Engineering
