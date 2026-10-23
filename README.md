# Air-Quality-monitoring-system
# 🌿 Smart Air Quality Monitoring System

An Arduino UNO-based IoT project designed to monitor air quality, temperature, and humidity using the MQ-135 and DHT11 sensors. Sensor data is transmitted to a cloud platform and presented through a web dashboard, enabling users to monitor environmental conditions and make informed decisions for healthier indoor spaces.

## 📌 Project Overview

Air quality is an important factor affecting human health and comfort. This project combines embedded systems, environmental sensors, cloud connectivity, and web-based visualization to provide a convenient way to monitor environmental conditions.

The system collects sensor readings, transmits the data to a cloud platform, and displays the information through a web dashboard.

## 🎯 Objectives

- Monitor air quality using the MQ-135 sensor.
- Measure temperature and humidity using the DHT11 sensor.
- Process sensor readings using an Arduino UNO.
- Transmit environmental data to a cloud platform.
- Display sensor information through a web dashboard.
- Improve awareness of indoor environmental conditions.

## 🛠️ Hardware Components

| Component | Purpose |
|---|---|
| Arduino UNO | Reads and processes sensor data |
| MQ-135 Air Quality Sensor | Detects changes in air quality and certain gases |
| DHT11 Sensor | Measures temperature and relative humidity |
| Connecting Wires | Establish electrical connections |
| Breadboard (if used) | Simplifies circuit prototyping |

## 💻 Technologies Used

- **Embedded System:** Arduino UNO
- **Programming Language:** Embedded C/C++ using Arduino IDE
- **Sensors:** MQ-135 and DHT11
- **Data Transmission:** Cloud connectivity
- **User Interface:** Web dashboard

## ⚙️ System Architecture

```text
     MQ-135 Sensor       DHT11 Sensor
    (Air Quality)    (Temperature & Humidity)
           \                 /
            \               /
             v             v
               Arduino UNO
                    |
                    v
             Data Transmission
                    |
                    v
              Cloud Platform
                    |
                    v
              Web Dashboard
                    |
                    v
          Environmental Monitoring
```

## 🔄 Working Principle

1. **Data Collection:** The MQ-135 sensor detects changes associated with air quality, while the DHT11 measures temperature and humidity.
2. **Data Processing:** The Arduino UNO reads the sensor outputs and prepares the readings for transmission.
3. **Cloud Transmission:** The collected data is sent to the configured cloud platform.
4. **Data Visualization:** The web dashboard presents the received readings in an easy-to-understand format.
5. **Environmental Awareness:** Users can observe changing conditions and take appropriate action when necessary.

## 📊 Dashboard

The web dashboard is intended to provide a clear view of the monitored environmental parameters.

Planned dashboard information:
- Air quality sensor readings
- Temperature in °C
- Relative humidity in %
- Historical readings or trends, if supported by the implementation
- Cloud connection or data update status, if available

<!-- Add your dashboard screenshot here after uploading it to the Dashboard folder. -->

## 📁 Repository Structure

```text
Smart-Air-Quality-Monitoring-System/
│
├── Code/
│   └── smart_air_quality.ino
│
├── Prototype/
│   └── circuit-diagram.png
│
├── Dashboard/
│   └── dashboard-preview.png
│
└── README.md
```

*Replace the example filenames with your actual filenames. Add other files as your project develops.*

## 🚀 Getting Started

### Prerequisites

- Arduino IDE
- Arduino UNO board
- MQ-135 air quality sensor
- DHT11 temperature and humidity sensor
- Required Arduino libraries
- Configured cloud platform and dashboard
- USB cable and connecting wires

### Installation and Setup

1. Clone or download this repository.
2. Open the `.ino` file inside the `Code` folder using Arduino IDE.
3. Install the required libraries used by your source code.
4. Connect the MQ-135 and DHT11 sensors according to your circuit diagram and pin configuration.
5. Configure the cloud platform credentials and data transmission settings required by your implementation.
6. Select the correct Arduino UNO board and port in Arduino IDE.
7. Upload the program to the board.
8. Open the configured web dashboard and verify that sensor data is being received.

## 🌟 Key Features

- Real-time sensor data collection, subject to the configured update interval
- Air quality monitoring using MQ-135
- Temperature and humidity monitoring using DHT11
- Cloud-based data transmission
- Web-based visualization of environmental readings
- Modular design combining sensing, embedded processing, and IoT connectivity

## 🔮 Future Improvements

- Add alerts for configurable air quality thresholds.
- Integrate a particulate matter sensor such as PMS5003.
- Improve dashboard charts and historical data analysis.
- Add mobile-friendly monitoring and notifications.
- Evaluate sensor calibration and measurement accuracy.
- Add automated ventilation control where appropriate.

## ⚠️ Important Note

The MQ-135 is a gas-sensitive sensor and does not directly provide a certified air quality index (AQI) or precise concentrations of every pollutant without suitable calibration and processing. Its readings should be interpreted according to the sensor setup. This prototype is intended for educational and environmental monitoring purposes, not as a substitute for certified air quality instruments or safety alarms.

## 👨‍💻 Project Information

**Project Name:** Smart Air Quality Monitoring System  
**Domain:** Embedded Systems and Internet of Things (IoT)  
**Controller:** Arduino UNO  
**Sensors:** MQ-135 and DHT11

---

*Developed as an embedded systems and IoT project to explore environmental sensing, cloud data transmission, and web-based monitoring.*
