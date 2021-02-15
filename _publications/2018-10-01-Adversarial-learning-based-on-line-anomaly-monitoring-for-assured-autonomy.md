---
title: "Adversarial learning-based on-line anomaly monitoring for assured autonomy"
collection: publications
permalink: /publication/2018-10-01-Adversarial-learning-based-on-line-anomaly-monitoring-for-assured-autonomy
excerpt: "An on-line monitoring framework for continuous real-time safety/security in learning-based control systems."
date: 2018-10-01
venue: "IROS 2018"
venuetype: "conference"
paperauthors: 'N. Patel, A. N. Saridena, A. Choromanska, P. Krishnamurthy, F. Khorrami'
thumbnail: "anomaly_monitor_framework.gif"
---

Links: [IROS 2018 page](https://ieeexplore.ieee.org/abstract/document/8593375), [IROS 2018 pdf](https://arxiv.org/pdf/1811.04539.pdf), [bibtex](#bibtex)

### Anomaly Monitoring Framework
![Anomaly Monitoring Framework](/images/cfam_sfam_system_diagram.png)

### CFAM
![CFAM Framework](/images/CFAM_framework.png)

### SFAM
![SFAM Framework](/images/SFAM_framework.png)

### Abstract

The paper proposes an on-line monitoring framework for continuous real-time safety/security in learning-based control systems (specifically application to a unmanned ground vehicle). We monitor validity of mappings from sensor inputs to actuator commands, controller-focused anomaly detection (CFAM), and from actuator commands to sensor inputs, system-focused anomaly detection (SFAM). CFAM is an image conditioned energy based generative adversarial network (EBGAN) in which the energy based discriminator distinguishes between proper and anomalous actuator commands. SFAM is based on an action condition video prediction framework to detect anomalies between predicted and observed temporal evolution of sensor data. We demonstrate the effectiveness of the approach on our autonomous ground vehicle for indoor environments and on Udacity dataset for outdoor environments.

### Video

{% include youtube_embed.html id="SaPoeDT88LU" %}

### Bibtex

    @inproceedings{PatelSCKK18,
      author    = {Naman Patel and
                 Apoorva Nandini Saridena and
                 Anna Choromanska and
                 Prashanth Krishnamurthy and
                 Farshad Khorrami},
      title     = {Adversarial learning-based on-line anomaly monitoring for assured autonomy},
      booktitle = {Proceedings of the {IEEE/RSJ} International Conference on Intelligent Robots and
               Systems, {IROS}}
      address	= {Madrid, Spain},
      month		= {October},
      pages     = {6149--6154},
      year      = {2018},
    }