# RC Submarine

## Overview

This is a low-cost, advanced RC submarine designed for underwater robotics and STEM learning. The project is meant to be submitted for a HackClub grant and includes smart control, 3D printed body, and sensor integration.

---
<img width="600" height="333" alt="2f815423-4aff-486b-aad0-247c102af4b6_removalai_preview" src="https://github.com/user-attachments/assets/d8b53d92-61f5-4964-a4e9-11b543a289d3" />

## Features

- Wireless Remote-Controlled Navigation
- Waterproof 3D Printed Hull
- Camera Integration 
- Arduino-based Smart Control System
- Depth and Leak Sensors
- 6-7 Days Build Timeline

---<img width="1536" height="1024" alt="ChatGPT Image Jul 29, 2025, 04_57_19 PM" src="https://github.com/user-attachments/assets/aa8bd55f-718a-4b47-9c5b-e648d5fd32e5" />
<img width="1907" height="1111" alt="Screenshot 2025-07-29 175733" src="https://github.com/user-attachments/assets/137520f0-b5d7-41b5-9c69-8e5a82a02db1" />

This project aims to build a compact, WiFi-controlled submarine equipped with an ESP32-CAM for live First-Person View (FPV) streaming. It uses brushless waterproof motors for propulsion and servo-controlled fins for steering. The submarine will also log environmental data such as water temperature, depth (via pressure sensor), and motion (via IMU) to an onboard SD card for analysis.

The system is wireless but includes a tether fallback for power or control in case of signal loss. Designed with an acrylic waterproof body, custom 3D-printed parts, and epoxy-sealed electronics, the sub can perform basic underwater maneuvers and real-time monitoring.

 Key Features:
| Feature                | Component Used                 | Purpose                              |
| ---------------------- | ------------------------------ | ------------------------------------ |
| FPV Video Streaming    | ESP32-CAM                      | Real-time video wirelessly           |
| Wireless Control       | ESP32 / Mobile app (future)    | Submarine movement                   |
| Propulsion             | Waterproof Brushless DC Motors | Forward and reverse motion           |
| Steering Control       | SG90 Servo Motors              | Pitch and yaw adjustments            |
| Depth Sensing          | BMP280 / MS5803                | Pressure-based water depth detection |
| Temperature Monitoring | DS18B20 Waterproof Sensor      | Logs water temperature               |
| Orientation Control    | MPU6050 IMU                    | Detect and correct tilt and motion   |
| Data Logging           | SD Card Module + 16GB SD Card  | Stores sensor data                   |
| Waterproof Body        | Acrylic Tube + O-rings + Epoxy | Ensures leak-proof underwater use    |
| Emergency Tether       | Ethernet/Custom Cable          | Power and signal backup              |



---

## Tools and Tech Used

- Arduino UNO
- ESC (Electronic Speed Controller)
- LiPo Battery (11.1V 2200mAh)
- 775 DC Motor (2x)
- SG90 Servo (for rudder)
- NRF24L01 Wireless Module
- 3D Printer (PLA filament)
- Fusion 360 / TinkerCAD / OpenSCAD
- Waterproof Sealants
- Miscellaneous wires, tubing, screws

---

## Budget and BOM

## Component Breakdown

| Component                    | Quantity | Approx. Cost (INR) | Notes |
|-----------------------------|----------|---------------------|-------|
| ESP32-CAM                   | 1        | ₹650                | Live camera and WiFi control |
| Waterproof BLDC motors      | 2        | ₹2400               | Core propulsion unit |
| SG90 servo motors           | 2        | ₹400                | Controls steering fins |
| MS5803 or BMP280 sensor     | 1        | ₹1000               | Depth sensing via water pressure |
| MPU6050 IMU                 | 1        | ₹300                | Orientation and pitch detection |
| DS18B20 waterproof sensor   | 1        | ₹200                | Measures underwater temperature |
| SD card + adapter module    | 1        | ₹750                | Data logging functionality |
| Acrylic tube + end caps     | 1        | ₹1200               | Core waterproof enclosure |
| O-rings, epoxy, seals       | -        | ₹850                | Ensures leak-proof housing |
| PLA filament (1kg)          | -        | ₹1100               | For 3D printing components |
| Misc: wires, screws, heat shrink | -   | ₹700                | Connectors, stabilizers, mounting |

**Total estimated cost: ₹11,550 - ₹13,000** (varies by sensor availability)

Estimated Total Cost: **$170 USD**


---


## Open Source Plan

All source files—including STL files, wiring schematics, and Arduino code—will be documented and published on GitHub. Full replication instructions will be provided for students, teachers, and open-source contributors.

## License

This project is open-source under the MIT License.
