---
title: "Experience"
permalink: /experience/
author_profile: true
---

{% include base_path %}

With my goal of becoming a computer hardware designer, I have been fortunate to have had the opportunity to grow from these experiences.

# Open Source Contributions

## gEMA: gem5 Extended Modules API
In an effort to extend and maintain gem5 standardized interfaces, we introduce gEMA: the gem5 external modules API. Building upon the standard library, gEMA enables a simple HTTP interface to configure, manage, and execute gem5 simulations from any external program.
> Under Review.

* View the Pull Request [here](https://github.com/gem5/gem5/pull/1288).

## RISC-V support in MemGuard
Implemented the necessary performance counters to enable MemGuard on RISC-V Linux. Tested on the Beagle-V Ahead single board computer.
* View the Pull Request [here](https://github.com/heechul/memguard/pull/17).

# Internships

## RF Hardware Engineering Intern
**Taikan Company**  
*Lawrence, Kansas*  
*May 2023 - August 2023*

During the summer of 2023, I had the opportunity to work as an RF Hardware Engineering Intern for [Taikan Company](https://www.taikan.com), a designer and manufacturer of broadband networking equipment. From day one, I was able to be a part of a company developing real products with customers all around the globe. As part of the engineering team, I was responsible for several projects that directly affected daily company operations.

Taikan has been in business for 50 years, so it is extremely important for their operations to stay up-to-date and cutting edge. Part of my responsibility was to update many product designs to modern PCB design software. This gave me more experience with circuit design and an in-depth understanding of RF design, while also having a direct impact on streamlining the design process. Management was very receptive to my suggestions and inquiries about bottlenecks and methods to mitigate them.

**Skills Obtained:**
* Hardware Reverse Engineering
* Design Methodologies and Manufacturing Principles
* Printed Circuit Board EDA
* Cross-discipline Communication
* Detailed Research Techniques
* Efficient Workflow Documentation

**Recommendations Received:**
![Recommendation](/images/ewang.png "Recommendation")

## Electrical Engineering Intern
**Peraton Incorporated - USPS Central Repair Facility**  
*Topeka, Kansas*  
*May 2022 - August 2022*

During the summer of 2022, I worked as an Electrical Engineering Intern for [Peraton Incorporated](https://www.peraton.com/) on their USPS Central Repair Facility contract. This facility maintains a standard of repair for all electronic and mechanical equipment that the United States Postal Service uses for daily operations. Often, the equipment had no documented repair methodology or test procedure, and it was the job of the engineering department to develop these procedures for continued use at the facility.

Given the unique circumstances of the facility, I was assigned a season-long project along with many smaller projects where I had the freedom to develop solutions individually with the expectation that results would be provided. This was an excellent experience that helped me build confidence in my own skills through a structured workplace environment.

### Vitronic Camera Dimensioner Retrieval System

* **Problem:** Package dimensioning scanners are required to be sent to an off-site facility for repairs. The facility had no means of screening the dimensioners to determine defectiveness before shipments, often leading to unnecessary shipments costing time and money.
* **Objective:** Develop a motorized retrieval system to allow for rapid on-site screening of dimensioners in a simulated workspace environment by a trained technician.

Over the summer, I worked with other interns and employees to develop a self-contained controller box that, using a reprogrammable microcontroller (PLC), allowed the precise control of a motor to either (a) release a latch mechanism and slowly lower the dimensioner to a technician waiting to replace it with a new testing unit, or (b) raise the dimensioner back to its standard position and latch it securely to perform the unit test. The system needed to be simple and reliable for daily technician operation, while maintaining a high standard of safety.

**Challenges:**
* Calculating the weight of the system to obtain a motor with sufficient torque.
* Redesigning the motor controller to operate an AC motor instead of a stepper motor.
* Ensuring 3D printed parts were strong enough for actual operation.

Overall, the project was successful and received praise from executives at the company. Due to the reduction in the need to send the dimensioner to the off-site facility, the project provided an average cost savings of $1,760 - $5,000 per repair. Documentation was created to ensure maintenance and repeatability, as well as for easy reference on parts and system hardware layout.

**Skills Obtained:**
* Hardware Design and Prototyping
* Software Microcontroller Programming (C)
* Printed Circuit Board Design (EAGLE) and Manufacturing (isoPro)
* Lab Equipment (Power Supply, Multimeter, Soldering Station)
* Mechanical Part Brainstorming and Manufacturing (3D Printing)

### Other Minor Projects

#### Motor Controller Reverse Engineering
* **Problem:** A commonly repaired motor controller board lacked complete documentation on schematics, part lists, and board layout.
* **Solution:** Designed a schematic and expanded documentation for the board, allowing for a $1,200 cost saving per board and a 50% increase in repair time due to improved technician diagnosis.

#### Conveyor Test Loop Reverse Engineering
* **Problem:** A recently acquired conveyor belt test loop lacked adequate documentation and had operational issues.
* **Solution:** Took a system-wide approach to assist in understanding the conveyor belt system, leading to rewritten documentation and fixed issues. Additionally, redesigned the loop interface to allow a technician to change the conveyor loop speed 100x faster, potentially leading to presets to emulate systems in other postal facilities.
