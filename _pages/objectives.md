---
layout: single
title: "Objectives"
permalink: /objectives/
header:
  overlay_color: "#000"
  defaultdefaultoverlay_filter: "0.4"
  overlay_image: images/banner.png
toc: true
toc_label: "Objectives"
toc_icon: "cog"
sidebar:
  nav: "main"
---
## Objectives
This project aims to develop key technologies at the PHY and network layers in an end-to-end latency framework for enabling seamless, high-quality edge-assisted AR/VR over 5G and Beyond (B5G) networks. To address shortcomings of the present 5G mmWave network and edge infrastructure, we envision an enhanced infrastructure for B5G networks featuring: 

### Joint BS Association and Beamforming from Both BSs and UEs. 
To minimize coverage holes and increase the probability that a mobile device will be in LoS of at least one BS, we envision a dense deployment of mmWave BSs. However, a dense BS deployment complicates the user association and handover problem, as a user equipment (UE) device will typically be within the transmission range of multiple BSs at a given moment. Additionally, the interference problem, due to imperfect phased arrays featuring strong sidelobes from BSs or broad mainlobes from UEs, is exacerbated in dense deployments. Joint consideration of BS association/handover and beamforming will be crucial in such environments to enable the high data rates required by AR/VR apps. In this project, we consider the joint optimization of BS association and BS/UE beamforming for both uplink and downlink, and design novel distributed algorithms to overcome the typically large overhead and long delay of centralized schemes. 

### Intelligent Caching to Reduce E2E Latency. 
Since computationally-intensive tasks can take in the order of 10 ms even on high-end CPUs/GPUs, caching plays a key role in reducing the end-to-end (E2E) latency. For VR applications, recent work has proposed pre-rendering and storing all possible views at all positions to avoid the cost of online rendering. Similarly, for AR apps, recent work has proposed caching computational results (e.g., the outcome of DNN inference) for popular scenes, which can then be reused for new users joining the same scene. However, in practice, caching all possible views for multiple VR apps or DNN inference results for multiple AR apps can result in prohibitively high storage requirements. Hence, in this project, we plan to design novel, intelligent, and efficient caching algorithms to control storage requirements while minimizing the E2E latency. 

### Distributed, Hierarchical Storage and Computing Infrastructure. 
To reduce the long round-trip time (RTTs) from/to today’s edge servers, which are attached to the mobile packet core network, we envision adding computational and storage units to each BS and each mobile packet core router. This will result in a distributed hierarchical computing/storage infrastructure inside the cellular B5G network that will trade off storage capacity, computing latency, and communication latency. We envision edge servers attached to the packet core network to have higher computing and storage capacity, at the cost of longer RTTs (in the order of 10-20 ms), and computing/storage units attached to the BSs and packet core routers to have lower computing and storage capacity, but also much shorter RTTs (in the order of a few ms). Such a hierarchical computing/storage infrastructure necessitates a joint design of the request routing, caching, and computational placement as considered in this project. 
