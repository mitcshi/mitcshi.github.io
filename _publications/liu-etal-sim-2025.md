---
layout: single-sc
permalink: /publication/liu-etal-sim-2025
author_profile: true
---

<header>
<p style="font-size: 24px;"><b>A graph-theoretic approach to detection of Parkinsonian freezing of gait from videos</b></p>
</header>

Freezing of Gait (FOG) is a prevalent symptom in advanced Parkinson’s Disease (PD), characterized by intermittent transitions between normal gait and freezing episodes. This study introduces a novel graphtheoretic
approach to detect FOG from video data of PD patients. We construct a sequence of pose graphs that represent the spatial relations and temporal progression of a patient’s posture over time. Each graph
node corresponds to an estimated joint position, while the edges reflect the anatomical connections and their proximity. We propose a hypothesis testing procedure that deploys the Fréchet statistics to identify break
points in time between regular gait and FOG episodes, where we model the central tendency and dispersion of the pose graphs in the presentation of graph Laplacian matrices by computing their Fréchet mean and
variance. We implement binary segmentation and incremental computation in our algorithm for efficient calculation. The proposed framework is validated on two datasets, Kinect3D and AlphaPose, demonstrating
its effectiveness in detecting FOG from video data. The proposed approach that extracts matrix features distincts from the prevailing pixel-based deep learning methods. It provides a new perspective on feature
extraction for FOG detection, and potentially contributes to improved diagnosis and treatment of PD.

<p style="font-size: 14px;">Recommended citation: Q. Liu, J. Bao, X. Zhang, C. Shi, C. C. Liu, and R. Luo (2025). A graph-theoretic approach to detection of Parkinsonian freezing of gait from videos. <i>Statistics in Medicine</i>.</p>
