---
title: "Towards a New Thermal Monitoring Based Framework for Embedded CPS Device Security"
collection: publications
permalink: /publication/2020-02-14-Towards-a-new-thermal-monitoring-based-framework-for-embedded-CPS-device-security
excerpt: "Introduces a methodology to use the thermal side channel as a proxy for the behavior of embedded processors to detect changes in this behavior in a cyber-physical system."
date: 2020-02-14
venue: "IEEE TDSC"
venuetype: "journal"
paperauthors: 'N. Patel, P. Krishnamurthy, H. Amrouch, J. Henkel, M. Shamouilian, R. Karri, F. Khorrami'
thumbnail: "thermal_framework.png"
---

Links: [IEEE TDSC page](https://ieeexplore.ieee.org/abstract/document/8999554), [bibtex](#bibtex)

### Abstract

This paper introduces a methodology to use the thermal side channel as a proxy for the behavior of embedded processors to detect changes in this behavior in a cyber-physical system. Such changes may be due to software attacks, hardware attacks, and altered processors. Since control system processes are periodic computations, the thermal side channel signals exhibit a temporal pattern. This enables detection of altered code and changed device characteristics. We present a machine learning approach to estimate the activity of the embedded device from the time sequence of thermal images and show the extent that deviations from expected behavior can be detected. The approach is validated on a testbed of a multi-core processor running a periodic computational code. The infrared imager directly collects thermal imagery from the processor, which is cooled from the backside. While an external infrared imager is used in this study, it is desirable to deploy a finite number of on-chip temperature sensors. This paper shows that integrating on-chip temperature sensors allows robust real-time monitoring of the processor behavior. Finally, we also offer a machine learning approach to find the optimal locations of the on-chip sensors to aid detection.


### Thermal Monitoring Setup and Examples of Thermal images of an Intel 8-core chip

![Thermal Monitoring Setup](/images/thermal_setup.png)

### Proposed Machine learning based methodology to estimate the CPS device computational activity time and for anomaly detection from a sequence of thermal heat maps.

![Anomaly Monitoring Framework](/images/thermal_anomaly_setup.png)


### Bibtex

    @article{PatelKAHSKK20,
        author    = {Naman Patel and
                 Prashanth Krishnamurthy and
                 Hussam Amrouch and
                 Jörg Henkel and
                 Michael Shamouilian and
                 Ramesh Karri and
                 Farshad Khorrami},
        title     = {Towards a new thermal monitoring based framework for embedded CPS device security},
        journal={IEEE Transactions on Dependable and Secure Computing},
        year      = {2020},
    }
