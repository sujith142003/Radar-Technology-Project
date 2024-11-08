Automatic Targeting Military Radar Vehicle 🚀
"A smarter vehicle for a safer mission."

Project Overview: 

The Automatic Targeting Military Radar Vehicle is a semi-autonomous, radar-equipped vehicle designed to assist soldiers in high-risk combat environments. With both manual and autonomous operational modes, this project aims to reduce direct human involvement in hazardous situations, enhancing safety and mission efficiency. The vehicle detects and targets enemy vehicles using a combination of radar and camera technologies, and it's remotely controllable via Bluetooth using an ESP32 interface.

Problem Statement:

Modern combat environments demand fast, accurate responses, often exposing soldiers to life-threatening situations. This project proposes a solution that leverages technology to assist soldiers, reducing the need for direct human involvement in combat and high-risk areas. By equipping a vehicle with a radar for detection and a camera for targeting, we aim to improve operational safety and efficiency.

Features
Dual Operation Modes:
Manual: Remotely controlled via Bluetooth, offering precise control for operators.
Autonomous: Self-driving mode with obstacle avoidance for independent operation.
Real-Time Targeting: Radar and camera integration allows for precise enemy detection and targeting.
Safety Enhancements: Minimizes direct human involvement, reducing soldier exposure to danger.
Project Components
Arduino Uno: Core microcontroller for sensor data processing and motor control.
L298N Motor Driver: Controls the vehicle's motors for movement and maneuvering.
Radar System: Detects enemy vehicles and sends data to the Arduino.
ESP32 CAM: Streams live video for target confirmation and visual identification.
Ultrasonic Sensors: Facilitates autonomous navigation by detecting and avoiding obstacles.
Bluetooth Interface (ESP32): Allows remote control in manual mode via a mobile application.
How It Works
Manual Operation
The vehicle is controlled via a mobile app over Bluetooth, using an ESP32 interface.
The radar continuously scans for potential enemy vehicles.
The ESP32 CAM streams real-time footage for visual confirmation.
The operator can lock onto and neutralize the detected target, providing precise control in sensitive scenarios.
Autonomous Operation
The vehicle operates independently, using ultrasonic sensors for obstacle detection and avoidance.
Radar continuously monitors for threats.
Once a target is detected and confirmed by the camera, the vehicle autonomously locks and neutralizes the enemy, avoiding obstacles along the way.
Applications
Combat and Warfare: Enhances soldier safety by detecting and neutralizing enemy vehicles autonomously.
Surveillance and Border Security: Ideal for autonomous patrolling and monitoring in high-risk zones.
Disaster Response: Adaptable for search-and-rescue operations in hazardous terrains.
Challenges and Future Improvements
Signal Interference: Enhancing radar and camera accuracy to function reliably in complex signal environments.
Real-Time Processing: Improving processing speeds to ensure minimal delays for responsive targeting.
Conclusion
The Automatic Targeting Military Radar Vehicle offers a next-gen solution for military applications by combining radar, camera, and autonomous technologies. With both manual and autonomous modes, it provides versatility and safety enhancements suitable for modern warfare and other high-risk applications.

Getting Started
Prerequisites
Arduino IDE
Java Runtime Environment (for control interface)
Bluetooth-enabled device for remote control
Required libraries:
ESP32
Ultrasonic Sensor Library
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/sujith142003/automatic-targeting-military-radar-vehicle
Set up the hardware components as per the circuit diagram (refer to the documentation).
Upload the Arduino code in the src directory to your Arduino Uno.
Connect via Bluetooth to the ESP32 interface for manual control.
Usage
Manual Mode: Connect to the ESP32 interface via a mobile app and control the vehicle remotely.
Autonomous Mode: Switch to autonomous mode to enable self-navigation and target engagement.




Contributors:
Sujith G. GitHub
Jeevabharathi R
Gokul Raj
