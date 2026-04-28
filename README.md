# IoT-based-Smart-Lighting-System
IoT-based smart lighting system using ESP32 and sensors for automated, energy-efficient lighting.

# IoT-based Smart Lighting System (ESP32)

## Overview
Developed an IoT-based smart lighting system using ESP32 that automatically controls lighting based on motion, sound, and ambient light conditions.

## Hardware Components
- ESP32 WiFi/Bluetooth Microcontroller
- HC-SR04 Ultrasonic Sensor (motion detection)
- KY-038 Sound Sensor
- BH1750 Light Sensor
- LED

## Features
- Automatic light control based on motion and sound
- Ambient light detection for energy optimization
- Remote monitoring using Blynk IoT Cloud
- Real-time sensor data visualization

## Working Principle
The system uses multiple sensors to detect environmental conditions:
- Ultrasonic sensor detects human presence
- Sound sensor detects ambient noise
- Light sensor measures surrounding brightness  

Based on these inputs, ESP32 processes data and controls lighting automatically while sending data to Blynk dashboard.

## Technologies Used
- C++ (Arduino IDE)
- ESP32
- I2C, GPIO
- Blynk IoT Cloud

## Applications
- Smart homes
- Energy-efficient buildings
- Automated lighting systems

## Author
Rishav Jaiswal
