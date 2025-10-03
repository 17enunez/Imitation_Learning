# Imitation_Learning
Robotic Manipulation in Nvidia Isaac Sim

**Author:** Ela Nuñez | **Summer 2024 – NRL, Washington DC**

## Project Summary
Simulated and controlled a **Robotiq 2F85 gripper** attached to a **Kinova Gen3 7-DOF arm** in **Nvidia Isaac Sim Omniverse** for imitation learning data collection. This project enables efficient generation of robot demonstration datasets without manual teleoperation.

## Highlights
- **Rigging & Assembly:** Imported CAD models, resolved articulation loops, enabled collisions, and assembled gripper + arm.  
- **Control Implementation:** Applied position and velocity PD controllers for smooth gripper and arm motion.  
- **Simulation Testing:** Demonstrated gripper open/close actions and partial automated arm-gripper control.  
- **Bug Fixes & Contributions:** Identified and resolved Nvidia Isaac Sim software issues, submitted bug fixes to improve robot control.

## Tools & Frameworks
- Nvidia Isaac Sim & Isaac Lab  
- Python & USD assets  
- Robot Assembler Extension  
- Robomimic framework (for future imitation learning datasets)

## Outcome
- Fully rigged and partially controllable gripper-arm assembly in simulation.  
- Velocity control effective for grasping; position control suited for precise placement.  
- Platform ready for generating imitation learning datasets.

[![NVIDIA Robot Assembler](https://img.youtube.com/vi/dC7FEgKUbtI/maxresdefault.jpg)](https://www.youtube.com/watch?v=dC7FEgKUbtI)

_Distribution Statement A: Approved for public release; distribution is unlimited._
