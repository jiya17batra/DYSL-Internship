# DYSL Internship — Simulated Drone Swarm Controller

## Overview

This repository contains the work completed during my internship at **DRDO-DYSL (Defence Research and Development Organisation – DYSL)** from **April 2025 to June 2025**.

The project focuses on designing and simulating a **multi-drone swarm control system** using **ROS, PX4, MAVROS, Gazebo, and RViz**, along with a web-based interface for real-time monitoring and control.

As **Team Leader** and **Web Interface Integrator**, I contributed to both project coordination and frontend-backend integration for seamless drone interaction.

---

## Project Objective

The goal of this project is to simulate and manage multiple autonomous drones in a virtual environment, enabling:

* Drone swarm coordination
* Real-time telemetry visualization
* Multi-drone communication
* Web-based remote control
* Scalable autonomous flight simulations

---

## Tech Stack

### Robotics & Simulation

* ROS Noetic
* PX4 SITL
* MAVROS
* Gazebo
* RViz
* Ubuntu 20.04

### Web Interface

* Python
* Flask
* HTML
* CSS
* JavaScript
* rosbridge_suite
* roslibjs

### Development Tools

* Git
* GitHub
* Linux Terminal

---

## Key Features

✅ Multi-drone simulation environment
✅ ROS-based communication architecture
✅ PX4 + MAVROS integration
✅ Namespace-based swarm management
✅ Drone formation simulation
✅ Real-time telemetry visualization
✅ Browser-based control dashboard

---

## System Architecture

```bash
Web Interface (HTML/CSS/JS)
        ↓
      Flask Server
        ↓
   rosbridge_suite
        ↓
        ROS
   ↙          ↘
MAVROS       ROS Nodes
   ↓
  PX4 SITL
   ↓
Gazebo / RViz
```

---

## Repository Structure

```bash
dysl-internship/
│
├── docs/               # Documentation and reports
├── simulation/         # Gazebo / PX4 setup files
├── web-interface/      # Flask + frontend code
├── ros-nodes/          # ROS publisher/subscriber nodes
├── assets/             # Images, screenshots
└── README.md
```

---

## My Contributions

### Team Leadership

* Coordinated team workflow
* Assigned tasks and monitored progress
* Ensured smooth communication between modules

### Web Interface Integration

* Designed frontend architecture
* Connected browser UI with ROS backend
* Enabled telemetry and control visualization
* Worked with WebSockets for real-time communication

### Development & Research

* Studied ROS architecture
* Worked on node communication
* Assisted in simulation debugging
* Improved system integration

---

## Challenges Faced

* ROS ↔ PX4 version compatibility
* Multi-drone namespace management
* Real-time browser communication latency
* WebSocket and ROS bridge debugging

---

## Outcomes

* Successfully simulated drone swarms
* Visualized drone data in RViz
* Demonstrated formation control
* Built a functional web interface for interaction

---

## Future Scope

* AI-based swarm intelligence
* Obstacle avoidance algorithms
* Real-world drone deployment
* Advanced mission planning dashboard
* ML-powered autonomous navigation

---

## Team

* Nalli Tareni
* Christina Joseph
* Kannishkitha
* Sindhu Kamandla
* Sree Samhitha
* Onteddula Vamshi
* Rahul Patel
* **Jiya Batra (Team Leader)**

---

## Author

## Jiya Batra

Developer • Designer • Problem Solver

Passionate about building interactive systems that bridge software, design, and real-world applications.

---

> “Innovation happens where software meets intelligence.”
