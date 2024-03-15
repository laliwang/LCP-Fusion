# LCP-Fusion

Official code implemention for "LCP-Fusion: A Neural Implicit SLAM with Enhanced Local Constraints and Computable Prior". 

# Abstract
Recently the dense Simultaneous Localization and Mapping (SLAM) based on neural implicit representation has shown impressive progress in hole filling and high-fidelity mapping. Nevertheless, existing methods either heavily rely on known scene bounds or suffer inconsistent reconstruction due to drift in potential loop-closure regions, or both, which can be attributed to the inflexible representation and lack of local constraints. In this paper, we present LCP-Fusion, a neural implicit SLAM system with enhanced local constraints and computable prior, which takes the sparse voxel octree structure containing feature grids and SDF priors as hybrid scene representation, enabling the scalability and robustness during mapping and tracking. To enhance the local constraints, we propose a novel sliding window selection strategy based on visual overlap to address the loop-closure, and a practical warping loss to constrain relative poses. Moreover, we estimate SDF priors as coarse initialization for implicit features, which brings additional explicit constraints and robustness, especially when a light but efficient adaptive early ending is adopted. Experiments demonstrate that our method achieve better localization accuracy and reconstruction consistency than existing RGB-D implicit SLAM, especially in challenging real scenes (ScanNet) as well as self-captured scenes with unknown scene bounds.

# Overview
The overview of LCP-Fusion goes as follows:

![image](https://github.com/laliwang/LCP-Fusion/blob/main/Image/Overview.png)

# Code for installation
The full implementation of LCP-Fusion is coming soon !!!
