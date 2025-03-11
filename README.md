# Car-Accident-Detector-Alert-System
Car Accident Detector &amp; Alert System using BlackBox Technology 

## 📌 Introduction
Car accidents are a major cause of fatalities worldwide. The **Car Accident Detector & Recorder** is an **IoT-based smart system** designed to detect car accidents, record crucial data, and send instant alerts to emergency contacts. This system helps in **saving lives** by providing **real-time location tracking**, accident data storage, and **immediate alerts** for critical incidents such as fire, vibration, and alcohol detection.

## 🏗️ Project Overview
This system utilizes multiple sensors, a microcontroller (ESP8266 NodeMCU), and GSM/GPS communication to detect accidents and alert emergency contacts. The collected data is also stored for future analysis.

## 🔧 Features
- 🚀 **Real-time Accident Detection** using vibration, gyroscope, and temperature sensors.
- 📡 **GPS & GSM Integration** for sending instant location alerts via SMS.
- 🛰️ **IoT-based Remote Monitoring** using **Blynk** for live status tracking.
- 🔥 **Fire & Alcohol Detection** to identify hazardous situations.
- 💾 **Accident Data Storage** for investigation and analytics.
- 📊 **Live Data Monitoring** via mobile app.

## 📜 System Architecture
### ⚙️ Components Used
- **Microcontroller**: NodeMCU ESP8266
- **Sensors**:
  - Temperature Sensor (Fire Detection)
  - Vibration Sensor (Impact Detection)
  - Alcohol Sensor (Drunk Driving Detection)
  - Gyroscope Sensor (Vehicle Tilt Detection)
- **Communication Modules**:
  - GPS Module (Location Tracking)
  - GSM Module (SMS Alerts)
- **Storage**: SD Card Module
- **Software & Cloud Services**:
  - Blynk IoT Platform
  - Arduino IDE for Programming

## 📲 How It Works
1. **Accident Detection**: When an impact is detected, data is recorded.
2. **Data Logging**: Sensor readings are stored on the SD card.
3. **Emergency Alert**: SMS with **GPS Location** is sent via the GSM module.
4. **Remote Monitoring**: Live data is accessible through the **Blynk IoT App**.
