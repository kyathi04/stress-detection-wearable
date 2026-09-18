# Stress Detection Using Wearable Physiological Sensors

A wearable-based system designed to estimate stress levels using physiological parameters collected from biomedical sensors.

## Overview

Stress can cause measurable changes in physiological signals such as heart rate, heart rate variability, skin conductance,oxygen saturation spo2 and skin temperature.

This project explores the use of wearable physiological sensors to monitor these parameters and estimate the user's stress level.

## Objective

To develop a wearable system that collects physiological parameters and provides an estimated stress level based on the measured signals.

## Parameters Monitored

- Heart Rate (HR)
- Heart Rate Variability (HRV)
- Galvanic Skin Response (GSR)
- Skin Temperature
- SpO₂

## Hardware

- ESP32
- MAX30102
- GSR Sensor
- Temperature Sensor DS18B20
- OLED Display
- Supporting electronic components

## Working Principle

The sensors collect physiological parameters from the user.

The ESP32 processes the sensor readings and evaluates the physiological changes associated with stress. A stress estimation algorithm is then used to determine the corresponding stress level.

The estimated stress percentage is displayed through the system interface.

## Methodology

1. Acquire physiological signals from wearable sensors.
2. Process the sensor readings using the microcontroller.
3. Analyze changes in the measured parameters.
4. Apply the stress estimation logic that is fuzzy logic.
5. Display the estimated stress level.

## Applications

- Wearable stress monitoring
- Stress awareness
- Physiological monitoring
- Healthcare technology
- Personal wellness systems

## Future Scope

The system can be further developed by improving sensor accuracy, signal processing, personalization of stress estimation, and real-time data analysis.

## Project Status

Completed hardware prototype developed for academic purposes.
