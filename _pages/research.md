---
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

Contributing to the next generation of hardware and computer system innovations.

## Graduate Studies

As of August 2023, I have begun the next chapter of my academic career as a Master of Science in Computer Engineering candidate at the University of Kansas, [Department of Electrical Engineering and Computer Science](https://eecs.ku.edu/). I am now co-advised by [Dr. Heechul Yun](https://www.ittc.ku.edu/~heechul/) (Univ. of Kansas) and [Dr. Mohammad Alian](https://eecs.ku.edu/people/mohammad-alian) (Cornell) and am affiliated with the [Computer Systems Lab](https://www.ittc.ku.edu/~heechul/people.html).

### The Future of Computer Architecture.
"Mastering Computer Architecture through Guided Simulation"

This project is developing an educational training platform to teach the next generation of computer architects. See more information on the project [here](https://eecs.ku.edu/eecs-professors-receive-200000-nsf-award-develop-ai-driven-computer-architecture-learning-tool). See information on the NSF funding [here](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2327971&HistoricalAwards=false).

We have developed two modules that make up this project:
* gEMA: gem5 Extended Modules API - A standardized interface developed to allow gem5 to be integrated into any external program.
    * View the open source code [here](https://github.com/amanley97/gEMA).
    * gEMA is under review for contribution to mainline gem5!

* SimScholar: A GUI Platform to allow users to create and run gem5 simulations with ease.
    * View the open source sode [here](https://github.com/amanley97/SimScholar)   

* SystemSavant: An AI model to offer system insights based on user programs
    * > Updates coming soon!

### Shared Resource Contention in Real-Time Systems.
"Providing Determinism and Performance through Bandwidth Regulation."

* Background: Modern commercial-off-the-shelf (COTS) multicore processors feature advanced memory hierarchies that enhance memory-level parallelism (MLP), essential for high performance. However, uneven distribution of cache requests from multiple cores can lead to significant contention, affecting all cores and potentially being exploited through cache bank-aware denial-of-service (DoS) attacks to disrupt system timing predictability.

* Objective: Our project investigates the impact of cache bank contention in multicore processors and explores mitigation strategies to ensure consistent and predictable system performance. By analyzing the causes and effects of contention and developing solutions to minimize it, we aim to improve the robustness and security of multicore systems.

The design was implemented and evaluated on real hardware using an FPGA SoC Framework:

* Hardware: Beagle-V Ahead, Raspberry Pi 4
* Implementation Tools: FireSim, Chipyard SoC Framework
* Analysis Tools: Cadence Genus, Innovus, Voltus
* Benchmarks: Synthetic, SD-VBS, SPEC 2017

## Undergraduate Career

Beginning in November of 2020, I became an Undergraduate Research Assistant for the Electrical Engineering and Computer Science department of the University of Kansas, under mentorship of Professor Mohammad Alian. Our work revolves around the idea that with the development of big data it has become critical to better develop our systems to be highly efficient to handle this kind of extensive workload. Through my work on his team I have developed a passion for innovation of computer hardware design to fuel the next generation of computer systems. See my works below.

### The Growing Problem of Architectural Simulators.
"A Deep Dive into gem5 Profiling: Finding and Addressing Bottlenecks"

* Background: [Gem5](https://www.gem5.org/) is a state-of-the-art full system computer simulator that is widely used in academia and the industry. It's flexibility and extensive dedicated community make for a program which is constantly improving the state of computer architecture design. With its extensive use, it is important to ensure a program that is efficient in order to reduce the overall time it takes to run simulations.

* Objective: That being said, the goal of our project is to obtain a deep comprehensive benchmark and profile of Gem5 to understand it's strengths and weaknesses. With this profile we can understand where in the program lie its bottlenecks and offer improvements on how the efficiency can be improved.

To accomplish our goal we have already found and published an in-depth analysis of Gem5.
There were many different analysis methods that were utilized:

* Tools: VTune, perfTools
* Workloads: boot-exit, PARSEC, SPLASH-2X, SPEC 2017
* Host Hardware: Intel Xeon (x86), Apple M1 (ARM), [FireSim](https://fires.im/)(FPGA-acclerated RISC-V)
* Gem5 configurations: CPU type, operation mode (full/syscall), memory heirarchy

As an undergraduate, my role in this project took a more implementation approach. Working closely with the graduate researchers, I developed the full-system simulation environment which contained the benchmark workloads. Likewise, I applied this knowledge to develop the simulation environment to allow micro-architectural exploration of gem5 bottlenecks. I developed a project stack built of FPGA hardware, Firesim, Gem5, and a C++ workload from bottom up.

See my publications tab to view our whitepages!

### A World Limited by Data Transfer.
"A Block Efficient Memory Controller"

Reducing write queue contention through a specially designed Memory Controller which handles block data transfers at high efficiency. Ideal for programs with large data usage.

* ~~Project in progress, more info soon!~~ Project disbanded.
