---
title: "Lack of Robustness of LIDAR-Based Deep Learning Systems to Small Adversarial Perturbations"
collection: publications
permalink: /publication/2018-06-20-Lack-of-Robustness-of-LIDAR-Based-Deep-Learning-Systems-to-Small-Adversarial-Perturbations
excerpt: "Attack on LIDAR-based autonomous navigation system using Deep Neural Networks (DNN) for navigation."
date: 2018-06-20
venue: "ISR 2018"
venuetype: "conference"
paperauthors: 'N. Patel, K. Liu, P. Krishnamurthy, S. Garg, F. Khorrami'
thumbnail: "LIDAR_attack.gif"
---

Links: [ISR 2018 page](https://ieeexplore.ieee.org/abstract/document/8470620), [bibtex](#bibtex)

### Abstract

In this paper, we investigate the robustness of LIDAR-based autonomous navigation for unmanned vehicles using Deep Neural Networks (DNN) to adversarial perturbations. A well-trained network robust to sensor noise can yield an undesirable network response (e.g., steering the vehicle in a wrong direction) by maliciously crafted perturbations in sensor data. We show through experimental evaluations on our unmanned ground vehicle (UGV) that small perturbations in some of the LIDAR sensor data (even perturbations smaller than the sensor accuracy) can lead the DNN to generate incorrect outputs. This is somewhat unexpected from a sensor such as LIDAR, which provides very well-defined structural/geometrical information about the environment.

### Video

{% include youtube_embed.html id="V-IlctFytu4" %}


### Bibtex

    @inproceedings{PatelKKGK18,
      author    = {Naman Patel and
                  Kang Liu and
                  Prashanth Krishnamurthy and
                  Siddharth Garg and
                  Farshad Khorrami},
      title     = {Lack of Robustness of LIDAR-Based Deep Learning Systems to Small Adversarial Perturbations},
      booktitle={Proceedings of the International Symposium on Robotics},
      pages={359--365},
      address = {Munich, Germany},
      month = {June},
      year={2018},
    }
