---
title: TARGET
layout: single
classes: wide
permalink: /
header:
  overlay_color: "#000"
  defaultoverlay_filter: "0.4"
  overlay_image: banner.png
  actions:
    - label: "NSF Award Page"
      url: "https://www.nsf.gov/awardsearch/showAward?AWD_ID=2340283&HistoricalAwards=false"
excerpt: "Latency-aware Edge Computing for VR/AR in 5G and Beyond Networks."
# sidebar:
#   - title: "Project"
#     image: TARGET-ICON.png
#     image_alt: "image"
#     text: "TARGET: Latency-aware Edge Computing for VR/AR in 5G and Beyond Networks."
#   - title: "Time"
#     text: "May 15, 2024 - April 30, 2027 (Estimated)"
# toc: true
# toc_label: "My Table of Contents"
# toc_icon: "cog"
sidebar:
  nav: "main"
---


## Introduction
<img src="logo.png" alt="TARGET Icon" style="float:left; margin-right:20px; width:400px;" />
Augmented/Virtual/Mixed Reality (AR/VR/MR), or XR for short, is one of the next technological frontiers that will profoundly impact society. To provide high-quality and interactive experiences, XR apps on mobile devices such as smartphones will need to offload heavy computational tasks such as object detection and video frame rendering to edge servers at low latency and high data rates, which places high bandwidth demands on the wireless network. While 5G millimeter wave networks promise unprecedented data rates and ultra-low latency for wireless communication, their performance is not optimized for dynamic networks where signals may be blocked and the user may be moving. Additionally, today's edge servers are attached to the core of the cell phone network (called the mobile packet core network), resulting in long round trip times unsuitable for high frame rate XR applications. To address these shortcomings of today?s 5G millimeter wave network and edge infrastructure, this project proposes an enhanced edge architecture for Beyond 5G (B5G) networks featuring (i) dense base station deployment, (ii) caching of XR contents to eliminate long processing latency of heavy computational tasks, and (iii) a distributed infrastructure with computational and storage units attached to each base station and mobile packet core router to reduce the round trip times between mobile devices and edge servers. Using this new architecture, the project develops TARGET, a novel algorithmic framework for latency-aware edge computing for XR in B5G networks. TARGET establishes the theoretical foundations for enabling seamless mobile high-quality XR applications, enabled by the anticipated wide deployment of 5G and B5G networks. The proposed research activities also offer new materials for integration in classes taught by the PIs and help extend the PIs? excellent track record of involving undergraduate students and recruiting students from under-represented groups.

The TARGET framework consists of algorithms that (i) jointly optimize base station association/handover and beamforming directions for both uplink and downlink to minimize wireless latency by maximizing a weighted sum rate; (ii) jointly optimize caching and routing over general multi-hop edge computing networks to meet end-to-end latency constraints; and (iii) optimally trade off the computation and storage resources of a distributed hierarchical computing/storage infrastructure, through joint routing, computation placement and caching, to minimize end-to-end latency. The project examines both traditional optimization approaches and complementary machine learning approaches in designing and integrating these algorithms. The algorithms and protocols are evaluated via extensive network simulations along with experimental validation on two Northeastern University testbeds.
