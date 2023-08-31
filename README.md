# Accident Locator and Emergency Notification System

Accident Locator and Emergency Notification System is a project aimed at addressing the increasing number of accidents due to the rise in vehicle usage caused by population growth. The system utilizes a combination of hardware components and software to swiftly identify accident locations, gather crucial information about the individuals involved, and relay this data to relevant authorities and emergency contacts. This README file provides an overview of the project, its components, setup instructions, and usage guidelines.

![Accident Locator System](https://github.com/Mahalakshmee/Accident-detection-project/blob/main/images/accident_locator.jpeg)

## Table of Contents

- [Introduction](#introduction)
- [Key Features](#key-features)
- [Hardware Components](#hardware-components)
- [Software Components](#software-components)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

With the surge in vehicle usage due to population growth, there's a corresponding increase in accidents, leading to potential injuries or fatalities. The Accident Locator and Emergency Notification System is designed to mitigate the response time in such scenarios. The system employs a Node MCU, IR sensor, vibration sensor, and GPS to detect accidents, gather crucial data, and instantly relay it to control rooms, primary health centers, and designated emergency contacts.

## Key Features

- **Accident Detection:** The system employs IR and vibration sensors to detect accidents and trigger an alert.
- **Data Collection:** When an accident occurs, the system gathers vital data including heart rates, location, date, and time.
- **Instant Notification:** The collected data is sent as a message to the nearest control room, primary health centers, and user's emergency contacts.
- **GPS Integration:** Accurate location data is obtained using GPS, ensuring quick and precise emergency response.
- **User-Friendly:** The system is seamlessly integrated into the user's vehicle and operates automatically without requiring user intervention after setup.

## Hardware Components

- Node MCU
- IR Sensor
- Vibration Sensor
- GPS Module
- Power Supply Unit
- Connecting Wires

## Software Components

- Arduino IDE (for programming Node MCU)
- GPS Data Parsing Script
- Notification Interface

## Installation

1. **Setting Up Node MCU:**
   - Install the Arduino IDE.
   - Open the Arduino IDE and install the necessary libraries for Node MCU.
   - Upload the provided code to the Node MCU after configuring Wi-Fi credentials.

2. **Assembling Hardware:**
   - Connect the IR and vibration sensors to the appropriate pins on the Node MCU.
   - Attach the GPS module and ensure proper wiring.

3. **GPS Data Parsing:**
   - Use the provided GPS data parsing script to extract accurate location information.

## Usage

1. **System Operation:**
   - After setup, the system runs autonomously in the vehicle.
   - In the event of an accident, the IR and vibration sensors trigger the system.

2. **Data Transmission:**
   - The system collects heart rate, location, date, and time data.
   - This data is sent as a message to the nearest control room, primary health centers, and emergency contacts via an established communication protocol.

3. **Emergency Response:**
   - Relevant authorities and contacts receive the alert message.
   - Quick response can be initiated, minimizing the time taken to provide emergency services.

## Contributing

Contributions to the Accident Locator and Emergency Notification System project are welcome. If you have ideas, improvements, or bug fixes, feel free to open an issue or submit a pull request.
