---
title: "Safe Human-Robot Interactions with Continuous and Differentiable Distance Fields"
collection: publications
permalink: /publication/ICRA-IDMP-RMP
excerpt: 'This extended abstract is about using IDMP and RMP for safe interactions.'
date: 2024-09-23
venue: '40th Anniversary of the IEEE Conference on Robotics and Automation, ICRA@40'
paperurl: 'http://Usaali.github.io/files/ICRA_IDMP_RMPs.pdf'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Human-robot collaboration applications require safe and reactive planning. Euclidean distance fields (EDF) are a promising representation of such dynamic scenes due to their ability to reason about free space and the readily available distance to collision costs. A key challenge for the commonly used discrete EDF representations, however, is the need for differentiable distance fields to produce smooth collision costs and efficient updates of dynamic objects. In this paper, we propose to use a Gaussian Process (GP) distance field-based framework that enables both, differentiable distance fields and fast dynamic scene updates. 
%This framework allows implicit semantic reasoning of static and dynamic regions of the scene. 
Moreover, we combine this framework with the Riemannian Motion Policies as a local reactive planner to enable safe human-robot interactions. We design a collision avoidance policy that models the repulsive motion using the distance and gradient fields from our GP. We show our reactive planner in an experiment with a UR5e interacting safely and smoothly with a human.