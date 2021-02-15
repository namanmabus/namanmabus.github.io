---
title: "Semantic Segmentation Guided SLAM Using Vision and LIDAR"
collection: publications
permalink: /publication/2018-16-20-Semantic-Segmentation-Guided-Using-Vision-LIDAR
excerpt: "Framework for incorporating semantic information in a SLAM system to alleviate drifts caused by translation and rotation errors."
date: 2017-06-20
venue: "ISR 2018"
venuetype: "conference"
paperauthors: 'N. Patel, P. Krishnamurthy, F. Khorrami'
thumbnail: "sem_slam_framework.gig"
---

Links: [ISR 2018 page](https://ieeexplore.ieee.org/document/8470619), [bibtex](#bibtex)

![Semantic Segmentation Guided SLAM](/images/Sem_SLAM_Framework.png)

### Abstract

This paper presents a novel framework for incorporating semantic information in a Simultaneous Localization and Mapping (SLAM) framework based on LIDAR and camera to improve navigation accuracy and alleviate drifts caused by translation and rotation errors. Specifically, an unmanned ground vehicle (UGV) equipped with a camera and LIDAR, operating in an indoor environment is considered. The proposed method uses features extracted from a camera and its correspondences in the LIDAR depth map to obtain the pose relative to a keyframe which is refined by semantic features obtained from a deep neural network. Additionally, each point in the map is associated with a semantic label to perform semantically guided local and global pose optimization. Since semantically correlated features can be expected to have higher likelihood of correct data association, the proposed coupling of semantic labeling and SLAM provides better robustness and accuracy. We demonstrate our approach using an unmanned ground vehicle (UGV) operating in an indoor environment equipped with a camera and a LIDAR.


### Bibtex
    @inproceedings{patel2018semantic,
      title={Semantic segmentation guided SLAM using Vision and LIDAR},
      author={Patel, Naman and Krishnamurthy, Prashanth and Khorrami, Farshad},
      booktitle={Proceedings of the International Symposium on Robotics},
      pages={352--358},
      address = {Munich, Germany},
      month = {June},
      year={2018},
    }
