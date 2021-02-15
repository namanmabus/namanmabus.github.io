---
title: "Adaptive Adversarial Videos on Roadside Billboards: Dynamically Modifying Trajectories of Autonomous Vehicles"
collection: publications
permalink: /publication/2019-11-09-Adaptive-adversarial-videos-on-roadside-billboards-Dynamically-modifying-trajectories-of-autonomous-vehicles
excerpt: "Dynamic adversarial billboard attack on an end-to-end trained DNN controlling an autonomous vehicle."
date: 2019-11-09
venue: "IROS 2019"
venuetype: "conference"
paperauthors: 'N. Patel, P. Krishnamurthy, S. Garg, F. Khorrami'
thumbnail: "adversarial_billboard_framework.gif"
---

Links: [IROS 2019 page](https://ieeexplore.ieee.org/abstract/document/8968267), [IROS 2019 pdf](https://par.nsf.gov/servlets/purl/10179576), [bibtex](#bibtex)

### Abstract

Deep neural networks (DNNs) are being incorporated into various autonomous systems like self-driving cars and robots. However, there is a rising concern about the robustness of these systems because of their susceptibility to adversarial attacks on DNNs. Past research has established that DNNs used for classification and object detection are prone to attacks causing targeted misclassification. In this paper, we show the effectiveness of an adversarial dynamic attack on an endto-end trained DNN controlling an autonomous vehicle. We launch the attack by installing a billboard on the roadside and displaying videos to approaching vehicles to cause the DNN controller in the vehicle to generate steering commands that cause, for example, unintended lane changes or motion off the road causing accidents. The billboard has an integrated camera estimating the pose of the on-coming vehicle. The approach enables dynamic adversarial perturbation that adapts to the relative pose of the vehicle and uses the dynamics of the vehicle to steer it along adversary-chosen trajectories while being robust to variations in view, lighting, and weather. We demonstrate the effectiveness of the attack on a recently published off-the-shelf end-to-end learning-based autonomous navigation system in a high-fidelity simulator, CARLA (CAR Learning to Act). The proposed approach may also be applied to other systems driven by an end-to-end trained network.

### Adversary model
![Adversary model](/images/adversarial_UGV_attack_model.png)

### Adaptive Adversarial Video Framework
![Video Framework](/images/adversaraial_billboard_framework.png)

### Video

{% include youtube_embed.html id="m7JdeR8IU6k" %}

### Bibtex

    @inproceedings{PatelKGK19,
      author    = {Naman Patel and
                   Prashanth Krishnamurthy and
                   Siddharth Garg and
                   Farshad Khorrami},
      title     = {Adaptive Adversarial Videos on Roadside Billboards: Dynamically Modifying
                  Trajectories of Autonomous Vehicles},
      booktitle = {Proceedings of the {IEEE/RSJ} International Conference on Intelligent Robots and
               Systems},
      address   = {Macau, SAR, China},
      month     = {November},
      pages     = {5916--5921},
      year      = {2019},
    }
