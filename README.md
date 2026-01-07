# Awesome NeRFs and 3DGS in Robotics and Underwater
A list of resources to start working with Neural Radiance Fields (NeRFs) and 3D Gaussian Splatting (3DGS). </br>
From foundations to novelty, tailored for Robotics applications and underwater domain. </br>
inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).

## Table of Contents

- [Foundations](#foundations)
- [NeRFs](#neural-radiance-fields)
- [3DGS](#3d-gaussian-splatting)
- [Tools](#tools)

## Foundations 

### The Basics

Basic theory to understand Volumetric Rendering techniques. 

- [The Plenoptic Function and the Elements of Early Vision](https://persci.mit.edu/pub_pdfs/elements91.pdf) <br/>
  Edward H. Adelson and James R. Bergen, Computational models of visual processing (pp. 3–20). The MIT Press. 1991

### Related Works

- [Implicit Neural Representations with Periodic Activation Functions](https://arxiv.org/abs/2006.09661) <br>
  Vincent Sitzmann et el., arxiv Jun. 2020
  
## Neural Radiance Fields

Resources to start understanding and working with NeRFs.

### Papers

[NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf) <br/>
Mildenhall et al., ECCV 2020

<details open>
<summary>Underwater NeRFs</summary>

  - [AquaNeRF: Neural Radiance Fields in Underwater Media with Distractor Removal](https://arxiv.org/abs/2502.16351) <br/>
    Luca Gough et al., arxiv Feb. 2025
    
  - [AONeuS: A Neural Rendering Framework for Acoustic-Optical Sensor Fusion](https://aoneus.github.io/) <br/>
     Mohamad Qadri et al., SIGGRAPH Aug. 2024

  - [SeaThru-NeRF: Neural Radiance Fields in Scattering Media](https://sea-thru-nerf.github.io) <br/>
      Deborah Levy et al., CVPR Apr. 2023

  - [Neural Implicit Surface Reconstruction using Imaging Sonar](https://arxiv.org/abs/2209.08221) <br/>
    Mohamad Qadri et al., arxiv Sep. 2022
</details>

<details open>
<summary>Improvements</summary>
  
</details>

<details open>
<summary>Multi-Modal</summary>

</details>
  
<details open>
<summary>SLAM</summary>

</details>

<details open>
<summary>Semantic</summary>

</details>

### Books' Chapters

### Blog Posts 

### Videos


## 3D Gaussian Splatting

Resources to start understanding and working with 3DGS.

### Papers 
[3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) <br/>
Kerbl et al., ACM Transactions on Graphics 2023

<details open>
<summary>Underwater 3DGS</summary>

  - [SonarSplat: Novel View Synthesis of Imaging Sonar via Gaussian Splatting](https://umfieldrobotics.github.io/sonarsplat3D/) <br/>
    Advaith V. Sethuraman et al., arxiv Nov. 2025

  - [Aqua-Splat: Physically-Informed Sonar-Camera Gaussian Splatting for Underwater 3D Reconstruction](https://ieeexplore.ieee.org/document/11184160) <br/>
    Zijie Ling et al., IEEE Robotics and Automation Letters Sept. 2025

  - [SWAGSplatting: Semantic-guided Water-scene Augmented Gaussian Splatting](https://arxiv.org/abs/2509.00800) <br/>
    Zhuodong Jiang et al., arxiv Aug.2025
    
  - [RUSplatting: Robust 3D Gaussian Splatting for Sparse-View Underwater Scene Reconstruction](https://theflash987.github.io/RUSplatting.page/) <br/>
    Zhuodong Jiang et al., BMVC Aug. 2025

  - [SeaSplat: Representing Underwater Scenes with 3D Gaussian Splatting and a Physically Grounded Image Formation Model](https://seasplat.github.io/) <br/>
    Daniel Yang et al., ICRA Jun. 2025
    
  - [WaterSplatting Fast Underwater 3D Scene Reconstruction Using Gaussian Splatting](https://water-splatting.github.io) <br/>
     Huapeng Li et al., 3DV May 2025

  - [Z-Splat: Z-Axis Gaussian Splatting for Camera-Sonar Fusion](https://arxiv.org/abs/2404.04687) | [github](https://github.com/QuintonQu/gaussian-splatting-with-depth/tree/gaussian-splatting-with-depth-FLS-2) <br/>
      Ziyuan Qu et al., arXiv Jul. 2024
    
</details>

<details open>
<summary>Improvements</summary>
  
</details>

<details open>
<summary>Multi-Modal</summary>

</details>
  
<details open>
<summary>SLAM</summary>

</details>

<details open>
<summary>Semantic</summary>

</details>

### Books' Chapters

### Blog Posts 

### Videos

## Tools

Usefull software tools and code implementation to work with NeRFs and 3DGS.

- **colmap**<br/>
  [github](https://github.com/colmap/colmap)  | [docs](https://colmap.github.io/) <br/>
  Structure from Motion (SfM) pipeline required by radiance fields methods for preliminary camera pose estimation and sparse reconstruction.
  
- **viser**<br/>
  [github](https://github.com/nerfstudio-project/viser)  | [docs](https://viser.studio/main/) <br/>
  3D visualization library for computer vision and robotics in Python.
  
- **nerfstudio**<br/>
  [github](https://github.com/nerfstudio-project/nerfstudio) | [docs](https://docs.nerf.studio/)  <br/>
  Ready to use API to work with NeRFs and 3DGS  

