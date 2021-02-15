---
title: "Tightly Coupled Semantic RGB-D Inertial Odometry for Accurate Long-Term Localization and Mapping"
collection: publications
permalink: /publication/2019-12-02-Tightly-coupled-semantic-RGB-D-inertial-odometry-for-accurate-long-term-localization-and-mapping
excerpt: "Semantically enhanced feature matching and visual inertial bundle adjustment to improve the robustness of odometry especially in feature-sparse environments."
date: 2019-12-02
venue: "ICAR 2019"
venuetype: "conference"
paperauthors: 'N. Patel, , F. Khorrami, P. Krishnamurthy, A. Tzes'
thumbnail: "sem_slam_vi_framework.gif"
---

Links: [ICAR 2019 page](https://ieeexplore.ieee.org/abstract/document/8981658), [bibtex](#bibtex)

### Abstract

In this paper, we utilize semantically enhanced feature matching and visual inertial bundle adjustment to improve the robustness of odometry especially in feature-sparse environments. A novel semantically enhanced feature matching algorithm is developed for robust: 1) medium and long-term tracking, and 2) loop-closing. Additionally, a semantic visual inertial bundle adjustment algorithm is introduced to robustly estimate pose in presence of ambiguous correspondences or in feature sparse environment. Our tightly coupled semantic RGB-D odometry approach is demonstrated on a real world indoor dataset collected using our unmanned ground vehicle (UGV). Our approach improves traditional visual odometry relying on low-level geometric features like corners, points, and planes for localization and mapping. Additionally, prior approaches are limited due to their sensitivity to scene geometry and changes in light intensity. The semantic inertial odometry is especially important to significantly reduce drifts in longer intervals.

### Our proposed odometry pipeline with blocks shaded in green and purple are novel components added to the ORB-SLAM2 algorithm
![Semantic Segmentation Guided SLAM](/images/Sem_SLAM_VI_Framework.png)

### Bibtex
    @inproceedings{PatelKKT19,
      author    = {Naman Patel and
               Farshad Khorrami and
               Prashanth Krishnamurthy and
               Anthony Tzes},
      title     = {Tightly Coupled Semantic RGB-D Inertial Odometry for Accurate Long-Term
               Localization and Mapping},
      booktitle = {Proceedings of the International Conference on Advanced Robotics, {ICAR}},
      address   = {Belo Horizonte, Brazil},
      month     = {December},
      pages     = {523--528},
      year      = {2019},
    }
