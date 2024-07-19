---
title: "Per-Bank Bandwidth Regulation of Shared Last-Level Cache for Real-Time Systems"
collection: publications
permalink: /publication/publication-3
excerpt: 'Introducing a hardware bank-aware bandwidth regulation technique.'
date: 2024-07-31
venue: '2024 Real-Time Systems Symposium (RTSS)'
citation: 'Currently Under Review.'
---
Abstract: Modern commercial-off-the-shelf (COTS) multicore processors have advanced memory hierarchies that enhance memory-level parallelism (MLP), crucial for high performance. To support high MLP, shared last-level caches (LLCs) are divided into multiple banks, allowing parallel access. However, uneven distribution of cache requests from the cores, especially when requests from multiple cores are concentrated on a single bank, can result in significant contention affecting all cores that access the cache. Such cache bank contention can even be maliciously induced---known as cache bank-aware denial-of-service (DoS) attacks -- in order to jeopardize the system's timing predictability. 
In this paper, we propose a per-bank bandwidth regulation approach for multi-banked shared LLC based multicore real-time systems. By regulating bandwidth on a per-bank basis, the approach aims to prevent unnecessary throttling of cache accesses to non-contended banks, thus improving overall performance (throughput) without compromising isolation benefits of throttling. 
We implement our approach on a RISC-V system-on-chip (SoC) platform using FireSim and evaluate extensively using both synthetic and real-world workloads. Our evaluation results show that the proposed per-bank regulation approach effectively protects real-time tasks from co-running cache bank-aware DoS attacks, and offers up to a 3.66X performance improvement for the throttled benign best-effort tasks compared to prior bank-oblivious bandwidth throttling approaches. 

<!-- [Download paper here](http://amanley97.github.io/files/paper2.pdf) -->
