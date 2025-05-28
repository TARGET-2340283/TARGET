---
layout: single
title: "Key Outcomes"
permalink: /outcome/
header:
  overlay_color: "#000"
  defaultdefaultoverlay_filter: "0.4"
  overlay_image: banner.png
toc: true
toc_label: "Key outcomes"
toc_icon: "cog"
sidebar:
  nav: "main"
---

## Key outcomes or Other achievements: 

### Key Outcome for Activity 1 GNN with Reparameterization for Joint Beamforming and Integer User Association 
To jointly optimize beamforming and integer-based user association, we developed a GNN structure leveraging Straight-Through Gumbel-Softmax (STGS) and GumbelSoftmax (GS) reparameterization, overcoming the challenge of integer outputs in neural networks while maintaining differentiability. Simulation results show that our GNN not only produces integer associations but also generalizes better to larger networks, achieving higher wireless network sum rates than all fractional association solutions. 

### Key Outcome for Activity 2 & 3 Attention-based GNN and Dual Optimization for User Association
We proposed a novel attention-based GNN with reparameterization and normalization that achieves consistently near-balanced user association, as well as a dual optimization method that guarantees perfectly balanced associations. For the attention based GNN, we introduced an additional rebalancing phase to further refine the initial association decisions and guarantee load balancing, in case the initial output is not fully load balanced. Following the association step, we employed another GNN to optimize beamforming for the given association results and maximize the wireless network sumrate. Extensive numerical results show that the proposed techniques yield near-optimal performance in terms of sum-rate, while the attention-based GNN architecture demonstrates excellent generalization ability, maintaining consistent performance as the 
network density/size increases and as the BS transmit power varies. 

### Key Outcome for Activity 4:  Joint Congestion Control and Flow Optimization with Percentile-Based Delay Constraints
To solve the optimization problem, we develop a distributed algorithm based on the barrier method, using the projected gradient method for the inner iterations at each barrier parameter. In parallel, we also develop a centralized approach that applies the barrier method with an equality-constrained Newton method for the inner iterations, offering faster convergence. Both methods ensure primal feasibility at every iteration. 

### Key outcomes of Activity 5: Delay-Optimal Service Chain Forwarding and Offloading in Collaborative Edge Computing 
We develop a joint forwarding and offloading model for service chain applications in CEC. We formulate a nonconvex total cost minimization problem and optimally solve it by providing sufficient optimality conditions. We devise a distributed and adaptive online algorithm that reaches the global optimal. Our method achieves delay-optimal forwarding and offloading for service chain computations, and can be applied to embed computation-intensive complex applications, e.g., DNN, into CEC networks. Our future work focuses on extending the proposed framework to incorporate more general interdependency among tasks, e.g., directed acyclic graphs.

### Key outcomes of Activity 6: Cost-aware Joint Caching and Forwarding in Networks with Heterogeneous Cache Resources 
We present an object-level multi-tiered caching policy that can address the challenges in realizing this transition. We build our policy using the VIP framework, which proves to be a suitable tool for this challenge. We show that our approach yields a stabilizing algorithm that provides minimal upper bounds on both the queue backlogs and cost accumulation across the network, and establishes the trade-off between these two bounds. We demonstrate through simulation experiments that the data plane policy driven by our algorithm in the virtual plane outperforms adapted traditional policies.

### Key Outcome for Activity 7: Measurement-based study of beam management in operational 5G mmWave networks
 The key outcome of Activity 5 is a detailed understanding of the beam management procedures in operational 5G mmWave networks that can guide future optimizations. Our results show that beam management is quite optimized in terms of performance, selecting near-optimal beams most of the time, however, the reporting overhead can be high, especially when beam refinement is applied on top of coarse SSB beams. Our findings suggest that future research efforts should focus on reducing the beam management overhead and consider beam management jointly with other components of the 5G protocol stack (e.g., signal processing, RA, CA, MIMO), which also have a major impact on performance.

### Key outcomes of Activity 8: A research agenda for spatial video streaming
 The main outcome of this activity is a comprehensive research agenda for spatial video streaming on emerging XR headsets, comprising view and packet adaptive bitrate algorithms, multipath support, and a QoE model for spatial video streaming.
