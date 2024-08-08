---
title: "IDMP"
excerpt: "I am currently working on the IDMP framework, that we open-sourced. It uses Gaussian Processes to model Distance Fields and can be used for planning and other applications. Feel free to check it out!<br/><img src='/images/IDMP.png'>"
collection: projects
---

IDMP stands for Interactive Distance Field for Mapping and Planning and is an algorithm that uses Gaussian Processes to model a Distance Field. You can find more information at this [website](https://uts-ri.github.io/IDMP/).

We made the code freely available and it is compatible with ROS Noetic on Ubuntu 20.04. It is able to run in real-time scenarios on a CPU only system. As IDMP generates a Distance Field and a Gradient Field, it can easily be used for reactive planning with repulsive vectors or gradient based planners like CHOMP. I am also working on integrating IDMP into a policy for Riemannian Motion Policies which works really well.

Feel free to check out the code, run it and write me an E-Mail or Issue if there are any problems!