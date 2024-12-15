# IoT Relay Control System

This project demonstrates an IoT-based relay control system using:
- **Ultrasonic Sensor** for distance measurement
- **OLED Display** for status visualization
- **Firebase** for real-time database updates
- **Wi-Fi Module** for connectivity

## Features
- Detects entry and exit using an ultrasonic sensor.
- Turns the relay on/off based on proximity.
- Updates the relay status to Firebase.
- Displays system status on an OLED screen.

## Requirements
- **Hardware**: 
  - ESP32
  - Ultrasonic Sensor (HC-SR04)
  - OLED Display (SSD1306)
  - Relay Module
- **Software**:
  - Arduino IDE
  - Required libraries:
    - `FirebaseESP32`
    - `SSD1306`

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/meahnaf/IOT-.git
