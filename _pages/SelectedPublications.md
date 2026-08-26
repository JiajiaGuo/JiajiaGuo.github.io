---
layout: archive
title: ""
permalink: /SelectedPublications/
author_profile: true
---

You can also find my publications on
[Google Scholar](https://scholar.google.com/citations?user=WN7-Mz4AAAAJ).

My research centers on **AI-native wireless communications**, with a long-standing
research foundation in **channel intelligence for advanced MIMO** and current
interests in **efficient, adaptive and trustworthy wireless AI**, as well as
**wireless foundation models and environment intelligence**.


## **Surveys, Perspectives, and Tutorials**

[1] [J. Guo, Y. Cui, S. Jin, and J. Zhang,
“Large AI Models for Wireless Physical Layer,”
IEEE Communications Magazine, vol. 64, no. 5, pp. 148–155, May 2026.](https://doi.org/10.1109/MCOM.001.2500505)

This article reviews large AI models for wireless physical-layer communications
and organizes existing approaches into two paradigms: leveraging pre-trained
large models and developing wireless-native large models.


[2] [J. Guo, C.-K. Wen, S. Jin, and X. Li,
“AI for CSI Feedback Enhancement in 5G-Advanced,”
IEEE Wireless Communications, vol. 31, no. 3, pp. 169–176, Jun. 2024.](https://ieeexplore.ieee.org/document/9970357)

This article reviews AI-based CSI feedback enhancement from a
**3GPP standardization perspective**, including evaluation methodology,
deployment challenges, and protocol evolution.

**ESI Highly Cited Paper**


[3] [J. Guo, C.-K. Wen, S. Jin, and G. Y. Li,
“Overview of Deep Learning-Based CSI Feedback in Massive MIMO Systems,”
IEEE Transactions on Communications, vol. 70, no. 12,
pp. 8017–8045, Dec. 2022.](https://ieeexplore.ieee.org/document/9931713)

A comprehensive overview of deep learning-based CSI feedback, covering
architectures, quantization, multi-rate feedback, practical deployment,
and future research directions.

**Invited Paper; ESI Highly Cited Paper**


[4] [Q. Xue, J. Guo, B. Zhou, Y. Xu, Z. Li, and S. Ma,
“AI/ML for Beam Management in 5G-Advanced: A Standardization Perspective,”
IEEE Vehicular Technology Magazine, vol. 19, no. 4,
pp. 64–72, Dec. 2024.](https://ieeexplore.ieee.org/document/10627924)

This article reviews AI/ML-enabled beam management with emphasis on
5G-Advanced standardization, evaluation, and deployment.


[5] [J. Guo, C.-K. Wen, and S. Jin,
“AI-Native Air Interface,”
in *Fundamentals of 6G Communications and Networking*,
Springer, pp. 143–163, 2024.](https://link.springer.com/chapter/10.1007/978-3-031-37920-8_6)

This book chapter introduces AI-native air-interface design and discusses
end-to-end communications, single-module enhancement, and practical challenges
for integrating AI into future wireless systems.



# **Research Direction 1: Channel Intelligence for Advanced MIMO**

My work in this direction investigates how advanced MIMO systems can
efficiently **acquire, represent, predict, and exploit channel knowledge**
under limited pilot, feedback, signaling, and computational resources.


### **CSI Representation and Feedback**

[1] [J. Guo, C.-K. Wen, S. Jin, and G. Y. Li,
“Convolutional Neural Network-Based Multiple-Rate Compressive Sensing
for Massive MIMO CSI Feedback: Design, Simulation, and Analysis,”
IEEE Transactions on Wireless Communications, vol. 19, no. 4,
pp. 2827–2840, Apr. 2020.](https://ieeexplore.ieee.org/document/8972904)

This work develops a flexible CSI compression framework supporting
multiple feedback rates and practical quantization.

**ESI Highly Cited Paper**


[2] [J. Guo, C.-K. Wen, and S. Jin,
“CAnet: Uplink-Aided Downlink Channel Acquisition in FDD Massive MIMO
Using Deep Learning,”
IEEE Transactions on Communications, vol. 70, no. 1,
pp. 199–214, Jan. 2022.](https://ieeexplore.ieee.org/document/9570376)

This work exploits uplink channel information to assist downlink channel
acquisition in FDD massive MIMO.


[3] [J. Guo, C.-K. Wen, and S. Jin,
“Eliminating CSI Feedback Overhead via Deep Learning-Based Data Hiding,”
IEEE Journal on Selected Areas in Communications, vol. 40, no. 8,
pp. 2267–2281, Aug. 2022.](https://ieeexplore.ieee.org/document/9791341)

This work explores a fundamentally different feedback mechanism in which
CSI information is embedded into transmitted data rather than occupying
dedicated feedback resources.



### **Task-Oriented Channel Acquisition**

[4] [J. Guo, C.-K. Wen, and S. Jin,
“Deep Learning-Based CSI Feedback for Beamforming in Single- and Multi-Cell
Massive MIMO Systems,”
IEEE Journal on Selected Areas in Communications, vol. 39, no. 7,
pp. 1872–1884, Jul. 2021.](https://ieeexplore.ieee.org/document/9279228)

This work shifts CSI feedback optimization from minimizing reconstruction
error toward directly maximizing downstream beamforming performance.


[5] [J. Guo, T. Chen, S. Jin, G. Y. Li, X. Wang, and X. Hou,
“Deep Learning for Joint Channel Estimation and Feedback in Massive MIMO
Systems,”
Digital Communications and Networks, vol. 10, no. 1,
pp. 83–93, 2024.](https://www.sciencedirect.com/science/article/pii/S235286482300024X)

This work jointly designs channel estimation, compression, and reconstruction
instead of optimizing individual channel-acquisition modules separately.

**ESI Highly Cited Paper**



### **RIS and Cell-Free Massive MIMO**

[6] [J. Guo, W. Chen, C.-K. Wen, and S. Jin,
“Deep Learning-Based Two-Timescale CSI Feedback for Beamforming Design
in RIS-Assisted Communications,”
IEEE Transactions on Vehicular Technology, vol. 72, no. 4,
pp. 5452–5457, Apr. 2023.](https://ieeexplore.ieee.org/document/9969163)

This work develops a two-timescale CSI feedback framework for jointly
supporting beamforming and RIS phase-shift design.


[7] [J. Guo, X. Yang, C.-K. Wen, S. Jin, and G. Y. Li,
“Deep Learning-Based CSI Feedback for RIS-Assisted Multi-User Systems,”
IEEE Transactions on Communications, vol. 73, no. 7,
pp. 4974–4989, 2025.](https://ieeexplore.ieee.org/document/10818491)

This work exploits inter-user correlation in RIS-user channels to reduce
redundant feedback and improve multi-user CSI acquisition efficiency.


[8] [J. Guo, C.-K. Wen, X. Li, and S. Jin,
“Deep Learning-Based Position-Domain Channel Extrapolation for Cell-Free
Massive MIMO,”
IEEE Transactions on Wireless Communications, vol. 25,
pp. 1996–2011, 2026.](https://doi.org/10.1109/TWC.2025.3594033)

This work introduces **position-domain channel extrapolation**, using the
user position as a bridge for transferring channel knowledge across
geographically distributed links in cell-free massive MIMO.



# **Research Direction 2: Efficient, Adaptive and Trustworthy Wireless AI**

This direction focuses on making wireless AI models **lightweight,
adaptive, reliable, and practically deployable** under constraints on
computation, data, latency, energy, and changing environments.


[1] [J. Guo, J. Wang, C.-K. Wen, S. Jin, and G. Y. Li,
“Compression and Acceleration of Neural Networks for Communications,”
IEEE Wireless Communications, vol. 27, no. 4,
pp. 110–117, Aug. 2020.](https://ieeexplore.ieee.org/document/9136588)

This work investigates neural-network compression and acceleration for
resource-constrained wireless AI deployment.


[2] [J. Guo, X. Li, M. Chen, et al.,
“AI Enabled Wireless Communications with Real Channel Measurements:
Channel Feedback,”
Journal of Communications and Information Networks, vol. 5, no. 3,
pp. 310–317, 2020.](https://doi.org/10.23919/JCIN.2020.9200895)

This work evaluates AI-based CSI feedback using real wireless channel
measurements and studies the gap between simulation-based development
and practical deployment.

**Cover Paper**


[3] [J. Guo, Y. Zuo, C.-K. Wen, and S. Jin,
“User-Centric Online Gossip Training for Autoencoder-Based CSI Feedback,”
IEEE Journal of Selected Topics in Signal Processing, vol. 16, no. 3,
pp. 559–572, Apr. 2022.](https://ieeexplore.ieee.org/document/9737435)

This work develops distributed online adaptation that exploits spatial
correlation among users without requiring centralized retraining.


[4] [J. Guo, S. Ma, C.-K. Wen, and S. Jin,
“Performance Monitoring-Enabled Reliable AI-Based CSI Feedback,”
IEEE Transactions on Wireless Communications, vol. 24, no. 1,
pp. 197–212, 2025.](https://ieeexplore.ieee.org/document/10750249)

This work introduces online performance monitoring for AI-based CSI feedback,
enabling unreliable model outputs to be identified during deployment.



### **Selected Collaborative Work**

[5] Y. Cui, J. Guo, Z. Cao, et al.,
“Lightweight Neural Network with Knowledge Distillation for CSI Feedback,”
IEEE Transactions on Communications, vol. 72, no. 8,
pp. 4917–4929, 2024.

[6] X. Li, J. Guo, C.-K. Wen, X. Geng, and S. Jin,
“Auto-CsiNet: Scenario-Customized Automatic Neural Network Architecture
Generation for Massive MIMO CSI Feedback,”
IEEE Transactions on Wireless Communications, vol. 23, no. 10,
pp. 14759–14775, 2024.

[7] X. Li, J. Guo, C.-K. Wen, X. Geng, and S. Jin,
“Facilitating AI-Based CSI Feedback Deployment in Massive MIMO Systems
with Learngene,”
IEEE Transactions on Wireless Communications, vol. 23, no. 9,
pp. 11325–11340, 2024.

[8] J. Zhang, J. Guo, X. Li, C.-K. Wen, X. Geng, and S. Jin,
“Efficient Deployment of Deep MIMO Detection Using Learngene,”
IEEE Transactions on Wireless Communications, vol. 25,
pp. 4405–4418, 2026.



# **Research Direction 3: Wireless Foundation Models and Environment Intelligence**

My recent work explores how wireless AI can move beyond task-specific
and scenario-specific models by learning and exploiting **reusable channel,
spatial, semantic, and environment knowledge**.


[1] [J. Guo, C.-K. Wen, M. Chen, and S. Jin,
“Environment Knowledge-Aided Massive MIMO Feedback Codebook Enhancement
Using Artificial Intelligence,”
IEEE Transactions on Communications, vol. 70, no. 7,
pp. 4527–4542, Jul. 2022.](https://ieeexplore.ieee.org/document/9789120)

This work explicitly introduces propagation-environment knowledge into
CSI feedback while retaining compatibility with conventional codebook-based
feedback procedures.


[2] [J. Guo, Y. Lv, C.-K. Wen, X. Li, and S. Jin,
“Learning-Based Integrated CSI Feedback and Localization in Massive MIMO,”
IEEE Transactions on Wireless Communications, vol. 23, no. 10,
pp. 14988–15001, 2024.](https://ieeexplore.ieee.org/document/10597358)

This work jointly exploits channel and location information, demonstrating
how shared wireless representations can benefit multiple channel-related tasks.


[3] [J. Guo, Y. Cui, and S. Jin,
“Semantic-Aware Digital Twin for AI-Based CSI Acquisition,”
IEEE Communications Standards Magazine, vol. 9, no. 4,
pp. 50–57, 2025.](https://doi.org/10.1109/MCOMSTD.2025.3585026)

This work introduces semantic-aware wireless digital twins as an interface
between physical environments and AI-based CSI acquisition, with the goal
of reducing data-collection and deployment costs.


[4] [J. Guo, Y. Cui, C.-K. Wen, and S. Jin,
“Prompt-Enabled Large AI Models for CSI Feedback,”
IEEE Journal on Selected Areas in Communications, vol. 44,
pp. 2654–2668, 2026.](https://doi.org/10.1109/JSAC.2025.3643823)

This work investigates why AI-based CSI feedback generalizes across
environments and develops a large CSI model that incorporates
environment-specific channel-distribution knowledge through prompts.


### **Selected Collaborative Work**

[5] [T. Zheng, J. Guo, L. Dai, S. Jin, and J. Zhang,
“MUSE-FM: Multi-Task Environment-Aware Foundation Model for Wireless
Communications,”
IEEE Transactions on Wireless Communications, vol. 25,
pp. 19791–19806, 2026.](https://doi.org/10.1109/TWC.2026.3708709)

MUSE-FM develops a unified foundation-model architecture for heterogeneous
wireless tasks and explicitly incorporates environmental context to improve
cross-scenario adaptation.


[6] Y. Cui, J. Guo, X. Li, C.-K. Wen, and S. Jin,
“Large and Small Model Collaboration for Air Interface,”
IEEE Transactions on Wireless Communications, accepted, 2026.

This work develops a large-small model collaboration paradigm in which
a large model provides reusable wireless knowledge while lightweight models
support efficient environment-specific adaptation.
