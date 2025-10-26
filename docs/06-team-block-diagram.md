---
title: Team Block Diagram
---



## Introduction
The team block diagram demonstrates how each PIC Curiosity Nano micocontroller will take in analog signals, filter them, and process them through specific input pins, and which pins will output to analog devices or digital pins. Finally the diagram shows how we will communicate across microcontrollers using the 8 pin ribbon connectors. <br>

## First Iteration
![Team Block Diagram](Team203BlockDiagram.jpeg)
The diagram shown above was our first attempt at a simplifcation of our idea into a demo where each microcontroller has at least one analog sensor or actuator with the required filters, amplifiers, or drivers.

**Notes from this iteration:**
 1. We didn't realize our boards all needed to communicate to at least one other board.
 2. Manny's board was initially planned to include a motor with a door latch solenoid, plus limit switches to determine when the door was open or closed.
 3. We believed it necessary to have both a voltage sensor and a current sensor.

 ## Final Iteration
![Team Block Diagram](Team203BlockDiagram.jpeg)

**Notes from this iteration:**
1. All boards send/receive some sort of communication
2. Functionality is simplified and aligns with updated design direction.
3. Current sensor is all that is required to calculate power with a constant voltage.
