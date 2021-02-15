---
title: "A deep learning gated architecture for UGV navigation robust to sensor failures"
collection: publications
permalink: /publication/2019-06-01-deep-learning-gated-architecture-for UGV-navigation
excerpt: "Methodology for fusing sensors and improving robustness to sensor failures in end-to-end learning based autonomous navigation of ground vehicles in unknown environments."
date: 2019-06-01
venue: "Robotics and Autonomous Systems"
venuetype: "journal"
paperauthors: 'N. Patel, A. Choromanska, P. Krishnamurthy, F. Khorrami'
thumbnail: "modality_fusion_200.gif"
---

Links: [RAS page](https://www.sciencedirect.com/science/article/pii/S0921889018305645), [bibtex](#bibtex)

### Abstract

In this paper, we introduce a novel methodology for fusing sensors and improving robustness to sensor failures in end-to-end learning based autonomous navigation of ground vehicles in unknown environments. We propose the first learning based camera–LiDAR fusion methodology for autonomous in-door navigation. Specifically, we develop a multimodal end-to-end learning system, which maps raw depths and pixels from LiDAR and camera, respectively, to the steering commands. A novel gating based dropout regularization technique is introduced which effectively performs multimodal sensor fusion and reliably predicts steering commands even in the presence of various sensor failures. The robustness of our network architecture is demonstrated by experimentally evaluating its ability to autonomously navigate in the indoor corridor environment. Specifically, we show through various empirical results that our framework is robust to sensor failures, partial image occlusions, modifications of the camera image intensity, and the presence of noise in the camera or LiDAR range images. Furthermore, we show that some aspects of obstacle avoidance are implicitly learned (while not being specifically trained for it); these learned navigation capabilities are shown in ground vehicle navigation around static and dynamic obstacles.

### Sensor Modality Fusion Architecture

![Modality fusion framework overview](/images/modality_fusion_framework.png)

### Video

{% include youtube_embed.html id="3DGifIBux1s" %}

### Bibtex

    @article{PatelCKK19,
      author    = {Naman Patel and
                  Anna Choromanska and
                  Prashanth Krishnamurthy and
                  Farshad Khorrami},
      title     = {A deep learning gated architecture for {UGV} navigation robust to sensor failures},
      journal   = {Robotics and Autonomous Systems},
      volume    = {116},
      pages     = {80--97},
      year      = {2019},
    }
