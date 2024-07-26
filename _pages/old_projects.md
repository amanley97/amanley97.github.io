---
title: "Projects"
permalink: /oldddddprojects/
author_profile: true
---

{% include base_path %}

# Projects

## (AI)-larm: A Modular Alarm System
**Course:** EECS 542 (Senior Design II) - Spring 2023

For our senior design capstone, we designed and built a modular alarm system. The goal was to create a simple wireless alarm system allowing the user to dynamically set up their environment based on their needs. The system is optimal for users like apartment/office renters who may not have the option to place wires through walls to install a traditional alarm system. Additionally, the system features facial recognition for deactivating the alarm, making it cutting edge and useful in various situations.

**Role:** Team Leader - Coordinated hardware and software teams, ensured project goals were achieved, and provided assistance as needed.

**Technologies used:**
* Raspberry Pi (Python GUI)
* Facial Recognition (OpenCV)
* ESP32 (Bluetooth)

**Skills:** Python Programming, System Design, Hardware Prototyping, Wireless Communication

![Overview](https://amanley97.github.io/files/seniordesign.jpg "Overview")

See [here](https://github.com/amanley97/AI-larm) for project code!

## Microcontroller Infrared Communication System
**Course:** EECS 541 (Senior Design I) - Fall 2022

In this computer engineering project, we designed a system to wirelessly transmit data using infrared pulses. The project involved a transmitter and receiver using Arduino microcontrollers to encode and decode data. The transmitter generated data packets transmitted via an infrared LED array, while the receiver detected transmission rates, captured data, and determined error rates.

**Skills:** C Programming

![Transmitter](https://amanley97.github.io/files/transmitter.png "Transmitter") ![Receiver](https://amanley97.github.io/files/receiver.png "Receiver")

## Linear Power Supply
**Course:** EECS 541 (Senior Design I) - Fall 2022

In this project, we designed a linear power supply circuit to provide a steady 11V DC output from an AC input of 20-30V. The circuit featured current limiting with a 1A cutoff, using a bridge rectifier and an LM723 linear regulator IC. We simulated the circuit in PSpice before soldering it on a protoboard.

**Skills:** Circuit Design, PSpice, Soldering

![LPS Schematic](https://amanley97.github.io/files/lps-schematic.png "Schematic") ![LPS Board](https://amanley97.github.io/files/lps-board.jpg "Protoboard")

## Embedded Systems Car
**Course:** EECS 388 (Embedded Systems) - Fall 2021

Throughout the semester, we built a drivable RC-style car controlled by a SiFive microcontroller. We developed functions for driving and turning, created a UART interface for communication between a Raspberry Pi and the microcontroller, and wrote Python scripts to control the car. An extra feature allowed the car to be controlled via keyboard arrow keys.

**Skills:** C and Python Programming

## Custom Filter Design
**Course:** EECS 212 (Circuits II) - Fall 2021

We designed a custom frequency filter with a Low Pass, 6kHz cutoff, and 5V Gain. We calculated the required resistances using datasheets, prototyped the filter on a breadboard, and tested it. Once confirmed, we designed the board in OrCAD and acid-etched it. After soldering, we had a completed filter.

**Skills:** Circuit Design, PCB Software

![Custom Filter Design](https://amanley97.github.io/files/filter.png "Filter Board")
