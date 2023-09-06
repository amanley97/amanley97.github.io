---
title: "Profiling gem5 Simulator"
collection: publications
permalink: /publication/publication-2
excerpt: 'A deeper exploration into the performance and bottlenecks of the Gem5 Simulator.'
date: 2023-04-23
venue: '2023 IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS)'
citation: 'J. Umeike, N. Patel, A. Manley, A. Mamandipoor, H. Yun and M. Alian, "Profiling gem5 Simulator," 2023 IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS), Raleigh, NC, USA, 2023, pp. 103-113, doi: 10.1109/ISPASS57527.2023.00019.'
---
Abstract: In this work, we set out to find the answers to the following questions: (1) Where are the bottlenecks in a state-of-theart architectural simulator? (2) How much faster can architectural simulations run by tuning system configurations? (3) What are the opportunities in accelerating software simulation using hardware accelerators? We choose gem5 as the representative architectural simulator, run several simulations with various configurations, perform a detailed architectural analysis of the gem5 source code on different server platforms, tune both system and architectural settings for running simulations, and discuss the future opportunities in accelerating gem5 as an important application. Our detailed profiling of gem5 reveals that its performance is extremely sensitive to the size of the Ll cache. Our experimental results show that a RISC-V core with 32KB data and instruction cache improves gem5’s simulation speed by 31%∼61% compared with a baseline core with 8KB Ll caches. Our paper is the first step toward building specialized hardware and software environments for accelerating software-based simulators.

[Download paper here](http://amanley97.github.io/files/paper2.pdf)
