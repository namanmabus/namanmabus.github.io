---
title: "Sensor Modality Fusion with CNNs for UGV Autonomous Driving in Indoor Environments"
collection: publications
permalink: /publication/2017-09-25-Sensor-Modality-Fusion-with-CNNs
excerpt: "End-to-End Learning based Sensor Fusion for Autonomous Navigation in an indoor environment."
date: 2017-09-25
venue: "IROS 2017"
venuetype: "conference"
paperauthors: 'N. Patel, A. Choromanska, P. Krishnamurthy, F. Khorrami'
thumbnail: "modality_fusion_200.gif"
---

Links: [IROS 2017 page](https://ieeexplore.ieee.org/abstract/document/8205958), [IROS 2017 pdf](http://www.columbia.edu/~aec2163/NonFlash/Papers/SMF_CNN.pdf), [bibtex](#bibtex)

### Abstract

We present a novel end-to-end learning framework to enable ground vehicles to autonomously navigate unknown environments by fusing raw pixels from cameras and depth measurements from a LiDAR. A deep neural network architecture is introduced to effectively perform modality fusion and reliably predict steering commands even in the presence of sensor failures. The proposed network is trained on our own dataset, from LiDAR and a camera mounted on a UGV taken in an indoor corridor environment. Comprehensive experimental evaluation to demonstrate the robustness of our network architecture is performed to show that the proposed deep learning neural network is able to autonomously navigate in the corridor environment. Furthermore, we demonstrate that the fusion of the camera and LiDAR modalities provides further benefits beyond robustness to sensor failures. Specifically, the multimodal fused system shows a potential to navigate around static and dynamic obstacles and to handle changes in environment geometry without being trained for these tasks.

### Sensor Modality Fusion Framework

![Modality fusion framework overview](/images/modality_fusion_framework.png)

### Video

{% include youtube_embed.html id="3DGifIBux1s" %}

### Bibtex

    @inproceedings{PatelCKK17,
        title={Sensor modality fusion with CNNs for {UGV} autonomous driving in indoor environments},
        author={Naman Patel and Anna Choromanska and Prashanth Krishnamurthy and Farshad Khorrami},
        booktitle={Proceedings of the {IEEE/RSJ} International Conference on Intelligent Robots and Systems, {IROS}},
        address	= {Vancouver, BC, Canada},
        month	= {September},
        pages   = {1531--1536},
        year    = {2017},
    }
