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
Peter is a 42 -year-old homeowner who enjoys seetting up his backyard for family gatherings and seasonal decorations.He recently purchased the HBN Outdoor smart plug to manage his string lights and small fountain. The installation was straightfoward, the rugged stick pushed firmily into the ground,and the weather resistant spring covers gave him confidence that the outlets would stay safe from the rain and dust. with Wifi connectivity, Peter quickly programmed schedules from his phone so the lights automatically turned on at dusk.

Over time, Peter noticed how well the product matched his expectations. The heavy six-foot cord allowed him to reach power comfortably, and the photocell sensor made sure his Christmas lights stayed on after dusk without extra effort. He even enjoyed the small touch of the included remote, which let him control the outlets when his phone wasn’t nearby.

**User Story #2: Ayush**
Ayush is a 21 year old student, he recently upgraded his home office setup with the Kasa Smart Plug Power Strip KP303. He works remotely and wanted something easy to manage multiple devices without clutter. The simple app setup impressed him, it connected quickly to his Alexa, and within minutes, he could control his desk lamp, monitor and coffee machine with his voice. He found the interface intuitive and reliable, matching what others had said in their reviews. For Ayush, not having to juggle multiple individual plugs was a relief,  one strip that could handle all his essentials felt both practical and cost-effective.

On weekends, Ayush enjoys experimenting with tech projects, so the extra flexibility came in handy. Inspired by a review, he used the power strip in his Halloween setup, running lights and sound effects triggered from his PC with a simple script. The surge protection gave him peace of mind while powering multiple gadgets, and the individual control over outlets meant he could turn off just the devices he didn’t need.

## Aspects

Our product design will be based on current market offerings for smart surge protectors, with improvements that adhere to the following requirements. The **P1 - P10** is the "code" to indicate the priority of the requirement, from low to high priority.

1. **Hardware / Product Design**
      * 1.1 Product should be compact, light, and easily portable to allow our customers to easily relocate it as needed.
      * 1.1. Product should be easy to stow away without messing with long wires.
      * 1.2. Product needs to be sturdy, in order to withstand impacts and the being dropped ocasionally.
      * 1.2. Product needs to be weather resitant to protect the delicate internal electronics from changes in temperature, water intrussion, and constant UV light exposure.
      * 1.3. Product should have mounting holes on its base to allow multiple mounting options.
      * 1.4. Product should provide a combination of power outlets such as NEMA 5-15 and USB A outlets to power various appliances.
      * 1.4. Outlets should be generously spaced to allow multiple configurations of power connectors and device power cables.    
      * 1.5. Plug should be low profile and angled to fit behind furniture.
  
1. **Software / Functionality**
      * 2.1 The fucntionality of the product must not rely on an app for control, and should have multiple avenues for control.
      * 2.1. The control should be redundant and operation of the device should automatically resume on the last known good setting in case of a power outage or spike.
      * 2.2. The setup and configuration should be eassily setup in under 5 minutes.
      * 2.2. Instruction manual should be clear and detailed.   
      * 2.3. Product should allow user to manually program it from the device without the need explicit of an external source, such as a mobile app.
      * 2.4. Multiple devices might be grouped together in order to control them simultaneously. 

1. **Interactivity & User Experience**
      * 3.1. Product should educate the user about their power consumption.
      * 3.2. Displayed data should be visually represented and easy to read.  
      * 3.3. User should be able to individually control each outlet of the product.
      * 3.4. Product should have voice assistant integration for esy control.
      * 3.5. Product should have easily communicate to the customer which outlets are on or off without an app.

4. **Customization**
* 4.1 The product shall allow the user to use multiple control methods and be able to program the device by editing the code we develop to run customized routines.
* 4.2 The product shall allow the user to customize power output from each plug and USB port.
* 4.3 The design is to be modular with the user customizing the location and type of each port.

5. **Manufacturing**
* 5.1 The product shall be easy to manufacture.
* 5.2 The product exterior should be manufactured with materials resistant to elements and use weather resistant mechanical components such as switches and plug covers.
* 5.3 The PIC Curiosity Nano microcontrollers used in the design shall be easily removable from the device for use in other projects.

6. **Safety**
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

## Open Questions
* Can we manufacture this product for under $100?
* Can we find a safe way to merge high amperage needs with low?
* What type of interface would be the most marketable based on the requirement of reliable connectivity as well as convenience?: a remote, smartphone app, connected touch screen, etc.