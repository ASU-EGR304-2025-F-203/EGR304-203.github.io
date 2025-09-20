---
title: Product Requirements
tags:
- tag1
- tag2
---

## Project Objective
>This project aims to investigate and develop a highly versatile smart power strip with an improved setup, more reliable interface, easy to program outlets and USB ports, for use in a wide range of electrical applications indoors as well as out. The outcome of this investigation and the prototype that will be created will benefit the industry as a whole, as we are posting all documentation, electrical schematics, code, and CAD files to our github page which is freely viewable and downloadable. We believe that by providing this research as a public resource it will benefit fellow ASU students taking EGR304 or similar embedded systems classes by providing an example of a project that can serve as inspiration. And, since we are developing a real product it will benefit entrepreneurs or engineering firms looking to actually sell a product like the one we design.

## Aspects
4. Customization
* 4.1 The product shall allow the user to use multiple control methods and be able to program the device by editing the code we develop to run customized routines.
* 4.2 The product shall allow the user to customize power output from each plug and USB port.
* 4.3 The design is to be modular with the user customizing the location and type of each port.

5. Manufacturing
* 5.1 The product shall be easy to manufacture.
* 5.2 The product exterior should be manufactured with materials resistant to elements and use weather resistant mechanical components such as switches and plug covers.
* 5.3 The PIC Curiosity Nano microcontrollers used in the design shall be easily removable from the device for use in other projects.

6. Safety
* 6.1 Product shall protect against overcurrent.
* 6.2 Product shall protect against short circuits.
* 6.3 Product shall filter the current to prevent spikes that may damage.
* 6.4 Product automatically limits current to what each port can deliver. 
* 6.5 Product dissipates heat so it does not become a fire hazard with high current usage.

## Requirement Criteria Specifications
* 4.1.1 Device supports three control interfaces: physical buttons with a screen to display information, mobile app, and web interface.
* 4.1.2 Device has a port for reprogramming.
* 4.1.3 Source code is accessible for reprogramming.
* 4.2.1 Power settings for each plug and USB-port can be specified with the control interface.
* 4.2.2 Device provides real time feedback for desired output and delivers within +-5% of what was specified.
* 4.3.1 Ports 

## Open Questions

* Can we manufacture this product for under $100?
* Can we find a safe way to merge high amperage needs with low?
* What type of interface would be the most marketable based on the requirement of reliable connectivity as well as convenience?: a remote, smartphone app, connected touch screen, etc.