# Awesome-Video-Frame-Interpolation
### <img src="https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation/blob/main/media/icon2.png?raw=true" width="20" style="vertical-align: middle;"> AceVFI: A Comprehensive Survey of Advances in Video Frame Interpolation

<p align="center">
  <img src="https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation/blob/main/media/figure.png?raw=true" alt="figure">
</p>



[![awesome](https://img.shields.io/badge/awesome-yes-critical?style=flat&logo=awesome-lists&labelColor=purple)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=CMLab-Korea.Awesome-Video-Frame-Interpolation)](https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation)
[![arXiv](https://img.shields.io/badge/arXiv-Preprint-b31b1b.svg)](https://arxiv.org/abs/your-paper-id)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC--BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Stars](https://img.shields.io/github/stars/CMLab-Korea/Awesome-Video-Frame-Interpolation.svg?style=social&label=Star)](https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation)


This repository provides a curated collection of papers, benchmarks, and resources from our survey:  
**"Advances in Video Frame Interpolation: A Comprehensive Survey"** (2025, submitted to [Journal/Conference]).

> 📝 **Authors**: Dahyeon Kye\*, Changhyun Roh, Sukhun Ko, Chanho Eom, Jihyong Oh†

> 🎓 **Institution**: Chung-Ang University, Department of Imaging Science, GSAIM  

---

## 📘 Abstract

Video Frame Interpolation (VFI) aims to synthesize intermediate frames between given input frames and has advanced significantly from traditional motion-compensation to deep learning-based methods.
We comprehensively categorize VFI approaches—kernel-based, flow-based, attention-based, Transformer-based, Mamba-based, and diffusion-based—highlighting their motion representations and core architectures.
We further formalize training objectives into Center-Time Frame Interpolation (CTFI) and Arbitrary-Time Frame Interpolation (ATFI), offering a unified perspective across learning paradigms.
This survey identifies key challenges such as large motion, occlusion, lighting changes, and non-linear motion, and reviews how each method addresses them.
We also examine practical components like datasets, loss functions, and evaluation metrics used across the literature.
Additionally, we explore extended applications including event-guided VFI, joint VFI with super-resolution or deblurring, and domain-specific uses like animation or medical imaging.
Our study offers a consolidated reference point and future directions for researchers in the field of video frame interpolation.


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

- 📌 2025-05-01: Paper released to ArXiv.
- 🚀 2025-03-15: Repository initialized.

---

## 🔖 BibTeX

If you find this survey helpful, please consider citing us:

```bibtex
@article{Kye2025AceVFI,
  title={🂡 AceVFI: A Comprehensive Survey of Advances in Video Frame Interpolation},
  author={Kye, Dahyeon and Roh, Changhyun and Ko, Sukhun and Eom, Chanho and Oh, Jihyong},
  journal={arXiv preprint arXiv:your-paper-id},
  year={2025}
}
```

## 🔍 Survey Paper

You can find the preprint of our survey here:  
📄 [arXiv:your-paper-id](https://arxiv.org/abs/your-paper-id)

---

## 📄 Paper List

We categorize recent VFI papers by methodology:  
![VFI Categories](https://github.com/CMLab-Korea/Awesome-Video-Frame-Interpolation/blob/main/media/paper_overview.png)

## II.A. Motion Compensation-based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/6651823">Frame rate up conversion based on variational image fusion</a></td><td align="center">IEEE TIP</td><td align="center">2013</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/5440975">Motion-compensated frame rate up-conversion—Part II: New algorithms for frame interpolation</a></td><td align="center">IEEE on Broadcasting</td><td align="center">2010</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/5443548">Motion-compensated frame rate up-conversion—Part I: Fast multi-frame motion estimation</a></td><td align="center">IEEE on Broadcasting</td><td align="center">2010</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4480123">A multistage motion vector processing method for motion-compensated frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4429281">Motion compensated frame rate up-conversion using extended bilateral motion estimation</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4162523">Motion-compensated frame interpolation using bilateral motion estimation and adaptive overlapped block motion compensation</a></td><td align="center">IEEE on Circuits and Systems for Video Technology</td><td align="center">2007</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/1309458">Motion compensated frame interpolation by new block-based motion estimation algorithm</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2004</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1037026">Adaptive motion-compensated interpolation for frame rate up-conversion</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2002</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=538926">A method for motion adaptive frame rate up-conversion</a></td><td align="center">IEEE on circuits and Systems for Video Technology</td><td align="center">1996</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=305878">Motion compensation based on spatial transformations</a></td><td align="center">IEEE on circuits and systems for video technology</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=44281">Fractional frame rate up-conversion using weighted median filters</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">1989</td></tr>
</tbody>
</table>

## II.B. Deep learning-based

### Kernel-based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/supplemental/Kalluri_FLAVR_Flow-Agnostic_Video_WACV_2023_supplemental.pdf">Flavr: Flow-agnostic video representations for fast frame interpolation</a></td><td align="center">WACV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Zhou_Exploring_Motion_Ambiguity_and_Alignment_for_High-Quality_Video_Frame_Interpolation_CVPR_2023_paper.pdf">Exploring motion ambiguity and alignment for high-quality video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2104.01517">PDWN: Pyramid deformable warping network for video interpolation</a></td><td align="center">IEEE of Signal Processing</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2202.07731">Enhancing deformable convolution based video frame interpolation with coarse-to-fine 3D CNN</a></td><td align="center">ICIP</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/9747182/">Video frame interpolation via local lightweight bidirectional encoding with channel attention cascade</a></td><td align="center">ICASSP</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2008.10680">Video frame interpolation via generalized deformable convolution</a></td><td align="center">IEEE on multimedia</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9501506">Multiple video frame interpolation via enhanced deformable separable convolution</a></td><td align="center">TPAMI</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Ding_CDFI_Compression-Driven_Network_Design_for_Frame_Interpolation_CVPR_2021_paper.pdf">Cdfi: Compression-driven network design for frame interpolation</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2008.10680">Video frame interpolation via generalized deformable convolution</a></td><td align="center">IEEE on multimedia</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6693/6693-13-9922-1-10-20200521.pdf">Channel attention is all you need for video frame interpolation</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6634/6634-13-9862-1-10-20200520.pdf">Video frame interpolation via deformable separable convolution</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Peleg_IM-Net_for_High_Resolution_Video_Frame_Interpolation_CVPR_2019_paper.pdf">Im-net for high resolution video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Deformable_ConvNets_V2_More_Deformable_Better_Results_CVPR_2019_paper.pdf">Deformable convnets v2: More deformable, better results</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Niklaus_Video_Frame_Interpolation_CVPR_2017_paper.pdf">Video frame interpolation via adaptive convolution</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1708.01692">Video frame interpolation via adaptive separable convolution</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf">ImageNet classification with deep convolutional neural networks</a></td><td align="center">Communications of the ACM</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1703.06211">Deformable convolutional networks</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1603.06041">Learning image matching by simply watching video</a></td><td align="center">ECCV</td><td align="center">2016</td></tr>
</tbody>
</table>


### Flow-based
<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.02316">Unified Arbitrary-Time Video Frame Interpolation and Prediction</a></td><td align="center">ICASSP</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Hu_IQ-VFI_Implicit_Quadratic_Motion_Estimation_for_Video_Frame_Interpolation_CVPR_2024_paper.pdf">IQ-VFI: implicit quadratic motion estimation for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Jeong_OCAI_Improving_Optical_Flow_Estimation_by_Occlusion_and_Consistency_Aware_CVPR_2024_paper.pdf">Ocai: Improving optical flow estimation by occlusion and consistency aware interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/7495fa446f10e9edef6e47b2d327596e-Paper-Conference.pdf">Generalizable implicit motion modeling for video frame interpolation</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_Perception-Oriented_Video_Frame_Interpolation_via_Asymmetric_Blending_CVPR_2024_paper.pdf">Perception-oriented video frame interpolation via asymmetric blending</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04908.pdf">Clearer frames, anytime: Resolving velocity ambiguity in video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.11365">BiM-VFI: directional Motion Field-Guided Frame Interpolation for Video with Non-uniform Motions</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/papers/Niklaus_Splatting-Based_Synthesis_for_Video_Frame_Interpolation_WACV_2023_paper.pdf">Splatting-based synthesis for video frame interpolation</a></td><td align="center">WACV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/papers/Jin_Enhanced_Bi-Directional_Motion_Estimation_for_Video_Frame_Interpolation_WACV_2023_paper.pdf">Enhanced bi-directional motion estimation for video frame interpolation</a></td><td align="center">WACV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Park_BiFormer_Learning_Bilateral_Motion_Estimation_via_Bilateral_Transformer_for_4K_CVPR_2023_paper.pdf">Biformer: Learning bilateral motion estimation via bilateral transformer for 4k video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Jin_A_Unified_Pyramid_Recurrent_Network_for_Video_Frame_Interpolation_CVPR_2023_paper.pdf">A unified pyramid recurrent network for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Li_AMT_All-Pairs_Multi-Field_Transforms_for_Efficient_Frame_Interpolation_CVPR_2023_paper.pdf">Amt: All-pairs multi-field transforms for efficient frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Extracting_Motion_and_Appearance_via_Inter-Frame_Attention_for_Efficient_Video_CVPR_2023_paper.pdf">Extracting motion and appearance via inter-frame attention for efficient video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136740608.pdf">Real-time intermediate flow estimation for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750509.pdf">Learning cross-video neural representations for high-quality frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2202.04901">Film: Frame interpolation for large motion</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_Many-to-Many_Splatting_for_Efficient_Video_Frame_Interpolation_CVPR_2022_paper.pdf">Many-to-many splatting for efficient video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Kong_IFRNet_Intermediate_Feature_Refine_Network_for_Efficient_Frame_Interpolation_CVPR_2022_paper.pdf">Ifrnet: Intermediate feature refine network for efficient frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Sim_XVFI_eXtreme_Video_Frame_Interpolation_ICCV_2021_paper.pdf">Xvfi: extreme video frame interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Park_Asymmetric_Bilateral_Motion_Estimation_for_Video_Frame_Interpolation_ICCV_2021_paper.pdf">Asymmetric bilateral motion estimation for video frame interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720103.pdf">All at once: Temporally adaptive multi-frame interpolation with advanced motion modeling</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Niklaus_Softmax_Splatting_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Softmax splatting for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2009.04642">Enhanced quadratic video interpolation</a></td><td align="center">ECCV Workshops</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700477.pdf">A flexible recurrent residual pyramid network for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1609/aaai.v33i01.33018794">Deep video frame interpolation using cyclic frame generation</a></td><td align="center">AAAI</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Yuan_Zoom-In-To-Check_Boosting_Video_Interpolation_via_Instance-Level_Discrimination_CVPR_2019_paper.pdf">Zoom-in-to-check: Boosting video interpolation via instance-level discrimination</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Reda_Unsupervised_Video_Interpolation_Using_Cycle_Consistency_ICCV_2019_paper.pdf">Unsupervised video interpolation using cycle consistency</a></td><td align="center">ICCV</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper/2019/file/d045c59a90d7587d8d671b5f5aec4e7c-Paper.pdf">Quadratic video interpolation</a></td><td align="center">NeurIPS</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1702.02463">Video frame synthesis using deep voxel flow</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://papers.nips.cc/paper_files/paper/2015/file/33ceb07bf4eeb3da587e268d663aba1a-Paper.pdf">Spatial transformer networks</a></td><td align="center">NeurIPS</td><td align="center">2015</td></tr>
</tbody>
</table>

### Kernel- and Flow-based Combined


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2404.11108">LADDER: An Efficient Framework for Video Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2021/papers/Niklaus_Revisiting_Adaptive_Convolutions_for_Video_Frame_Interpolation_WACV_2021_paper.pdf">Revisiting adaptive convolutions for video frame interpolation</a></td><td align="center">WACV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Gui_FeatureFlow_Robust_Video_Interpolation_via_Structure-to-Texture_Generation_CVPR_2020_paper.pdf">Featureflow: Robust video interpolation via structure-to-texture generation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_AdaCoF_Adaptive_Collaboration_of_Flows_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Adacof: Adaptive collaboration of flows for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590103.pdf">Bmbc: Bilateral motion estimation with bilateral cost volume for video interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf/3ae72db22e8443112a8e7e61a943c8044053e135.pdf">Memc-net: Motion estimation and motion compensation driven neural network for video interpolation and enhancement</a></td><td align="center">TPAMI</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0130.pdf">Context-aware synthesis for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
</tbody>
</table>

### Phase-based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Meyer_PhaseNet_for_Video_CVPR_2018_paper.pdf">Phasenet for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2015/papers/Meyer_Phase-Based_Frame_Interpolation_2015_CVPR_paper.pdf">Phase-based frame interpolation for video</a></td><td align="center">CVPR</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://people.csail.mit.edu/billf/publications/Phase-Based_Video.pdf">Phase-based video motion processing</a></td><td align="center">TOG (ToG)</td><td align="center">2013</td></tr>
<tr><td align="left"><a href="https://people.csail.mit.edu/pdidyk/projects/MultiviewConversion/MultiviewConversion.pdf">Joint view expansion and filtering for automultiscopic 3D displays</a></td><td align="center">TOG (TOG)</td><td align="center">2013</td></tr>
<tr><td align="left"><a href="https://link.springer.com/content/pdf/10.1023/a:1026553619983.pdf">A parametric texture model based on joint statistics of complex wavelet coefficients</a></td><td align="center">International journal of computer vision</td><td align="center">2000</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=537667">The steerable pyramid: A flexible architecture for multi-scale derivative computation</a></td><td align="center">ICIP</td><td align="center">1995</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=119725">Shiftable multiscale transforms</a></td><td align="center">IEEE on Information Theory</td><td align="center">1992</td></tr>
</tbody>
</table>

### GAN-based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Danier_ST-MFNet_A_Spatio-Temporal_Multi-Flow_Network_for_Frame_Interpolation_CVPR_2022_paper.pdf">St-mfnet: A spatio-temporal multi-flow network for frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.sciencedirect.com/science/article/pii/S1077314222000546">Video frame interpolation via down--up scale generative adversarial networks</a></td><td align="center">Computer Vision and Image Understanding</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="Generative Adversarial Networks for Video-to-Video Domain Adaptation">Generative adversarial networks for video-to-video domain adaptation</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9097443">Multi-scale attention generative adversarial networks for video frame interpolation</a></td><td align="center">IEEE</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.mdpi.com/2076-3417/10/18/6245">Efficient video frame interpolation using generative adversarial networks</a></td><td align="center">Applied Sciences</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.sciencedirect.com/science/article/pii/S0925231219315747">Frame-GAN: Increasing the frame rate of gait videos with generative adversarial networks</a></td><td align="center">Neurocomputing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/8451971">Generating realistic videos from keyframes with concatenated GANs</a></td><td align="center">IEEE on Circuits and Systems for Video Technology</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1711.06045">Frame interpolation with multi-scale deep loss functions and generative adversarial networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="http://vision.stanford.edu/teaching/cs231n/reports/2017/pdfs/317.pdf">Frame interpolation using generative adversarial networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/892c3b1c6dccd52936e27cbd0ff683d6-Paper.pdf">Improved training of wasserstein gans</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1703.10717">Began: Boundary equilibrium generative adversarial networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1701.07875">Wasserstein generative adversarial networks</a></td><td align="center">ICML</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/abs/1512.09300">Autoencoding beyond pixels using a learned similarity metric</a></td><td align="center">ICML</td><td align="center">2016</td></tr>
</tbody>
</table>

### Transformer-based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Sparse_Global_Matching_for_Video_Frame_Interpolation_with_Large_Motion_CVPR_2024_paper.pdf">Sparse global matching for video frame interpolation with large motion</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3547660">L2BEC2: Local lightweight bidirectional encoding and channel attention cascade for video frame interpolation</a></td><td align="center">ACM Transactions on Multimedia Computing, Communications and Applications</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2207.09048">TTVFI: Learning trajectory-aware transformer for video frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Lu_Video_Frame_Interpolation_With_Transformer_CVPR_2022_paper.pdf">Video frame interpolation with transformer</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Shi_Video_Frame_Interpolation_Transformer_CVPR_2022_paper.pdf">Video frame interpolation transformer</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zamir_Restormer_Efficient_Transformer_for_High-Resolution_Image_Restoration_CVPR_2022_paper.pdf">Restormer: Efficient transformer for high-resolution image restoration</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Swin_Transformer_Hierarchical_Vision_Transformer_Using_Shifted_Windows_ICCV_2021_paper.pdf">Swin transformer: Hierarchical vision transformer using shifted windows</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf">Attention is all you need</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
</tbody>
</table>



### Mamba-based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.07046">MambaFlow: A Mamba-Centric Architecture for End-to-End Optical Flow Estimation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/c1e9db5e1b04322963af91ac0c943568-Paper-Conference.pdf">Vfimamba: Video frame interpolation with state space models</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02740.pdf">Mambair: A simple baseline for image restoration with state-space model</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2411.15269">MambaIRv2: Attentive State Space Restoration</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=tEYskw1VY2">Mamba: Linear-time sequence modeling with selective state spaces</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=uYLFoz1vlAC">Efficiently modeling long sequences with structured state spaces</a></td><td align="center">arXiv</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1511.06464">Unitary evolution recurrent neural networks</a></td><td align="center">ICML</td><td align="center">2016</td></tr>
</tbody>
</table>

## II.C. Diffusion Model-based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.03699">Motion-Aware Generative Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.15831">EDEN: Enhanced Diffusion for High-quality Large-motion Video Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2504.00380">Hierarchical Flow Diffusion for Efficient Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2303.09508">Ldmvfi: Video frame interpolation with latent diffusion models</a></td><td align="center">AAAI</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Jain_Video_Interpolation_with_Diffusion_Models_CVPR_2024_paper.pdf">Video interpolation with diffusion models</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=u0geEr7X2O">Motion-aware latent diffusion models for video frame interpolation</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2409.09605">Dreammover: Leveraging the prior of diffusion models for image interpolation with large motion</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2408.15239">Generative inbetweening: Adapting image-to-video models for keyframe interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2403.14611">Explorative inbetweening of time and space</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/abs/2405.05953">Frame Interpolation with Consecutive Brownian Bridge Diffusion</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.11755">Generative Inbetweening through Frame-wise Conditions-Driven Video Generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.05651">ViBiDSampler: Enhancing Video Interpolation Using Bidirectional Diffusion Sampler</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/944618542d80a63bbec16dfbd2bd689a-Paper-Conference.pdf">Mcvd-masked conditional video diffusion for prediction, generation, and interpolation</a></td><td align="center">NeurIPS</td><td align="center">2022</td></tr>
</tbody>
</table>

## V.A. Datasets


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/333f81766b242b1837fa65c2172afb76-Paper-Datasets_and_Benchmarks_Track.pdf">Lavib: A large-scale video interpolation benchmark</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2407.02371">Openvid-1M: A large-scale high-quality dataset for text-to-video generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Bain_Frozen_in_Time_A_Joint_Video_and_Image_Encoder_for_ICCV_2021_paper.pdf">Frozen in time: A joint video and image encoder for end-to-end retrieval</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Su_Deep_Video_Deblurring_CVPR_2017_paper.pdf">Deep video deblurring for hand-held cameras</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Nah_Deep_Multi-Scale_Convolutional_CVPR_2017_paper.pdf">Deep multi-scale convolutional neural network for dynamic scene deblurring</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Perazzi_A_Benchmark_Dataset_CVPR_2016_paper.pdf">A benchmark dataset and evaluation methodology for video object segmentation</a></td><td align="center">CVPR</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1212.0402">UCF101: A dataset of 101 human actions classes from videos in the wild</a></td><td align="center">arXiv</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://www.cvlibs.net/publications/Geiger2012CVPR.pdf">Are we ready for autonomous driving? the kitti vision benchmark suite</a></td><td align="center">CVPR</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://files.is.tue.mpg.de/black/papers/ButlerECCV2012.pdf">A naturalistic open source movie for optical flow evaluation</a></td><td align="center">ECCV</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4408903">A database and evaluation methodology for optical flow</a></td><td align="center">International Journal of Computer Vision</td><td align="center">2011</td></tr>
<tr><td align="left"><a href="https://media.xiph.org/video/derf/">Xiph.org video test media (derf's collection)</a></td><td align="center"></td><td align="center">1994</td></tr>
</tbody>
</table>


## V.A. Loss Functions


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/1711.07837">Unflow: Unsupervised learning of optical flow with a bidirectional census loss</a></td><td align="center">AAAI</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1707.05776">Optimizing the latent space of generative networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1511.05440">Deep multi-scale video prediction beyond mean square error</a></td><td align="center">arXiv</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=413553">Two deterministic half-quadratic regularization algorithms for computed imaging</a></td><td align="center">ICIP</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="https://www.cs.cornell.edu/~rdz/Papers/ZW-ECCV94.pdf">Non-parametric local transforms for computing visual correspondence</a></td><td align="center">ECCV</td><td align="center">1994</td></tr>
</tbody>
</table>




## V.A. Evaluation Metrics


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Huang_VBench_Comprehensive_Benchmark_Suite_for_Video_Generative_Models_CVPR_2024_paper.pdf">Vbench: Comprehensive benchmark suite for video generative models</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf/798d301795f1200b0ee8c8ea5de15169a1da49d2.pdf">Fr$\backslash$'echet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2207.08119">FloLPIPS: A bespoke video quality metric for frame interpolation</a></td><td align="center">PCS</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9298952">Image quality assessment: Unifying structure and texture similarity</a></td><td align="center">TPAMI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3343031.3351028">Quality assessment of in-the-wild videos</a></td><td align="center">ACM MM</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.pdf">The unreasonable effectiveness of deep features as a perceptual metric</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1812.01717">Towards accurate generative models of video: A new metric \& challenges</a></td><td align="center">arXiv</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/8a1d694707eb0fefe65871369074926d-Paper.pdf">Gans trained by a two time-scale update rule converge to a local nash equilibrium</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6353522">Making a “completely blind” image quality analyzer</a></td><td align="center">IEEE Signal processing letters</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1284395">Image quality assessment: from error visibility to structural similarity</a></td><td align="center">IEEE TIP</td><td align="center">2004</td></tr>
</tbody>
</table>

## VI. Applications


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
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.01715">KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/10647865">Real-time video prediction with fast video interpolation model and prediction training</a></td><td align="center">ICIP</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2024/papers/Huang_Scale-Adaptive_Feature_Aggregation_for_Efficient_Space-Time_Video_Super-Resolution_WACV_2024_paper.pdf">Scale-adaptive feature aggregation for efficient space-time video super-resolution</a></td><td align="center">WACV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.04221">Tango: Co-speech gesture video reenactment with hierarchical audio motion embedding and diffusion interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11464711&googleIPSandBox=false&mark=0&minRead=10&ipRange=false&b2cLoginYN=false&icstClss=010000&isPDFSizeAllowed=true&accessgl=Y&language=en_US&hasTopBanner=true">Dynamic Framerate SlowFast Network for Improving Autonomous Driving Performance</a></td><td align="center">IEIE Transactions on Smart Processing \& Computing</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2210.00823">BVI-VFI: a video quality database for video frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3633780">Neighbor correspondence matching for flow-based video frame synthesis</a></td><td align="center">Proceedings of the 30th ACM International Conference on Multimedia</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750231.pdf">A perceptual quality metric for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Neural_Scene_Flow_Fields_for_Space-Time_View_Synthesis_of_Dynamic_CVPR_2021_paper.pdf">Neural scene flow fields for space-time view synthesis of dynamic scenes</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Xiang_Zooming_Slow-Mo_Fast_and_Accurate_One-Stage_Space-Time_Video_Super-Resolution_CVPR_2020_paper.pdf">Zooming slow-mo: Fast and accurate one-stage space-time video super-resolution</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE09307292">Compressed video restoration using a generative adversarial network for subjective quality enhancement</a></td><td align="center">IEIE Transactions on Smart Processing \& Computing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="http://toflow.csail.mit.edu/toflow_ijcv.pdf">Video enhancement with task-oriented flow</a></td><td align="center">International Journal of Computer Vision</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Bao_Depth-Aware_Video_Frame_Interpolation_CVPR_2019_paper.pdf">Depth-aware video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ECCV_2018/papers/Chao-Yuan_Wu_Video_Compression_through_ECCV_2018_paper.pdf">Video compression through image interpolation</a></td><td align="center">ECCV</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Jiang_Super_SloMo_High_CVPR_2018_paper.pdf">Super slomo: High quality estimation of multiple intermediate frames for video interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1605.03557">View synthesis by appearance flow</a></td><td align="center">ECCV</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/Flynn_DeepStereo_Learning_to_CVPR_2016_paper.pdf">Deepstereo: Learning to predict new views from the world's imagery</a></td><td align="center">CVPR</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/790301/">Prediction error as a quality metric for motion and stereo</a></td><td align="center">ICCV</td><td align="center">1999</td></tr>
</tbody>
</table>

## VI.A. Event-Based VFI


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.20268">EGVD: Event-Guided Video Diffusion Model for Physically Realistic Large-Motion Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.22491">Coupled Video Frame Interpolation and Encoding with Hybrid Event Cameras for Low-Power High-Framerate Video</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2309.08891">V2ce: Video to continuous events simulator</a></td><td align="center">ICRA</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Video_Frame_Interpolation_via_Direct_Synthesis_with_the_Event-based_Reference_CVPR_2024_paper.pdf">Video frame interpolation via direct synthesis with the event-based reference</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/11208.pdf">TimeLens-XL: Real-Time Event-Based Video Frame Interpolation with Large Motion</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.07761">Repurposing pre-trained video diffusion models for event-based video interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10067566">A 2.97 $\mu$m-pitch event-based vision sensor with shared pixel front-end circuitry and low-noise intensity readout mode</a></td><td align="center">ISSCC</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_Event-Based_Video_Frame_Interpolation_With_Cross-Modal_Asymmetric_Bidirectional_Motion_Fields_CVPR_2023_paper.pdf">Event-based video frame interpolation with cross-modal asymmetric bidirectional motion fields</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3581783.3612093">Event-guided frame interpolation and dynamic range expansion of single rolling shutter image</a></td><td align="center">ACM MM</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Unifying_Motion_Deblurring_and_Frame_Interpolation_With_Events_CVPR_2022_paper.pdf">Unifying motion deblurring and frame interpolation with events</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2203.17191">Time lens++: Event-based frame interpolation with parametric non-linear flow and multi-scale fusion</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/He_TimeReplayer_Unlocking_the_Potential_of_Event_Cameras_for_Video_Interpolation_CVPR_2022_paper.pdf">Timereplayer: Unlocking the potential of event cameras for video interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670261.pdf">Video interpolation by event-driven anisotropic adjustment of optical flow</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Tulyakov_Time_Lens_Event-Based_Video_Frame_Interpolation_CVPR_2021_paper.pdf">Time lens: Event-based video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1912.01584">Eventgan: Leveraging large scale image datasets for event cameras</a></td><td align="center">ICCP</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_Training_Weakly_Supervised_Video_Frame_Interpolation_With_Events_ICCV_2021_paper.pdf">Training weakly supervised video frame interpolation with events</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123530681.pdf">Learning event-driven video deblurring and interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ICCVW_2019/papers/PBDL/Wang_Event-Driven_Video_Frame_Synthesis_ICCVW_2019_paper.pdf">Event-driven video frame synthesis</a></td><td align="center">ICCV Workshops</td><td align="center">2019</td></tr
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8296630">PIX2NVS: Parameterized conversion of pixel-domain video frames to neuromorphic vision streams</a></td><td align="center">ICIP</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7862386">Towards a framework for end-to-end control of a simulated vehicle with spiking neural networks</a></td><td align="center">SIMPAR</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4444573">A 128 $\times$ 128 120 dB 15 $\mu$ s latency asynchronous temporal contrast vision sensor</a></td><td align="center">IEEE of solid-state circuits</td><td align="center">2008</td></tr>
</tbody>
</table>

## VI.B. Cartoon VFI


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.16550">PhysAnimator: Physics-Guided Generative Cartoon Animation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2504.05402">Time-adaptive Video Frame Interpolation based on Residual Diffusion</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.11838">High-Resolution Frame Interpolation with Patch-based Cascaded Diffusion</a></td><td align="center">AAAI</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.08295">LayerAnimate: Layer-specific control for animation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06298.pdf">Dynamicrafter: Animating open-domain images with video diffusion priors</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.17933">Tooncrafter: Generative cartoon interpolation</a></td><td align="center">TOG</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=Lp40Z40N07">Framer: Interactive frame interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.14173">Anidoc: Animation creation made easier</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Siyao_Deep_Geometrized_Cartoon_Line_Inbetweening_ICCV_2023_paper.pdf">Deep sketch-guided cartoon video inbetweening</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136770275.pdf">Improving the perceptual quality of 2d animation interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Siyao_Deep_Animation_Video_Interpolation_in_the_Wild_CVPR_2021_paper.pdf">Deep animation video interpolation in the wild</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
</tbody>
</table>

## VI.C. Medical Image VFI


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Kim_Data-Efficient_Unsupervised_Interpolation_Without_Any_Intermediate_Frame_for_4D_Medical_CVPR_2024_paper.pdf">Data-efficient unsupervised interpolation without any intermediate frame for 4d medical images</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.15385">CPT-Interp: Continuous sPatial and Temporal Motion Modeling for 4D Medical Image Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_A_Spatiotemporal_Volumetric_Interpolation_Network_for_4D_Dynamic_Medical_Image_CVPR_2020_paper.pdf">A spatiotemporal volumetric interpolation network for 4d dynamic medical image</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
</tbody>
</table>



## VI.D. Joint VFI: SR


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_MoTIF_Learning_Motion_Trajectories_with_Local_Implicit_Neural_Functions_for_ICCV_2023_paper.pdf">Motif: Learning motion trajectories with local implicit neural functions for continuous space-time video super-resolution</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Temporal_Modulation_Network_for_Controllable_Space-Time_Video_Super-Resolution_CVPR_2021_paper.pdf">Temporal modulation network for controllable space-time video super-resolution</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6788/6788-13-10017-1-10-20200522.pdf">Fisr: Deep joint frame interpolation and super-resolution with a multi-scale temporal loss</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Haris_Space-Time-Aware_Multi-Resolution_Video_Enhancement_CVPR_2020_paper.pdf">Space-time-aware multi-resolution video enhancement</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.cvl.iis.u-tokyo.ac.jp/class2013/2013w/paper/time-varyingImageProcessing/Increasing_Space-Time_Resolution_in_Video_(ECCV02).pdf">Increasing space-time resolution in video</a></td><td align="center">ECCV</td><td align="center">2002</td></tr>
</tbody>
</table>



## VI.D. Joint VFI: Deblur


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Latency_Correction_for_Event-guided_Deblurring_and_Frame_Interpolation_CVPR_2024_paper.pdf">Latency correction for event-guided deblurring and frame interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Shang_Joint_Video_Multi-Frame_Interpolation_and_Deblurring_Under_Unknown_Exposure_Time_CVPR_2023_paper.pdf">Joint video multi-frame interpolation and deblurring under unknown exposure time</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136790588.pdf">Animation from blur: Multi-modal blur decomposition with motion guidance</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670193.pdf">Demfi: deep joint deblurring and multi-frame interpolation with flow-guided attentive correlation and recursive boosting</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper/2020/file/9a11883317fde3aef2e2432a58c86779-Paper.pdf">Video frame interpolation without temporal priors</a></td><td align="center">NeurIPS</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9257179">Video frame interpolation and enhancement via pyramid recurrent framework</a></td><td align="center">IEEE TIP</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Shen_Blurry_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Blurry video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
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
