---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview
Purpose fo block diagram is to ensure that my subsystem is going to be connected properly to subsystem of my teammates and the project will run properly. The sensor I will be working on is resistive sensor for the project. Button and LED will be helping me to make required actions from the measurements the sensor will give. Team connections are be shown more in the team block diagram.This shows a person a reasonable outline about why a part was chosen based on power levels. A block diagram also helps with our team project, which shows you where each board will be connected with the other team members.

To see more about block diagram of my other teammates, please visit the team website ["here"](https://egr304-2025-f-210.github.io/) for more details.


## Block Diagram 
Following is my block diagram and is made in draw.io



![Individual Block Diagram](Block diagram EGR 304 individual.drawio (2).png)



## How each element meets product requirements
1. **9V 3A Unregulated Power Supply**
   - Provides ample supply for the full system and future peripheral expansion.
2. **L7805 5V Regulator**
   - Supplies a stable 5V rail for MCU, analog front-end, and indicator LEDs ensuring reliable operation.
3. **Zinc/Copper Resistive Probe**
   - Directly senses water conductivity/resistance; robust and low-cost sensing element meeting sensing requirement.
4. **MCP6004 Op-Amp (Signal Conditioning)**
   - Implements current-to-voltage conversion and differential amplification where needed, providing a stable 0-5V signal for the MCU ADC under varying water conditions.
   - Input protection components (series resistor, clamps) protect the MCU and reduce electrolysis effects.
5. **PIC18F57Q43 Microcontroller**
   - Performs ADC sampling, filtering, threshold detection, PWM drives for LEDs, and UART/SPI as needed for team communication.
6. **Status LEDs & Buttons**
   - Visual indication of safe/danger states and manual calibration/debug controls.
7. **Protection & Filtering**
   - Ensures EMC robustness and protection from voltage spikes or reverse connection—improving reliability.
8. **Team Connector (8-pin)**
   - Matches team-standard connector providing 5V, GND, analog out, and digital signals for integration with other subsystems.

## Notes on PCB / Schematic integration
- Use series resistors and diodes on probe lines to limit current and reduce electrolysis.
- Consider multiplexing or switching if multiple probes or sensors are introduced.
- Calibrate in known-conductivity solutions to map ADC readings to conductivity values.
