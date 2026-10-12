# Arduino-Based Health Monitoring System

## Project Description

This project is a basic Arduino-based health monitoring prototype using the MAX30102 sensor and an analog pressure sensor.

The system reads infrared and red-light sensor values, reads an analog input from the pressure sensor, and displays the readings through the Arduino Serial Monitor.

## Components Required

* Arduino board
* MAX30102 pulse oximeter sensor
* Analog pressure sensor
* Jumper wires
* USB cable
* Computer with Arduino IDE

## Features

* Reads IR and Red values from the MAX30102 sensor.
* Includes placeholder functions for heart rate and SpO2 calculations.
* Reads analog pressure sensor values through pin A0.
* Displays readings using the Serial Monitor.

## Software Requirements

* Arduino IDE
* Wire library
* MAX30105 sensor library compatible with the MAX30102 module

## Current Limitations

The heart rate and SpO2 functions currently return fixed placeholder values. The systolic and diastolic blood pressure values are also simulated and are not measured from the sensor.

This prototype is for learning and demonstration purposes only. It is not intended for medical diagnosis.

## Future Improvements

* Implement a validated heart rate calculation algorithm.
* Implement SpO2 estimation using an appropriate algorithm.
* Integrate a suitable calibrated blood pressure measurement system.
* Display readings on an LCD or web dashboard.

## Project Status

Basic prototype — further development and testing required.
