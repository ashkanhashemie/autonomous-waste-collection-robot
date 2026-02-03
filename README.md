# Autonomous Waste Collection Robot

An autonomous mobile robot designed for indoor and outdoor waste collection, featuring embedded control, sensor-based navigation, and environmentally responsible mechanical design.

---

## Project Overview

This project focuses on the design and development of an autonomous mobile robot capable of collecting small waste materials from indoor environments as well as outdoor areas such as beaches, jungles and forests.
The robot is equipped with a rotating brush mechanism that transfers surface waste into an internal storage container. Using multiple ultrasonic distance sensors, the system navigates autonomously and avoids obstacles without human intervention (almost :)).
A key objective of this project is to contribute to environmental protection by enabling efficient and selective waste collection while minimizing disturbance to natural surfaces.

---

## Project Objectives

- Design an autonomous robot for waste collection in various environments.  
- Enable obstacle avoidance using distance sensors.  
- Implement a mechanical filtering system to separate waste from sand and soil.  
- Develop a modular and maintainable mechanical structure.  
- Ensure safe operation in semi-structured outdoor environments.  

---

## Mechanical Design

The mechanical structure of the robot was designed using CAD software and optimized for outdoor operation.

Key mechanical features include:

- Tracked wheel system inspired by tank tracks for improved traction on sand, soil, and uneven terrain  
- Replaceable wheel mechanism allowing conversion to standard wheels for indoor use  
- Dual-compartment internal structure:
  - Upper section: Electronic circuits, wiring, and control units  
  - Lower section: Motors, Sensors, and waste collection chamber  
- Perforated waste chamber base that allows sand and soil to pass through while retaining solid waste.  
- Rotating brush system for surface cleaning and waste intake.  

This modular design improves accessibility for maintenance and protects sensitive electronic components from environmental damage.

Detailed mechanical models and files are available in the "CAD" directory.

---

## Hardware System

The electronic system is based on an embedded control architecture and includes various electronic components.
The hardware subsystem is documented in detail in the "Hardware" directory.

---

## Firmware and Control Logic

The robot firmware was developed using the Arduino framework in C/C++.
Main software features include:
- Real-time distance measurement using ultrasonic sensors.  
- Autonomous navigation based on multi-sensor distance analysis.  
- Obstacle detection and avoidance algorithm. 
- Motor speed and direction control.  
- System status display on LCD.  
- Safety and fault-handling routines.

All source code and documentation are available in the "Firmware" directory.

---

## Navigation Strategy

The navigation system relies on four ultrasonic sensors placed strategically around the robot.
Based on distance measurements, the robot determines safe movement paths and dynamically changes direction to avoid obstacles.
This approach enables fully autonomous operation in both indoor and outdoor environments without external positioning systems.

---

## Setup and Deployment

1. Assemble the mechanical frame using the CAD designs.
2. Install motors, sensors, and the brush mechanism.
3. Print PCB Board and do the soldering, and then connect electronic components according to the hardware schematics.
4. Upload the firmware to the microcontroller.
5. Calibrate sensors and test navigation performance.
6. Deploy the robot in the target environment.

---

## Demonstration and Media

Photos, videos, and additional documentation of the working prototype are available in the "Media" directory.

---

## Current Limitations

Although the prototype demonstrates reliable autonomous operation, several limitations remain:

- Navigation accuracy depends on the ultrasonic sensor resolution  
- Limited operation time due to battery capacity  
- Reduced performance in highly cluttered environments  
- No visual-based object recognition system  
- Manual control mode not yet implemented  

These limitations represent opportunities for future development.

---

## Future Improvements

Planned and potential enhancements include:

- Integration of solar panels for continuous battery charging  
- Addition of Raspberry Pi and camera module for computer vision and AI-based waste detection  
- Hybrid control system with autonomous and manual modes  
- Mobile application for monitoring and remote control  
- Wireless communication via Bluetooth and Wi-Fi  
- Advanced path-planning algorithms  

---

## Project Status

This project is currently implemented as a functional prototype and remains open for further development and optimization.

---

## Learning Outcomes

Through this project, practical experience was gained in:

- Mechanical system design and modular construction  
- Embedded electronics and power management  
- Autonomous navigation algorithms  
- Sensor integration and calibration  
- System-level robotics engineering  

