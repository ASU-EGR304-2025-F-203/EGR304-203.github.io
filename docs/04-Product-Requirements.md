---
title: Product Requirements
tags:
- tag1
- tag2
---

## Project Objective
>This project aims to investigate and develop a highly versatile smart power strip with an improved setup, more reliable interface, easy to program outlets and USB ports, for use in a wide range of electrical applications indoors as well as out. The outcome of this investigation and the prototype that will be created will benefit the industry as a whole, as we are posting all documentation, electrical schematics, code, and CAD files to our github page which is freely viewable and downloadable. We believe that by providing this research as a public resource it will benefit fellow ASU students taking EGR304 or similar embedded systems classes by providing an example of a project that can serve as inspiration. And, since we are developing a real product it will benefit entrepreneurs or engineering firms looking to actually sell a product like the one we design.

## Stakeholders

- **Target group** Upper middle class people of 18 years and above. It would be people money conscious people who are looking to learn more about their enegy consumption habits and lower their electricity costs. It is ideally for both tech savy or a non-technical person 
- **Target purchaser** The target group would be homeowners, landlords, renters, and office workers.
- **Customer service** Simple to troubleshoot remotely, and components should be modular and easy to replace. Maintenance and service will be simple to perform by anyone with basic hand tools.
- **Marketing & Sales division** Will look place this product higher than a normal surge protector. They will look at existing market offerings and show off our unique and superior features such as real time energy monitoring, dependable connectivity, superior weather resitance and durability.
- **Retailers** Expect the product to be durable enough to be placed in longer term storage in various temperature and humidity conditions. Packaging should be drop safe and impact resistant.

## Use Cases

**User Story #1: peter**
Emily is a 35-year-old mother of two small children. She frequently uses many extension cables for her kids night lights, phone chargers, and living room lamps because she enjoys decorating her house. Emily made the decision to convert to Spark Guard, the smart extension cable with built-in safety safeguards, when her toddler nearly touched an exposed electrical outlet.

Ports are now kept closed when not in use thanks to Spark Guard's child-safe locking cover. Emily is no longer concerned about small, inquisitive hands being close to electricity. The voice-activated solenoid mechanism opens the outlet safely. When she needs to plug something in, she can see when the power is on thanks to the integrated LED indicator, and she can monitor her energy consumption in real time thanks to the digital display.

**User Story #2: Ayush**
Ethan is a 22 year old off-campus engineering student, dealing with rising SRP electrical costs as a result of his laptop, gaming setup, and 3D printer. He used the Spark Guard Smart Extension Cord to control his energy usage  and it completely changed the way he tracked power usage. He was able to detect high-usage equipment with the aid of the digital display and switch them off overnight, saving about 20% on his monthly payment.

The voice-activated solenoid lid kept unused outlets locked for safety, while the LED indicator indicated whether current was flowing. The tight lid prevented a short circuit when his roommate spilled a drink close by. Ethan now has peace of mind, safety and energy savings in one stylish gadget thanks to Spark Guard's integration with his smart assistant, which also turns down and locks automatically.

## Aspects

Our product design will be based on current market offerings for smart surge protectors, with improvements that adhere to the following aspects.

**Hardware / Product Design**<br>
* 1.1 Product should be compact, light, and easily portable to allow our customers to easily relocate it as needed.<br>
* 1.1. Product should be easy to stow away without messing with long wires.<br>
* 1.2. Product needs to be sturdy, in order to withstand impacts and the being dropped ocasionally.<br>
* 1.2. Product needs to be weather resitant to protect the delicate internal electronics from changes in temperature, water intrussion, and constant UV light exposure.<br>
* 1.3. Product should have mounting holes on its base to allow multiple mounting options.<br>
* 1.4. Product should provide a combination of power outlets such as NEMA 5-15 and USB A outlets to power various appliances.<br>
* 1.4. Outlets should be generously spaced to allow multiple configurations of power connectors and device power cables. <br>   
* 1.5. Plug should be low profile and angled to fit behind furniture.<br>
  
**Software / Functionality**<br>
* 2.1 The fucntionality of the product must not rely on an app for control, and should have multiple avenues for control.<br>
* 2.1. The control should be redundant and operation of the device should automatically resume on the last known good setting in case of a power outage or spike.<br>
* 2.2. The setup and configuration should be eassily setup in under 5 minutes.<br>
* 2.2. Instruction manual should be clear and detailed.<br>   
* 2.3. Product should allow user to manually program it from the device without the need explicit of an external source, such as a mobile app.<br>
* 2.4. Multiple devices might be grouped together in order to control them simultaneously.<br>

**Interactivity & User Experience**<br>
* 3.1. Product should educate the user about their power consumption.<br>
* 3.2. Displayed data should be visually represented and easy to read.<br>  
* 3.3. User should be able to individually control each outlet of the product.<br>
* 3.4. Product should have voice assistant integration for esy control.<br>
* 3.5. Product should have easily communicate to the customer which outlets are on or off without an app.<br>

**Customization**<br>
* 4.1 The product shall allow the user to use multiple control methods and be able to program the device by editing the code we develop to run customized routines.<br>
* 4.2 The product shall allow the user to customize power output from each plug and USB port.<br>
* 4.3 The design is to be modular with the user customizing the location and type of each port.<br>

**Manufacturing**<br>
* 5.1 The product shall be easy to manufacture.<br>
* 5.2 The product exterior should be manufactured with materials resistant to elements and use weather resistant mechanical components such as switches and plug covers.<br>
* 5.3 The PIC Curiosity Nano microcontrollers used in the design shall be easily removable from the device for use in other projects.<br>
* 5.4 Product is manufactured of recylcled materials for lower enviromental impact during manufacturing.<br>

**Safety**<br>
* 6.1 Product shall protect against overcurrent.<br>
* 6.2 Product shall protect against short circuits.<br>
* 6.3 Product shall filter the current to prevent spikes that may damage electrical components.<br>
* 6.4 Product automatically limits current to what each port can deliver.<br>
* 6.5 Product dissipates heat so it does not become a fire hazard with high current usage.<br>

## Requirement Criteria Specifications
Our product should henceforth meet the below requirements. The **P1 - P10** is the "code" to indicate the priority of the requirement, from low to high priority.

**Hardware / Product Design Requirements**<br>
* 1.1.1 Device should weith three pounds or less(P7).<br>
* 1.1.2 Device should be compact enough to carry it with one hand(P7).<br>
* 1.2.1 Device must be IP-65 or IP-66 rated(P2).<br>
* 1.2.2 Device should withstand being dropped from shoulder height multiple times(P5).<br>
* 1.3.1 Device should have spaced out holes for wall mounting and desk mounting(P7).<br>
* 1.4.1 Device outlets must be generously spaced to allow multiple power connector configurations(P4).<br>
* 1.5.1 Device plug must be angled at 90 degrees and be as thin as possible(P7).<br>

**Software / Functionality Requirements**<br>
* 2.1.1 Device must have redundancy in case of one of the control methods failing. This would allow the devivice to continue working in case of failure(P3).<br>
* 2.2.1 Device should be configurable and operable in less than 5 minutes(P5).<br>
* 2.3.1 Device must allow for manual physical control and programming(P3).<br>
* 2.4.1 Device should allow for control grouping with additional surge protector products of its kind.<br>

**Interactivity & User Experience Requirements**<br>
* 3.1.1 Device should provide information to the user about their power consumption(P6).<br>
* 3.2.1 Device must display data visually to the customer(P6).<br>
* 3.3.1 Device outlets should be individually controller by the user(P4).<br>
* 3.4.1 Device must have voice control integration with a common use assistant such as Google Assistant, Amazon Alexa, Microsoft Cortana, and Siri(P6).<br>
* 3.5.1 Device must have LED indicators to show which outlets are on and which are off(P5).<br>

**Customization Requirements**<br>
* 4.1.1 Device supports three control interfaces: physical buttons with a screen to display information, mobile app, and web interface(P3).<br>
* 4.1.2 Device has a port for reprogramming(P10).<br>
* 4.1.3 Source code is accessible for reprogramming(P10).<br>
* 4.2.1 Power settings for each plug and USB-port can be specified with the control interface(P6).<br>
* 4.2.2 Device provides real time feedback for desired output and delivers within +-5% of what was specified(P4).<br>
* 4.3.1 Ports are mounted on interchangable modules with standardized connectors(P8).<br>
* 4.3.2 User can rearrange or swap out port types to design their own array of power sources(P8).<br>

**Manufacturing Requirements**<br>
* 5.1.1 Material besides internal PCB and Curiosity Nano controllers is sourced from at least two different materials in case of unavailability(P9).<br>
* 5.1.2 There are at least two ways to manufacture the outer shell of the assembly, e.g. 3D printing or injection molding(P9).<br>
* 5.1.3 Assembly time is under 30 minutes using basic hand tools(P9).<br>
* 5.2.1 Enclosure meets IP65 rating for dust and water resistance while components are plugged in(P2).<br>
* 5.2.2 Enclosure must pass 10 simulated outdoor durability tests, including being sprayed with water, shaken around in a container of dust, and a drop from shoulder height while components are plugged in (specific moisture level and particulate level to pass TBD)(P2).<br>
* 5.3.1 PIC Curiosity Nanos are mounted on headers allowing removal/replacement in under 2 minutes without soldering(P9).<br>
* 5.4.1 Outer shell assembly is made from biodegradable or recyclable plastic(P9).<br>


**Safety Requirements**<br>
* 6.1.1 Device includes automatic shutoff when current exceeds rated current(TBD); recovery requires manual reset(P1).<br>
* 6.2.1 IEC 62368-1 compliant(P1).<br>
* 6.3.1 Includes EMI filters and transient voltage suppressors that reduce spikes to below 5% of rated current (TBD), verified via oscilloscope(P1).<br>
* 6.5.1 Product operates between 32 - 122 degrees F(P2).<br>
* 6.5.2 Product does not exceed 122 degrees F during intended use(P2).<br>
* 6.5.3 On board temperature sensor automatically shuts off device if temperature exceeds 122 F(P1).<br>

## Open Questions
* Can we manufacture this product for under $100?
* Can we find a safe way to merge high amperage needs with low?
* What type of interface would be the most marketable based on the requirement of reliable connectivity as well as convenience?: a remote, smartphone app, connected touch screen, etc.
