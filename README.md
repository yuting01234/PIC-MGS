# PIC-MGS: Perception Over Geometry for Mesh Gaussian Splatting

Official implementation of:

**Perception Over Geometry: Rethinking Gaussian Allocation and Optimization in Mesh-based Splatting**


## Overview

PIC-MGS is a Mesh Gaussian Splatting framework designed for high-fidelity rendering and flexible object manipulation.

While existing Gaussian-based representations achieve impressive rendering quality, enabling editable and geometry-aware representations remains challenging. PIC-MGS explores a new direction for combining Gaussian Splatting with mesh structures, achieving both high-quality novel-view synthesis and mesh-driven object editing.


<p align="center">
<img src="assets/teaser.png" width="95%">
</p>


## Highlights

- High-fidelity novel-view synthesis with mesh-aware Gaussian representation.

- Flexible object manipulation with consistent visual appearance.

- Improved representation efficiency compared with existing mesh-based Gaussian methods.

- Supports diverse editing scenarios, including deformation and pose manipulation.


## Results


### Novel View Synthesis

PIC-MGS achieves superior rendering quality on synthetic and real-world benchmarks while maintaining explicit geometric correspondence.


<p align="center">
<img src="assets/static_rendering.png" width="95%">
</p>


### Mesh-driven Manipulation

PIC-MGS enables flexible object editing while preserving appearance details after geometric modifications.


<p align="center">
<img src="assets/manipulation.png" width="95%">
</p>


