---
title: "Scene2Gym: Transforming Real-World Scenes into Interactive Training Environments for Robot Learning"
collection: publications
category: conferences
permalink: /publication/2026-scene2gym
excerpt: 'A real-to-gym framework that turns real-world scene observations into interactive, metric-consistent 3DGS digital twins for embodied policy learning.'
date: 2026-10-01
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
citation: 'Z. Ji, F. Chen, Z. Wang, Z. Wang, F. Qiu, W. Hou, M. Yang and T. Qin, "Scene2Gym: Transforming Real-World Scenes into Interactive Training Environments for Robot Learning," IROS, 2026.'
header:
  teaser: papers/scene2gym_thumb.jpg
---

<img src="/images/papers/scene2gym_fig1.jpg" alt="Scene2Gym overview" style="width:100%;border:1px solid #e2ded6;border-radius:6px;">

Ziheng Ji, Fengyi Chen, **Ziqian Wang**, Zhitao Wang, Feng Qiu, Wenguo Hou, Ming Yang, Tong Qin

Scaling embodied intelligence remains bottlenecked by the high cost of manual asset engineering and persistent sim-to-real gaps. Scene2Gym is a framework that transforms real-world scene observations into interactive, metric-consistent digital twins for embodied policy learning. It combines 3D Gaussian Splatting (3DGS) with an object-centric metric alignment pipeline: 3DGS improves visual realism to reduce the visual gap, while metric alignment anchors reconstructed assets to real-world scale for geometrically consistent, contact-rich interaction. A hybrid co-simulation stack decouples photorealistic rendering from the physics clock, providing time-synchronized observations for closed-loop policy training.

Across tasks with increasing interaction complexity, Scene2Gym yields consistent sim-to-real gains. Imitation learning policies trained entirely on Scene2Gym-synthesized data achieve real-world success rates comparable to policies trained on costly human demonstrations; articulated-object manipulation transfers zero-shot to a real-world microwave-heating task; and visual reinforcement learning policies reach a 56% zero-shot real-world success rate, highlighting the importance of visual fidelity and perception-action consistency for transferable embodied learning.
