
# Plant Parent 🌱👪

## Introduction 🌟
Welcome to Plant Parent, your personal plant care assistant! This handy device keeps an eye on your plants' soil moisture, alerting you when it's time to water them. It's a simple, effective solution for anyone who loves plants but might not always remember when to water them. With Plant Parent, taking care of your plants is easy and worry-free. 🌿🌺🌱

## Features 🎉
- **Real-Time Soil Moisture Detection**: Tracks the moisture level of your soil.
- **Automated Alerts**: Notifies you via smartphone or email to water your plants.
- **User-Friendly Dashboard**: Easy monitoring of your plant's health.
- **Historical Data Analysis**: Review and analyze soil moisture over time.
- **Adjustable Moisture Thresholds**: Set moisture levels according to your plant's needs.
- **Water Conservation**: Prevents over and under-watering.

## Components 🛠️
- ESP32 Module
- Soil Moisture Sensor
- Jumper Wires
- USB Cable for ESP32
- Breadboard (optional)

## Software Requirements 💻
- Arduino IDE with ESP32 support
- Python 3.x
- AWS Account

## Setup and Installation 📖
### Hardware Assembly
1. Connect the soil moisture sensor to the ESP32. Wiring guide in `docs`.
### Programming the ESP32
2. Upload the C++ code to the ESP32 using Arduino IDE.
### AWS Configuration
3. Setup AWS IoT Core, Lambda, and SNS for data reception and alerts.
### Python Script
4. Run the Python script to manage AWS interactions and receive alerts.
### Sensor Calibration
5. Adjust the moisture threshold levels according to your plant's needs.

## Usage 📚
- Place the sensor in your plant's soil.
- ESP32 sends data to AWS.
- Receive alerts when moisture is low.
- Water your plant and the system resets.

## Customization 🌿
- Modify Python script for different alert types or moisture thresholds.
- Integrate with home automation for automated watering.
- Expand to multiple plants.

## Landing Page

![alt text](https://github.com/codewitty/Plant-Parent/blob/main/landingPage.png?raw=true)

## Moisture and UV graphs

![alt text](https://github.com/codewitty/Plant-Parent/blob/main/Moisture_UV_Graph.png?raw=true)

## Contributing and Support 💡
Contributions are welcome! See `CONTRIBUTING.md` for guidelines. For support, open an issue in the GitHub repository.

## License 📜
Distributed under the MIT License. See `LICENSE` for more information.

Happy Plant Parenting! 🌺🌿🌵














