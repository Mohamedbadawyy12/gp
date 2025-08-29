# Autonomous Indoor Navigation Robot with ROS2

A full-scale autonomous robot designed for real-time mapping (SLAM) and navigation in dynamic indoor environments. This project showcases a complete mechatronics and software engineering workflow, from initial design and simulation to physical deployment and testing.

---

## 📋 Table of Contents
- [About The Project](#about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [System Architecture](#-system-architecture)
- [Getting Started](#-getting-started)
- [Usage](#-usage)
- [Contact](#-contact)

---

## 🚀 About The Project

This project was developed to create a complete autonomous indoor robot from the ground up, demonstrating a holistic skill set across robotics, mechatronics, and software engineering. The core challenge was to build a robust and reliable navigation system capable of performing Simultaneous Localization and Mapping (SLAM) and executing autonomous path planning tasks in real-time.

The entire system was architected using the Robot Operating System 2 (ROS2), with a focus on modularity and real-world performance. The development process spanned from theoretical calculations and digital design in SOLIDWORKS and PROTEUS to physical prototyping with 3D printing and final deployment on a Raspberry Pi and Arduino-based platform.

---

## ✨ Key Features

* **Real-Time SLAM:** Implemented a SLAM algorithm using the ROS2 stack for simultaneous environment mapping and robot localization. 🗺️
* **Autonomous Navigation:** Developed a robust path planning stack utilizing Navi Stacks, AMCL, and a Local Planner for dynamic obstacle avoidance.
* **Multi-Sensor Integration:** Successfully integrated and calibrated a suite of sensors including an RP Lidar A1 M8, IMU, and wheel encoders for precise environmental perception. 📡
* **High-Fidelity Simulation:** Constructed a custom virtual environment in Gazebo for rigorous testing of algorithms and system validation before physical deployment. 💻
* **Custom Mechanical & Electronic Design:** Designed the robot chassis in SOLIDWORKS and custom PCBs in PROTEUS, supported by detailed stress, load, and power calculations. ⚙️⚡

---

## 🛠️ Tech Stack

### Hardware
* **Primary Lidar:** RP Lidar A1 M8
* **Microcontroller:** Raspberry Pi (High-level logic, ROS2)
* **Microcontroller:** Arduino (Low-level motor control, sensor interface)
* **Sensors:** Inertial Measurement Unit (IMU), Wheel Encoders
* **Power:** DC/DC Converters
* **Actuators:** DC Motors with custom PID tuning
* **Drivers:** Motor Drivers

### Software & OS
* **Robotics Framework:** ROS2 (Robot Operating System 2)
* **Operating System:** Linux (Ubuntu)
* **Programming Languages:** C++ (low-level sensor communication, control loops), Python (high-level logic, scripting)
* **Navigation:** ROS2 Navi Stacks, AMCL (Adaptive Monte Carlo Localization), Local Planner

### Simulation & Visualization
* **Simulation Environment:** Gazebo
* **Data Visualization:** RViz

### CAD & Electronics Design
* **Mechanical CAD:** SOLIDWORKS
* **Electronics Design & Simulation:** PROTEUS

---
![1718560139212](https://github.com/user-attachments/assets/9d268694-056a-44a3-8ec0-4980c687c3d3)
![1719368251191](https://github.com/user-attachments/assets/df8dd031-4fe8-4039-b04c-4d9920bd2510)
![1719363006972](https://github.com/user-attachments/assets/8812c606-c477-4dfa-97bf-631db975dd41)
![1720797049773](https://github.com/user-attachments/assets/7ea30279-40d7-4356-b05e-a3fd30831ab9)



