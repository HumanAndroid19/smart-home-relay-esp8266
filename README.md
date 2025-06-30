# Smart Home Relay ESP8266 🌐🏠

![ESP8266](https://img.shields.io/badge/ESP8266-NodeMCU-blue?style=flat-square) ![Home Automation](https://img.shields.io/badge/Home%20Automation-Project-green?style=flat-square) ![Alexa](https://img.shields.io/badge/Alexa-Voice%20Control-orange?style=flat-square)

Welcome to the **Smart Home Relay ESP8266** repository! This project allows you to control your home appliances using voice commands via Alexa or manual switches. Built on the ESP8266 platform with a 4-channel relay, this project serves as an excellent introduction to home automation and IoT.

For the latest updates and downloadable files, visit the [Releases section](https://github.com/HumanAndroid19/smart-home-relay-esp8266/releases).

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Hardware Requirements](#hardware-requirements)
4. [Software Requirements](#software-requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [How It Works](#how-it-works)
8. [Troubleshooting](#troubleshooting)
9. [Contributing](#contributing)
10. [License](#license)

## Project Overview

This mini-project, created in November 2022, is part of a 3rd-year Electrical Engineering curriculum. It demonstrates the capabilities of the ESP8266 in a practical application. With the integration of Alexa, users can control various appliances with simple voice commands, enhancing convenience and efficiency in daily life.

## Features

- **Voice Control**: Use Alexa to control your devices.
- **Manual Control**: Switches for manual operation.
- **Multiple Devices**: Control up to four appliances.
- **WiFi Connectivity**: Operates over your home WiFi network.
- **Easy Setup**: Simple installation process.
- **User-Friendly Interface**: Intuitive design for easy interaction.

## Hardware Requirements

To set up this project, you will need the following hardware components:

- **ESP8266 NodeMCU**: The main microcontroller.
- **4-Channel Relay Module**: For controlling appliances.
- **Power Supply**: Suitable for the ESP8266 and relay.
- **Wires**: For connections.
- **Manual Switches**: For manual control of devices.
- **Home Appliances**: Devices you wish to control.

## Software Requirements

You will need the following software to work with this project:

- **Arduino IDE**: For programming the ESP8266.
- **Blynk App**: Optional for remote control.
- **IFTTT Account**: Optional for advanced automation.
- **Libraries**: Install the required libraries in the Arduino IDE for ESP8266 and relay control.

## Installation

Follow these steps to set up the project:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/HumanAndroid19/smart-home-relay-esp8266.git
   ```
   
2. **Open Arduino IDE**: Launch the Arduino IDE on your computer.

3. **Install ESP8266 Board**: 
   - Go to `File` > `Preferences`.
   - Add the following URL to the "Additional Board Manager URLs":
     ```
     http://arduino.esp8266.com/stable/package_esp8266com_index.json
     ```
   - Open `Tools` > `Board` > `Boards Manager`, search for "ESP8266", and install it.

4. **Install Required Libraries**: 
   - Go to `Sketch` > `Include Library` > `Manage Libraries`.
   - Search for and install the necessary libraries for WiFi and relay control.

5. **Upload the Code**: 
   - Open the main code file in the repository.
   - Connect your ESP8266 to the computer.
   - Select the correct board and port in the Arduino IDE.
   - Click on the upload button.

6. **Connect Hardware**: 
   - Connect the relay module to the ESP8266 as per the wiring diagram in the repository.
   - Ensure all connections are secure.

7. **Power On**: 
   - Connect the power supply to the ESP8266 and relay module.
   - Your setup should now be operational.

## Usage

Once installed, you can control your appliances using either Alexa or the manual switches. For voice commands, ensure that your Alexa device is connected to the same WiFi network as your ESP8266. You can also use the Blynk app for remote control if you have set it up.

### Alexa Commands

- "Alexa, turn on [device name]."
- "Alexa, turn off [device name]."

### Manual Control

Use the physical switches connected to the relay module to control the appliances directly.

## How It Works

The ESP8266 connects to your home WiFi network and listens for commands. When you issue a voice command to Alexa, it sends a request to the ESP8266 via the cloud. The ESP8266 processes the command and activates the corresponding relay, turning the appliance on or off.

The manual switches provide an alternative way to control the devices without using voice commands. This dual control feature enhances usability and flexibility.

## Troubleshooting

If you encounter issues, consider the following:

- **Connection Issues**: Ensure your ESP8266 is connected to the WiFi network. Check the credentials in the code.
- **Relay Not Responding**: Verify the wiring and connections to the relay module.
- **Voice Commands Not Recognized**: Ensure the Alexa device is properly set up and connected.

For further assistance, check the [Releases section](https://github.com/HumanAndroid19/smart-home-relay-esp8266/releases) for updates and troubleshooting tips.

## Contributing

We welcome contributions to improve this project. If you have ideas or enhancements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and submit a pull request.

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own projects. 

---

Thank you for exploring the **Smart Home Relay ESP8266** project. We hope it inspires you to dive deeper into the world of home automation and IoT!