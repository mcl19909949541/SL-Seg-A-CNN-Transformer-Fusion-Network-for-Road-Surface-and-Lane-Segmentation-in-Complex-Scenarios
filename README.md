# SL-Seg-A-CNN-Transformer-Fusion-Network-for-Road-Surface-and-Lane-Segmentation-in-Complex-Scenarios
Our paper has been accepted by IEEE Transactions on Intelligent Transportation Systems! This is the official project website of our work.

## Overview
Road and lane segmentation is crucial for intelligent transportation systems, especially in traffic video surveillance. However, complex environments—such as diverse geographical terrains, lighting conditions, and occlusions—pose significant challenges to accurate segmentation from a surveillance perspective.
To address these challenges, we propose ​​SL-Seg​​, an end-to-end semantic segmentation network that integrates CNN and Transformer architectures. Our model includes:
1. ​​SP-AttnConv Module​​: A spatial pyramid attention-style convolution module that enhances multi-scale local feature extraction while preserving boundary details.
​​2. Lightweight Multi-Scale (LMS) Module​​: Captures multi-scale features efficiently to handle scale imbalance.
​​3. Occlusion Relief Branch (ORB)​​: Improves feature fusion during decoding to handle occlusions and improve segmentation continuity.
We also introduce the ​​Surface-Lane (SL) dataset​​, the first high-quality road and lane segmentation dataset tailored for complex surveillance scenarios.

## Key Features
​​Dual-branch Architecture​​: Combines global context modeling of Transformers with local feature extraction of CNNs.
​​Multi-scale Processing​​: Lightweight Multi-Scale (LMS) module handles varying road structures and lane scales.
​​Occlusion Handling​​: Specialized Occlusion Relief Branch (ORB) addresses segmentation discontinuities.
​​Real-time Performance​​: Achieves 56.74 FPS with high accuracy on surveillance camera.

## Dataset
We introduce the Surface-Lane (SL) dataset featuring:
1345 high-resolution images (1920×1080).
2685 road annotations + 5416 lane annotations.
Three complex scenarios: Common, Vehicle-intensive, and Tunnel scenes.
Diverse environmental conditions and occlusion challenges.
