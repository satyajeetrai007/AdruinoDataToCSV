# Arduino Data Logger using PySerial

## Project Description

This project logs data sent from an Arduino through a serial port and stores it in a CSV file. The serial communication between the Arduino and the computer is handled using the PySerial library, making it easy to collect and save sensor data for further analysis.

## Features

- Logs data sent from Arduino to a CSV file.
- Utilizes PySerial for serial communication between the Arduino and the computer.
- Supports real-time data collection and storage.

## Requirements

- Python 3.x
- PySerial library
- Arduino with appropriate sensor setup (e.g., temperature, humidity, distance sensors, etc.)

## Installation

1. Install Python 3.x if not already installed. You can download it from the [official Python website](https://www.python.org/downloads/).
2. Install the PySerial library by running the following command in your terminal:

   ```bash
   pip install pyserial
