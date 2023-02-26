---
layout: archive
title: "Experience"
permalink: /exp/
author_profile: true
---

{% include base_path %}

With my goal of becoming a computer hardware designer, I have been fortunate to have had the opportunity to grow from these experiences.

Internships
======
## Electrical Engineering Intern
"May 2022 - August 2022"

During the summer of 2022 I worked as an Electrical Engineering Intern for [Peraton Incorporated](https://www.peraton.com/) on their USPS Central Repair Facility contract. This was a unique facility whose job is to maintain a standard of repair for all electronic and mechanical equipment that the United States Postal Service uses for their daily operation. In many cases, the equipment had no documented repair methodology or test procedure and therefore it was the job of the engineering department to develop said procedures for continued use at the facility.

Given the unique circumstances of the facility, I was given a season long project along with many smaller projects where I had the freedom to develop solutions individually with the expectation that results would be provided. This was an excellent experience that helped me build confidence in my own skills through a structured workplace environment.

### Vitronic Camera Dimensioner Retrieval System

* Problem: Package dimensioning scanners are required to be sent to off-site facility in order to be repaired. The facility had no means of screening the dimensioners to determine defectiveness before shipments are made. This often leads to unnecessary shipments costing the facility time and money.

* Object: Our goal is to develop a motorized retrieval system to allow for rapid on-site screening of dimensioners on a simulated workspace environment by a trained technician.

Over the course of the summer I worked with other interns and employees to develop a self-contained controller box which, using a reprogrammable microcontroller (PLC) allowed the precise control of a motor to either (a) release a latch mechanism and slowly lower the dimensioner to a technician waiting to replace it with a new testing unit, or (b) raise the dimensioner back to its standard position and latch into place securely to perform the unit test. Additionally the system needed to be simple and reliable for a technician to operate daily, while maintaining a high standard of safety.

There were many challenges that needed to be overcome through the course of the project:
* It took time to calculate the weight of the system in order to obtain a motor with enough torque.
* Motor controller had to be redesigned to operate AC motor instead of stepper motor.
* 3D Printed parts were not strong enough in actual operation.

Overall the project was successful and recieved praise from executives at the company. Due to the reduction in the need for the dimensioner to be sent to the off-site facility, the project provided between `1,760 - 5,000 dollars` in average cost savings per repair. In addition, documentation was wrote on the project to ensure maintenence and repatability as well as easy reference on parts and system hardware layout.

Skills obtained:
* Hardware design and prototyping
* Software microcontroller programming (C)
* Printed circuit board design (EAGLE) and manufacturing (isoPro)
* Lab equipment (Power supply, multimeter, soldering station)
* Mechanical part brainstorming and manufacturing (3D Printing)

### Other Minor Projects

(1) Motor Controller Reverse Engineering
* Problem: Commonly repaired motor controller board did not have complete documentation on schematics, part list, and board layout.
I took some time to design a schematic and expand documentation for this particular part. Overall, this allowed for a `1,200 dollars` in cost saving per board as they no longer had to be completely replaced. Likewise, the lack of documentation costed technicians time to diagnose common problems. My documentation now allowed for an average of 50% increase in repair time.

(2) Conveyor Test Loop Reverse Engineering
* Problem: Recently acquired conveyor belt test loop did not have adequate documentation and contained some problems prohibiting operation.
I had to take a system wide approach to assist in the understanding of the conveyor belt system which allowed for the control of speed and direction of each conveyor belt. Overall, the documentation was rewritten and the problems were fixed. This also went into a separate project which was the redesign of the loop interface to allow a technician to change the conveyor loop speed 100x faster and may lead to presets to emulate systems in other postal facilities.
