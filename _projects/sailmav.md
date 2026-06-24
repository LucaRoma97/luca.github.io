---
layout: page
title: SailMAV
description: Sailing flying robot for water environmental sensing
img: assets/img/sailmav_pic.jpg
importance: 1
category: aerial-aquatic
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sailmav_pic.jpg" title="SailMAV robot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The **SailMAV** sailing-flying robot was developed to meet the need for a water surface vehicle capable of **rapidly** and **autonomously** deploying for environmental water sensing or disaster search and rescue missions.

Its fixed-wing design enables **long-term** missions by leveraging aerodynamic lift for high efficiency. Sailing is very efficient and silent in water, making it suitable for collecting data in fragile environments. The sailing-flying robot addresses the need for flight flexibility combined with extended water-based monitoring. Its core innovation lies in using high-performance wings for both flight and sailing, enabling long-range flight and energy-neutral surface locomotion.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sailmav_design.png" title="SailMAV design" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The robot's design enables extended, precise missions at the **water surface** by harnessing wind for propulsion. It also provides the agility of flight to quickly reach target areas, navigate obstacles, and transition between water bodies, making it ideal for water sampling in complex environments. With a 0.96 m wingspan, the SailMAV utilizes the same wings and control surfaces for both sailing and flying, achieving water surface locomotion, takeoff, and flight at a cruising speed of 10.8 m/s.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sailmav_mission.png" title="SailMAV mission" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

**Sailing-Flight Cycle**: The robot lands on water, transitions to a sailing configuration, and carries out its mission. Takeoff is achieved through propelled acceleration, progressing from displacement mode to hydroplaning and finally becoming fully airborne.

I developed a **control** system enabling autonomous mission execution, including an optimized tacking strategy. The system was tested across Europe, including two deployments at *Lake Vrana*, Croatia, where the robot equipped with an audio sensor successfully performed tasks to scan the lake's **ornithological** area. Ecological analysis mapped birds' **species** and **abundance**, comparing data from winter and summer expeditions.

#### Publications

{% cite farinha2025sailmav %} {% cite zufferey2019sailmav %} {% cite lawson2023aerial %}
