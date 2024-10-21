---
layout: page
title: Shared Resource Contention in Real-Time Systems
description: Developing mitigation techniques for resource contention in real-time-systems.
img: assets/img/projects/bru.png
importance: 2
category: research
related_publications: true
---

**Project:** Providing Determinism and Performance through Bandwidth Regulation

* **Background:** Modern commercial-off-the-shelf (COTS) multicore processors feature advanced memory hierarchies that enhance memory-level parallelism (MLP), essential for high performance. However, uneven distribution of cache requests from multiple cores can lead to significant contention, affecting all cores and potentially being exploited through cache bank-aware denial-of-service (DoS) attacks to disrupt system timing predictability.

* **Objective:** Our project investigates the impact of cache bank contention in multicore processors and explores mitigation strategies to ensure consistent and predictable system performance. By analyzing the causes and effects of contention and developing solutions to minimize it, we aim to improve the robustness and security of multicore systems.

The design was implemented and evaluated on real hardware using an FPGA SoC Framework:

* **Hardware:** Beagle-V Ahead, Raspberry Pi 4
* **Implementation Tools:** FireSim, Chipyard SoC Framework
* **Analysis Tools:** Cadence Genus, Innovus, Voltus
* **Benchmarks:** Synthetic, SD-VBS, SPEC 2017

Related publications: {% cite SullivanRegulation2024 %}
