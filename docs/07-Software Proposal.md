---
title: Software Proposal
---

## Introduction
The intention of this section is to provide you with an overview of what our subsystem logic looks like overall, and how each individual PCB interacts and communicate with one another. Below are some questions we asked ourselves as we reseached our solutions and the sofware logic diagram that we produced.

## Research Question

1. Does our subsystem logic have an end?
2. What were the shapes for UML activity or state machine diagram?
3. What better represents our logic: activity diagram or state machine diagram?

## Software Diagram

![Software logig diagram](Softwarediagram.jpg)<br>
**Figure 1:** Software proposal logic diagram<br>

![Software logic diagram](Softwarediagram2.jpg)
**Figure 2:** Updated software proposal logic diagram.<br>
We felt that an updated diagram was warranted since our team felt that the logic did not have an end as it is always running in a continuous repeating loop that is checking to see if the required conditions are met to take action.

In this UML format diagram we walk you though each action that is taken when the user interacts with our product and how those trigger certain operations in our individual subsystems. The diagram is divided into a "User Side", "Voice Recognition", "Door Actuator", and "Power Monitoring" sections that showcase what operations happen when conditions are met.

Our current software proposal meets our requirements of localized control, voice recognition, reliable energy monitoring, and it provides safety features for the end user and their families.

## Results
1. Our logic does not have an end as it loops continuously as long as the design is being powered.
2. We successfully represented the logic with the correct shapes [1].
3. We decided an activity diagram best models our logic because our code will be instructions carried out one after another with only a few conditions that change the flow of operations, whereas a state machine model would mean each action has a condition before it [2].

## References
[1] [Activity Diagrams - Unified Modeling Language (UML)](https://www.geeksforgeeks.org/system-design/unified-modeling-language-uml-activity-diagrams/)
[2] [What is the difference between State Machine Diagram and Activity Diagram?](https://www.geeksforgeeks.org/system-design what-is-the-difference-between-state-machine-diagram-and-activity-diagram/)

