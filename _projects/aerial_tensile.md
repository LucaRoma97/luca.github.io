---
layout: page
title: Aerial Tensile Perching
description: Aerial tensile perching and disentangling mechanism for long-term environmental monitoring
img: assets/img/aerial_tensile_pic.png
importance: 2
category: in-canopy
related_publications: true
---

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0 mx-auto">
        {% include figure.liquid loading="eager" path="assets/img/aerial_tensile_pic.png" title="Aerial tensile perching mechanism" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Aerial robots show significant potential for forest canopy research and environmental monitoring, but limited **flight endurance** hinders their application. Inspired by natural perching behaviours, we propose a multi-modal aerial robot system that integrates **tensile perching** for energy conservation and a suspended actuated pod for data collection.

The system consists of a quadrotor drone, a slewing ring mechanism allowing **360° tether rotation**, and a streamlined pod with two ducted propellers connected via a tether. Winding and unwinding the tether allows the pod to move within the canopy; activating the propellers allows the tether to be wrapped around branches for perching or disentangling.

We experimentally determined the minimum counterweights required for **stable** perching under various conditions and evaluated multiple perching and disentangling strategies. Key results:

- Energy savings to only **22%** of the energy required for a drone disentangling manoeuvre using the pod
- Energy savings to only **1.5%** using tether winding
- Minimum idle time for energy savings after perching: **48.9%** of operating time

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/aerial_tensile_mission.png" title="Aerial tensile perching mission" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The integrated system expands operational capabilities and enhances the **energy efficiency** of aerial robots for long-term monitoring tasks.

#### Publications

{% cite lan2024aerial %}
