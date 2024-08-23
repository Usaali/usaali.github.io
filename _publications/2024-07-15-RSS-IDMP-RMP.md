---
title: "Leveraging Interactive Distance Fields for Safe and Smooth Reactive Planning"
collection: publications
permalink: /publication/RSS-IDMP-RMP
excerpt: 'This workshop paper is about combining IDMP with Riemannian Motion Policies.'
date: 2024-07-15
venue: 'RSS’24 Workshop on Semantics for Robotics'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
# posterurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'http://Usaali.github.io/files/RSS_Workshop_IDMP_RMPs.pdf'
websiteurl: 'https://usaali.github.io/IDMP-RMP/'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Human-robot collaboration applications require safe and reactive planning. Euclidean distance fields (EDF) are a promising representation of such dynamic scenes due to their ability to reason about free space and the readily available distance to collision costs. A key challenge for the commonly used discrete EDF representations, however, is the need for differentiable distance fields to produce smooth collision costs and efficient updates of the dynamic objects. In this paper, we propose to use a Gaussian Process (GP) distance field-based framework that enables both, differentiable distance fields and fast dynamic scene updates. This framework allows implicit semantic reasoning of static and dynamic regions of the scene. Moreover, we propose to use this framework in combination with the Riemannian Motion Policies (RMP) as a local reactive planner to enable safe human-robot interactions. We design a collision avoidance policy that models the repulsive motion using the distance and gradient fields from our GP. We show the performance of our reactive planner in an experiment with a UR5e interacting safely and smoothly with a human. A detailed demonstration of the framework and the experimental setup is available [here](https://usaali.github.io/IDMP-RMP/).