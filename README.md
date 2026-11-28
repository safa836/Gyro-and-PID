# ESP32 PID Motor Control

## Overview

This project focuses on implementing a PID-based motor speed controller using an ESP32 microcontroller.

The system uses an HW-290 IMU module equipped with an MPU-6050 sensor to measure angular velocity along three axes and an ESC to control a brushless DC motor.

## Objectives

- Read gyroscope data from the HW-290 IMU module.
- Process and filter sensor measurements.
- Implement a one-axis PID controller and a Kalman filter.
- Generate PWM signals using the ESP32.
- Control the brushless motor through an ESC.
- Set up and evaluate the system's performance on a test bench.
- Develop a real-time PID tuning and sensor monitoring panel with live gyroscope data visualization and adjustable controller gains.

## Hardware

- ESP32 Devkit V1
- HW-290 IMU module
- Brushless DC motor (BLDC)
- Electronic Speed Controller (ESC)
- Power supply
- Connecting wires

## Software and Tools

- Arduino IDE
- C++
- Python and Matlab simulation
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

## Project Status

Currently under development.