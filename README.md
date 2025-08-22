# Unified 3D Gaussian Splatting for Motion and Defocus Blur Reconstruction

Official implementation of our CAD/Graphics 2025 & Visual Informatics paper.  
[Project Webpage](https://sunbeam-217.github.io/Dual-blur-reconstruction/)




## 🔍 Method Overview

Our method leverages a unified 3D Gaussian representation to jointly model motion blur and defocus blur across multi-view images. The key contributions include:

- We introduce a dual-blur perception module that generates pixel-level blur masks to explicitly mitigate the impact of motion and defocus blur during 3D reconstruction.
- We design a blur-aware Gaussian splatting process that incorporates blur masks for gradient optimization, ensuring accurate modeling and avoiding degraded information.
- We propose a UGR-Opacity adaptive optimization that refines Gaussian representations in under-optimized blurred regions, improving accuracy and quality.

![pipeline](https://sunbeam-217.oss-cn-chengdu.aliyuncs.com/img/202506261356962.png)

## 🎥 Rendering Results

We present several rendering results demonstrating our method's ability to handle motion and defocus blur in 3D Gaussian splatting.

The following videos show rendered results on the left and the input images on the right.

<video src="https://github.com/user-attachments/assets/377de659-3e9f-47ed-b9f6-5821fefa944d" controls width="640"></video>

<video src="https://github.com/user-attachments/assets/86f79308-6970-49d7-8d1f-e2954600b49b" controls width="640"></video>

<video src="https://github.com/user-attachments/assets/75e338ee-7c7e-4935-a1e8-60910ea7ee13" controls width="640"></video>

<video src="https://github.com/user-attachments/assets/0158289b-1163-4f98-b1b4-054e9f72fff1" controls width="640"></video>

<video src="https://github.com/user-attachments/assets/c40cb281-be34-410c-abac-1bda991e4bc1" controls width="640"></video>

## Quick Start

## Limitation

## Acknowledge
This repository is built upon the [BAD-Gaussians](https://github.com/...) framework.  
We sincerely thank the authors for their excellent work and open-source contribution.  
Some file structures and variable names are retained from BAD-Gaussians for implementation consistency.
