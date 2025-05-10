# Pothole Detection System using Ultrasonic and Vibration Sensors

This repository contains the implementation of a low-cost, real-time pothole detection system developed at Shri Ramdeobaba College of Engineering and Management, Nagpur.

## Project Overview

Poor road conditions are a major contributor to accidents and vehicle damage. This system addresses the issue by automatically detecting potholes and transmitting their location and severity to the concerned authorities. It aims to improve road safety and response time for maintenance.

## How It Works

The system integrates the following components:

- Ultrasonic Sensor: Measures the depth and volume of potholes.
- Vibration Sensor: Confirms the presence of potholes.
- GPS Module: Pinpoints the geographic location.
- GSM Module: Sends SMS alerts to authorities.
- Arduino UNO: Processes and controls the system logic.
- ThinkSpeak Server: Stores and visualizes pothole data in real time.

## Components Used

| Component              | Cost (INR) |
|------------------------|------------|
| GSM SIM 900A Module    | 900        |
| Arduino UNO            | 600        |
| Ultrasonic Sensor      | -          |
| Vibration Sensor       | 120        |
| Breadboard             | 80         |
| Power Adapter          | 130        |
| Misc. Cables/Connectors| 160        |

**Total Cost: Approximately ₹2,000**

## Features

- Detects pothole presence and dimensions
- Sends geographic coordinates via SMS
- Real-time data storage and visualization on ThinkSpeak
- Offline data logging using CoolTerm and Sublime Text
- Cost-effective and scalable system

## Sample Output

Example SMS message:

```
Pothole of volume 3 x 3 x 3 feet at coordinates: 21.1458, 79.0882
```

Data is also available on the ThinkSpeak dashboard for visualization and analysis.

## Methodology

1. Sensors detect pothole presence and characteristics.
2. Arduino processes sensor inputs.
3. GPS module captures location coordinates.
4. GSM module sends alert via SMS.
5. Data is transmitted to ThinkSpeak for storage and visualization.

## Future Scope

- Integration with Android or web-based applications
- Real-time government dashboard integration
- Community-sourced reporting via public vehicles
- Expansion to detect additional anomalies like speed breakers and manholes

Guided by: **Prof. Pravin Dwaramwar**  
Department of Electronics Engineering  
Shri Ramdeobaba College of Engineering and Management, Nagpur

## License

This project is intended for academic and research use only.
