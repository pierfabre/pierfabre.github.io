---
layout: post
title: Furuta Pendulum
subtitle: Building and swing up of an open-source and affordable cart-pole robot
gh-repo: Armandpl/furuta
thumbnail-img: /assets/img/pendule.png
---

With this project we aimed at building and swinging-up an open-source and affordable cart-pole robot so that everyone could build one at home!
What we already did :
- Carefully choose and buy the components (motors, sensors, electronics, ...)
- Design and 3D print the mechanical parts
- Code the firmware on a seeduino
- Code a physical simulation using [Pinocchio](https://github.com/stack-of-tasks/pinocchio)
- Code a NMPC (Non Linear Model Predictive Controller) using [Crocoddyl](https://github.com/loco-3d/crocoddyl)
- Swing-up the pendulum in simulation

![pendulum](https://pierfabre.github.io/assets/img/pendule.png)

Armand already swang-up the real robot using DRL (Deep Reinforcement Learning) and made a [video](https://www.youtube.com/watch?v=Y6FVBbqjR40) about it!
I still need to swing-up the real robot using NMPC, stay tuned!