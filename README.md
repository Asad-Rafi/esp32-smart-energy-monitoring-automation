# ESP32 Smart Energy Monitoring and Home Automation System

## Overview
An ESP32-based IoT project for real-time energy monitoring and home automation. The system measures AC voltage, current, power, and energy consumption while providing local and remote monitoring through a web dashboard, Blynk mobile application, and OLED display.

## Features

- Real-time voltage and current measurement
- Power and energy consumption calculation
- CSV data logging using SPIFFS
- Secure web dashboard with login authentication
- Blynk IoT mobile app integration
- 0.96" SSD1306 OLED display
- Temperature and humidity monitoring
- Ultrasonic sensor-based automation
- Device scheduling and automation
- Over-current auto-trip protection

## Hardware Components

- ESP32 Development Board
- SSD1306 OLED Display
- Voltage Sensor Module
- Current Sensor (ACS712 or equivalent)
- DHT11/DHT22 Sensor
- Ultrasonic Sensor (HC-SR04)
- Relay Module
- Power Supply

## Software & Technologies

- Arduino IDE
- ESP32 Framework
- Blynk IoT
- SPIFFS
- HTML/CSS/JavaScript
- Embedded C/C++

## System Architecture

1. Sensors collect electrical and environmental data.
2. ESP32 processes measurements and automation logic.
3. Data is logged to SPIFFS in CSV format.
4. Users monitor and control the system via:
   - Web Dashboard
   - Blynk Mobile App
   - OLED Display

## Safety Features

- Over-current detection
- Automatic load disconnection
- Real-time monitoring and alerts

## Future Improvements

- Cloud database integration
- Energy consumption analytics
- MQTT support
- Machine learning-based load prediction

## Author
Asadul Akter, S M Utshob, and Tamim Ahmed  
Department of Electronics and Telecommunication Engineering (ETE)  

Asadul Akter, S M Utshob, Tamim Ahmed
Department of Electronics and Telecommunication Engineering (ETE)
Chittagong University of Engineering and Technology (CUET)
