---
title: "Sliding-Window Temporal Attention based Deep Learning System for Robust Sensor Modality Fusion"
collection: publications
permalink: /publication/2019-07-23-Sliding-window-temporal-attention-based-deep-learning-system-for-robust-sensor-modality-fusion-for-UGV-navigation
excerpt: "Temporal attention based neural network architecture for robotics tasks that involve fusion of time series of sensor data."
date: 2019-07-23
venue: "IEEE Robotics and Automation Letters"
venuetype: "journal"
paperauthors: 'H. Utku Unlu, N. Patel, P. Krishnamurthy, F. Khorrami'
thumbnail: "modality_fusion_time.gif"
---

Links: [RA-L page](https://ieeexplore.ieee.org/document/8770056), [bibtex](#bibtex)

### Abstract

We propose a novel temporal attention based neural network architecture for robotics tasks that involve fusion of time series of sensor data, and evaluate the performance improvements in the context of autonomous navigation of unmanned ground vehicles (UGVs) in uncertain environments. The architecture generates feature vectors by fusing raw pixel and depth values collected by camera(s) and LiDAR(s), stores a history of the generated feature vectors, and incorporates the temporally attended history with current features to predict a steering command. The experimental studies show the robust performance in unknown and cluttered environments. Furthermore, the temporal attention is resilient to noise, bias, blur, and occlusions in the sensor signals. We trained the network on indoor corridor datasets (that will be publicly released) from our UGV. The datasets have LiDAR depth measurements, camera images, and human tele-operation commands.

### NetGated Dropout Architecture

![NetGated Dropout Architecture](/images/ngd_arch.png)

### Sliding-Window Temporal Fusion Architecture

![Sequential Architecture](/images/seq_arch.png)

### Video

{% include youtube_embed.html id="-TC1m_f6ipQ" %}

### Bibtex

    @article{UnluPKK19,
        author    = {Halil Utku Unlu and
                    Naman Patel and
                    Prashanth Krishnamurthy and
                    Farshad Khorrami},
        title     = {Sliding-Window Temporal Attention Based Deep Learning System for Robust Sensor Modality Fusion for {UGV} Navigation},
        journal   = {IEEE Robotics and Automation Letters},
        volume    = {4},
        number    = {4},
        pages     = {4216--4223},
        year      = {2019},
}
