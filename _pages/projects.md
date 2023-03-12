---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Here are some projects that have allowed the development of my skills.

## Microcontroller Infrared Communication System
* EECS 541 (Senior Design I) - Fall 2022

This was more of a computer engineering project that was a part of our senior design class. In this project we designed a system which could wirelessly transmit data through the air using infrared pulses. The project consisted of one transmitter and one receiver which used Arduino microcontrollers to encode data as pulse to transmit or recieve pulses to decode. The transmitter would generate packets of data which would then be pulsed along the I/O pin which the infrared LED array was driven. The receiver would use an initial pattern to detect the transmission rate, then capture a byte of data after a start byte sequence was recieved. The receiver could also determine an overall error rate by comparing the data to an expected value. Overall, the system was very stable and was able to transmit 4.5 meters in practice.

* Skills: C programming

![Transmitter](https://amanley97.github.io/files/transmitter.png "Transmitter") ![Receiver](https://amanley97.github.io/files/receiver.png "Receiver")

## Linear Power Supply
* EECS 541 (Senior Design I) - Fall 2022

This was the first of our senior design projects in which we designed a linear power supply circuit according to some desired characteristics. The given characteristics were that when connected to an input AC voltage of 20-30 volts, the linear power supply should provide a steady 11 volt DC output. The output should have current limiting such that there is a cutoff current of 1 amp. The circuit used a bridge rectifier to convert the voltage to DC, followed by an LM723 linear regulator IC. Since the LM723 is limited to an output current of 150 milliamps, we use a pass transistor to boost the output current to the desired range. We then simulated the circuit in PSpice to ensure correct parameters before soldering the circuit on a protoboard.

* Skills: Circuit design, PSpice, Soldering

![LPS Schematic](https://amanley97.github.io/files/lps-schematic.png "Schematic") ![LPS Board](https://amanley97.github.io/files/lps-board.jpg "Protoboard"){: width=80%}

## Embedded Systems Car
* EECS 388 (Embedded Systems) - Fall 2021

This was an exciting project in which we worked through the semester to build a drivable RC-style car. We used a SiFive microcontroller to control the motors for driving the wheels. Using the microcontrollers specifications and the I2C timing protocol we developed functions to drive forward, backwards, turn left, and turn right. Then we developed a UART interface which links communication between the Raspberry Pi and microcontroller. We write simple movement scripts in Python which send commands to the car. As an extra feature we enabled the ability for the car to be controlled via the arrow keys on the keyboard connected to the Raspberry Pi.

* Skills: C and Python programming

## Custom Filter Design
* EECS 212 (Circuits II) - Fall 2021

In this project, we designed a custom frequency filter according to some given design specifications. The give characteristics were Low Pass, 6kHz cutoff, and 5V Gain. We had to use the datasheet to calculate the required resistances to achieve these results. Then we prototyped the filter on a breadboard and tested for the desired characteristics. Once confirmed, we designed the board in OrCAD and then acid etched the board. After soldering, we had a completed filter!

* Skills: Circuit design, PCB Software

![Custom Filter Design](https://amanley97.github.io/files/filter.png "Filter Board")
