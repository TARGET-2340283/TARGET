---
layout: single
title: "Objectives"
permalink: /objectives
header:
  overlay_color: "#000"
  defaultdefaultoverlay_filter: "0.4"
  overlay_image: banner.png
toc: true
toc_label: "Objectives"
toc_icon: "cog"
sidebar:
  nav: "main"
---
## Specific Objectives

### Activity 1: GNN with Reparameterization for Joint Beamforming and Integer User Association
 Our objective here is to design a novel GNN structure to produce integer user association outputs while maximizing the wireless network sum rate (which is used as a negative loss function to train the GNN). To maintain integer association while preserving the gradients for backpropagation, we incorporate reparameterization techniques into our GNN design. Specifically, we use the Straight-Through GumbelSoftmax (STGS) method, which provides a differentiable approximation of discrete sampling, making it well-suited for user association tasks. Additionally, we explore Gumbel-Softmax (GS), which does not strictly enforce integer outputs but provides close approximations, potentially enhancing exploration and learning during training. We compare these methods against existing approaches such as Softmax that quantize continuous association outputs, demonstrating the effectiveness of our reparameterized GNNs in achieving higher network sum rates with integer user association decisions. 

### Activity 2: Attention-based GNN for User Association with Rebalancing Architecture
Attention-based GNN for User Association with Rebalancing Architecture Our goal in this task is to find a novel way to integrate an attention mechanism into our GNN design to further improve the wireless network sum rate. Instead of using the traditional Graph Attention Networks (GATs) to compute attention coefficients based on shallow neural networks applied to node features, we use the full attention mechanism inspired by the Transformer architecture. In particular, instead of relying solely on pairwise node embeddings as in GAT, we compute full attention scores using querykey-value (QKV) projections in our GNN architecture. The computed attention weights between a UE and all BSs enable our GNN model to dynamically learn the strength of interactions between each UE and the BSs, allowing the GNN to focus more on the most relevant or influential connections within the graph. 

### Activity 3:  Dual Optimization for Load-Balanced User Association
 Dual Optimization for Load-Balanced User Association Our goal here is to use traditional optimization methods instead of ML to design a low complexity distributed algorithm to determine user association decisions while ensuring integer association and load balancing. To do this, we formulate the dual problem of the association optimization and design a dual algorithm to update both the dual and primal variables while meeting the load balancing constraints. Each BS makes local decisions based on its own state and limited network information, avoiding the need for global coordination. Despite its simplicity, the algorithm converges to a near-optimal solution while guaranteeing an integer and balanced solution. 

### Activity 4: Joint Congestion Control and Flow Optimization with Percentile-Based Delay Constraints
Our goal is to design iterative algorithms to jointly solve multicommodity network flow optimization and congestion control problems in multi-hop networks with arbitrary topologies, incorporating the percentile-based end-to-end delay constraints for each network session. Such optimization problems seek optimal admission and forwarding rates that maximize overall utility while minimizing link flow costs, subject to link capacity and flow conservation constraints. 

### Activity 5: Delay-Optimal Service Chain Forwarding and Offloading in Collaborative Edge Computing
Our goal is to formulate the service chain forwarding and offloading problem in CEC with arbitrary topology and heterogeneous transmission/computation capability, and minimize the aggregated network cost. We aim to minimize the congestion-aware non-linear cost functions that cover various performance metrics and constraints, such as average queueing delay with limited processor capacity.

### Activity 6: Cost-aware Joint Caching and Forwarding in Networks with Heterogeneous Cache Resources
Our goal is to model the cache as a set of storage blocks with varying rate parameters and utilization costs, and design a joint caching and forwarding optimization framework to maximize the throughput and minimize the cache replacement penalty. 

### Activity 7: Measurement-based study of beam management in operational 5G mmWave networks 
Our goal here is to study the main aspects of beam management in operational 5G mMWave networks, understand its performance and the factors that affect it, its limitations, and its interaction with other components of the 5G stack, such as rate adaptation and carrier aggregation. The lessons learned from this study will guide future beamforming optimizations.

### Activity 8: A research agenda for spatial video streaming 
Our goal here is to create a research agenda for spatial video streaming, outline the main research threads for exploration, and identify the fundamental components for future XR experiences on mobile and wearable devices.
