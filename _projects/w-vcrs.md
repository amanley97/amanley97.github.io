---
layout: page
title: Vitronic Camera Dimensioner Retreival System
description: USPS Central Repair Facility - Intern Project.
img: assets/img/projects/vitronic.jpg
importance: 1
category: work
related_publications: false
---

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

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/vitronic.jpg" title="Dimensioner Example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example Vitronic Dimensioner Setup
</div>