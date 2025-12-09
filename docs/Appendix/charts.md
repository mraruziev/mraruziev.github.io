---
title: Appendix -Lessons learned and suggestions
---


# Lessons Learned  
### VibeWater Subsystem (Conductivity Sensor)

Throughout the development of my subsystem for the VibeWater project, I learned several important technical and workflow skills that significantly improved my understanding of embedded design.

## Technical Lessons Learned
- **KiCad PCB Design:**  
  I learned how to design schematics, create footprints, route traces, and generate Gerber files. The process taught me how important component placement, grounding, and spacing are for analog accuracy.

- **UART and Digital Communication:**  
  I gained experience working with UART communication between microcontrollers. Understanding how to configure UART pins and send/receive data was crucial for team integration.

- **Using MPLAB X and Coding in C:**  
  I learned how to develop firmware using MPLAB X and write C programs for the PIC18F57Q43. This included ADC sampling, debouncing inputs, and PWM control for LEDs.

- **GitHub Workflow:**  
  I learned how to use GitHub for version control, file tracking, and documentation. Writing Markdown pages for the individual datasheet taught me how to communicate engineering decisions clearly.

- **Understanding Course Structure:**  
  I realized that the individual datasheet assignments function like a **midterm**, because they require full documentation, technical justification, and integration with the team project.

---

# Recommendations for Future Students

Based on my experience in EGR 304, here are my recommendations for students taking this course in the future:

## 1. Start Labs Early  
Do the labs as early as possible. They build the foundation needed for the final design, and falling behind makes the hardware and software parts much harder later.

## 2. Begin PCB Design Early  
Start the PCB process early in the semester. Routing and fixing errors always takes longer than expected, especially when waiting for board revisions or troubleshooting mistakes.

## 3. Begin Software Coding Early  
Firmware development should not wait until the end. Getting code running early helps test hardware assumptions, verify sensors, and prepare for integration with teammates.

## 4. Use GitHub from Day One  
GitHub is essential for:
- backing up your work  
- tracking changes  
- collaborating with teammates  
- submitting documentation  

Learning Markdown and practicing frequent commits will save a lot of time later.

## 5. Take the Datasheet Assignments Seriously  
The individual datasheet assignments feel like a **midterm exam** because they require:
- clear engineering justification  
- block diagrams  
- schematics  
- BOM  
- power budgets  
- firmware explanation  

Completing them well makes the final project much easier.

---

# Final Thoughts
This course taught me real engineering workflow: designing hardware, coding firmware, debugging systems, documenting professionally, and integrating with a team. The skills I learned—KiCad, UART, C programming, MPLAB X, and GitHub—are directly applicable to real embedded engineering work.
