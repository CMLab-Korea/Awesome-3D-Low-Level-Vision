# Awesome-3D-Low Level Vision
### R<sup>3</sup>eVision: A Survey on Robust Rendering, Restoration, and Enhancement for 3D Low-Level Vision

<p align="center">
  <img src="imgs/image4.png" alt="figure">
</p>



[![awesome](https://img.shields.io/badge/awesome-yes-critical?style=flat&logo=awesome-lists&labelColor=purple)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=CMLab-Korea.CMLab-Korea.Awesome-3D-Low-Level-Vision)](https://github.com/CMLab-Korea/Awesome-3D-Low-Level-Vision)
<!-- TODO: 아래 arxiv 는 논문 공개되면 수정해야 함  -->
<!-- [![arXiv](https://img.shields.io/badge/arXiv-Preprint-b31b1b.svg)](https://arxiv.org/abs/your-paper-id) -->
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC--BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Stars](https://img.shields.io/github/stars/CMLab-Korea/Awesome-3D-Low-Level-Vision.svg?style=social&label=Star)](https://github.com/CMLab-Korea/Awesome-3D-Low-Level-Vision)


This repository provides a curated collection of papers, benchmarks, and resources from our survey:  
**"R3eVision: A Survey on Robust Rendering, Restoration, and Enhancement for 3D Low-Level Vision"** (arXiv2025).

> 📝 **Authors**: Dahyeon Kye, Changhyun Roh, Sukhun Ko, Chanho Eom, Jihyong Oh†

> 🎓 **Institution**: Chung-Ang University, GSAIM  

---

## 📘 Abstract

Video Frame Interpolation (VFI) is a fundamental Low-Level Vision (LLV) task that synthesizes intermediate frames between existing ones while maintaining spatial and temporal coherence. VFI techniques have evolved from classical motion compensation-based approach to deep learning-based approach, including kernel-, flow-, hybrid-, phase-, GAN-, Transformer-, Mamba-, and more recently diffusion model-based approach. We introduce AceVFI, the most comprehensive survey on VFI to date, covering over 250+ papers across these approaches. We systematically organize and describe VFI methodologies, detailing the core principles, design assumptions, and technical characteristics of each approach. We categorize the learning paradigm of VFI methods namely, Center-Time Frame Interpolation (CTFI) and Arbitrary-Time Frame Interpolation (ATFI). We analyze key challenges of VFI such as large motion, occlusion, lighting variation, and non-linear motion. In addition, we review standard datasets, loss functions, evaluation metrics. We examine applications of VFI including event-based, cartoon, medical image VFI and joint VFI with other LLV tasks. We conclude by outlining promising future research directions to support continued progress in the field. This survey aims to serve as a unified reference for both newcomers and experts seeking a deep understanding of modern VFI landscapes.


---

## 📚 Contents

- [📣 News](#-news)
- [🔖 BibTeX](#-bibtex)
- [🔍 Survey Paper](#-survey-paper)
- [📄 Paper List](#-paper-list)
- [📊 Datasets & Benchmarks](#-datasets--benchmarks)
- [📈 Evaluation Metrics](#-evaluation-metrics)

---

## 📣 News

- 📌 2025-xx: Paper released to ArXiv.
- 🚀 2025-xx: Repository initialized.

---

## 🔖 BibTeX

If you find this survey helpful, please consider citing us:

```bitex
not upload yet
```

---

## 🔍 Survey Paper

You can find the preprint of our survey here:  
📄 [arXiv:paper-id](https://arxiv.org/abs/paper-id)


The overview of our survey paper:
![3D-LLV category](./imgs/texanomy.png)

---

## 📄 Paper List

We categorize recent 3D-LLV papers by methodology:  


## 4.Low-Level Vision For Robust 3D Rendering

### 4.1. Super-Resolution (SR) in 3D LLV
### 4.1.1. Predictive Method

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>
<tr>
  <td align="left">
    <a href="https://dl.acm.org/doi/abs/10.1145/3503161.3547808">
      Multi-task View Synthesis with Neural Radiance Fields
    </a>
  </td>
  <td align="center">ACM MM</td>
  <td align="center">2022</td>
<td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2023/html/Huang_RefSR-NeRF_Towards_High_Fidelity_and_Super_Resolution_View_Synthesis_CVPR_2023_paper.html">
      RefSR-NeRF: Towards High Fidelity and Super Resolution View Synthesis
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2023</td>
<td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2023/html/Yoon_Cross-Guided_Optimization_of_Radiance_Fields_With_Multi-View_Image_Super-Resolution_for_CVPR_2023_paper.html">
      Cross-Guided Optimization of Radiance Fields With Multi-View Image Super-Resolution for High-Resolution Novel View Synthesis
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2023</td>
<td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/WACV2024/html/Lin_FastSR-NeRF_Improving_NeRF_Efficiency_on_Consumer_Devices_With_a_Simple_WACV_2024_paper.html">
      FastSR-NeRF: Improving NeRF Efficiency on Consumer Devices With a Simple Super-Resolution Pipeline
    </a>
  </td>
  <td align="center">WACV</td>
  <td align="center">2024</td>
<td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2404.10318">
      SRGS: Super-Resolution 3D Gaussian Splatting
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
<td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2410.02571">
      SuperGS: Super-Resolution 3D Gaussian Splatting Enhanced by Variational Residual Features and Uncertainty-Augmented Learning
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
<td align="center">Image-based</td>
<tr>
  <td align="left">
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32458">
      Sequence Matters: Harnessing Video Models in 3D Super-Resolution
    </a>
  </td>
  <td align="center">AAAI</td>
  <td align="center">2024</td>
<td align="center">Video-based</td>
</tr>

</tr>
</tbody>
</table>

### 4.1.2. Generative-based
### 4.1.2.1. Image-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>

<tr>
  <td align="left">
    <a href="https://ieeexplore.ieee.org/abstract/document/10742507">
      Super-NeRF: View-consistent Detail Generation for NeRF Super-resolution
    </a>
  </td>
  <td align="center">TVCG</td>
  <td align="center">2024</td>
<td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2024/html/Lee_DiSR-NeRF_Diffusion-Guided_View-Consistent_Super-Resolution_NeRF_CVPR_2024_paper.html">
      DiSR-NeRF: Diffusion-Guided View-Consistent Super-Resolution NeRF
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2024</td>
  <td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2406.10111">
      GaussianSR: 3D Gaussian Super-Resolution with 2D Diffusion Priors
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Wan_S2Gaussian_Sparse-View_Super-Resolution_3D_Gaussian_Splatting_CVPR_2025_paper.html">
      S2Gaussian: Sparse-View Super-Resolution 3D Gaussian Splatting
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2025</td>
  <td align="center">Image-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2410.20815">
      Grid4D: 4D Decomposed Hash Encoding for High-Fidelity Dynamic Gaussian Splatting
    </a>
  </td>
  <td align="center">NeurIPS</td>
  <td align="center">2024</td>
  <td align="center">Video-based</td>
</tr>
</tbody>
</table>


### 4.2. Deblurring in 3D LLV
### 4.2.1. Motion Deblurring
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>

<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2023/html/Wang_BAD-NeRF_Bundle_Adjusted_Deblur_Neural_Radiance_Fields_CVPR_2023_paper.html">
      BAD-NeRF: Bundle Adjusted Deblur Neural Radiance Fields
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2023</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Lee_ExBluRF_Efficient_Radiance_Fields_for_Extreme_Motion_Blurred_Images_ICCV_2023_paper.html">
      ExBluRF: Efficient Radiance Fields for Extreme Motion Blurred Images
    </a>
  </td>
  <td align="center">ICCV</td>
  <td align="center">2023</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2024/html/Sun_DyBluRF_Dynamic_Neural_Radiance_Fields_from_Blurry_Monocular_Video_CVPR_2024_paper.html">
      DyBluRF: Dynamic Neural Radiance Fields from Blurry Monocular Video
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2024</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2407.03923">
      CRiM-GS: Continuous Rigid Motion-Aware Gaussian Splatting from Motion-Blurred Images
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2412.06424">
      Deblur4DGS: 4D Gaussian Splatting from Blurry Monocular Video
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2503.05332">
      CoMoGaussian: Continuous Motion-Aware Gaussian Splatting from Motion-Blurred Images
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2025</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Lu_BARD-GS_Blur-Aware_Reconstruction_of_Dynamic_Scenes_via_Gaussian_Splatting_CVPR_2025_paper.html">
      BARD-GS: Blur-Aware Reconstruction of Dynamic Scenes via Gaussian Splatting
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2025</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2504.15122">
      MoBGS: Motion Trajectory-based Dynamic 3D Gaussian Splatting for Blurry Monocular Video
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2025</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://ieeexplore.ieee.org/abstract/document/11017407">
      MoBluRF: Motion Trajectory-based Neural Radiance Fields for Blurry Monocular Video
    </a>
  </td>
  <td align="center">TPAMI</td>
  <td align="center">2025</td>
  <td align="center">Trajectory-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://ieeexplore.ieee.org/abstract/document/10028738">
      E-NeRF: Neural Radiance Fields From a Moving Event Camera
    </a>
  </td>
  <td align="center">IEEE RAL</td>
  <td align="center">2023</td>
  <td align="center">Event-based</td>
</tr>

<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Qi_E2NeRF_Event_Enhanced_Neural_Radiance_Fields_from_Blurry_Images_ICCV_2023_paper.html">
      E2NeRF: Event Enhanced Neural Radiance Fields from Blurry Images
    </a>
  </td>
  <td align="center">ICCV</td>
  <td align="center">2023</td>
  <td align="center">Event-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2024/html/Cannici_Mitigating_Motion_Blur_in_Neural_Radiance_Fields_with_Events_and_CVPR_2024_paper.html">
      Mitigating Motion Blur in Neural Radiance Fields with Events and Frames
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2024</td>
  <td align="center">Event-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2405.20224">
      EvaGaussians: Event Stream Assisted Gaussian Splatting from Blurry Images
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">Event-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2407.13520">
      EaDeblur-GS: Event assisted 3D Deblur Reconstruction with Gaussian Splatting
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">Event-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Lee_DiET-GS_Diffusion_Prior_and_Event_Stream-Assisted_Motion_Deblurring_3D_Gaussian_CVPR_2025_paper.html">
      DiET-GS: Diffusion Prior and Event Stream-Assisted Motion Deblurring 3D Gaussian Splatting
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2025</td>
  <td align="center">Event-based</td>
</tr>

</tbody>
</table>

### 4.2.2. Motion and Defocus Deblurring
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>

</tr>
</thead>
<tbody>

<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2022/html/Ma_Deblur-NeRF_Neural_Radiance_Fields_From_Blurry_Images_CVPR_2022_paper.html">
      Deblur-NeRF: Neural Radiance Fields From Blurry Images
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2022</td>
  <td align="center">Motion & Defocus</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2208.08049">
      PDRF: Progressively Deblurring Radiance Field for Fast and Robust Scene Reconstruction from Blurry Images
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2022</td>
  <td align="center">Motion & Defocus</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2023/html/Lee_DP-NeRF_Deblurred_Neural_Radiance_Field_With_Physical_Scene_Priors_CVPR_2023_paper.html">
      DP-NeRF: Deblurred Neural Radiance Field With Physical Scene Priors
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2023</td>
  <td align="center">Motion & Defocus</td>
</tr>
<tr>
  <td align="left">
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-72989-8_17">
      BAGS: Blur Agnostic Gaussian Splatting Through Multi-scale Kernel Modeling
    </a>
  </td>
  <td align="center">ECCV</td>
  <td align="center">2024</td>
  <td align="center">Motion & Defocus</td>
</tr>
<tr>
  <td align="left">
    <a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07539.pdf">
      Deblurring 3D Gaussian Splatting
    </a>
  </td>
  <td align="center">ECCV</td>
  <td align="center">2024</td>
  <td align="center">Motion & Defocus</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Choi_Exploiting_Deblurring_Networks_for_Radiance_Fields_CVPR_2025_paper.html">
      Exploiting Deblurring Networks for Radiance Fields
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2025</td>
  <td align="center">Motion & Defocus</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2405.17351">
      DOF-GS: Adjustable Depth-of-Field 3D Gaussian Splatting for Post-Capture Refocusing, Defocus Rendering and Blur Removal
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">Defocus</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Lee_CoCoGaussian_Leveraging_Circle_of_Confusion_for_Gaussian_Splatting_from_Defocused_CVPR_2025_paper.html">
      CoCoGaussian: Leveraging Circle of Confusion for Gaussian Splatting from Defocused Images
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2025</td>
  <td align="center">Defocus</td>
</tr>


</tbody>
</table>


### 4.3. Weather Degradation Removal on 3D LLV
### 4.3.1. Pysics-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>

<tr>
  <td align="left">
    <a href="https://ieeexplore.ieee.org/abstract/document/10550844">
      DehazeNeRF: Multi-image Haze Removal and 3D Shape Reconstruction using Neural Radiance Fields
    </a>
  </td>
  <td align="center">3DV</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2304.11448">
      Dehazing-NeRF: Neural Radiance Fields from Hazy Images
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2023</td>
  <td align="center">-</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Ramazzina_ScatterNeRF_Seeing_Through_Fog_with_Physically-Based_Inverse_Neural_Rendering_ICCV_2023_paper.html">
      ScatterNeRF: Seeing Through Fog with Physically-Based Inverse Neural Rendering
    </a>
  </td>
  <td align="center">ICCV</td>
  <td align="center">2023</td>
  <td align="center">-</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2501.03659">
      DehazeGS: Seeing Through Fog with 3D Gaussian Splatting
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2025</td>
  <td align="center">-</td>
</tr>

</tbody>
</table>

### 4.3.2. Detection-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>
<tr>
  <td align="left">
    <a href="https://ieeexplore.ieee.org/abstract/document/10609981">
      DerainNeRF: 3D Scene Estimation with Adhesive Waterdrop Removal
    </a>
  </td>
  <td align="center">ICRA</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>

<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2412.18862">
      WeatherGS: 3D Scene Reconstruction in Adverse Weather Conditions via Gaussian Splatting
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>

</tbody>
</table>

## 4.4. Restoration
### 4.4.1. Reference-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>

<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2023/html/Zhou_NeRFLix_High-Quality_Neural_View_Synthesis_by_Learning_a_Degradation-Driven_Inter-Viewpoint_CVPR_2023_paper.html">
      NeRFLiX: High-Quality Neural View Synthesis by Learning a Degradation-Driven Inter-Viewpoint MiXer
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2023</td>
  <td align="center">-</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2401.03257">
      RustNeRF: Robust Neural Radiance Field with Low-Quality Images
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>
<tr>
  <td align="left">
    <a href="https://link.springer.com/content/pdf/10.1007/978-3-031-72630-9_15.pdf">
      [Title Not Available]
    </a>
  </td>
  <td align="center">ECCV</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2411.11691">
      Towards Degradation-Robust Reconstruction in Generalizable NeRF
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2411.16172">
      U2NeRF: Unsupervised Underwater Image Restoration and Neural Radiance Fields
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>

</tbody>
</table>

### 4.4.2. Generative-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>

<tr>
  <td align="left">
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-72855-6_10">
      RaFE: Generative Radiance Fields Restoration
    </a>
  </td>
  <td align="center">ECCV</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2407.07461">
      Drantal-NeRF: Diffusion-Based Restoration for Anti-aliasing Neural Radiance Field
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">-</td>
</tr>

</tbody>
</table>

## 4.5. Enhancement in 3D LLV
### 4.5.1. Low-light Enhancement
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2022/html/Mildenhall_NeRF_in_the_Dark_High_Dynamic_Range_View_Synthesis_From_CVPR_2022_paper.html">
      NeRF in the Dark: High Dynamic Range View Synthesis From Noisy Raw Images
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2022</td>
  <td align="center">HDR-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32842">
      [Title Not Available]
    </a>
  </td>
  <td align="center">AAAI</td>
  <td align="center">2024</td>
  <td align="center">HDR-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Lighting_up_NeRF_via_Unsupervised_Decomposition_and_Enhancement_ICCV_2023_paper.html">
      Lighting up NeRF via Unsupervised Decomposition and Enhancement
    </a>
  </td>
  <td align="center">ICCV</td>
  <td align="center">2023</td>
  <td align="center">Retinex-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2403.13337">
      Learning Novel View Synthesis from Heterogeneous Low-light Captures
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">Retinex-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-72913-3_18">
      Leveraging Thermal Modality to Enhance Reconstruction in Low-Light Conditions
    </a>
  </td>
  <td align="center">ECCV</td>
  <td align="center">2024</td>
  <td align="center">Retinex-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/27908">
      An Ad-Hoc Interpretable Classifier for 3D Point Clouds
    </a>
  </td>
  <td align="center">AAAI</td>
  <td align="center">2024</td>
  <td align="center">Degradation Modeling-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://link.springer.com/article/10.1007/s11042-024-19699-3">
      Ambient-NeRF: Light Train Enhancing Neural Radiance Fields in Low-Light Conditions with Ambient-Illumination
    </a>
  </td>
  <td align="center">Multimedia Tools and Applications</td>
  <td align="center">2024</td>
  <td align="center">Degradation Modeling-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.15213">
      [Title Not Available]
    </a>
  </td>
  <td align="center">Computer Graphics Forum</td>
  <td align="center">2024</td>
  <td align="center">Degradation Modeling-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2411.06757">
      LuSh-NeRF: Lighting up and Sharpening NeRFs for Low-light Scenes
    </a>
  </td>
  <td align="center">NeurIPS</td>
  <td align="center">2024</td>
  <td align="center">Degradation Modeling-based</td>
</tr>


</tbody>
</table>

### 4.5.2. Detail Enhancement
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/ICCV2021/html/Barron_Mip-NeRF_A_Multiscale_Representation_for_Anti-Aliasing_Neural_Radiance_Fields_ICCV_2021_paper.html">
      Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields
    </a>
  </td>
  <td align="center">ICCV</td>
  <td align="center">2021</td>
  <td align="center">Antialiasing-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2022/html/Barron_Mip-NeRF_360_Unbounded_Anti-Aliased_Neural_Radiance_Fields_CVPR_2022_paper.html">
      Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2022</td>
  <td align="center">Antialiasing-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Barron_Zip-NeRF_Anti-Aliased_Grid-Based_Neural_Radiance_Fields_ICCV_2023_paper.html">
      Zip-NeRF: Anti-Aliased Grid-Based Neural Radiance Fields
    </a>
  </td>
  <td align="center">ICCV</td>
  <td align="center">2023</td>
  <td align="center">Antialiasing-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Hu_Tri-MipRF_Tri-Mip_Representation_for_Efficient_Anti-Aliasing_Neural_Radiance_Fields_ICCV_2023_paper.html">
      Tri-MipRF: Tri-Mip Representation for Efficient Anti-Aliasing Neural Radiance Fields
    </a>
  </td>
  <td align="center">ICCV</td>
  <td align="center">2023</td>
  <td align="center">Antialiasing-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2024/html/Yu_Mip-Splatting_Alias-free_3D_Gaussian_Splatting_CVPR_2024_paper.html">
      Mip-Splatting: Alias-free 3D Gaussian Splatting
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2024</td>
  <td align="center">Antialiasing-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-19824-3_7">
      BungeeNeRF: Progressive Neural Radiance Field for Extreme Multi-scale Scene Rendering
    </a>
  </td>
  <td align="center">ECCV</td>
  <td align="center">2022</td>
  <td align="center">Multi-scale-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/767c1b5f7c03d9299e493bc9e1feeba6-Abstract-Conference.html">
      PyNeRF: Pyramidal Neural Radiance Fields
    </a>
  </td>
  <td align="center">NeurIPS</td>
  <td align="center">2023</td>
  <td align="center">Multi-scale-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/ICCV2023/html/Hu_Multiscale_Representation_for_Real-Time_Anti-Aliasing_Neural_Rendering_ICCV_2023_paper.html">
      Multiscale Representation for Real-Time Anti-Aliasing Neural Rendering
    </a>
  </td>
  <td align="center">ICCV</td>
  <td align="center">2023</td>
  <td align="center">Multi-scale-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2024/html/Yan_Multi-Scale_3D_Gaussian_Splatting_for_Anti-Aliased_Rendering_CVPR_2024_paper.html">
      Multi-Scale 3D Gaussian Splatting for Anti-Aliased Rendering
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2024</td>
  <td align="center">Multi-scale-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/pdf/2503.19232">
      HoGS: Unified Near and Far Object Reconstruction via Homogeneous Gaussian Splatting
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2025</td>
  <td align="center">Multi-scale-based</td>
</tr>


</tbody>
</table>

### 4.5.3. Texture Enhancement
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>

</tr>
</thead>
<tbody>
<tr>
  <td align="left">
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-72980-5_18">
      LATTE3D: Large-scale Amortized Text-To-Enhanced3D Synthesis
    </a>
  </td>
  <td align="center">ECCV</td>
  <td align="center">2024</td>
  <td align="center">Diffusion-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/f0b42291ddab77dcb2ef8a3488301b62-Abstract-Conference.html">
      3DGS-Enhancer: Enhancing Unbounded 3D Gaussian Splatting with View-consistent 2D Diffusion Priors
    </a>
  </td>
  <td align="center">NeurIPS</td>
  <td align="center">2024</td>
  <td align="center">Diffusion-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Luo_3DEnhancer_Consistent_Multi-View_Diffusion_for_3D_Enhancement_CVPR_2025_paper.html">
      3DEnhancer: Consistent Multi-View Diffusion for 3D Enhancement
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2025</td>
  <td align="center">Diffusion-based</td>
</tr>


</tbody>
</table>

### 4.5. Restoration in 3D LLV
#### 4.5.1. Reference-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>

<tr>
  <td align="left">
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-72698-9_3">
      Texture-GS: Disentangling the Geometry and Texture for 3D Gaussian Splatting Editing
    </a>
  </td>
  <td align="center">ECCV</td>
  <td align="center">2024</td>
  <td align="center">Texture modeling-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://arxiv.org/abs/2407.09733">
      Textured-GS: Gaussian Splatting with Spatially Defined Color and Opacity
    </a>
  </td>
  <td align="center">arXiv</td>
  <td align="center">2024</td>
  <td align="center">Texture modeling-based</td>
</tr>
<tr>
  <td align="left">
    <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Chao_Textured_Gaussians_for_Enhanced_3D_Scene_Appearance_Modeling_CVPR_2025_paper.html">
      Textured Gaussians for Enhanced 3D Scene Appearance Modeling
    </a>
  </td>
  <td align="center">CVPR</td>
  <td align="center">2025</td>
  <td align="center">Texture modeling-based</td>
</tr>

</tbody>
</table>

#### 4.5.2. Generative-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>


</tbody>
</table>


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
<th align="center">Tags</th>
</tr>
</thead>
<tbody>


</tbody>
</table>


## 📊 Datasets & Benchmarks 

We include commonly used datasets for evaluating VFI performance.  
Datasets are categorized into **Triplet** and **Multi-frame** types depending on the supervision format.



### 🔹 Triplet Datasets

Early learning-based VFI approaches primarily rely on triplet datasets, where two input frames are used to predict the temporally centered GT frame.

- <a href="https://vision.middlebury.edu/flow/data/" target="_blank"><strong>Middlebury</strong></a>: Originally designed for optical flow, Middlebury contains short video clips with moderate complexity. Its small size limits scalability, but it remains a standard benchmark for consistency evaluation.

- <a href="https://www.crcv.ucf.edu/data/UCF101.php" target="_blank"><strong>UCF101</strong></a>: A human action dataset from which a small subset of triplets is used for VFI. Due to its low resolution and simple motion, it is mainly used for training or sanity checks.

- <a href="http://toflow.csail.mit.edu/" target="_blank"><strong>Vimeo90K</strong></a>: A widely adopted benchmark with diverse scenes and consistent format. It offers clean supervision and balanced motion complexity, making it ideal for comparative analysis.

- <a href="https://myungsub.github.io/CAIN/" target="_blank"><strong>SNU-FILM</strong></a>: Constructed from high-speed footage and categorized by motion difficulty, SNU-FILM enables evaluation across varying levels of motion, occlusion, and blur.

- <a href="https://github.com/lisiyao21/AnimeInterp" target="_blank"><strong>ATD-12K</strong></a>: A large-scale animation dataset with rich stylistic diversity. Its variation in artistic textures and motion patterns supports both general-purpose and domain-specific evaluation.

---

### 🔸 Multi-frame Datasets

Multi-frame datasets enable dense temporal supervision and are commonly used in both CTFI and ATFI settings. They support flexible frame sampling and evaluation under diverse temporal intervals.

- <a href="https://media.xiph.org/video/derf/" target="_blank"><strong>Xiph</strong></a>: A curated set of 4K video sequences designed for assessing interpolation fidelity in subtle motion settings.

- <a href="http://www.cvlibs.net/datasets/kitti/" target="_blank"><strong>KITTI</strong></a>: Captured in autonomous driving scenarios, KITTI poses unique challenges with sparse GT and large ego-motion.

- <a href="http://sintel.is.tue.mpg.de/" target="_blank"><strong>Sintel</strong></a>: A synthetic dataset rendered from the Sintel film, offering photorealistic motion and structured flow annotations.

- <a href="https://davischallenge.org/" target="_blank"><strong>DAVIS</strong></a>: Originally for segmentation, DAVIS features complex object motion, occlusion, and deformation, offering rich dynamics for interpolation.

- <a href="http://www.cs.ubc.ca/labs/imager/tr/2017/DeepVideoDeblurring/" target="_blank"><strong>Adobe240</strong></a>: Collected at 240fps, this dataset captures real-world motion blur and lighting changes, ideal for fine-grained temporal modeling.

- <a href="https://seungjunnah.github.io/Datasets/gopro.html" target="_blank"><strong>GOPRO</strong></a>: Featuring high-frame-rate recordings with handheld cameras, GOPRO provides realistic non-linear motion and defocus blur.

- <a href="https://jianghz.me/projects/superslomo/" target="_blank"><strong>Youtube240</strong></a>: A large-scale, in-the-wild dataset collected from YouTube, encompassing varied content and challenging motion artifacts.

- <a href="https://media.xiph.org/video/derf/" target="_blank"><strong>HD</strong></a>: A subset of high-resolution content from Xiph, with sharper motion content suited for realistic evaluation.

- <a href="https://github.com/JihyongOh/XVFI" target="_blank"><strong>X4K1000FPS</strong></a>: A premier benchmark for ultra-slow motion and long-range interpolation, thanks to its dense 1000fps and 4K capture settings.

- <a href="https://github.com/m-bain/webvid" target="_blank"><strong>WebVid-10M</strong></a>: A large-scale web video corpus originally built for text-video tasks. Its size and diversity support generative VFI when properly filtered.

- <a href="https://alexandrosstergiou.github.io/datasets/LAVIB" target="_blank"><strong>LAVIB</strong></a>: Designed for large-scale, diverse-domain evaluation with balanced splits and curated subsets for out-of-distribution testing.

- <a href="https://github.com/NJU-PCALab/OpenVid-1M" target="_blank"><strong>OpenVid</strong></a>: A text-video dataset supporting multi-modal VFI and DM-based interpolation research via dense, aligned samples.

---

## 📈 Evaluation Metrics

This section summarizes commonly used metrics for evaluating the quality of video frame interpolation (VFI) results.


### 📷 Image-level Metrics

These metrics compare each interpolated frame to its ground truth (GT) reference on a pixel level.

- <a href="https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio" target="_blank"><strong>PSNR (Peak Signal-to-Noise Ratio)</strong></a>  
  Measures reconstruction fidelity via Mean Squared Error (MSE).  
  📌 Higher is better, but it often doesn't align with human perception, especially in high-frequency regions.

- <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1284395" target="_blank"><strong>SSIM (Structural Similarity Index)</strong></a>  
  Compares luminance, contrast, and texture to evaluate structural similarity.  
  📌 More perceptually aligned than PSNR. Higher SSIM indicates stronger similarity.

- <a href="https://link.springer.com/article/10.1007/s11263-010-0390-2" target="_blank"><strong>IE (Interpolation Error)</strong></a>  
  Root-mean-square error between the interpolated and GT frame.  
  📌 Simple and intuitive but limited in perceptual relevance.

---

### 👁️ Perceptual Metrics

These metrics better reflect human perception by analyzing textures, semantics, and style.

- <a href="https://ieeexplore.ieee.org/document/6353522" target="_blank"><strong>NIQE (Natural Image Quality Evaluator)</strong></a>  
  A no-reference metric using statistical deviations from natural images.  
  📌 Lower NIQE implies higher natural image quality.


---

### 🎞️ Video-level Metrics

These metrics evaluate spatiotemporal coherence across video sequences, important for smooth motion and consistency.

- <a href="https://dl.acm.org/doi/pdf/10.1145/3343031.3351028" target="_blank"><strong>VSFA (Video Spatial-Feature Aggregation)</strong></a>  
  No-reference model estimating perceptual quality from human-labeled videos using deep recurrent features.  

