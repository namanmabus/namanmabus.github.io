---
title: "Emerging (Un-)Reliability Based Security Threats and Mitigations for Embedded Systems"
collection: publications
permalink: /publication/2017-10-15-Emerging-un-reliability-based-security-threats-and-mitigations-for-embedded-systems
excerpt: "Addresses reliability-based security threats and mitigations for embedded systems, namely, aging and thermal side channels."
date: 2017-10-15
venue: "CASES 2017"
venuetype: "conference"
paperauthors: 'H. Amrouch, P. Krishnamurthy, N. Patel, J. Henkel, R. Karri, F. Khorrami'
thumbnail: "thermal_setup.png"
---

Links: [CASES 2017 page](https://dl.acm.org/doi/abs/10.1145/3125501.3125529), [CASES 2017 pdf](http://ces.itec.kit.edu/img/CASES17.pdf), [bibtex](#bibtex)

### Abstract

This paper addresses two reliability-based security threats and mitigations for embedded systems namely, aging and thermal side channels. Device aging can be used as a hardware attack vector by using voltage scaling or specially crafted instruction sequences to violate embedded processor guard bands. Short-term aging effects can be utilized to cause transient degradation of the embedded device without leaving any trace of the attack. (thermal) side channels can be used as an attack vector and as a defense. Specifically, thermal side channels are an effective and secure way to remotely monitor code execution on an embedded processor and/or to possibly leak information. Although various algorithmic means to detect anomaly are available, machine learning tools are effective for anomaly detection. We will show such utilization of deep learning networks in conjunction with thermal side channels to detect code injection/modification representing anomaly.

### Thermal Monitoring Setup and Examples of Thermal images of an Intel 8-core chip

![Thermal Monitoring Setup](/images/thermal_setup.png)

### Proposed Machine learning based methodology to estimate the CPS device computational activity time and for anomaly detection from a sequence of thermal heat maps.

![Anomaly Monitoring Framework](/images/thermal_anomaly_setup.png)

### Bibtex

    @inproceedings{AmrouchKPHKK17,
    author    = {Hussam Amrouch and
                 Prashanth Krishnamurthy and
                 Naman Patel and
                 J{\"{o}}rg Henkel and
                 Ramesh Karri and
                 Farshad Khorrami},
    title     = {Emerging (un-)reliability based security threats and mitigations for
               embedded systems: special session},
    booktitle = {Proceedings of the 2017 International Conference on Compilers, Architectures and Synthesis for Embedded Systems, {CASES}},
    address = {Seoul, Republic of Korea},
    month   = {October},
    pages     = {17:1--17:10},
    year      = {2017},
    }
