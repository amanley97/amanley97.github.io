---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

Research
======
Beginning in November of 2020, I became an Undergraduate Research Assistant for the Electrical Engineering and Computer Science department of the University of Kansas, under mentorship of Professor [Mohammad Alian](https://alian-eecs.ku.edu/).His work revolves around the idea that with the development of big data it has become critical to better develop our systems to be highly efficient to handle this kind of extensive workload. Through my work on his team I have developed a passion for innovation of computer hardware design to fuel the next generation of computer systems.

My Projects
======
The Growing Problem of Architectural Simulators.
"A Deep Dive into gem5 Profiling: Finding and Addressing Bottlenecks"

* Background: Gem5 [(More info)](https://www.gem5.org/) is a state-of-the-art full system computer simulator that is widely used in academia and the industry. It's flexibility and extensive dedicated community make for a program which is constantly improving the state of computer architecture design. With its extensive use, it is important to ensure a program that is efficient in order to reduce the overall time it takes to run simulations.

* Objective: That being said, the goal of our project is to obtain a deep comprehensive benchmark and profile of Gem5 to understand it's strengths and weaknesses. With this profile we can understand where in the program lie its bottlenecks and offer improvements on how the efficiency can be improved.

To accomplish our goal we have already found and published an in-depth analysis of Gem5.
There were many different analysis methods that were utilized:

* Tools: VTune, perfTools
* Workloads: boot-exit, PARSEC, SPLASH-2X, SPEC 2017
* Host Hardware: Intel Xeon (x86), Apple M1 (ARM), [FireSim](https://fires.im/)(FPGA-acclerated RISC-V)
* Gem5 configurations: CPU type, operation mode (full/syscall), memory heirarchy

As an undergraduate, my role in this project took a more implementation approach. Working closely with the graduate researchers, I developed the full-system simulation environment which contained the benchmark workloads. Likewise, I applied this knowledge to develop the simulation environment to allow micro-architectural exploration of gem5 bottlenecks. I developed a project stack built of FPGA hardware, Firesim, Gem5, and a C++ workload from bottom up.

======

Memory Controllers
"A Block Efficient Memory Controller"

* Project in progress, more info soon!
