# Awesome-Video-Frame-Interpolation
### <img src="https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation/blob/main/media/icon2.png?raw=true" width="20" style="vertical-align: middle;"> AceVFI: A Comprehensive Survey of Advances in Video Frame Interpolation

<p align="center">
  <img src="https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation/blob/main/media/figure.png?raw=true" alt="figure">
</p>



[![awesome](https://img.shields.io/badge/awesome-yes-critical?style=flat&logo=awesome-lists&labelColor=purple)](https://github.com/sindresorhus/awesome)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=CMLab-Korea.Awesome-Video-Frame-Interpolation)](https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation)
[![arXiv](https://img.shields.io/badge/arXiv-Preprint-b31b1b.svg)](https://arxiv.org/abs/2506.01061)
[![Stars](https://img.shields.io/github/stars/CMLab-Korea/Awesome-Video-Frame-Interpolation.svg?style=social&label=Star)](https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation)


This repository provides a curated collection of papers, benchmarks, and resources from our survey:  
**"AceVFI: A Comprehensive Survey of Advances in Video Frame Interpolation"** (arXiv2025).

> 📝 **Authors**: Dahyeon Kye, Changhyun Roh, Sukhun Ko, Chanho Eom, Jihyong Oh†

> 🎓 **Institution**: Chung-Ang University, GSAIM  

---

## 📘 Abstract

Video Frame Interpolation (VFI) is a fundamental Low-Level Vision (LLV) task that synthesizes intermediate frames between existing ones while maintaining spatial and temporal coherence. VFI techniques have evolved from classical motion compensation-based approach to deep learning-based approach, including kernel-, flow-, hybrid-, phase-, GAN-, Transformer-, Mamba-, and more recently diffusion model-based approach. We introduce AceVFI, the most comprehensive survey on VFI to date, covering over 250+ papers across these approaches. We systematically organize and describe VFI methodologies, detailing the core principles, design assumptions, and technical characteristics of each approach. We categorize the learning paradigm of VFI methods namely, Center-Time Frame Interpolation (CTFI) and Arbitrary-Time Frame Interpolation (ATFI). We analyze key challenges of VFI such as large motion, occlusion, lighting variation, and non-linear motion. In addition, we review standard datasets, loss functions, evaluation metrics. We examine applications of VFI including event-based, cartoon, medical image VFI and joint VFI with other LLV tasks. We conclude by outlining promising future research directions to support continued progress in the field. This survey aims to serve as a unified reference for both newcomers and experts seeking a deep understanding of modern VFI landscapes.


---

## 📚 Contents

- [📣 News](#-news)
- [🔖 Citation](#-citation)
- [🔍 Survey Paper](#-survey-paper)
- [📄 Paper List](#-paper-list)
- [📊 Datasets & Benchmarks](#-datasets--benchmarks)
- [📈 Evaluation Metrics](#-evaluation-metrics)

---

## 📣 News

- 📌 2025-06: Paper released to ArXiv.
- 🚀 2025-05: Repository initialized.

---

## 🔖 Citation

If you find this survey helpful, please consider citing us:

```citation
@article{Kye2025AceVFI,
  title={AceVFI: A Comprehensive Survey of Advances in Video Frame Interpolation},
  author={Kye, Dahyeon and Roh, Changhyun and Ko, Sukhun and Eom, Chanho and Oh, Jihyong},
  journal={arXiv preprint arXiv:2506.01061},
  year={2025}
}
```
---

## 🧩 Community Contribution

We welcome contributions from the VFI research community!

If you have a new method, dataset, or related resource that fits within the scope of this VFI repository,
please feel free to submit a pull request (PR) with the following:

A brief description of your method/resource.

Relevant links (e.g., arXiv, project page, code).

Suggested placement (e.g., under “2.3 Diffusion Model-based", "6.4 Joint Task”).

Our maintainers will review your submission and merge it if appropriate.
We hope this page will grow into a collaborative hub for Video Frame Interpolation (VFI) research.

---

## 🔍 Survey Paper

You can find the preprint of our survey here:  
📄 [arXiv:2506.01061](https://arxiv.org/abs/2506.01061)


The overview of our survey paper:
![VFI Categories](https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation/blob/main/media/paper_overview.png)

---


## 📄 Paper List

We categorize recent VFI papers by methodology:  


## 2.1 Motion Compensation-based

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/5440975">Motion-compensated Frame Rate Up-conversion—part Ii: New Algorithms for Frame Interpolation</a></td><td align="center">IEEE Transactions on Broadcasting</td><td align="center">2010</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/5443548">Motion-compensated Frame Rate Up-conversion—part I: Fast Multi-frame Motion Estimation</a></td><td align="center">IEEE Transactions on Broadcasting</td><td align="center">2010</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4480123">A Multistage Motion Vector Processing Method for Motion-compensated Frame Interpolation</a></td><td align="center">IEEE Transactions on Image Processing</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4429281">Motion Compensated Frame Rate Up-conversion Using Extended Bilateral Motion Estimation</a></td><td align="center">IEEE Transactions on Consumer Electronics</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4162523">Motion-compensated Frame Interpolation Using Bilateral Motion Estimation and Adaptive Overlapped Block Motion Compensation</a></td><td align="center">IEEE Transactions on Circuits and Systems for Video Technology</td><td align="center">2007</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/1309458">Motion Compensated Frame Interpolation by New Block-based Motion Estimation Algorithm</a></td><td align="center">IEEE Transactions on Consumer Electronics</td><td align="center">2004</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1037026">Adaptive Motion-compensated Interpolation for Frame Rate Up-conversion</a></td><td align="center">IEEE Transactions on Consumer Electronics</td><td align="center">2002</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=538926">A Method for Motion Adaptive Frame Rate Up-conversion</a></td><td align="center">IEEE Transactions on Circuits and Systems for Video Technology</td><td align="center">1996</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=305878">Motion Compensation Based on Spatial Transformations</a></td><td align="center">IEEE Transactions on Circuits and Systems for Video Technologyy</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=44281">Fractional Frame Rate Up-conversion Using Weighted Median Filters</a></td><td align="center">IEEE Transactions on Consumer Electronics</td><td align="center">1989</td></tr>
</tbody>
</table>


## 2.2 Deep Learning-based

### 2.2.1 Kernel-based

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/abs/2404.11108">LADDER: An Efficient Framework for Video Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/supplemental/Kalluri_FLAVR_Flow-Agnostic_Video_WACV_2023_supplemental.pdf">FLAVR: Flow-agnostic Video Representations for Fast Frame Interpolation</a></td><td align="center">WACV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Zhou_Exploring_Motion_Ambiguity_and_Alignment_for_High-Quality_Video_Frame_Interpolation_CVPR_2023_paper.pdf">Exploring Motion Ambiguity and Alignment for High-quality Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3547660">L2BEC2: Local Lightweight Bidirectional Encoding and Channel Attention Cascade for Video Frame Interpolation</a></td><td align="center">ACM Transactions on Multimedia Computing, Communications and Applications</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2202.07731">Enhancing Deformable Convolution Based Video Frame Interpolation with Coarse-to-fine 3d CNN</a></td><td align="center">ICIP</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/9747182/">Video Frame Interpolation via Local Lightweight Bidirectional Encoding with Channel Attention Cascade</a></td><td align="center">ICASSP</td><td align="center">2022</td></tr>  
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2021/papers/Niklaus_Revisiting_Adaptive_Convolutions_for_Video_Frame_Interpolation_WACV_2021_paper.pdf">Revisiting Adaptive Convolutions for Video Frame Interpolation</a></td><td align="center">WACV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2104.01517">PDWN: Pyramid Deformable Warping Network for Video Interpolation</a></td><td align="center">IEEE Open Journal of Signal Processing</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2008.10680">Video Frame Interpolation via Generalized Deformable Convolution</a></td><td align="center">IEEE Transactions on Multimedia</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9501506">Multiple Video Frame Interpolation via Enhanced Deformable Separable Convolution</a></td><td align="center">IEEE Transactions on Pattern Analysis and Machine Intelligence</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Ding_CDFI_Compression-Driven_Network_Design_for_Frame_Interpolation_CVPR_2021_paper.pdf">CDFI: Compression-Driven Network Design for Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Xiang_Zooming_Slow-Mo_Fast_and_Accurate_One-Stage_Space-Time_Video_Super-Resolution_CVPR_2020_paper.pdf">Zooming Slow-mo: Fast and Accurate One-stage Space-time Video Super-resolution</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Gui_FeatureFlow_Robust_Video_Interpolation_via_Structure-to-Texture_Generation_CVPR_2020_paper.pdf">Featureflow: Robust Video Interpolation via Structure-to-texture Generation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_AdaCoF_Adaptive_Collaboration_of_Flows_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Adacof: Adaptive Collaboration of Flows for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590103.pdf">Bmbc: Bilateral Motion Estimation with Bilateral Cost Volume for Video Interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6634/6634-13-9862-1-10-20200520.pdf">Video Frame Interpolation via Deformable Separable Convolution</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1810.08768">Memc-net: Motion Estimation and Motion Compensation Driven Neural Network for Video Interpolation and Enhancement</a></td><td align="center">IEEE Transactions on Pattern Analysis and Machine Intelligence</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Deformable_ConvNets_V2_More_Deformable_Better_Results_CVPR_2019_paper.pdf">Deformable Convnets v2: More Deformable, Better Results</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Peleg_IM-Net_for_High_Resolution_Video_Frame_Interpolation_CVPR_2019_paper.pdf">IM-Net for High Resolution Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0130.pdf">Context-aware Synthesis for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Niklaus_Video_Frame_Interpolation_CVPR_2017_paper.pdf">Video Frame Interpolation via Adaptive Convolution</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1708.01692">Video Frame Interpolation via Adaptive Separable Convolution</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1702.02463">Video Frame Synthesis Using Deep Voxel Flow</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
</tbody>
</table>



### 2.2.2 Flow-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/abs/2404.11108">LADDER: An Efficient Framework for Video Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Jeong_OCAI_Improving_Optical_Flow_Estimation_by_Occlusion_and_Consistency_Aware_CVPR_2024_paper.pdf">OCAI: Improving Optical Flow Estimation by Occlusion and Consistency Aware Interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_Perception-Oriented_Video_Frame_Interpolation_via_Asymmetric_Blending_CVPR_2024_paper.pdf">Perception-oriented Video Frame Interpolation Via Asymmetric Blending</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/7495fa446f10e9edef6e47b2d327596e-Paper-Conference.pdf">Generalizable Implicit Motion Modeling for Video Frame Interpolation</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04908.pdf">Clearer Frames, Anytime: Resolving Velocity Ambiguity in Video Frame Interpolation</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/papers/Niklaus_Splatting-Based_Synthesis_for_Video_Frame_Interpolation_WACV_2023_paper.pdf">Splatting-based Synthesis for Video Frame Interpolation</a></td><td align="center">WACV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/papers/Jin_Enhanced_Bi-Directional_Motion_Estimation_for_Video_Frame_Interpolation_WACV_2023_paper.pdf">Enhanced Bi-directional Motion Estimation for Video Frame Interpolation</a></td><td align="center">WACV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Park_BiFormer_Learning_Bilateral_Motion_Estimation_via_Bilateral_Transformer_for_4K_CVPR_2023_paper.pdf">BiFormer: Learning Bilateral Motion Estimation Via Bilateral Transformer for 4k Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Jin_A_Unified_Pyramid_Recurrent_Network_for_Video_Frame_Interpolation_CVPR_2023_paper.pdf">A Unified Pyramid Recurrent Network for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Li_AMT_All-Pairs_Multi-Field_Transforms_for_Efficient_Frame_Interpolation_CVPR_2023_paper.pdf">AMT: All-pairs Multi-field Transforms for Efficient Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Extracting_Motion_and_Appearance_via_Inter-Frame_Attention_for_Efficient_Video_CVPR_2023_paper.pdf">Extracting Motion and Appearance Via Inter-frame Attention for Efficient Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136740608.pdf">Real-time Intermediate Flow Estimation for Video Frame Interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750509.pdf">Learning Cross-video Neural Representations for High-quality Frame Interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2202.04901">FILM: Frame Interpolation for Large Motion</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_Many-to-Many_Splatting_for_Efficient_Video_Frame_Interpolation_CVPR_2022_paper.pdf">Many-to-many Splatting for Efficient Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Kong_IFRNet_Intermediate_Feature_Refine_Network_for_Efficient_Frame_Interpolation_CVPR_2022_paper.pdf">IfRNet: Intermediate Feature Refine Network for Efficient Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9328265">Video Frame Interpolation via Generalized Deformable Convolution</a></td><td align="center">IEEE Transactions on Multimedia</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Sim_XVFI_eXtreme_Video_Frame_Interpolation_ICCV_2021_paper.pdf">XVFI: Extreme Video Frame Interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Park_Asymmetric_Bilateral_Motion_Estimation_for_Video_Frame_Interpolation_ICCV_2021_paper.pdf">Asymmetric Bilateral Motion Estimation for Video Frame Interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2021/papers/Niklaus_Revisiting_Adaptive_Convolutions_for_Video_Frame_Interpolation_WACV_2021_paper.pdf">Revisiting Adaptive Convolutions for Video Frame Interpolation</a></td><td align="center">WACV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720103.pdf">All at Once: Temporally Adaptive Multi-frame Interpolation with Advanced Motion Modeling</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590103.pdf">Bmbc: Bilateral Motion Estimation with Bilateral Cost Volume for Video Interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Gui_FeatureFlow_Robust_Video_Interpolation_via_Structure-to-Texture_Generation_CVPR_2020_paper.pdf">Featureflow: Robust Video Interpolation via Structure-to-texture Generation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Niklaus_Softmax_Splatting_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Softmax Splatting for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2009.04642">Enhanced Quadratic Video Interpolation</a></td><td align="center">ECCV Workshops</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700477.pdf">A Flexible Recurrent Residual Pyramid Network for Video Frame Interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1810.08768">Memc-net: Motion Estimation and Motion Compensation Driven Neural Network for Video Interpolation and Enhancement</a></td><td align="center">IEEE Transactions on Pattern Analysis and Machine Intelligence</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1609/aaai.v33i01.33018794">Deep Video Frame Interpolation Using Cyclic Frame Generation</a></td><td align="center">AAAI</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Yuan_Zoom-In-To-Check_Boosting_Video_Interpolation_via_Instance-Level_Discrimination_CVPR_2019_paper.pdf">Zoom-in-to-check: Boosting Video Interpolation Via Instance-level Discrimination</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Reda_Unsupervised_Video_Interpolation_Using_Cycle_Consistency_ICCV_2019_paper.pdf">Unsupervised Video Interpolation Using Cycle Consistency</a></td><td align="center">ICCV</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper/2019/file/d045c59a90d7587d8d671b5f5aec4e7c-Paper.pdf">Quadratic Video Interpolation</a></td><td align="center">NeurIPS</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0130.pdf">Context-aware Synthesis for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
</tbody>
</table>


### 2.2.3 Kernel- and Flow-based Combined
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Danier_ST-MFNet_A_Spatio-Temporal_Multi-Flow_Network_for_Frame_Interpolation_CVPR_2022_paper.pdf">St-mfnet: A Spatio-temporal Multi-flow Network for Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2021/papers/Niklaus_Revisiting_Adaptive_Convolutions_for_Video_Frame_Interpolation_WACV_2021_paper.pdf">Revisiting Adaptive Convolutions for Video Frame Interpolation</a></td><td align="center">WACV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Gui_FeatureFlow_Robust_Video_Interpolation_via_Structure-to-Texture_Generation_CVPR_2020_paper.pdf">FeatureFlow: Robust Video Interpolation Via Structure-to-texture Generation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_AdaCoF_Adaptive_Collaboration_of_Flows_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">AdaCoF: Adaptive Collaboration of Flows for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590103.pdf">BMBC: Bilateral Motion Estimation with Bilateral Cost Volume for Video Interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Yuan_Zoom-In-To-Check_Boosting_Video_Interpolation_via_Instance-Level_Discrimination_CVPR_2019_paper.pdf">Zoom-in-to-check: Boosting Video Interpolation Via Instance-level Discrimination</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Bao_Depth-Aware_Video_Frame_Interpolation_CVPR_2019_paper.pdf">Depth-aware Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf/3ae72db22e8443112a8e7e61a943c8044053e135.pdf">MEMC-Net: Motion Estimation and Motion Compensation Driven Neural Network for Video Interpolation and Enhancement</a></td><td align="center">IEEE Transactions on Pattern Analysis and Machine Intelligence</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0130.pdf">Context-aware Synthesis for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1702.02463">Video Frame Synthesis Using Deep Voxel Flow</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
</tbody>
</table>


### 2.2.4 Phase-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Meyer_PhaseNet_for_Video_CVPR_2018_paper.pdf">PhaseNet for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2015/papers/Meyer_Phase-Based_Frame_Interpolation_2015_CVPR_paper.pdf">Phase-based Frame Interpolation for Video</a></td><td align="center">CVPR</td><td align="center">2015</td></tr>
</tbody>
</table>

### 2.2.5 GAN-based

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Danier_ST-MFNet_A_Spatio-Temporal_Multi-Flow_Network_for_Frame_Interpolation_CVPR_2022_paper.pdf">ST-MFNet: A Spatio-temporal Multi-flow Network for Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.sciencedirect.com/science/article/pii/S1077314222000546">Video Frame Interpolation via Down--up Scale Generative Adversarial Networks</a></td><td align="center">Computer Vision and Image Understanding</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9097443">Multi-scale Attention Generative Adversarial Networks for Video Frame Interpolation</a></td><td align="center">IEEE Access</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.mdpi.com/2076-3417/10/18/6245">Efficient Video Frame Interpolation Using Generative Adversarial Networks</a></td><td align="center">Applied Sciences</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.sciencedirect.com/science/article/pii/S0925231219315747">Frame-GAN: Increasing the Frame Rate of Gait Videos with Generative Adversarial Networks</a></td><td align="center">Neurocomputing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_AdaCoF_Adaptive_Collaboration_of_Flows_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">AdaCoF: Adaptive Collaboration of Flows for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Yuan_Zoom-In-To-Check_Boosting_Video_Interpolation_via_Instance-Level_Discrimination_CVPR_2019_paper.pdf">Zoom-in-to-check: Boosting Video Interpolation Via Instance-level Discrimination</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/8451971">Generating Realistic Videos From Keyframes with Concatenated Gans</a></td><td align="center">IEEE Transactions on Circuits and Systems for Video Technology</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1711.06045">Frame Interpolation with Multi-scale Deep Loss Functions and Generative Adversarial Networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="http://vision.stanford.edu/teaching/cs231n/reports/2017/pdfs/317.pdf">Frame Interpolation Using Generative Adversarial Networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
</tbody>
</table>


### 2.2.6 Transformer-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.15831">EDEN: Enhanced Diffusion for High-quality Large-motion Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Sparse_Global_Matching_for_Video_Frame_Interpolation_with_Large_Motion_CVPR_2024_paper.pdf">Sparse Global Matching for Video Frame Interpolation with Large Motion</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.05953">Frame Interpolation with Consecutive Brownian Bridge Diffusion</a></td><td align="center">ACM CM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Extracting_Motion_and_Appearance_via_Inter-Frame_Attention_for_Efficient_Video_CVPR_2023_paper.pdf">Extracting Motion and Appearance via Inter-frame Attention for Efficient Video Frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Li_AMT_All-Pairs_Multi-Field_Transforms_for_Efficient_Frame_Interpolation_CVPR_2023_paper.pdf">Amt: All-pairs Multi-field Transforms for Efficient Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Park_BiFormer_Learning_Bilateral_Motion_Estimation_via_Bilateral_Transformer_for_4K_CVPR_2023_paper.pdf">Biformer: Learning Bilateral Motion Estimation via Bilateral Transformer for 4k Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3547660">L2bec2: Local Lightweight Bidirectional Encoding and Channel Attention Cascade for Video Frame Interpolation</a></td><td align="center">ACM Transactions on Multimedia Computing, Communications and Applications</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2207.09048">TTVFI: Learning Trajectory-aware Transformer for Video Frame Interpolation</a></td><td align="center">IEEE Transactions on Image Processing</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Lu_Video_Frame_Interpolation_With_Transformer_CVPR_2022_paper.pdf">Video Frame Interpolation with Transformer</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Shi_Video_Frame_Interpolation_Transformer_CVPR_2022_paper.pdf">Video Frame Interpolation Transformer</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6693/6693-13-9922-1-10-20200521.pdf">Channel Attention Is All You Need for Video Frame Interpolation</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
</tbody>
</table>




### 2.2.7 Mamba-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Jeong_LC-Mamba_Local_and_Continuous_Mamba_with_Shifted_Windows_for_Frame_CVPR_2025_paper.pdf">LC-Mamba: Local and Continuous Mamba with Shifted Windows
for Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/c1e9db5e1b04322963af91ac0c943568-Paper-Conference.pdf">VFIMamba: Video Frame Interpolation with State Space Models</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
</tbody>
</table>

### 2.2.8 Optimization-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2306.13933">Boost Video Frame Interpolation via Motion Adaptation</a></td><td align="center">BMVC</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Choi_Scene-Adaptive_Video_Frame_Interpolation_via_Meta-Learning_CVPR_2020_paper.pdf">Scene-Adaptive Video Frame Interpolation via Meta-Learning</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
</tbody>
</table>

## 2.3 Diffusion Model-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2505.21205">Sci-Fi: Symmetric Constraint for Frame Inbetweening</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2406.17256">Disentangled Motion Modeling for Video Frame Interpolation</a></td><td align="center">AAAI</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2506.03119">Controllable Human-centric Keyframe Interpolation with Generative Prior</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.03699">Motion-aware Generative Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.15831">EDEN: Enhanced Diffusion for High-quality Large-motion Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Hai_Hierarchical_Flow_Diffusion_for_Efficient_Frame_Interpolation_CVPR_2025_paper.pdf">Hierarchical Flow Diffusion for Efficient Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2408.15239">Generative Inbetweening: Adapting Image-to-video Models for Keyframe Interpolation</a></td><td align="center">ICLR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.11755">Generative Inbetweening Through Frame-wise Conditions-driven Video Generation</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.05651">VIBIDSAMPLER: Enhancing Video Interpolation Using Bidirectional Diffusion Sampler</a></td><td align="center">ICLR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2303.09508">LDMVFI: Video Frame Interpolation with Latent Diffusion Models</a></td><td align="center">AAAI</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Jain_Video_Interpolation_with_Diffusion_Models_CVPR_2024_paper.pdf">Video Interpolation with Diffusion Models</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=u0geEr7X2O">Motion-aware Latent Diffusion Models for Video Frame Interpolation</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2409.09605">DreamMover: Leveraging the Prior of Diffusion Models for Image Interpolation with Large Motion</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2403.14611">Explorative Inbetweening of Time and Space</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/abs/2405.05953">Frame Interpolation with Consecutive Brownian Bridge Diffusion</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/944618542d80a63bbec16dfbd2bd689a-Paper-Conference.pdf">MCVD-masked Conditional Video Diffusion for Prediction, Generation, and Interpolation</a></td><td align="center">NeurIPS</td><td align="center">2022</td></tr>
</tbody>
</table>



## 3.4 Loss Functions

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Sim_XVFI_eXtreme_Video_Frame_Interpolation_ICCV_2021_paper.pdf">XVFI: Extreme Video Frame Interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Jiang_Super_SloMo_High_CVPR_2018_paper.pdf">Super SloMo: High Quality Estimation of Multiple Intermediate Frames for Video Interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1711.07837">UnFlow: Unsupervised Learning of Optical Flow with a Bidirectional Census Loss</a></td><td align="center">AAAI</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1707.05776">Optimizing the Latent Space of Generative Networks</a></td><td align="center">ICLR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1702.02463">Video Frame Synthesis Using Deep Voxel Flow</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1511.05440">Deep Multi-scale Video Prediction Beyond Mean Square Error</a></td><td align="center">ICLR</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=413553">Two Deterministic Half-quadratic Regularization Algorithms for Computed Imaging</a></td><td align="center">ICIP</td><td align="center">1994</td></tr>
</tbody>
</table>





## 5.1 Datasets

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/333f81766b242b1837fa65c2172afb76-Paper-Datasets_and_Benchmarks_Track.pdf">LAVIB: A Large-scale Video Interpolation Benchmark</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2407.02371">OPENVID-1M: A Large-scale High-quality Dataset for Text-to-video Generation</a></td><td align="center">ICLR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Siyao_Deep_Animation_Video_Interpolation_in_the_Wild_CVPR_2021_paper.pdf">Deep animation video interpolation in the wild</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Bain_Frozen_in_Time_A_Joint_Video_and_Image_Encoder_for_ICCV_2021_paper.pdf">Frozen in Time: A Joint Video and Image Encoder for End-to-end Retrieval</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Sim_XVFI_eXtreme_Video_Frame_Interpolation_ICCV_2021_paper.pdf">XVFI: Extreme Video Frame Interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Niklaus_Softmax_Splatting_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Softmax Splatting for Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6693/6693-13-9922-1-10-20200521.pdf">Channel Attention Is All You Need for Video Frame Interpolation</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf/3ae72db22e8443112a8e7e61a943c8044053e135.pdf">MEMC-Net: Motion Estimation and Motion Compensation Driven Neural Network for Video Interpolation and Enhancement</a></td><td align="center">IEEE Transactions on Pattern Analysis and Machine Intelligence</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1711.09078">Video enhancement with task-oriented flow</a></td><td align="center">International Journal of Computer Vision</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Su_Deep_Video_Deblurring_CVPR_2017_paper.pdf">Deep Video Deblurring for Hand-held Cameras</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Nah_Deep_Multi-Scale_Convolutional_CVPR_2017_paper.pdf">Deep Multi-scale Convolutional Neural Network for Dynamic Scene Deblurring</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1702.02463">Video Frame Synthesis Using Deep Voxel Flow</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Perazzi_A_Benchmark_Dataset_CVPR_2016_paper.pdf">A Benchmark Dataset and Evaluation Methodology for Video Object Segmentation</a></td><td align="center">CVPR</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1212.0402">UCF101: A Dataset of 101 Human Actions Classes From Videos in the Wild</a></td><td align="center">CRCV</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://www.cvlibs.net/publications/Geiger2012CVPR.pdf">Are We Ready for Autonomous Driving? the Kitti Vision Benchmark Suite</a></td><td align="center">CVPR</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://files.is.tue.mpg.de/black/papers/ButlerECCV2012.pdf">A Naturalistic Open Source Movie for Optical Flow Evaluation</a></td><td align="center">ECCV</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4408903">A Database and Evaluation Methodology for Optical Flow</a></td><td align="center">International Journal of Computer Vision</td><td align="center">2011</td></tr>
<tr><td align="left"><a href="https://media.xiph.org/video/derf/">Xiph.org Video Test Media (derf's Collection)</a></td><td align="center"></td><td align="center">1994</td></tr>
</tbody>
</table>



## 5.3 Evaluation Metrics

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Huang_VBench_Comprehensive_Benchmark_Suite_for_Video_Generative_Models_CVPR_2024_paper.pdf">Vbench: Comprehensive Benchmark Suite for Video Generative Models</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf/798d301795f1200b0ee8c8ea5de15169a1da49d2.pdf">Frechet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos</a></td><td align="center">ICML Workshop</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2207.08119">FloLPIPS: A Bespoke Video Quality Metric for Frame Interpolation</a></td><td align="center">Picture Coding Symposium</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136780089.pdf">Shift-tolerant Perceptual Similarity Metric</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9298952">Image Quality Assessment: Unifying Structure and Texture Similarity</a></td><td align="center">IEEE Transactions on Pattern Analysis and Machine Intelligence</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3386569.3392457">Learning Temporal Coherence via Self-supervision for GAN-based Video Generation</a></td><td align="center">ACM Transactions on Graphics</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3343031.3351028">Quality Assessment of In-the-wild Videos</a></td><td align="center">ACM MM</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1812.01717">Towards Accurate Generative Models of Video: A New Metric & Challenges</a></td><td align="center">ICLR Workshop</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.pdf">The Unreasonable Effectiveness of Deep Features as a Perceptual Metric</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/8a1d694707eb0fefe65871369074926d-Paper.pdf">GANs Trained by a Two Time-scale Update Rule Converge to a Local Nash Equilibrium</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6353522">Making a “completely Blind” Image Quality Analyzer</a></td><td align="center">IEEE Signal Processing Letters</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://vision.middlebury.edu/flow/floweval-ijcv2011.pdf">A database and evaluation methodology for optical flow</a></td><td align="center">International Journal of Computer Vision</td><td align="center">2011</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1284395">Image Quality Assessment: From Error Visibility to Structural Similarity</a></td><td align="center">IEEE Transactions on Image Processing</td><td align="center">2004</td></tr>
</tbody>
</table>


## 6. Applications

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.20218">Video Motion Graphs</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.01715">KeyFace: Expressive Audio-driven Facial Animation for Long Sequences Via Keyframe Interpolation</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.04221">TANGO: Co-speech Gesture Video Reenactment with Hierarchical Audio Motion Embedding and Diffusion Interpolation</a></td><td align="center">ICLR</td><td align="center">2025</td></tr>  
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/10647865">Real-time Video Prediction with Fast Video Interpolation Model and Prediction Training</a></td><td align="center">ICIP</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2024/papers/Huang_Scale-Adaptive_Feature_Aggregation_for_Efficient_Space-Time_Video_Super-Resolution_WACV_2024_paper.pdf">Scale-adaptive Feature Aggregation for Efficient Space-time Video Super-resolution</a></td><td align="center">WACV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11464711&googleIPSandBox=false&mark=0&minRead=10&ipRange=false&b2cLoginYN=false&icstClss=010000&isPDFSizeAllowed=true&accessgl=Y&language=en_US&hasTopBanner=true">Dynamic Framerate Slowfast Network for Improving Autonomous Driving Performance</a></td><td align="center">IEIE Transactions on Smart Processing & Computing</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2210.00823">BVI-VFI: a Video Quality Database for Video Frame Interpolation</a></td><td align="center">IEEE Transactions on Image Processing</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3633780">Neighbor Correspondence Matching for Flow-based Video Frame Synthesis</a></td><td align="center">Proceedings of the 30th ACM International Conference on Multimedia</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750231.pdf">A Perceptual Quality Metric for Video Frame Interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Neural_Scene_Flow_Fields_for_Space-Time_View_Synthesis_of_Dynamic_CVPR_2021_paper.pdf">Neural Scene Flow Fields for Space-time View Synthesis of Dynamic Scenes</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Xiang_Zooming_Slow-Mo_Fast_and_Accurate_One-Stage_Space-Time_Video_Super-Resolution_CVPR_2020_paper.pdf">Zooming Slow-Mo: Fast and Accurate One-stage Space-time Video Super-resolution</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE09307292">Compressed Video Restoration Using a Generative Adversarial Network for Subjective Quality Enhancement</a></td><td align="center">IEIE Transactions on Smart Processing & Computing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="http://toflow.csail.mit.edu/toflow_ijcv.pdf">Video Enhancement with Task-oriented Flow</a></td><td align="center">International Journal of Computer Vision</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ECCV_2018/papers/Chao-Yuan_Wu_Video_Compression_through_ECCV_2018_paper.pdf">Video Compression Through Image Interpolation</a></td><td align="center">ECCV</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Jiang_Super_SloMo_High_CVPR_2018_paper.pdf">Super SloMo: High Quality Estimation of Multiple Intermediate Frames for Video Interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1605.03557">View Synthesis by Appearance Flow</a></td><td align="center">ECCV</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/Flynn_DeepStereo_Learning_to_CVPR_2016_paper.pdf">DeepStereo: Learning to Predict New Views From the World's Imagery</a></td><td align="center">CVPR</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/790301/">Prediction Error as a Quality Metric for Motion and Stereo</a></td><td align="center">ICCV</td><td align="center">1999</td></tr>
</tbody>
</table>


## 6.1 Event-based VFI

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2505.03116">TimeTracker: Event-based Continuous Point Tracking for Video Frame Interpolation with Non-linear Motion</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.20268">EGVD: Event-guided Video Diffusion Model for Physically Realistic Large-motion Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.22491">Coupled Video Frame Interpolation and Encoding with Hybrid Event Cameras for Low-power High-framerate Video</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.07761">Repurposing Pre-trained Video Diffusion Models for Event-based Video Interpolation</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>  
<tr><td align="left"><a href="https://arxiv.org/pdf/2309.08891">V2CE: Video to Continuous Events Simulator</a></td><td align="center">ICRA</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Video_Frame_Interpolation_via_Direct_Synthesis_with_the_Event-based_Reference_CVPR_2024_paper.pdf">Video Frame Interpolation Via Direct Synthesis with the Event-based Reference</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/11208.pdf">TimeLens-XL: Real-time Event-based Video Frame Interpolation with Large Motion</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_Event-Based_Video_Frame_Interpolation_With_Cross-Modal_Asymmetric_Bidirectional_Motion_Fields_CVPR_2023_paper.pdf">Event-based Video Frame Interpolation with Cross-modal Asymmetric Bidirectional Motion Fields</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3581783.3612093">Event-guided Frame Interpolation and Dynamic Range Expansion of Single Rolling Shutter Image</a></td><td align="center">ACM MM</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Unifying_Motion_Deblurring_and_Frame_Interpolation_With_Events_CVPR_2022_paper.pdf">Unifying Motion Deblurring and Frame Interpolation with Events</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2203.17191">Time Lens++: Event-based Frame Interpolation with Parametric Non-linear Flow and Multi-scale Fusion</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/He_TimeReplayer_Unlocking_the_Potential_of_Event_Cameras_for_Video_Interpolation_CVPR_2022_paper.pdf">TimeReplayer: Unlocking the Potential of Event Cameras for Video Interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670261.pdf">Video Interpolation by Event-driven Anisotropic Adjustment of Optical Flow</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Tulyakov_Time_Lens_Event-Based_Video_Frame_Interpolation_CVPR_2021_paper.pdf">Time Lens: Event-based Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1912.01584">EventGAN: Leveraging Large Scale Image Datasets for Event Cameras</a></td><td align="center">ICCP</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_Training_Weakly_Supervised_Video_Frame_Interpolation_With_Events_ICCV_2021_paper.pdf">Training Weakly Supervised Video Frame Interpolation with Events</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123530681.pdf">Learning Event-driven Video Deblurring and Interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ICCVW_2019/papers/PBDL/Wang_Event-Driven_Video_Frame_Synthesis_ICCVW_2019_paper.pdf">Event-driven Video Frame Synthesis</a></td><td align="center">ICCV Workshop</td><td align="center">2019</td></tr
</tbody>
</table>


## 6.2 Cartoon VFI


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.16550">PhysAnimator: Physics-guided Generative Cartoon Animation</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2504.05402">Time-adaptive Video Frame Interpolation Based on Residual Diffusion</a></td><td align="center">SIGGRAPH</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.11838">High-resolution Frame Interpolation with Patch-based Cascaded Diffusion</a></td><td align="center">AAAI</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.08295">LayerAnimate : Layer-specific Control for Animation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=Lp40Z40N07">FRAMER: Interactive Frame Interpolation</a></td><td align="center">ICLR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.14173">AniDoc: Animation Creation Made Easier</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>  
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.17933">ToonCrafter: Generative Cartoon Interpolation</a></td><td align="center">SIGGRAPH</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06298.pdf">DynamiCrafter: Animating Open-domain Images with Video Diffusion Priors</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Siyao_Deep_Geometrized_Cartoon_Line_Inbetweening_ICCV_2023_paper.pdf">Deep Sketch-guided Cartoon Video Inbetweening</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136770275.pdf">Improving the Perceptual Quality of 2d Animation Interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Siyao_Deep_Animation_Video_Interpolation_in_the_Wild_CVPR_2021_paper.pdf">Deep Animation Video Interpolation in the Wild</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
</tbody>
</table>

## 6.3 Medical Image VFI


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Kim_Data-Efficient_Unsupervised_Interpolation_Without_Any_Intermediate_Frame_for_4D_Medical_CVPR_2024_paper.pdf">Data-efficient Unsupervised Interpolation Without Any Intermediate Frame for 4d Medical Images</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.15385">CPT-Interp: Continuous Spatial and Temporal Motion Modeling for 4d Medical Image Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_A_Spatiotemporal_Volumetric_Interpolation_Network_for_4D_Dynamic_Medical_Image_CVPR_2020_paper.pdf">A Spatiotemporal Volumetric Interpolation Network for 4d Dynamic Medical Image</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
</tbody>
</table>



## 6.4 Joint Task 

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Zhang_Continuous_Space-Time_Video_Resampling_with__Invertible_Motion_Steganography_CVPR_2025_paper.pdf">Continuous Space-Time Video Resampling with
Invertible Motion Steganography</a></td><td align="center">CVPR</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Latency_Correction_for_Event-guided_Deblurring_and_Frame_Interpolation_CVPR_2024_paper.pdf">Latency Correction for Event-guided Deblurring and Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_MoTIF_Learning_Motion_Trajectories_with_Local_Implicit_Neural_Functions_for_ICCV_2023_paper.pdf">MoTIF: Learning Motion Trajectories with Local Implicit Neural Functions for Continuous Space-time Video Super-resolution</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Shang_Joint_Video_Multi-Frame_Interpolation_and_Deblurring_Under_Unknown_Exposure_Time_CVPR_2023_paper.pdf">Joint Video Multi-frame Interpolation and Deblurring Under Unknown Exposure Time</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136790588.pdf">Animation From Blur: Multi-modal Blur Decomposition with Motion Guidance</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670193.pdf">DeMFI: Deep Joint Deblurring and Multi-frame Interpolation with Flow-guided Attentive Correlation and Recursive Boosting</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Temporal_Modulation_Network_for_Controllable_Space-Time_Video_Super-Resolution_CVPR_2021_paper.pdf">Temporal Modulation Network for Controllable Space-time Video Super-resolution</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6788/6788-13-10017-1-10-20200522.pdf">FISR: Deep Joint Frame Interpolation and Super-resolution with a Multi-scale Temporal Loss</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Haris_Space-Time-Aware_Multi-Resolution_Video_Enhancement_CVPR_2020_paper.pdf">Space-time-aware Multi-resolution Video Enhancement</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper/2020/file/9a11883317fde3aef2e2432a58c86779-Paper.pdf">Video Frame Interpolation Without Temporal Priors</a></td><td align="center">NeurIPS</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9257179">Video Frame Interpolation and Enhancement Via Pyramid Recurrent Framework</a></td><td align="center">IEEE Transactions on Image Processing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Shen_Blurry_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Blurry Video Frame Interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.cvl.iis.u-tokyo.ac.jp/class2013/2013w/paper/time-varyingImageProcessing/Increasing_Space-Time_Resolution_in_Video_(ECCV02).pdf">Increasing Space-time Resolution in Video</a></td><td align="center">ECCV</td><td align="center">2002</td></tr>
</tbody>
</table>





## 📊 Datasets & Benchmarks 

We include commonly used datasets for evaluating VFI performance.  
Datasets are categorized into **Triplet** and **Multi-frame** types depending on the supervision format.

### 🔹 Triplet Datasets

Early learning-based VFI approaches primarily rely on triplet datasets, where two input frames are used to predict the temporally centered GT frame.


| Dataset    | Venue   | Type | Resolution                | Split        | #Videos / #Triplets | URL                                           |
| ---------- | ------- | ---- | ------------------------- | ------------ | ------------------- | --------------------------------------------- |
| Middlebury  | IJCV'11   | 🔹 T | ≤ 640×480 (VGA)         | test         | 12                  | [🔗](https://vision.middlebury.edu/flow/data/) |
| UCF101     | CRCV'12 | 🔹 T  | 256×256                   | test         | 379                 | [🔗](https://www.crcv.ucf.edu/data/UCF101.php) |
| Vimeo90K   | IJCV'19 | 🔹 T  | 448×256                   | train / test | 51,312 / 3,782      | [🔗](http://toflow.csail.mit.edu/)             |
| SNU-FILM   | AAAI'20 | 🔹 T  | ≤ 1280×720 (HD)           | test         | 1,240               | [🔗](https://myungsub.github.io/CAIN/)         |
| ATD-12K    | CVPR'21 | 🔹 T  | 1280×720, 1920×1080 (FHD) | train / test | 10,000 / 2,000      | [🔗](https://github.com/lisiyao21/AnimeInterp) |

---

### 🔸 Multi-frame Datasets

Multi-frame datasets enable dense temporal supervision and are commonly used in both CTFI and ATFI settings. They support flexible frame sampling and evaluation under diverse temporal intervals.

| Dataset    | Venue      | Type | Resolution                   | Split        | #Videos / #Triplets | URL                                                          |
| ---------- | ---------- | ---- | ---------------------------- | ------------ | ------------------- | ------------------------------------------------------------ |
| Xiph       | -          | 🔸 M  | 2048x1080 (2K), 3840×2160 (4K) | test         | 8                   | [🔗](https://media.xiph.org/video/derf/)                      |
| KITTI      | CVPR'12    | 🔸 M  | 1240×376                     | train / test | 194 / 195           | [🔗](http://www.cvlibs.net/datasets/kitti/)                   |
| DAVIS      | CVPR'16    | 🔸 M  | 1920×1080                    | train / test | 30 / 20             | [🔗](https://davischallenge.org/)                             |
| HD         | TPAMI'19   | 🔸 M  | 960×544, 1280×720, 1920×1080 | test         | 11                  | [🔗](https://media.xiph.org/video/derf/)                      |
| Sintel     | ECCV'12    | 🔸 M  | 1024×436                     | train / test | 23 / 12             | [🔗](http://sintel.is.tue.mpg.de/)                            |
| Adobe240   | CVPR'17    | 🔸 M  | 1280×720                     | train / test | 61 / 10             | [🔗](http://www.cs.ubc.ca/labs/imager/tr/2017/DeepVideoDeblurring/) |
| GOPRO      | CVPR'17    | 🔸 M  | 1280×720                     | train / test | 22 / 11             | [🔗](https://seungjunnah.github.io/Datasets/gopro.html)       |
| X4K1000FPS | ICCV'21    | 🔸 M  | 4096×2160                    | train / test | 4,408 / 15          | [🔗](https://github.com/JihyongOh/XVFI)                       |
| WebVid-10M | ICCV'21    | 🔸 M  | varied                       | train        | 10M                 | [🔗](https://github.com/m-bain/webvid)                        |
| LAVIB      | NeurIPS'24 | 🔸 M  | 4096×2160                    | train / test | 188,644 / 53,494    | [🔗](https://alexandrosstergiou.github.io/datasets/LAVIB)     |
| OpenVid    | ICLR'25    | 🔸 M  | ≥ 512×512, 1920×1080         | train        | 1M                  | [🔗](https://github.com/NJU-PCALab/OpenVid-1M)                |

---

🔹 **T (Triplet dataset)**: Two input frames predict the center frame  
🔸 **M (Multi-frame dataset)**: Multiple frames allow dense temporal supervision

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

- <a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/8a1d694707eb0fefe65871369074926d-Paper.pdf" target="_blank"><strong>FID (Fréchet Inception Distance)</strong></a>  
  Measures distributional difference in features between generated and GT frames.  
  📌 Lower FID indicates better semantic alignment.

- <a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.pdf" target="_blank"><strong>LPIPS (Learned Perceptual Image Patch Similarity)</strong></a>  
  Uses deep features to assess perceptual similarity.  
  📌 Lower LPIPS = better perceptual similarity.

- <a href="https://arxiv.org/pdf/2207.08119" target="_blank"><strong>FloLPIPS</strong></a>  
  Motion-aware LPIPS variant that uses optical flow for weighting.

- <a href="https://link.springer.com/chapter/10.1007/978-3-031-19797-0_6" target="_blank"><strong>STLPIPS</strong></a>  
  Shift-tolerant version of LPIPS, robust to slight misalignments.

- <a href="https://ieeexplore.ieee.org/document/9298952" target="_blank"><strong>DISTS (Deep Image Structure and Texture Similarity)</strong></a>  
  Separately evaluates structure and texture using deep features.  
  📌 Balances local detail and global coherence.

---

### 🎞️ Video-level Metrics

These metrics evaluate spatiotemporal coherence across video sequences, important for smooth motion and consistency.

- <a href="https://dl.acm.org/doi/pdf/10.1145/3343031.3351028" target="_blank"><strong>VSFA (Video Spatial-Feature Aggregation)</strong></a>  
  No-reference model estimating perceptual quality from human-labeled videos using deep recurrent features.  

- <a href="https://arxiv.org/pdf/1811.09393" target="_blank"><strong>tOF (temporal Optical Flow consistency)</strong></a>  
  Measures how consistent optical flow is across frames.  
  📌 Lower tOF = smoother motion continuity.

- <a href="https://arxiv.org/pdf/1812.01717" target="_blank"><strong>FVD (Fréchet Video Distance)</strong></a>  
  Uses I3D features to compare real vs generated video distributions.  
  📌 Lower FVD = better realism and temporal quality.

- <a href="https://arxiv.org/pdf/2407.16124" target="_blank"><strong>FVMD (Fréchet Video Motion Distance)</strong></a>  
  Enhances FVD by disentangling motion from appearance for better motion consistency evaluation.

- <a href="https://arxiv.org/pdf/2311.17982" target="_blank"><strong>VBench</strong></a>  
  Large-scale, no-reference benchmark for evaluating fidelity, coherence, and realism using semantic video representations.  
  📌 Ideal for reference-free evaluation.

---
## 💫 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=CMLab-Korea/Awesome-Video-Frame-Interpolation&type=Date)](https://www.star-history.com/#CMLab-Korea/Awesome-Video-Frame-Interpolation&Date)
