---
layout: page
title: "Research"
permalink: /research/
author_profile: true
---

## Water Treatment
This project focuses on enhancing the efficiency and reliability of compact Reverse Osmosis (RO) systems in nitrate-affected communities. Leveraging **Self-Organizing Maps (SOMs)**, **Reinforcement Learning (RL)**, and **graph neural networks (GATs)**, the system can:
- Detect sensor anomalies and track nonlinear correlations among key water-treatment variables (e.g., turbidity, flow rate, pressure, pH).
- Enable data-driven **predictive control** by adjusting operational parameters (like pressure or coagulant dosing) based on real-time sensor feedback.
- Reduce operational overhead and extend cleaning intervals, lowering overall maintenance costs and improving sustainability.

Funded in part by the U.S. Department of Energy, the California State Department of Water Resources, and the U.S. National Alliance for Water Innovation, this collaborative effort unites researchers from California State University, San Bernardino (CSUSB) and the University of California, Los Angeles (UCLA).


## Cooperative LiDAR Labeling & Data Fusion
In this project, multiple vehicles each equipped with LiDAR, camera, and IMU collect data from different vantage points. We then:
- **Calibrate and align** camera-based and LiDAR-based detections in a shared reference frame using transformation matrices (IMU/GPS, extrinsic calibration).
- Employ **Weighted Boxes Fusion (WBF)** to merge overlapping bounding boxes from various models or sensors (e.g., LiDAR 3D detection, camera 2D/3D detection) into a single, high-confidence result.
- Automate a significant portion of the annotation process, reducing manual labeling effort and enabling large-scale dataset creation.
- Address occlusion and limited visibility scenarios by pooling sensor outputs from multiple vehicles.

This advanced fusion pipeline improves reliability in challenging driving conditions (e.g., unprotected left turns, multi-vehicle interactions) and supports downstream tasks like multi-agent tracking and shared occupancy mapping.



## Dynamic Systems Model of Attention During Meditation
This project explores the **attentional dynamics** involved in a breath-counting meditation practice:
- Implements a **dynamic systems model** with an exponential decay function to simulate the gradual loss of focus during longer breath-counting cycles.
- Maps error likelihood to the model’s current “attention level,” reflecting empirical observations that participants are more prone to mistakes as their attention wanes.
- Calibrates key parameters (decay rates, min/max error thresholds) by comparing simulation outputs to real human data, validating the model’s fit to actual performance trends.
- Provides insights into **cognitive and neuropsychological** mechanisms behind mindfulness exercises, offering a quantifiable way to explore attentional lapses over time.
