---
title: "Embrace Collisions: Humanoid Shadowing for Deployable Contact-Agnostics Motions"
collection: publications
permalink: /publications/2025-02-04-EmbraceCollision
link: https://project-instinct.github.io
excerpt: 'We present a unified general humanoid motion interface and a zero-shot sim-to-real reinforcement learning framework, so that humanoid robots can successfully perform extreme contact-agnostic motion in the real world.
<img src="/images/getup-from-ground.gif" alt="Getup" width="500"/>'
citation: 'Ziwen Zhuang and Hang Zhao. "Embrace Collisions: Humanoid Shadowing for Deployable Contact-Agnostics Motions." (2025).'
date: 2025-02-04
venue: ''
twitter: 'https://x.com/ziwenzhuang_leo/status/1886455238837854575'
---

Previous humanoid robot research works treat the robot as a bipedal mobile manipulation platform, where only the feet and hands contact the environment. However, we humans use all body parts to interact with the world, e.g., we sit in chairs, get up from the ground, or roll on the floor. Contacting the environment using body parts other than feet and hands brings significant challenges in both model-predictive control and reinforcement learning-based methods. An unpredictable contact sequence makes it almost impossible for model-predictive control to plan ahead in real-time. The success of the zero-shot sim-to-real reinforcement learning method for humanoids heavily depends on the acceleration of GPU-based rigid-body physical simulator and simplification of the collision detection. Lacking extreme torso movement of the humanoid research makes all other components non-trivial to design, such as termination conditions, motion commands and reward designs. To address these potential challenges, we propose a general humanoid motion framework that takes discrete motion commands and controls the robot's motor action in real-time. Using a GPU-accelerated rigid-body simulator, we train a humanoid whole-body control policy that follows the high-level motion command in the real world in real-time, even with stochastic contacts and extremely large robot base rotation and not-so-feasible motion command.

![Parkour](/images/getup-from-ground.gif)