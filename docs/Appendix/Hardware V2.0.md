# Version 2.0 Hardware Improvements  
### Asadbek Ruziev — Resistive Conductivity Subsystem (VibeWater)

This page outlines the five major improvements that would be implemented in a Version 2.0 redesign of my hardware subsystem. These changes improve reliability, measurement accuracy, debugging capability, and integration with the rest of Team 210.

---

## 1. Larger PCB Size (From 7–8 cm to 10 × 10 cm)
The original PCB was compact and difficult to route cleanly. Increasing the size to 10 × 10 cm would:
- Provide better separation of analog and digital sections  
- Allow cleaner routing with less electrical noise  
- Improve heat dissipation around the LM7805 regulator  
- Create space for future expansion and easier debugging  

A larger board results in more stable readings and better long-term reliability.

---

## 2. Add Additional Headers for Expansion
Version 1.0 had limited header access. Version 2.0 would include:
- Two new GPIO header banks for future sensors or testing  
- A dedicated UART/SWD programming header  
- Clearly labeled test pads (ADC input, Op-amp output, VREF, 5V, GND)  

More headers give the system greater flexibility and make troubleshooting significantly easier.

---

## 3. Improve Probe Interface and Signal Stability
The zinc/copper resistive probe benefits from cleaner signal conditioning. Upgrades include:
An input polyfuse and reverse-polarity protection; a larger copper area for regulator heat dissipation; an optional footprint for a switching regulator (buck converter);  
 A better location for the regulator to cut down on noise entering the analog stage

These changes increase measurement accuracy and extend probe lifespan.

---

## 4. Power System Upgrades
The power section can be made more robust. Version 2.0 would add:
- Larger copper area for regulator heat dissipation  
- Optional footprint for a switching regulator (buck converter)  
- Reverse-polarity protection and an input polyfuse  
 - Improved regulator placement to reduce noise reaching the analog stage

These improvements protect the board and ensure more stable voltage to sensitive components.

---

## 5. Add Calibration and Testing Features
To improve usability and measurement accuracy, Version 2.0 would include:
- A calibration header for injecting known resistances  
- Optional footprint for a temperature sensor (conductivity depends on temperature)  
