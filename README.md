# TAMM-E

### Autonomous Local AI Campus Assistant for FEU Institute of Technology

TAMM-e is an autonomous robotic campus assistant developed as a Computer Engineering capstone project at FEU Institute of Technology.

The project combines autonomous indoor navigation, conversational artificial intelligence, and real-time user interaction into a single robotic platform designed to assist students, faculty, and visitors.

---

## Features

### Autonomous Navigation

* ROS2 Jazzy Navigation Stack (Nav2)
* LiDAR-based localization and mapping
* Autonomous point-to-point navigation
* Obstacle avoidance
* AMCL localization
* Touch-to-Move navigation interface
* Real-time path planning

### Conversational AI

* Local Speech-to-Text (STT)
* Local Large Language Model (LLM)
* Text-to-Speech (TTS)
* School information assistance
* Campus navigation assistance
* QR-based database updates

### Robot Systems

* ESP32 motor controller
* Differential drive locomotion
* Encoder-based odometry
* IMU-assisted localization
* Battery monitoring system
* Emergency stop system

### User Interface

* Navigation control panel
* Real-time robot monitoring
* Battery status display
* Map visualization
* Autonomous navigation controls

---

## System Architecture

TAMM-E consists of three primary subsystems:

### Robotics System

* ROS2 Jazzy
* Nav2
* AMCL
* SLAM Toolbox
* Robot Localization (EKF)
* RViz

### Embedded System

* ESP32
* BTS7960 Motor Drivers
* Wheel Encoders
* Battery Monitoring Circuit

### AI System

* Local LLM
* Speech Recognition
* Speech Synthesis
* Campus Knowledge Database

---

## Hardware

### Computing

* Laptop PC (Main Processing Unit)
* ESP32 Microcontroller

### Sensors

* RPLidar C1
* MPU6050 IMU
* Wheel Encoders

### Motion System

* 2x GB37Y3530 12V 83RPM Geared Motors
* 2x BTS7960 Motor Drivers
* Differential Drive Configuration

### Power System

* 24V Lithium Battery
* XL4016 Step Down Converter

---

## Software Stack

* Ubuntu 24.04
* ROS2 Jazzy
* Nav2
* AMCL
* SLAM Toolbox
* Robot Localization
* Python
* PyQt5

---

## Current Capabilities

✔ Autonomous Navigation

✔ Obstacle Avoidance

✔ Real-Time Localization

✔ Touch-to-Move Control

✔ Conversational AI

✔ Battery Monitoring

✔ Emergency Stop Recovery

✔ Map-Based Navigation

---

## Future Development

The following features are planned for future versions of TAMM-E:

* Depth Camera Integration
* Kinect-Based Object Recognition
* Person Following Mode
* Multi-Floor Navigation
* Facial Recognition
* Emotion Recognition
* Dynamic Route Learning
* Autonomous Charging Dock
* Expanded Campus Coverage

---

## Researchers

* Christofer P. Estrada
* Carl Marcius Daile D. Lacsamana
* John David Ceasar C. Perez
* Ivan Aron S. Simon

FEU Institute of Technology

Bachelor of Science in Computer Engineering

---

## Adviser

Engr. Niño U. Pilueta

---

## License

This repository is intended for academic and research purposes.
