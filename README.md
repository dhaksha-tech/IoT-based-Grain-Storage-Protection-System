# IoT-based-Grain-Storage-Protection-System
IoT-based grain storage protection system using ESP32 and DHT22 for real-time temperature and humidity monitoring, automatic alerts, and ventilation control.
## Overview
The IoT-Based Grain Storage Protection System is designed to monitor
temperature and humidity conditions inside grain storage environments.

The system uses a DHT22 sensor to continuously measure environmental
conditions. An ESP32 processes the sensor readings and sends the data
through Wi-Fi to an IoT dashboard.

When temperature or humidity exceeds predefined limits, the system
generates alerts and automatically activates a ventilation fan through
a relay to reduce the risk of grain spoilage.

## Features
- Real-time temperature monitoring
- Real-time humidity monitoring
- ESP32-based processing
- Wi-Fi connectivity
- IoT dashboard monitoring
- Automatic alerts
- Automatic ventilation control
- Reduced dependence on manual monitoring

## Components
- ESP32
- DHT22 Temperature and Humidity Sensor
- Relay Module
- Ventilation Fan
- Wi-Fi
- IoT Dashboard

## System Workflow

DHT22 Sensor
      ↓
    ESP32
      ↓
   Wi-Fi
      ↓
 IoT Dashboard

ESP32 → Relay → Ventilation Fan

## Project Documentation
The complete project review is available in the `docs` folder.

## Authors
 Dhatchayeni M
 
## References
The project references research papers related to IoT-based grain
storage monitoring and stored-food-grain health monitoring.
