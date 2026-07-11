# SafeCore Monitoring and Data Collection

Industrial Monitoring Platform

---

## Overview

SafeCore is an industrial monitoring and data collection platform designed for small and medium manufacturing companies.

The current version provides:

- Machine Monitoring
- Historical Data Collection
- Real-time Dashboards
- MariaDB Database
- Docker Deployment

---

## Hardware

### Controllers

- Siemens LOGO! 24RCE
- Siemens S7-1200

### Server

- Raspberry Pi 5

### Sensors

- PT100 Temperature Sensors
- ADXL345 Vibration Sensor
- Current Sensor

### Network

- Industrial Router
- 5-Port Ethernet Switch

### Enclosure

- Portable SafeCore Monitoring Box
- Cooling Fan
- Touch Display

---

## Software Stack

- Siemens PLC
- Node-RED
- MariaDB
- Grafana
- Docker

---

## Architecture

```text
Siemens LOGO!
- Motor Temperature
- Pump Temperature
- Current
- Box Cooling Status
          \
           \
            > Node-RED --> MariaDB --> Grafana
           /
          /
Raspberry Pi 5
- ADXL345 Vibration Sensor
```

---

## Features

- Motor Temperature Monitoring
- Pump Temperature Monitoring
- Box Temperature Monitoring
- Current Monitoring
- Vibration Monitoring
- Automatic Box Cooling
- Historical Data Collection
- MariaDB Data Storage
- Grafana Dashboards
- Docker Deployment

---

## Screenshots

### SafeCore Monitoring Box

(Add photo)

### Node-RED Flow

(Add screenshot)

### Grafana Dashboard

(Add screenshot)

### MariaDB Database

(Add screenshot)

### Docker Containers

(Add screenshot)

---

## Installation

Coming soon.

---

## Docker

The complete Docker deployment will be published after testing is completed.

Services:

- MariaDB
- Node-RED
- Grafana
- Adminer

---

## Author

Matej Kockovsky

Software Engineering Student

Industrial Automation • PLC • Industrial IoT
