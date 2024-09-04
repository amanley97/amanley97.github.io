---
layout: page
title: Linear Power Supply
description: EECS 541 (Senior Design I) - Linear power supply designed to output specified parameters.
img: assets/img/projects/lps-board.jpg
importance: 4
category: academic
related_publications: false
---

In this project, we designed a linear power supply circuit to provide a steady 11V DC output from an AC input of 20-30V. The circuit featured current limiting with a 1A cutoff, using a bridge rectifier and an LM723 linear regulator IC. We simulated the circuit in PSpice before soldering it on a protoboard.

**Skills:** Circuit Design, PSpice, Soldering

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/lps-schematic.png" title="Schematic" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/lps-board.jpg" title="Data Receiver" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     The left image shows the Power Supply Schematic, while the right shows the Final Prototype board design.
</div>
