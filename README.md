
# Robotic Arm Simulation – First Design in MATLAB Simulink

![Made with MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-blue?logo=mathworks&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-Modeling-red?logo=mathworks&logoColor=white)
![Status](https://img.shields.io/badge/Project-Prototype-yellow)
![Learning Project](https://img.shields.io/badge/Type-Learning_Project-green)

## Overview

This project marks my first attempt at designing and simulating a robotic arm using **MATLAB Simulink**. While the design does not represent a real robotic arm with motors and sensors, it visually and structurally mimics the components of one:

- **Base and Shoulder**: The foundational structure.  
- **Link 1 (Elbow)**: The first moving segment.  
- **Link 2 (Forearm)**: The second moving segment.  
- **End Effector**: A point representing a gripper or tool.

I followed this [YouTube tutorial](https://www.youtube.com/watch?v=_8YCc3pJDPI) to guide my process.

## What I Learned

- ✅ **Simulink Component Chain**: I understood how to logically connect blocks in Simulink to represent a mechanical system using a chain structure.  
- ✅ **Simulation Setup**: I learned how to configure joints, rigid transforms, and coordinate frames to build a robot-like system.  
- ✅ **Physics & Parameters**: I explored how physical parameters (mass, inertia, rotation axes, and joint limits) affect movement and interaction between parts.  
- ✅ **Basic Kinematics**: I observed how movement propagates through the chain, from the base to the end effector.

## Project Content

- 📷 **Simulation Video**: Includes a video showing the robotic arm moving through a predefined motion path.
  
    https://github.com/user-attachments/assets/9ee624a8-43e0-4fbb-860b-2a57a486e290


- 🖼️ **Design Image**: Displays each component and how they are arranged to resemble a robot arm.
    ![1st_Robotic_Design](https://github.com/user-attachments/assets/c7e14b08-8935-4e64-b622-76d1feed96da)

- 🧩 **Model Chain View**: Shows how the physical components are connected in Simulink's tree/chain format.
    ![1st_Robotic_Design_Final_Sketch](https://github.com/user-attachments/assets/ad14f692-621a-4e16-98de-e13224751934)

## Purpose

This project is a foundational step toward more advanced robotics development. It helped me:

- Understand how simulation tools like Simulink work for robotics.  
- Get hands-on experience with mechanical modeling and system dynamics.  
- Prepare for designing and building my first physical robot arm.

## Next Steps

- Add more degrees of freedom.  
- Implement motor control.  
- Introduce sensors and feedback systems.  
- Begin designing physical components for prototyping.

