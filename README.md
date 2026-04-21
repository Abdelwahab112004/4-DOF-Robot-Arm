# 4-DOF Robotic Arm

This repository contains the full development cycle of a 4-Degree of Freedom (4-DOF) robotic arm. The project bridges the gap between theoretical modeling and physical execution, featuring real-time synchronization, custom GUI control, and advanced Machine Learning integration.

## 🚀 Project Overview
The journey started with mathematical models and simulations, evolving into a physical robotic arm capable of precise pick-and-place operations. The system is designed to perform complex trajectory planning with high repeatability, monitored through a synchronized digital twin in MATLAB.

## 🛠 Tech Stack
* **Mechanical Design:** CAD Modeling (3D Design & Assembly).
* **Simulation & Control:** MATLAB & Simulink.
* **Embedded Systems:** Arduino (Real-world actuation).
* **AI & Machine Learning:** Python/MATLAB (Data-driven training and evaluation).
* **Interface:** Custom-built GUI for real-time visualization and execution.

## 🏗 Key Development Stages

### 1. Modeling & Simulation
* Developed mathematical equations for Kinematics and Dynamics.
* Used **MATLAB** for control development and system response modeling.
* Implemented **Trajectory Planning** to achieve smooth motion in various paths:
    * Straight Line
    * Square & Circular paths
    * Helical Trajectory

### 2. Hardware Implementation
* Fabricated the physical 4-DOF structure based on CAD designs.
* Integrated **Arduino** to translate digital commands into precise physical motion.
* Established real-time synchronization between the MATLAB simulation and the physical hardware.

### 3. AI & Machine Learning Integration 🆕
* Integrated ML models to enhance the robot's decision-making capabilities.
* **Training:** The robot was trained on target points using collected experimental data.
* **Evaluation:** Conducted data-driven experiments to evaluate the accuracy and efficiency of the AI-controlled motion compared to traditional algorithms.

## 📂 Repository Structure
* `AI Model/`: Machine Learning scripts, datasets, and trained models.
* `Codes/`: Arduino sketches and MATLAB control scripts.
* `Design/`: CAD files and mechanical specifications.
* `Images and Videos/`: Visual documentation of the project in action.
* `Reports/`: Detailed technical documentation and project milestones.
* `WorkSpace Data/`: Simulation environments and workspace analysis data.
