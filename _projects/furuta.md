---
layout: page
title: furuta
description: Build and swing up a furuta pendulum
img: assets/img/pendulum.jpg
importance: 1
category: fun
related_publications: false
---

With this project we aimed at building and swinging-up an open-source and affordable cart-pole robot so that everyone could build one at home!
What we already did :
- Carefully choose and buy the components (motors, sensors, electronics, ...)
- Design and 3D print the mechanical parts
- Code the firmware on a seeduino
- Code a physical simulation using [Pinocchio](https://github.com/stack-of-tasks/pinocchio)
- Code a NMPC (Non Linear Model Predictive Controller) using [Crocoddyl](https://github.com/loco-3d/crocoddyl)
- Swing-up the pendulum in simulation

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pendulum.jpg" title="pendulum" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Armand already swang-up the real robot using DRL (Deep Reinforcement Learning) and made a [video](https://www.youtube.com/watch?v=Y6FVBbqjR40) about it!
I still need to swing-up the real robot using NMPC, stay tuned!
