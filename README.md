# ESP32 PID Motor Control

## Overview

This project focuses on implementing a PID-based motor speed controller using an ESP32 microcontroller.

The system uses an MPU6050 IMU for sensor measurements and an ESC to control a brushless DC motor.

## Objectives

- Read gyroscope data from the MPU6050.
- Process and filter sensor measurements.
- Implement a PID controller.
- Generate PWM signals using the ESP32.
- Control the brushless motor through an ESC.
- Evaluate the system's performance.

## Hardware

- ESP32-C3 supermini
- MPU6050 / MPU9250 IMU
- Brushless DC motor (BLDC)
- Electronic Speed Controller (ESC)
- Power supply
- Connecting wires

## Software and Tools

- Arduino IDE
- C++
- ESP32 Arduino Core
- Git and GitHub

## Project Structure

```text
ESP32-PID-Control/
│
├── src/
│   ├── main.cpp
│   ├── imu.cpp
│   └── pid.cpp
│
├── include/
│   ├── imu.h
│   └── pid.h
│
├── docs/
│
└── README.md
```

## Implementation

The project is divided into the following stages:

1. IMU communication and data acquisition.
2. Sensor calibration and filtering.
3. PID controller implementation.
4. ESC signal generation.
5. Motor control and testing.
6. Performance evaluation.

## Contributors

- Safa — Hardware / Firmware
- Maryam — Control Systems
- Safa — Testing

## Project Status

Currently under development.[ESP32 Evaluation Project Assignment Brief.pdf](https://github.com/user-attachments/files/35398184/ESP32.Evaluation.Project.Assignment.Brief.pdf)
