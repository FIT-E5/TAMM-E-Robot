# TAMM-E
### Touch-enabled Autonomous Mobile Machine for Education

TAMM-E is an autonomous indoor service robot developed as a Computer Engineering capstone project at FEU Institute of Technology.

The robot combines autonomous navigation, obstacle avoidance, conversational AI, and an intuitive touchscreen interface to assist users in navigating indoor environments such as educational institutions.

---

## Project Overview

TAMM-E was designed to function as an intelligent mobile assistant capable of:

- Autonomous indoor navigation
- Human-robot interaction through conversational AI
- Real-time obstacle avoidance
- Location guidance and educational assistance
- Safe operation in populated environments

The system utilizes ROS 2 Jazzy, Nav2, LiDAR-based localization, encoder odometry, and a custom ESP32 motor control system to achieve reliable autonomous operation.

---

## Features

### Autonomous Navigation
- ROS 2 Jazzy Navigation Stack (Nav2)
- Touch-to-Move Navigation
- Autonomous Path Planning
- Dynamic Obstacle Avoidance
- AMCL Localization
- Emergency Stop Recovery System

### Mapping & Localization
- SLAM Toolbox
- Occupancy Grid Mapping
- LiDAR-Based Localization
- Encoder Odometry
- IMU Sensor Fusion

### Conversational AI
- Speech-to-Text
- Text-to-Speech
- Large Language Model Integration
- Interactive User Assistance

### User Interface
- Fullscreen Control Center
- Navigation Mode
- Mapping Mode
- Follow Object Mode *(In Development)*
- Battery Monitoring
- Robot Status Monitoring

### Safety Systems
- Emergency Stop Switch
- Collision Monitoring
- Obstacle Avoidance
- Localization Recovery

---

## Hardware Specifications

| Component | Specification |
|------------|------------|
| Controller | ESP32 |
| LiDAR | RPLidar C1 |
| IMU | MPU6050 |
| Motor Driver | BTS7960 |
| Motors | GB37Y3530 12V 83RPM Metal Gear Motors |
| Encoder Resolution | 2096 CPR |
| Battery | 24V 30Ah |
| Drive Type | Differential Drive |
| Wheel Diameter | 125mm |

---

## Software Stack

### Robotics
- ROS 2 Jazzy
- Nav2
- AMCL
- SLAM Toolbox
- Robot Localization

### Development
- Python
- C++
- Arduino Framework
- PyQt

### AI Components
- Speech-to-Text
- Large Language Model
- Text-to-Speech

---

## System Architecture

```text
Touchscreen UI
       │
       ▼
ROS 2 Control Layer
       │
 ┌─────┴─────┐
 ▼           ▼
Localization Navigation
 (AMCL)       (Nav2)
       │
       ▼
Motor Bridge
       │
       ▼
ESP32 Controller
       │
       ▼
BTS7960 Drivers
       │
       ▼
Differential Drive Motors
```

---

## Current Development Status

### Completed
- Differential Drive Motor Control
- Encoder Odometry
- LiDAR Integration
- Mapping System
- Localization System
- Autonomous Navigation
- Obstacle Avoidance
- Emergency Stop System
- Battery Monitoring
- Touch-to-Move Navigation

### In Progress
- Fullscreen Control Center
- Follow Object Mode
- Advanced Navigation UI
- Conversational AI Integration
- User Experience Improvements

---

## Project Goals

The primary objectives of TAMM-E are:

- Provide autonomous navigation assistance
- Deliver educational information through conversational interaction
- Safely operate in indoor environments
- Demonstrate the integration of robotics and artificial intelligence
- Serve as an educational service robot platform

---

## Future Improvements

- Follow-Me Navigation
- Object Detection & Tracking
- Face Recognition
- Autonomous Docking
- Multi-Floor Navigation

---

## Authors

### FEU Institute of Technology
Bachelor of Science in Computer Engineering

Thesis E5 Team

Members:
- John David Ceaser C. Perez
- Ivan Aron Simon
- Carl Lacsamana
- Christoper Estrada

---

## License

This project was developed for academic and research purposes.

© 2025 TAMM-E Development Team
