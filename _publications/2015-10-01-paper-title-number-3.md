---
title: "Distributed Adaptive and Resilient Control of Multi-Robot Systems with Limited Field of View Interactions"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'Adaptive control application for multi-robot limited field-of-view control.'
date: 2022-03-03
venue: 'IEEE Robotics and Automation Letters'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9726803'
citation: 'Mukherjee, Pratik, et al. "Distributed adaptive and resilient control of multi-robot systems with limited field of view interactions." IEEE Robotics and Automation Letters 7.2 (2022): 5318-5325.'
---

In this letter, we consider two coupled problems for distributed multi-robot systems (MRSs) coordinating with on-board sensors: rejection of sensor attacks and adaptive tuning of interaction gains . First, MRSs with on-board sensors can be more susceptible to sensor attacks, and therefore must be resilient to such attacks. Second, a typical shortcoming of distributed control frameworks (e.g., potential fields) is that the overall system behavior is highly sensitive to the gain assigned to relative interactions. Therefore, we derive H∞ control protocols by employing a static output-feedback technique, guaranteeing bounded L2 gains of the error induced by the attack (fault) signals for a potential-based control framework developed for the particular application of limited fields of view (FOVs) control of MRS with additive sensor and actuator attacks (or faults). Moreover, to overcome the shortcomings of general potential-based control framework in the first place, we also apply an adaptive gain tuning scheme based on satisfying nominal pairwise interactions , which yields a dynamic balancing of interaction strengths in a robot’s neighborhood. Finally, simulation results using ROS Gazebo are provided to support our theoretical findings.