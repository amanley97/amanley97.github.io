---
layout: page
title: The Growing Problem of Architectural Simulators
description: Profiling the gem5 simulator during my Undergraduate Research Fellowship.
img: assets/img/publication_preview/jumeike.png
importance: 3
category: research
related_publications: true
---

**Project:** A Deep Dive into gem5 Profiling: Finding and Addressing Bottlenecks

* **Background:** [Gem5](https://www.gem5.org/) is a state-of-the-art full system computer simulator that is widely used in academia and the industry. Its flexibility and extensive dedicated community constantly improve the state of computer architecture design. With its extensive use, it is important to ensure a program that is efficient in order to reduce the overall time it takes to run simulations.

* **Objective:** The goal of our project is to obtain a comprehensive benchmark and profile of Gem5 to understand its strengths and weaknesses. With this profile, we can identify bottlenecks and offer improvements to enhance efficiency.

To accomplish our goal, we have already published an in-depth analysis of Gem5.
Various analysis methods were utilized:

* **Tools:** VTune, perfTools
* **Workloads:** boot-exit, PARSEC, SPLASH-2X, SPEC 2017
* **Host Hardware:** Intel Xeon (x86), Apple M1 (ARM), [FireSim](https://fires.im/)(FPGA-accelerated RISC-V)
* **Gem5 configurations:** CPU type, operation mode (full/syscall), memory hierarchy

As an undergraduate, my role in this project was more implementation-focused. Working closely with graduate researchers, I developed the full-system simulation environment containing the benchmark workloads. I also applied this knowledge to develop the simulation environment to allow micro-architectural exploration of gem5 bottlenecks. I developed a project stack built of FPGA hardware, Firesim, Gem5, and a C++ workload from bottom up.

Related publications: {% cite UmeikeProfiling2023 %}, {% cite TaheriProfiling2022 %}