---
title: "Learning-Based Real-Time Process-Aware AnomalyMonitoring for Assured Autonomy"
collection: publications
permalink: /publication/2020-05-25-Learning-based-real-time-process-aware-anomaly-monitoring-for-assured-autonomy
excerpt: "An on-line monitoring framework for continuous real-time safety/security in learning-based control systems."
date: 2020-05-25
venue: ""
venuetype: "journal"
paperauthors: 'N. Patel, A. N. Saridena, A. Choromanska, P. Krishnamurthy, F. Khorrami'
thumbnail: "anomaly_monitor_framework.gif"
---

Links: [IEEE T-IV page](https://ieeexplore.ieee.org/abstract/document/9099389), [bibtex](#bibtex)

### Anomaly Monitoring Framework
![Anomaly Monitoring Framework](/images/cfam_sfam_system_diagram.png)

### CFAM
![CFAM Framework](/images/CFAM_framework.png)

### SFAM
![SFAM Framework](/images/SFAM_framework.png)

### Abstract

Various learning-based approaches have been proposed recently for robot control in complex unknown environments. However, ensuring safety in these systems is essential. Learning-based approaches are usually black-box systems which are difficult to interpret/verify. We propose a real-time continuous safety checking system which monitors the validity of the mapping from the sensor input to the actuator command (i.e., controller-focused anomaly detection) and from the actuator command to the sensor input (i.e., system-focused anomaly detection). Our controller-focused anomaly monitor is an image conditioned energy based generative adversarial network in which the discriminator acts as an energy function attributing low energies to proper actuator commands and high energy to anomalous actuator commands. Our system-focused anomaly monitor is based on an action condition video prediction framework, which finds the action conditioned future frame most similar to the actual future frame and compares it with the true action to detect anomaly. We experimentally demonstrate the effectiveness of our framework for an autonomous navigation system in indoor (on datasets from our ground vehicle) and outdoor environments (on Udacity dataset). Furthermore, we show through experimental evaluations that our proposed framework is resilient to various data corruptions common in a vision based system.

### Video

{% include youtube_embed.html id="SaPoeDT88LU" %}

### Bibtex

    @article{PatelSCKK20,
      author    = {Naman Patel and
                  Apoorva Nandini Saridena and
                  Anna Choromanska and
                 Prashanth Krishnamurthy and
                 Farshad Khorrami},
      title     = {Learning-Based Real-Time Process-Aware Anomaly Monitoring for Assured
               Autonomy},
      journal   = {IEEE Transactions on Intelligent Vehicles},
      volume    = {5},
      number    = {4},
      pages     = {659--669},
      year      = {2020},
    }
