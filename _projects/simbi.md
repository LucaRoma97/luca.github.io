---
layout: page
title: Simbi
description: Aerial-deployed soft underwater gripper for benthic operations
img: assets/img/simbi_pic.png
importance: 2
category: aerial-aquatic
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/simbi_pic.png" title="Simbi underwater gripper" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Underwater soft grippers exhibit significant potential for monitoring, research, and object retrieval. However, existing underwater gripping techniques frequently cause disturbances to ecosystems. **Simbi** presents a novel underwater gripping framework comprising a lightweight gripper affixed to a custom submarine pod deployable via drone. This approach minimizes water disturbance and enables efficient navigation to target areas.

The **pod** allows for underwater motion with four degrees of freedom, equipped with a custom buoyancy system, two water pumps for differential thrust and two for pitching. The system allows for **buoyancy** adjustments up to a depth of 6 meters, as well as motion in the plane.

The 3-fingered gripper is manufactured out of silicone and was successfully tested on objects with different shapes and sizes, demonstrating a maximum pulling force of up to **8 N** when underwater.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/simbi_mission.png" title="Simbi mission" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The reliability of the submarine pod was tested in a water tank by tracking its attitude and energy consumption during grasping maneuvers. The system accomplished a successful mission in a lake, deployed on a hexacopter. The integration of this system expands the operational capabilities of underwater grasping, makes missions more **efficient** and easy to automate, while causing **less disturbance** to the water ecosystem.

#### Publications

{% cite romanello2024simbi %} {% cite romanello2024simbi_soft %}
