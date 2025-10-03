# SL-Seg-A-CNN-Transformer-Fusion-Network-for-Road-Surface-and-Lane-Segmentation-in-Complex-Scenarios
Our paper has been accepted by IEEE Transactions on Intelligent Transportation Systems! This is the official project website of our work.

## Overview
Road and lane segmentation is crucial for intelligent transportation systems, especially in traffic video surveillance. However, complex environments—such as diverse geographical terrains, lighting conditions, and occlusions—pose significant challenges to accurate segmentation from a surveillance perspective.
To address these challenges, we propose ​​SL-Seg​​, an end-to-end semantic segmentation network that integrates CNN and Transformer architectures. Our model includes:

1. ​​SP-AttnConv Module​​: A spatial pyramid attention-style convolution module that enhances multi-scale local feature extraction while preserving boundary details.
2. Lightweight Multi-Scale (LMS) Module​​: Captures multi-scale features efficiently to handle scale imbalance.
3. Occlusion Relief Branch (ORB)​​: Improves feature fusion during decoding to handle occlusions and improve segmentation continuity.


We also introduce the ​​Surface-Lane (SL) dataset​​, the first high-quality road and lane segmentation dataset tailored for complex surveillance scenarios.

## Key Features
The Key Features are following:
1.​​ Dual-branch Architecture​​: Combines global context modeling of Transformers with local feature extraction of CNNs.

2. ​​Multi-scale Processing​​: Lightweight Multi-Scale (LMS) module handles varying road structures and lane scales.
   
3. ​​Occlusion Handling​​: Specialized Occlusion Relief Branch (ORB) addresses segmentation discontinuities.
   

## Dataset
We introduce the Surface-Lane (SL) dataset featuring:
1. 1345 high-resolution images (1920×1080).
   
2. 2685 road annotations + 5416 lane annotations.
   
3. Three complex scenarios: Common, Vehicle-intensive, and Tunnel scenes.
   
4. Diverse environmental conditions and occlusion challenges.

[Baidu Netdisk](https://pan.baidu.com/s/1AGZOMva99J13n3UpdlOF7g)
