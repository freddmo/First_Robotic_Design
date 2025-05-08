# Robotic Arm Simulation – First Design in MATLAB Simulink

![Made with MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-blue?logo=mathworks\&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-Modeling-red?logo=mathworks\&logoColor=white)
![Status](https://img.shields.io/badge/Project-Prototype-yellow)
![Learning Project](https://img.shields.io/badge/Type-Learning_Project-green)

## Overview

This project marks my first attempt at designing and simulating a robotic arm using **MATLAB Simulink**. While the design does not represent a real robotic arm with motors and sensors, it visually and structurally mimics the components of one:

* **Base and Shoulder**: The foundational structure.
* **Link 1 (Elbow)**: The first moving segment.
* **Link 2 (Forearm)**: The second moving segment.
* **End Effector**: A point representing a gripper or tool.

I followed this [YouTube tutorial](https://www.youtube.com/watch?v=_8YCc3pJDPI) to guide my process.

## What I Learned

* ✅ **Simulink Component Chain**: Logical connection of blocks to represent mechanical systems.
* ✅ **Simulation Setup**: Configuration of joints, rigid transforms, and coordinate frames.
* ✅ **Physics & Parameters**: Impact of mass, inertia, joint limits, and rotation axes.
* ✅ **Basic Kinematics**: Movement propagation from the base to the end-effector.
* ✅ **Jacobian Analysis**: Using the Jacobian to relate joint velocities to end-effector velocities.
* ✅ **Trajectory Generation**: Using toolbox blocks to generate smooth motion profiles.
* ✅ **Inverse Kinematics (IK)**: Driving a manipulator through predefined paths with IK solvers.

---

## Project Content

### 📹 Simulation Video

A demonstration of the robotic arm executing a predefined motion path.

[https://github.com/user-attachments/assets/9ee624a8-43e0-4fbb-860b-2a57a486e290](https://github.com/user-attachments/assets/9ee624a8-43e0-4fbb-860b-2a57a486e290)

---

### 🖼️ Design Image

Displays the physical layout of each component in the robotic arm.
![1st\_Robotic\_Design](https://github.com/user-attachments/assets/c7e14b08-8935-4e64-b622-76d1feed96da)

---

### 🧩 Simulink Model Chain View

Visualizes the hierarchical tree structure of the model.
![1st\_Robotic\_Design\_Final\_Sketch](https://github.com/user-attachments/assets/ad14f692-621a-4e16-98de-e13224751934)

---

## ➕ New Additions

---

### 🎯 Inverse Kinematics on a Simple Trajectory

Applied **Inverse Kinematics** (IK) to move a planar robotic arm along a simple 2D path. The target trajectory was defined, and joint configurations were calculated in real-time to follow the path.

📷 *First I understood how the joints on a simple arm*



https://github.com/user-attachments/assets/2fe4e228-7550-4879-a725-57aaa8887e0c



https://github.com/user-attachments/assets/0217a4c7-83f4-4e63-84d3-2c45f7f929b5


### 🔧 Jacobian and End-Effector Velocities

Used **Robotics System Toolbox** to compute the **Jacobian Matrix**, which allows mapping joint velocities to end-effector linear and angular velocities. This enables deeper analysis of motion behavior and control design.

https://github.com/user-attachments/assets/4d724a59-2772-4d2c-b0db-25063001dd02

![JacovianVelocity_InverseKinematics_Scope_Results](https://github.com/user-attachments/assets/fa55afe7-e639-4427-be63-1debe34ae1c5)

---

### 📈 Trajectory Generation using Toolbox Blocks

Implemented trajectory planning using:

* **Polynomial Trajectory Block**
* **Trapezoidal Velocity Trajectory Block**

These allow for the generation of smooth position, velocity, and acceleration profiles.

### 🛠️ Driving the Simscape-Based Manipulator with Random Trajectories
Used the previously designed manipulator model from Simscape and fed it with randomly generated trajectories. This tested the system's ability to follow various paths and react dynamically.

## Purpose

This project is a foundational step toward more advanced robotics development. It helped me:

* Understand how simulation tools like Simulink work for robotics.
* Get hands-on experience with mechanical modeling and system dynamics.
* Prepare for designing and building my first physical robot arm.

---

## Next Steps

* Add more degrees of freedom.
* Implement motor control.
* Introduce sensors and feedback systems.
* Begin designing physical components for prototyping.


