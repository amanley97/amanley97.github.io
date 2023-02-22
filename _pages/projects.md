---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Here are some projects that have allowed the development of my skills.

## Embedded Systems Car
* EECS 388 (Embedded Systems)

This was a class project in which we worked through the semester to build a drivable car. We used a SiFive microcontroller to control the motors for driving the wheels. Using the microcontrollers specifications and the I2C timing protocol we developed functions to drive forward, backwards, turn left, and turn right. Then we developed a UART interface which links communication between the Raspberry Pi and microcontroller. We write simple movement scripts in Python which send commands to the car. As an extra feature we enabled the ability for the car to be controlled via the arrow keys on the keyboard connected to the Raspberry Pi.

* Skills: C and Python programming

## Custom Filter Design
* EECS 212 (Circuits II)

This was another class project in which we designed a custom frequency filter according to some given design specifications. The give characteristics were Low Pass, 6kHz cutoff, and 5V Gain. We had to use the datasheet to calculate the required resistances to achieve these results. Then we prototyped the filter on a breadboard and tested for the desired characteristics. Once confirmed, we designed the board in OrCAD and then acid etched the board. After soldering, we had a completed filter!

* Skills: Circuit design, PCB Software

![Custom Filter Design](https://amanley97.github.io/files/filter.png)
