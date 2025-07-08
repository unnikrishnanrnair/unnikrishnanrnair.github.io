---
title: "Research & Publications"
date: 2025-01-08
draft: false
slug: "Research"
---

# 📚 Research & Publications

My research explores the intersection of **robotics**, **computer vision**, and **machine learning**, with a focus on autonomous navigation, planning, and language grounding.

---

## 🛰️ SROM: Real-Time Odometry and Mapping with LiDAR  
**IEEE IV 2020** • [Paper Link](https://arxiv.org/pdf/2005.02042)  
Introduced SROM, a SLAM system for autonomous vehicles that's robust to dynamic environments and fast maneuvers. Combines Phase-Only Correlation and ICP, without relying on IMU/GPS.  
<img src="/images/robotics/srom.png" alt="srom" style="width: 100%; max-width: 800px;">

---

## 📉 Bi-Convex Trajectory Optimization for Non-Holonomic Robots  
**ICRA 2020** • [Paper Link](https://ieeexplore.ieee.org/document/9197092)  
Developed a bi-convex formulation of trajectory optimization for cars and UAVs, leading to faster convergence and better path quality compared to nonlinear solvers.  
<img src="/images/robotics/biconvex.png" alt="biconvex" style="width: 100%; max-width: 800px;">

---

## 🧮 Cosine Meets Softmax: Leveraging Angular Distance for Multiclass Classification  
**ECCV 2020 Workshop** • [Paper Link](https://arxiv.org/pdf/2009.06066)  
Introduced a hybrid classifier combining cosine similarity with softmax cross-entropy. Shows improved performance on imbalanced and fine-grained datasets, especially under low-shot learning settings.  
<img src="/images/robotics/CMSVG.png" alt="cosine-meets-softmax" style="width: 100%; max-width: 800px;">

---

## 🧭 Grounding Linguistic Commands to Navigable Regions  
**IROS 2021** • [Paper Link](https://arxiv.org/pdf/2112.13031)  
Proposed the task of Referring Navigable Regions (RNR) — segmenting areas based on natural language commands like "park next to the yellow sedan." Introduced the Talk2Car-RegSeg dataset and a transformer-based model for language-conditioned planning.  
<img src="/images/robotics/referring_navigable_regions.png" alt="navigable_regions" style="width: 100%; max-width: 800px;">

---

## 🌉 Bridging Sim2Real via Image Gradients for End-to-End Driving  
**NeurIPS 2021 Workshop** • [Paper Link](https://openreview.net/forum?id=lDJzVaEBoCX)  
Improved sim-to-real generalization by using Canny edge features as input to an MLP-Mixer model. Demonstrated transfer on AWS DeepRacer from simulation to real-world track.  
<img src="/images/robotics/sim2real.png" alt="sim2real" style="width: 100%; max-width: 800px;">

---

## 🛡️ Non-Holonomic Collision Avoidance under Uncertainty  
**ECC 2021** • [Paper Link](https://ieeexplore.ieee.org/abstract/document/9655044)  
Formulated an MPC framework using Hilbert space embedding to handle non-parametric noise in state and control. Outperforms Gaussian-based and linearized chance-constrained methods in complex environments.  
<img src="/images/robotics/mmd_obs.png" alt="non-hol coll avoidance" style="width: 100%; max-width: 800px;">

---

## 👁️ Estimating Appearance and Occupancy in BEV  
**ICRA Workshop 2022** • [Paper Link](https://arxiv.org/pdf/2211.04557)  
Combined 360° monocular input to jointly estimate semantic occupancy and appearance in bird’s-eye view. Facilitates end-to-end driving and language-based command grounding.  
<img src="/images/robotics/color_bev.png" alt="color_bev" style="width: 100%; max-width: 800px;">

---

## 🧠 NMR: Neural Manifold Representation for Non-Planar Driving  
**arXiv** • [Paper Link](https://arxiv.org/pdf/2205.05551)  
Proposed a geometry-aware planning system that operates on learned surface manifolds instead of flat BEV grids. Enables accurate trajectory generation on sloped roads using monocular camera input.  
<img src="/images/robotics/neat+surfaces.png" alt="NMR" style="width: 100%; max-width: 800px;">

---

*See full list at [Google Scholar](https://scholar.google.com/citations?user=BTFTmSMAAAAJ&hl=en)*