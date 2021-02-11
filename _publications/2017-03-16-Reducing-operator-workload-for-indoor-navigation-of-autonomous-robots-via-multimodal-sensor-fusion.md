---
title: "Reducing operator workload for indoor navigation of autonomous robots via multimodal sensor fusion"
collection: publications
permalink: /publication/2017-03-16-Reducing-operator-workload-for-indoor-navigation-of-autonomous-robots-via-multimodal-sensor-fusion
excerpt: "Framework for operator assistance in indoor navigation and map building wherein the ground vehicle learns to navigate by imitating the operator commands while training."
date: 2017-03-16
venue: "Companion HRI 2017"
venuetype: "workshop"
paperauthors: 'N. Patel, P. Krishnamurthy, Y.Fang, F. Khorrami'
thumbnail: "operator_workload_architecture.png"
---

Links: [Companion HRI 2017 page](https://dl.acm.org/doi/10.1145/3029798.3038368), [Companion HRI 2017 pdf](https://dl.acm.org/doi/pdf/10.1145/3029798.3038368), [bibtex](#bibtex)

![Modality fusion framework for operator assistance](/images/operator_workload_architecture.png)

### Abstract

We present a novel framework for operator assistance in indoor navigation and map building wherein the ground vehicle learns to navigate by imitating the operator commands while training. Our framework reduces the workload on the human operator simplifying the process of human robot interaction. An end to end architecture is presented which takes inputs from camera and LIDAR and outputs the steering angle for the ground vehicle to navigate through an indoor environment. The presented framework includes static obstacle avoidance during navigation and map building. The architecture is made more reliable by an on-line mechanism in which the robot introspects its output and decides whether to rely on its output or transfer vehicle control to a human pilot. The end to end trained framework implicitly learns to avoid obstacles. We show that our framework works under various cases where other frameworks fail.

### Bibtex
    @inproceedings{PatelKFK17,
    author    = {Naman Patel and
               Prashanth Krishnamurthy and
                Yi Fang and
                Farshad Khorrami},
    title     = {Reducing Operator Workload for Indoor Navigation of Autonomous Robots via Multimodal Sensor Fusion},
    booktitle = {Companion of the 2017 {ACM/IEEE} International Conference on Human-Robot Interaction, {HRI}},
    address   = {Vienna, Austria},
    month     = {March},
    pages     = {253--254},
    year      = {2017},
    }
