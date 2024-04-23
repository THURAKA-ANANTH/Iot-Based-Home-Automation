# ESP RainMaker Home Automation Project

This project demonstrates how to create a home automation system using ESP32 microcontroller with ESP RainMaker. With this project, you can control 8 home appliances using Google Assistant, Alexa, IR remote, and manual switches. Additionally, you can monitor sensor readings such as temperature and light intensity.

## Overview

The ESP RainMaker Home Automation system allows you to:
- Control 8 relays with Google Assistant, Alexa, and switches.
- Add timers to automate relay control.
- Get HEX codes from an IR remote to control relays.
- Monitor sensor readings like temperature and light intensity.
- Control appliances remotely via Google Assistant and Alexa.
- Control appliances using manual switches.
- Design and order custom PCBs for a compact and professional-looking setup.

## Required Components

To build this project, you will need the following components:
- ESP32 DevKIT V1
- 4-channel or 8-channel 5V SPDT Relay Module
- TSOP1838 IR receiver
- DHT11 temperature sensor
- LDR (Light Dependent Resistor)
- 10k resistor
- Manual Switches or Pushbuttons
- Optional: Amazon Echo Dot or Google Nest Mini

## Circuit Diagram

The circuit is straightforward:
- Connect GPIO pins to control the relay module.
- Connect GPIO pins to switches for manual control.
- Connect IR receiver output to a GPIO pin.
- Connect DHT11 sensor output to the RX2 (GPIO16) pin.
- Connect LDR to a GPIO pin.

## Programming the ESP32

You'll need Arduino IDE to program the ESP32. Follow these steps:
1. Update Preferences in Arduino IDE.
2. Install the ESP32 board (Version: 2.0.3) from the Board Manager.
3. Download and install required libraries: AceButton, IRremote, DHT.
4. Select Board as 'ESP32 DEV Module' and Partition scheme as 'RainMaker'.
5. Upload the code to ESP32.

## Usage

1. Get HEX codes from an IR remote for each relay button.
2. Update the main sketch with these HEX codes.
3. Optionally, change the device names for Google Assistant and Alexa.
4. Add devices to ESP RainMaker app.
5. Connect ESP RainMaker with Amazon Alexa and Google Home App.
6. Control appliances with voice commands and switches.

## PCB Design (Optional)

A custom PCB design is available to make the circuit compact and professional-looking. You can order PCBs from PCBWay.

## Additional Information

- Explore more ESP32 projects on [iotcircuithub.com](https://iotcircuithub.com).
- For PCB orders, visit [PCBWay](https://pcbway.com/orderonline).

## Credits

This project was created by Subhajit.

## License

This project is licensed under the [MIT License](LICENSE).
