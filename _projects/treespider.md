---
layout: page
title: TreeSpider
description: In-canopy exploration with tether-based aerial modular arms
img: assets/img/spidi_pic.png
importance: 1
category: in-canopy
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spidi_pic.png" title="TreeSpider robot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Aerial robots offer significant potential for forest canopy research and environmental monitoring by enabling data collection at high spatial and temporal resolutions. However, their limited **maneuverability** constrains their ability to navigate and access dense canopy environments.

**TreeSpider** proposes a tether-based drone that integrates perching arms with anchoring capability for **in-canopy** stabilization and manipulation. Once tethered to a branch, the system — equipped with a 360° ring — can maneuver freely within the canopy in any direction.

The **ring** mechanism decouples the tether from the drone frame, allowing the pitch angle to be reoriented independently along the longitudinal axis. The system adjusts tether length dynamically to optimize movement and conserve **energy**. This flexibility allows the drone to approach branches from various angles within dense foliage and to extend its reach to adjacent trees while remaining tethered — enabling safe and efficient **multi-tree sensing**.

The **perching arms** can wrap around tree branches for secondary perching, allowing physical interaction with the environment at multiple locations over long time scales. Experiments demonstrated that tethered operation can reduce energy consumption by up to **fivefold** compared to untethered hovering. The perching arms showed reliability with retention forces of up to **10 N**, enhancing resistance to falling from branches.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spidi_mission.png" title="TreeSpider in-canopy mission" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The system incorporates a **leaf sampling** tool and a winding mechanism to adjust tether length, advancing the state-of-the-art in forest robotic sensing.

#### Publications

{% cite romanello2025treespider %}
