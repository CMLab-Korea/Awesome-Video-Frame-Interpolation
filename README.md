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
- [📊 Datasets & Benchmarks](#datasets--benchmarks)
- [📈 Evaluation Metrics](#evaluation-metrics)

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
  author={Kye, Dahyeon and Roh, Changhyun and Sim, Hyeonjun and Ko, Sukhun and Eom, Chanho and Oh, Jihyong},
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

## Feature Extraction Network


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/1409.1556">Very deep convolutional networks for large-scale image recognition</a></td><td align="center">arXiv</td><td align="center">2014</td></tr>
<tr><td align="left"><a href="https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28">U-net: Convolutional networks for biomedical image segmentation</a></td><td align="center">Medical image computing and computer-assisted intervention--MICCAI 2015: 18th international conference, Munich, Germany, October 5-9, 2015, proceedings, part III 18</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://lmb.informatik.uni-freiburg.de/Publications/2016/CABR16/cicek16miccai.pdf">3D U-Net: learning dense volumetric segmentation from sparse annotation</a></td><td align="center">Medical Image Computing and Computer-Assisted Intervention--MICCAI 2016: 19th International Conference, Athens, Greece, October 17-21, 2016, Proceedings, Part II 19</td><td align="center">2016</td></tr>
</tbody>
</table>



## VFI


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2211.14005">Efficient feature extraction for high-resolution video frame interpolation</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
</tbody>
</table>



## Application


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/790301/">Prediction error as a quality metric for motion and stereo</a></td><td align="center">Proceedings of the Seventh IEEE International Conference on Computer Vision</td><td align="center">1999</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1605.03557">View synthesis by appearance flow</a></td><td align="center">ECCV, Amsterdam, The Netherlands, October 11--14, 2016, Proceedings, Part IV 14</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/Flynn_DeepStereo_Learning_to_CVPR_2016_paper.pdf">Deepstereo: Learning to predict new views from the world's imagery</a></td><td align="center">CVPR</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ECCV_2018/papers/Chao-Yuan_Wu_Video_Compression_through_ECCV_2018_paper.pdf">Video compression through image interpolation</a></td><td align="center">ECCV</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Jiang_Super_SloMo_High_CVPR_2018_paper.pdf">Super slomo: High quality estimation of multiple intermediate frames for video interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="http://toflow.csail.mit.edu/toflow_ijcv.pdf">Video enhancement with task-oriented flow</a></td><td align="center">International Journal of Computer Vision</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Bao_Depth-Aware_Video_Frame_Interpolation_CVPR_2019_paper.pdf">Depth-aware video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Xiang_Zooming_Slow-Mo_Fast_and_Accurate_One-Stage_Space-Time_Video_Super-Resolution_CVPR_2020_paper.pdf">Zooming slow-mo: Fast and accurate one-stage space-time video super-resolution</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Neural_Scene_Flow_Fields_for_Space-Time_View_Synthesis_of_Dynamic_CVPR_2021_paper.pdf">Neural scene flow fields for space-time view synthesis of dynamic scenes</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2209.14792">Make-a-video: Text-to-video generation without text-video data</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3633780">Neighbor correspondence matching for flow-based video frame synthesis</a></td><td align="center">Proceedings of the 30th ACM International Conference on Multimedia</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE09307292">Compressed video restoration using a generative adversarial network for subjective quality enhancement</a></td><td align="center">IEIE Transactions on Smart Processing \& Computing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/10647865">Real-time video prediction with fast video interpolation model and prediction training</a></td><td align="center">2024 IEEE International Conference on Image Processing (ICIP)</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.04221">Tango: Co-speech gesture video reenactment with hierarchical audio motion embedding and diffusion interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.20218">Video Motion Graphs</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.01715">KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE11464711&googleIPSandBox=false&mark=0&minRead=10&ipRange=false&b2cLoginYN=false&icstClss=010000&isPDFSizeAllowed=true&accessgl=Y&language=en_US&hasTopBanner=true">Dynamic Framerate SlowFast Network for Improving Autonomous Driving Performance</a></td><td align="center">IEIE Transactions on Smart Processing \& Computing</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2024/papers/Huang_Scale-Adaptive_Feature_Aggregation_for_Efficient_Space-Time_Video_Super-Resolution_WACV_2024_paper.pdf">Scale-adaptive feature aggregation for efficient space-time video super-resolution</a></td><td align="center">Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/10031193">Subjective and objective quality assessment of high frame rate videos</a></td><td align="center">IEEE</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2312.15659">Perceptual quality assessment for video frame interpolation</a></td><td align="center">2023 IEEE International Conference on Visual Communications and Image Processing (VCIP)</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2210.00823">BVI-VFI: a video quality database for video frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2006.02671">Comparing H. 265/HEVC and VP9: Impact of high frame rates on the perceptual quality of compressed videos</a></td><td align="center">arXiv</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/10031193">Subjective and objective quality assessment of high frame rate videos</a></td><td align="center">IEEE</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750231.pdf">A perceptual quality metric for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
</tbody>
</table>



## Challenges


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://www.sciencedirect.com/science/article/pii/0004370281900242?via%3Dihub">Determining optical flow</a></td><td align="center">Artificial intelligence</td><td align="center">1981</td></tr>
</tbody>
</table>



## Motion-Compensated


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=44281">Fractional frame rate up-conversion using weighted median filters</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">1989</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=305878">Motion compensation based on spatial transformations</a></td><td align="center">IEEE on circuits and systems for video technology</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=538926">A method for motion adaptive frame rate up-conversion</a></td><td align="center">IEEE on circuits and Systems for Video Technology</td><td align="center">1996</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1037026">Adaptive motion-compensated interpolation for frame rate up-conversion</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2002</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/1309458">Motion compensated frame interpolation by new block-based motion estimation algorithm</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2004</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4162523">Motion-compensated frame interpolation using bilateral motion estimation and adaptive overlapped block motion compensation</a></td><td align="center">IEEE on Circuits and Systems for Video Technology</td><td align="center">2007</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4429281">Motion compensated frame rate up-conversion using extended bilateral motion estimation</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/4480123">A multistage motion vector processing method for motion-compensated frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/5443548">Motion-compensated frame rate up-conversion—Part I: Fast multi-frame motion estimation</a></td><td align="center">IEEE on Broadcasting</td><td align="center">2010</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/5440975">Motion-compensated frame rate up-conversion—Part II: New algorithms for frame interpolation</a></td><td align="center">IEEE on Broadcasting</td><td align="center">2010</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/6651823">Frame rate up conversion based on variational image fusion</a></td><td align="center">IEEE TIP</td><td align="center">2013</td></tr>
</tbody>
</table>



## GAN-Based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/1711.06045">Frame interpolation with multi-scale deep loss functions and generative adversarial networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="http://vision.stanford.edu/teaching/cs231n/reports/2017/pdfs/317.pdf">Frame interpolation using generative adversarial networks</a></td><td align="center"></td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9097443">Multi-scale attention generative adversarial networks for video frame interpolation</a></td><td align="center">IEEE</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.mdpi.com/2076-3417/10/18/6245">Efficient video frame interpolation using generative adversarial networks</a></td><td align="center">Applied Sciences</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.sciencedirect.com/science/article/pii/S0925231219315747">Frame-GAN: Increasing the frame rate of gait videos with generative adversarial networks</a></td><td align="center">Neurocomputing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.sciencedirect.com/science/article/pii/S1077314222000546">Video frame interpolation via down--up scale generative adversarial networks</a></td><td align="center">Computer Vision and Image Understanding</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/8451971">Generating realistic videos from keyframes with concatenated GANs</a></td><td align="center">IEEE on Circuits and Systems for Video Technology</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Danier_ST-MFNet_A_Spatio-Temporal_Multi-Flow_Network_for_Frame_Interpolation_CVPR_2022_paper.pdf">St-mfnet: A spatio-temporal multi-flow network for frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/892c3b1c6dccd52936e27cbd0ff683d6-Paper.pdf">Improved training of wasserstein gans</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1703.10717">Began: Boundary equilibrium generative adversarial networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1701.07875">Wasserstein generative adversarial networks</a></td><td align="center">ICML</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/abs/1512.09300">Autoencoding beyond pixels using a learned similarity metric</a></td><td align="center">ICML</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="Generative Adversarial Networks for Video-to-Video Domain Adaptation">Generative adversarial networks for video-to-video domain adaptation</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
</tbody>
</table>



## Diffusion-Based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2210.04628">Novel view synthesis with diffusion models</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/944618542d80a63bbec16dfbd2bd689a-Paper-Conference.pdf">Mcvd-masked conditional video diffusion for prediction, generation, and interpolation</a></td><td align="center">NeurIPS</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2303.09508">Ldmvfi: Video frame interpolation with latent diffusion models</a></td><td align="center">AAAI</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Jain_Video_Interpolation_with_Diffusion_Models_CVPR_2024_paper.pdf">Video interpolation with diffusion models</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=u0geEr7X2O">Motion-aware latent diffusion models for video frame interpolation</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2409.09605">Dreammover: Leveraging the prior of diffusion models for image interpolation with large motion</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2408.15239">Generative inbetweening: Adapting image-to-video models for keyframe interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2403.14611">Explorative inbetweening of time and space</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/abs/2405.05953">Frame Interpolation with Consecutive Brownian Bridge Diffusion</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.11755">Generative Inbetweening through Frame-wise Conditions-Driven Video Generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.05651">ViBiDSampler: Enhancing Video Interpolation Using Bidirectional Diffusion Sampler</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.03699">Motion-Aware Generative Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.15831">EDEN: Enhanced Diffusion for High-quality Large-motion Video Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2504.00380">Hierarchical Flow Diffusion for Efficient Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
</tbody>
</table>



## Flow-Based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/Xplore/login.jsp?reason=notIncluded&url=%2Fstamp%2Fstamp.jsp%3Farnumber%3Dx0401579&denied=">Digital image warping</a></td><td align="center"></td><td align="center">1990</td></tr>
<tr><td align="left"><a href="https://papers.nips.cc/paper_files/paper/2015/file/33ceb07bf4eeb3da587e268d663aba1a-Paper.pdf">Spatial transformer networks</a></td><td align="center">NeurIPS</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1702.02463">Video frame synthesis using deep voxel flow</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1609/aaai.v33i01.33018794">Deep video frame interpolation using cyclic frame generation</a></td><td align="center">AAAI</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Yuan_Zoom-In-To-Check_Boosting_Video_Interpolation_via_Instance-Level_Discrimination_CVPR_2019_paper.pdf">Zoom-in-to-check: Boosting video interpolation via instance-level discrimination</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Reda_Unsupervised_Video_Interpolation_Using_Cycle_Consistency_ICCV_2019_paper.pdf">Unsupervised video interpolation using cycle consistency</a></td><td align="center">ICCV</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper/2019/file/d045c59a90d7587d8d671b5f5aec4e7c-Paper.pdf">Quadratic video interpolation</a></td><td align="center">NeurIPS</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720103.pdf">All at once: Temporally adaptive multi-frame interpolation with advanced motion modeling</a></td><td align="center">ECCV, Glasgow, UK, August 23--28, 2020, Proceedings, Part XXVII 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Niklaus_Softmax_Splatting_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Softmax splatting for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2009.04642">Enhanced quadratic video interpolation</a></td><td align="center">Computer Vision--ECCV 2020 Workshops: Glasgow, UK, August 23--28, 2020, Proceedings, Part IV 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700477.pdf">A flexible recurrent residual pyramid network for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Sim_XVFI_eXtreme_Video_Frame_Interpolation_ICCV_2021_paper.pdf">Xvfi: extreme video frame interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_Many-to-Many_Splatting_for_Efficient_Video_Frame_Interpolation_CVPR_2022_paper.pdf">Many-to-many splatting for efficient video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Kong_IFRNet_Intermediate_Feature_Refine_Network_for_Efficient_Frame_Interpolation_CVPR_2022_paper.pdf">Ifrnet: Intermediate feature refine network for efficient frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Park_Asymmetric_Bilateral_Motion_Estimation_for_Video_Frame_Interpolation_ICCV_2021_paper.pdf">Asymmetric bilateral motion estimation for video frame interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136740608.pdf">Real-time intermediate flow estimation for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750509.pdf">Learning cross-video neural representations for high-quality frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2202.04901">Film: Frame interpolation for large motion</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/papers/Niklaus_Splatting-Based_Synthesis_for_Video_Frame_Interpolation_WACV_2023_paper.pdf">Splatting-based synthesis for video frame interpolation</a></td><td align="center">Proceedings of the IEEE/CVF winter conference on applications of computer vision</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/papers/Jin_Enhanced_Bi-Directional_Motion_Estimation_for_Video_Frame_Interpolation_WACV_2023_paper.pdf">Enhanced bi-directional motion estimation for video frame interpolation</a></td><td align="center">Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Park_BiFormer_Learning_Bilateral_Motion_Estimation_via_Bilateral_Transformer_for_4K_CVPR_2023_paper.pdf">Biformer: Learning bilateral motion estimation via bilateral transformer for 4k video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Jin_A_Unified_Pyramid_Recurrent_Network_for_Video_Frame_Interpolation_CVPR_2023_paper.pdf">A unified pyramid recurrent network for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Li_AMT_All-Pairs_Multi-Field_Transforms_for_Efficient_Frame_Interpolation_CVPR_2023_paper.pdf">Amt: All-pairs multi-field transforms for efficient frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Extracting_Motion_and_Appearance_via_Inter-Frame_Attention_for_Efficient_Video_CVPR_2023_paper.pdf">Extracting motion and appearance via inter-frame attention for efficient video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Hu_IQ-VFI_Implicit_Quadratic_Motion_Estimation_for_Video_Frame_Interpolation_CVPR_2024_paper.pdf">IQ-VFI: implicit quadratic motion estimation for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Jeong_OCAI_Improving_Optical_Flow_Estimation_by_Occlusion_and_Consistency_Aware_CVPR_2024_paper.pdf">Ocai: Improving optical flow estimation by occlusion and consistency aware interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/7495fa446f10e9edef6e47b2d327596e-Paper-Conference.pdf">Generalizable implicit motion modeling for video frame interpolation</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_Perception-Oriented_Video_Frame_Interpolation_via_Asymmetric_Blending_CVPR_2024_paper.pdf">Perception-oriented video frame interpolation via asymmetric blending</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04908.pdf">Clearer frames, anytime: Resolving velocity ambiguity in video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.11365">BiM-VFI: directional Motion Field-Guided Frame Interpolation for Video with Non-uniform Motions</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.02316">Unified Arbitrary-Time Video Frame Interpolation and Prediction</a></td><td align="center">ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</td><td align="center">2025</td></tr>
</tbody>
</table>



## Flow Network


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/1467470">Symmetric stereo matching for occlusion handling</a></td><td align="center">2005 IEEE Computer Society Conference on Computer Vision and Pattern Recognition (CVPR'05)</td><td align="center">2005</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Jiang_Learning_To_Estimate_Hidden_Motions_With_Global_Motion_Aggregation_ICCV_2021_paper.pdf">Learning to estimate hidden motions with global motion aggregation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_iccv_2013/papers/Weinzaepfel_DeepFlow_Large_Displacement_2013_ICCV_paper.pdf">DeepFlow: Large displacement optical flow with deep matching</a></td><td align="center">ICCV</td><td align="center">2013</td></tr>
<tr><td align="left"><a href="https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Dosovitskiy_FlowNet_Learning_Optical_ICCV_2015_paper.pdf">Flownet: Learning optical flow with convolutional networks</a></td><td align="center">ICCV</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Ilg_FlowNet_2.0_Evolution_CVPR_2017_paper.pdf">Flownet 2.0: Evolution of optical flow estimation with deep networks</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Ranjan_Optical_Flow_Estimation_CVPR_2017_paper.pdf">Optical flow estimation using a spatial pyramid network</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Occlusion_Aware_Unsupervised_CVPR_2018_paper.pdf">Occlusion aware unsupervised learning of optical flow</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_PWC-Net_CNNs_for_CVPR_2018_paper.pdf">Pwc-net: Cnns for optical flow using pyramid, warping, and cost volume</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Hui_LiteFlowNet_A_Lightweight_CVPR_2018_paper.pdf">Liteflownet: A lightweight convolutional neural network for optical flow estimation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/8778682">Refined TV-L 1 optical flow estimation using joint filtering</a></td><td align="center">IEEE on Multimedia</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470392.pdf">Raft: Recurrent all-pairs field transforms for optical flow</a></td><td align="center">ECCV, Glasgow, UK, August 23--28, 2020, Proceedings, Part II 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136770672.pdf">Flowformer: A transformer architecture for optical flow</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_GMFlow_Learning_Optical_Flow_via_Global_Matching_CVPR_2022_paper.pdf">Gmflow: Learning optical flow via global matching</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
</tbody>
</table>



## Kernel-Based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf">ImageNet classification with deep convolutional neural networks</a></td><td align="center">Communications of the ACM</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1703.06211">Deformable convolutional networks</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Deformable_ConvNets_V2_More_Deformable_Better_Results_CVPR_2019_paper.pdf">Deformable convnets v2: More deformable, better results</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1603.06041">Learning image matching by simply watching video</a></td><td align="center">ECCV, Amsterdam, The Netherlands, October 11-14, 2016, Proceedings, Part VI 14</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Niklaus_Video_Frame_Interpolation_CVPR_2017_paper.pdf">Video frame interpolation via adaptive convolution</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1708.01692">Video frame interpolation via adaptive separable convolution</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Peleg_IM-Net_for_High_Resolution_Video_Frame_Interpolation_CVPR_2019_paper.pdf">Im-net for high resolution video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2008.10680">Video frame interpolation via generalized deformable convolution</a></td><td align="center">IEEE on multimedia</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6693/6693-13-9922-1-10-20200521.pdf">Channel attention is all you need for video frame interpolation</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6634/6634-13-9862-1-10-20200520.pdf">Video frame interpolation via deformable separable convolution</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2008.10680">Video frame interpolation via generalized deformable convolution</a></td><td align="center">IEEE on multimedia</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9501506">Multiple video frame interpolation via enhanced deformable separable convolution</a></td><td align="center">TPAMI</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Ding_CDFI_Compression-Driven_Network_Design_for_Frame_Interpolation_CVPR_2021_paper.pdf">Cdfi: Compression-driven network design for frame interpolation</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2104.01517">PDWN: Pyramid deformable warping network for video interpolation</a></td><td align="center">IEEE of Signal Processing</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2202.07731">Enhancing deformable convolution based video frame interpolation with coarse-to-fine 3D CNN</a></td><td align="center">2022 IEEE International Conference on Image Processing (ICIP)</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/document/9747182/">Video frame interpolation via local lightweight bidirectional encoding with channel attention cascade</a></td><td align="center">ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2023/supplemental/Kalluri_FLAVR_Flow-Agnostic_Video_WACV_2023_supplemental.pdf">Flavr: Flow-agnostic video representations for fast frame interpolation</a></td><td align="center">Proceedings of the IEEE/CVF winter conference on applications of computer vision</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Zhou_Exploring_Motion_Ambiguity_and_Alignment_for_High-Quality_Video_Frame_Interpolation_CVPR_2023_paper.pdf">Exploring motion ambiguity and alignment for high-quality video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
</tbody>
</table>



## Kernel-Flow Combined


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/0130.pdf">Context-aware synthesis for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf/3ae72db22e8443112a8e7e61a943c8044053e135.pdf">Memc-net: Motion estimation and motion compensation driven neural network for video interpolation and enhancement</a></td><td align="center">TPAMI</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590103.pdf">Bmbc: Bilateral motion estimation with bilateral cost volume for video interpolation</a></td><td align="center">ECCV, Glasgow, UK, August 23--28, 2020, Proceedings, Part XIV 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_AdaCoF_Adaptive_Collaboration_of_Flows_for_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Adacof: Adaptive collaboration of flows for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Gui_FeatureFlow_Robust_Video_Interpolation_via_Structure-to-Texture_Generation_CVPR_2020_paper.pdf">Featureflow: Robust video interpolation via structure-to-texture generation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/WACV2021/papers/Niklaus_Revisiting_Adaptive_Convolutions_for_Video_Frame_Interpolation_WACV_2021_paper.pdf">Revisiting adaptive convolutions for video frame interpolation</a></td><td align="center">Proceedings of the IEEE/CVF winter conference on applications of computer vision</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2404.11108">LADDER: An Efficient Framework for Video Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
</tbody>
</table>



## Phase-Based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=119725">Shiftable multiscale transforms</a></td><td align="center">IEEE on Information Theory</td><td align="center">1992</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=537667">The steerable pyramid: A flexible architecture for multi-scale derivative computation</a></td><td align="center">Proceedings., international conference on image processing</td><td align="center">1995</td></tr>
<tr><td align="left"><a href="https://link.springer.com/content/pdf/10.1023/a:1026553619983.pdf">A parametric texture model based on joint statistics of complex wavelet coefficients</a></td><td align="center">International journal of computer vision</td><td align="center">2000</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2015/papers/Meyer_Phase-Based_Frame_Interpolation_2015_CVPR_paper.pdf">Phase-based frame interpolation for video</a></td><td align="center">CVPR</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Meyer_PhaseNet_for_Video_CVPR_2018_paper.pdf">Phasenet for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://people.csail.mit.edu/billf/publications/Phase-Based_Video.pdf">Phase-based video motion processing</a></td><td align="center">TOG (ToG)</td><td align="center">2013</td></tr>
<tr><td align="left"><a href="https://people.csail.mit.edu/pdidyk/projects/MultiviewConversion/MultiviewConversion.pdf">Joint view expansion and filtering for automultiscopic 3D displays</a></td><td align="center">TOG (TOG)</td><td align="center">2013</td></tr>
</tbody>
</table>



## Transformer-Based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/1406.1078">Learning phrase representations using RNN encoder-decoder for statistical machine translation</a></td><td align="center">arXiv</td><td align="center">2014</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf">Attention is all you need</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Swin_Transformer_Hierarchical_Vision_Transformer_Using_Shifted_Windows_ICCV_2021_paper.pdf">Swin transformer: Hierarchical vision transformer using shifted windows</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Lu_Video_Frame_Interpolation_With_Transformer_CVPR_2022_paper.pdf">Video frame interpolation with transformer</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Shi_Video_Frame_Interpolation_Transformer_CVPR_2022_paper.pdf">Video frame interpolation transformer</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3547660">L2BEC2: Local lightweight bidirectional encoding and channel attention cascade for video frame interpolation</a></td><td align="center">ACM Transactions on Multimedia Computing, Communications and Applications</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2207.09048">TTVFI: Learning trajectory-aware transformer for video frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Sparse_Global_Matching_for_Video_Frame_Interpolation_with_Large_Motion_CVPR_2024_paper.pdf">Sparse global matching for video frame interpolation with large motion</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zamir_Restormer_Efficient_Transformer_for_High-Resolution_Image_Restoration_CVPR_2022_paper.pdf">Restormer: Efficient transformer for high-resolution image restoration</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
</tbody>
</table>



## Mamba


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/1511.06464">Unitary evolution recurrent neural networks</a></td><td align="center">ICML</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=uYLFoz1vlAC">Efficiently modeling long sequences with structured state spaces</a></td><td align="center">arXiv</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=tEYskw1VY2">Mamba: Linear-time sequence modeling with selective state spaces</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/c1e9db5e1b04322963af91ac0c943568-Paper-Conference.pdf">Vfimamba: Video frame interpolation with state space models</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02740.pdf">Mambair: A simple baseline for image restoration with state-space model</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2411.15269">MambaIRv2: Attentive State Space Restoration</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.09873">IRSRMamba: Infrared Image Super-Resolution via Mamba-based Wavelet Transform Feature Modulation Model</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf/edef71b7f4e8b881c4803643a7655e9bd3b3fda3.pdf">Learning enriched features via selective state spaces model for efficient image deblurring</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.14343">Efficient visual state space model for image deblurring</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.20066">MaIR: A Locality-and Continuity-Preserving Mamba for Image Restoration</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2408.08665">QMambaBSR: Burst Image Super-Resolution with Query State Space Model</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.07046">MambaFlow: A Mamba-Centric Architecture for End-to-End Optical Flow Estimation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10887656">First-order State Space Model for Lightweight Image Super-resolution</a></td><td align="center">ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</td><td align="center">2025</td></tr>
</tbody>
</table>



## Deep learning-Based vs. Generative


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7486599">Very deep convolutional neural network based image classification using small training sample size</a></td><td align="center">2015 3rd IAPR Asian conference on pattern recognition (ACPR)</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9123096">Visual quality assessment for interpolated slow-motion videos based on a novel database</a></td><td align="center">2020 Twelfth International Conference on Quality of Multimedia Experience (QoMEX)</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2202.07727">A subjective quality study for video frame interpolation</a></td><td align="center">2022 IEEE International Conference on Image Processing (ICIP)</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2106.15282">Cascaded diffusion models for high fidelity image generation</a></td><td align="center">JMLR</td><td align="center">2022</td></tr>
</tbody>
</table>



## GAN


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/1406.2661">Generative adversarial networks</a></td><td align="center">Communications of the ACM</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1312.6114">Auto-encoding variational bayes</a></td><td align="center"></td><td align="center">2013</td></tr>
<tr><td align="left"><a href="https://proceedings.nips.cc/paper/2021/file/49ad23d1ec9fa4bd8d77d02681df5cfa-Paper.pdf">Diffusion models beat gans on image synthesis</a></td><td align="center">NeurIPS</td><td align="center">2021</td></tr>
</tbody>
</table>



## DM-Based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper/2020/file/4c5bcfec8584af0d967f1ab10179ca4b-Paper.pdf">Denoising diffusion probabilistic models</a></td><td align="center">NeurIPS</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=St1giarCHLP">Denoising diffusion implicit models</a></td><td align="center">arXiv</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.pdf">High-resolution image synthesis with latent diffusion models</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2204.03458">Video diffusion models</a></td><td align="center">NeurIPS</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Blattmann_Align_Your_Latents_High-Resolution_Video_Synthesis_With_Latent_Diffusion_Models_CVPR_2023_paper.pdf">Align your latents: High-resolution video synthesis with latent diffusion models</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2311.15127">Stable video diffusion: Scaling latent video diffusion models to large datasets</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2303.01469">Consistency models</a></td><td align="center"></td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=k7FuTOWMOc7">Elucidating the design space of diffusion-based generative models</a></td><td align="center">NeurIPS</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=TIdIXIpzhoI">Progressive distillation for fast sampling of diffusion models</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=duBCwjb68o">Latent consistency models: Synthesizing high-resolution images with few-step inference</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Yin_One-step_Diffusion_with_Distribution_Matching_Distillation_CVPR_2024_paper.pdf">One-step diffusion with distribution matching distillation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>



## Adapters


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_Adding_Conditional_Control_to_Text-to-Image_Diffusion_Models_ICCV_2023_paper.pdf">Adding conditional control to text-to-image diffusion models</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2408.06070">Controlnext: Powerful and efficient control for image and video generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
</tbody>
</table>



## T2V and I2V


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Tune-A-Video_One-Shot_Tuning_of_Image_Diffusion_Models_for_Text-to-Video_Generation_ICCV_2023_paper.pdf">Tune-a-video: One-shot tuning of image diffusion models for text-to-video generation</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=LQzN6TRFg9">Cogvideox: Text-to-video diffusion models with an expert transformer</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2411.17440">Identity-Preserving Text-to-Video Generation by Frequency Decomposition</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3680528.3687614">Lumiere: A space-time diffusion model for video generation</a></td><td align="center">SIGGRAPH Asia 2024 Conference Papers</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2311.04145">I2vgen-xl: High-quality image-to-video synthesis via cascaded diffusion models</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=vqniLmUDvj">Consisti2v: Enhancing visual consistency for image-to-video generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Hu_Animate_Anyone_Consistent_and_Controllable_Image-to-Video_Synthesis_for_Character_Animation_CVPR_2024_paper.pdf">Animate anyone: Consistent and controllable image-to-video synthesis for character animation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>



## Event-Based


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4444573">A 128 $\times$ 128 120 dB 15 $\mu$ s latency asynchronous temporal contrast vision sensor</a></td><td align="center">IEEE of solid-state circuits</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7862386">Towards a framework for end-to-end control of a simulated vehicle with spiking neural networks</a></td><td align="center">2016 IEEE International Conference on Simulation, Modeling, and Programming for Autonomous Robots (SIMPAR)</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8296630">PIX2NVS: Parameterized conversion of pixel-domain video frames to neuromorphic vision streams</a></td><td align="center">2017 IEEE International Conference on Image Processing (ICIP)</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://proceedings.mlr.press/v87/rebecq18a/rebecq18a.pdf">Esim: an open event camera simulator</a></td><td align="center">Conference on robot learning</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ICCVW_2019/papers/PBDL/Wang_Event-Driven_Video_Frame_Synthesis_ICCVW_2019_paper.pdf">Event-driven video frame synthesis</a></td><td align="center">ICCV Workshops</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123530681.pdf">Learning event-driven video deblurring and interpolation</a></td><td align="center">ECCV, Glasgow, UK, August 23--28, 2020, Proceedings, Part VIII 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Tulyakov_Time_Lens_Event-Based_Video_Frame_Interpolation_CVPR_2021_paper.pdf">Time lens: Event-based video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1912.01584">Eventgan: Leveraging large scale image datasets for event cameras</a></td><td align="center">2021 IEEE international conference on computational photography (ICCP)</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_Training_Weakly_Supervised_Video_Frame_Interpolation_With_Events_ICCV_2021_paper.pdf">Training weakly supervised video frame interpolation with events</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Unifying_Motion_Deblurring_and_Frame_Interpolation_With_Events_CVPR_2022_paper.pdf">Unifying motion deblurring and frame interpolation with events</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2203.17191">Time lens++: Event-based frame interpolation with parametric non-linear flow and multi-scale fusion</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/He_TimeReplayer_Unlocking_the_Potential_of_Event_Cameras_for_Video_Interpolation_CVPR_2022_paper.pdf">Timereplayer: Unlocking the potential of event cameras for video interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670261.pdf">Video interpolation by event-driven anisotropic adjustment of optical flow</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10067566">A 2.97 $\mu$m-pitch event-based vision sensor with shared pixel front-end circuitry and low-noise intensity readout mode</a></td><td align="center">2023 IEEE International Solid-State Circuits Conference (ISSCC)</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_Event-Based_Video_Frame_Interpolation_With_Cross-Modal_Asymmetric_Bidirectional_Motion_Fields_CVPR_2023_paper.pdf">Event-based video frame interpolation with cross-modal asymmetric bidirectional motion fields</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3581783.3612093">Event-guided frame interpolation and dynamic range expansion of single rolling shutter image</a></td><td align="center">Proceedings of the 31st ACM International Conference on Multimedia</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2309.08891">V2ce: Video to continuous events simulator</a></td><td align="center">2024 IEEE International Conference on Robotics and Automation (ICRA)</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Video_Frame_Interpolation_via_Direct_Synthesis_with_the_Event-based_Reference_CVPR_2024_paper.pdf">Video frame interpolation via direct synthesis with the event-based reference</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/11208.pdf">TimeLens-XL: Real-Time Event-Based Video Frame Interpolation with Large Motion</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.07761">Repurposing pre-trained video diffusion models for event-based video interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.20268">EGVD: Event-Guided Video Diffusion Model for Physically Realistic Large-Motion Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.22491">Coupled Video Frame Interpolation and Encoding with Hybrid Event Cameras for Low-Power High-Framerate Video</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
</tbody>
</table>



## Event + SR


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Jing_Turning_Frequency_to_Resolution_Video_Super-Resolution_via_Event_Cameras_CVPR_2021_paper.pdf">Turning frequency to resolution: Video super-resolution via event cameras</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Lu_Learning_Spatial-Temporal_Implicit_Neural_Representations_for_Event-Guided_Video_Super-Resolution_CVPR_2023_paper.pdf">Learning spatial-temporal implicit neural representations for event-guided video super-resolution</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2406.13457">EvTexture: event-driven texture enhancement for video super-resolution</a></td><td align="center">Forty-first ICML</td><td align="center">2024</td></tr>
</tbody>
</table>



## Medic


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_A_Spatiotemporal_Volumetric_Interpolation_Network_for_4D_Dynamic_Medical_Image_CVPR_2020_paper.pdf">A spatiotemporal volumetric interpolation network for 4d dynamic medical image</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Kim_Data-Efficient_Unsupervised_Interpolation_Without_Any_Intermediate_Frame_for_4D_Medical_CVPR_2024_paper.pdf">Data-efficient unsupervised interpolation without any intermediate frame for 4d medical images</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.15385">CPT-Interp: Continuous sPatial and Temporal Motion Modeling for 4D Medical Image Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
</tbody>
</table>



## Cartoon Interpolation


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Siyao_Deep_Animation_Video_Interpolation_in_the_Wild_CVPR_2021_paper.pdf">Deep animation video interpolation in the wild</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136770275.pdf">Improving the perceptual quality of 2d animation interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Siyao_Deep_Geometrized_Cartoon_Line_Inbetweening_ICCV_2023_paper.pdf">Deep sketch-guided cartoon video inbetweening</a></td><td align="center">IEEE on Visualization and Computer Graphics</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06298.pdf">Dynamicrafter: Animating open-domain images with video diffusion priors</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2405.17933">Tooncrafter: Generative cartoon interpolation</a></td><td align="center">TOG (TOG)</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf?id=Lp40Z40N07">Framer: Interactive frame interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2412.14173">Anidoc: Animation creation made easier</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.08295">LayerAnimate: Layer-specific control for animation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Dai_Learning_Inclusion_Matching_for_Animation_Paint_Bucket_Colorization_CVPR_2024_paper.pdf">Learning inclusion matching for animation paint bucket colorization</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2501.16550">PhysAnimator: Physics-Guided Generative Cartoon Animation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2504.05402">Time-adaptive Video Frame Interpolation based on Residual Diffusion</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2410.11838">High-Resolution Frame Interpolation with Patch-based Cascaded Diffusion</a></td><td align="center">AAAI</td><td align="center">2025</td></tr>
</tbody>
</table>



## Game


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2503.08417">AnyMoLe: Any Character Motion In-betweening Leveraging Video Diffusion Models</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
</tbody>
</table>



## Joint: SR


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://www.cvl.iis.u-tokyo.ac.jp/class2013/2013w/paper/time-varyingImageProcessing/Increasing_Space-Time_Resolution_in_Video_(ECCV02).pdf">Increasing space-time resolution in video</a></td><td align="center">Computer Vision—ECCV 2002: 7th ECCV Copenhagen, Denmark, May 28--31, 2002 Proceedings, Part I 7</td><td align="center">2002</td></tr>
<tr><td align="left"><a href="https://cdn.aaai.org/ojs/6788/6788-13-10017-1-10-20200522.pdf">Fisr: Deep joint frame interpolation and super-resolution with a multi-scale temporal loss</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Haris_Space-Time-Aware_Multi-Resolution_Video_Enhancement_CVPR_2020_paper.pdf">Space-time-aware multi-resolution video enhancement</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Temporal_Modulation_Network_for_Controllable_Space-Time_Video_Super-Resolution_CVPR_2021_paper.pdf">Temporal modulation network for controllable space-time video super-resolution</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_MoTIF_Learning_Motion_Trajectories_with_Local_Implicit_Neural_Functions_for_ICCV_2023_paper.pdf">Motif: Learning motion trajectories with local implicit neural functions for continuous space-time video super-resolution</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
</tbody>
</table>



## Joint: Deblur


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper/2020/file/9a11883317fde3aef2e2432a58c86779-Paper.pdf">Video frame interpolation without temporal priors</a></td><td align="center">NeurIPS</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9257179">Video frame interpolation and enhancement via pyramid recurrent framework</a></td><td align="center">IEEE TIP</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Shen_Blurry_Video_Frame_Interpolation_CVPR_2020_paper.pdf">Blurry video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136790588.pdf">Animation from blur: Multi-modal blur decomposition with motion guidance</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670193.pdf">Demfi: deep joint deblurring and multi-frame interpolation with flow-guided attentive correlation and recursive boosting</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Shang_Joint_Video_Multi-Frame_Interpolation_and_Deblurring_Under_Unknown_Exposure_Time_CVPR_2023_paper.pdf">Joint video multi-frame interpolation and deblurring under unknown exposure time</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Latency_Correction_for_Event-guided_Deblurring_and_Frame_Interpolation_CVPR_2024_paper.pdf">Latency correction for event-guided deblurring and frame interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>



## Loss Function


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=413553">Two deterministic half-quadratic regularization algorithms for computed imaging</a></td><td align="center">Proceedings of 1st international conference on image processing</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1511.05440">Deep multi-scale video prediction beyond mean square error</a></td><td align="center">arXiv</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Ledig_Photo-Realistic_Single_Image_CVPR_2017_paper.pdf">Photo-realistic single image super-resolution using a generative adversarial network</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1707.05776">Optimizing the latent space of generative networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://www.cs.cornell.edu/~rdz/Papers/ZW-ECCV94.pdf">Non-parametric local transforms for computing visual correspondence</a></td><td align="center">ECCV</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1711.07837">Unflow: Unsupervised learning of optical flow with a bidirectional census loss</a></td><td align="center">AAAI</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ECCV_2018/papers/Yuliang_Zou_DF-Net_Unsupervised_Joint_ECCV_2018_paper.pdf">Df-net: Unsupervised joint learning of depth and flow using cross-task consistency</a></td><td align="center">ECCV</td><td align="center">2018</td></tr>
</tbody>
</table>



## Dataset


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://media.xiph.org/video/derf/">Xiph.org video test media (derf's collection)</a></td><td align="center"></td><td align="center">1994</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4408903">A database and evaluation methodology for optical flow</a></td><td align="center">Int. J. Comput. Vis.</td><td align="center">2011</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1212.0402">UCF101: A dataset of 101 human actions classes from videos in the wild</a></td><td align="center">arXiv</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://www.cvlibs.net/publications/Geiger2012CVPR.pdf">Are we ready for autonomous driving? the kitti vision benchmark suite</a></td><td align="center">CVPR</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://files.is.tue.mpg.de/black/papers/ButlerECCV2012.pdf">A naturalistic open source movie for optical flow evaluation</a></td><td align="center">ECCV</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Perazzi_A_Benchmark_Dataset_CVPR_2016_paper.pdf">A benchmark dataset and evaluation methodology for video object segmentation</a></td><td align="center">CVPR</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1604.06182">THUMOS challenge: Action recognition with a large number of classes</a></td><td align="center"></td><td align="center">2015</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8099637">Slow flow: Exploiting high-speed cameras for accurate and diverse optical flow reference data</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Su_Deep_Video_Deblurring_CVPR_2017_paper.pdf">Deep video deblurring for hand-held cameras</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Nah_Deep_Multi-Scale_Convolutional_CVPR_2017_paper.pdf">Deep multi-scale convolutional neural network for dynamic scene deblurring</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Bain_Frozen_in_Time_A_Joint_Video_and_Image_Encoder_for_ICCV_2021_paper.pdf">Frozen in time: A joint video and image encoder for end-to-end retrieval</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/333f81766b242b1837fa65c2172afb76-Paper-Datasets_and_Benchmarks_Track.pdf">Lavib: A large-scale video interpolation benchmark</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2407.02371">Openvid-1M: A large-scale high-quality dataset for text-to-video generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
</tbody>
</table>



## Metric


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1284395">Image quality assessment: from error visibility to structural similarity</a></td><td align="center">IEEE Trans. Image Process.</td><td align="center">2004</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4586430">A new objective quality metric for frame interpolation used in video compression</a></td><td align="center">IEEE on broadcasting</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6353522">Making a “completely blind” image quality analyzer</a></td><td align="center">IEEE Signal processing letters</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/8a1d694707eb0fefe65871369074926d-Paper.pdf">Gans trained by a two time-scale update rule converge to a local nash equilibrium</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_The_Unreasonable_Effectiveness_CVPR_2018_paper.pdf">The unreasonable effectiveness of deep features as a perceptual metric</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/1812.01717">Towards accurate generative models of video: A new metric \& challenges</a></td><td align="center">arXiv</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="https://openreview.net/pdf/798d301795f1200b0ee8c8ea5de15169a1da49d2.pdf">Fr$\backslash$'echet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="https://dl.acm.org/doi/pdf/10.1145/3343031.3351028">Quality assessment of in-the-wild videos</a></td><td align="center">Proceedings of the 27th ACM international conference on multimedia</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9298952">Image quality assessment: Unifying structure and texture similarity</a></td><td align="center">TPAMI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper/2020/file/165a59f7cf3b5c4396ba65953d679f17-Paper.pdf">A loss function for generative neural networks based on watson’s perceptual model</a></td><td align="center">NeurIPS</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="https://proceedings.mlr.press/v139/radford21a/radford21a.pdf">Learning transferable visual models from natural language supervision</a></td><td align="center">ICML</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9887996">Image super-resolution via iterative refinement</a></td><td align="center">TPAMI</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2207.08119">FloLPIPS: A bespoke video quality metric for frame interpolation</a></td><td align="center">2022 Picture Coding Symposium (PCS)</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Huang_VBench_Comprehensive_Benchmark_Suite_for_Video_Generative_Models_CVPR_2024_paper.pdf">Vbench: Comprehensive benchmark suite for video generative models</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>



## Future Research Direction


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2502.05695">Semantic-Aware Adaptive Video Streaming Using Latent Diffusion Models for Wireless Networks</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2211.08428">Cadm: Codec-aware diffusion modeling for neural-enhanced video streaming</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Castrejon_Improved_Conditional_VRNNs_for_Video_Prediction_ICCV_2019_paper.pdf">Improved conditional vrnns for video prediction</a></td><td align="center">ICCV</td><td align="center">2019</td></tr>
</tbody>
</table>



## All-in-One: Image


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Li_All-in-One_Image_Restoration_for_Unknown_Corruption_CVPR_2022_paper.pdf">All-in-one image restoration for unknown corruption</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="https://arxiv.org/pdf/2504.04869">Content-Aware Transformer for All-in-one Image Restoration</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Ai_Multimodal_Prompt_Perceiver_Empower_Adaptiveness_Generalizability_and_Fidelity_for_All-in-One_CVPR_2024_paper.pdf">Multimodal prompt perceiver: Empower adaptiveness generalizability and fidelity for all-in-one image restoration</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>



## All-in-One: Video


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Wang_EDVR_Video_Restoration_With_Enhanced_Deformable_Convolutional_Networks_CVPRW_2019_paper.pdf">Edvr: Video restoration with enhanced deformable convolutional networks</a></td><td align="center">CVPR workshops</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/e635a25e49e73adc51f76aef462ff2f8-Paper-Conference.pdf">AverNet: All-in-one video restoration for time-varying unknown degradations</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
</tbody>
</table>



## 4D


<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="https://arxiv.org/pdf/2504.08366">In-2-4D: Inbetweening from Two Single-View Images to 4D Generation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Park_Temporal_Interpolation_Is_All_You_Need_for_Dynamic_Neural_Radiance_CVPR_2023_paper.pdf">Temporal interpolation is all you need for dynamic neural radiance fields</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Zheng_NeuralPCI_Spatio-Temporal_Neural_Field_for_3D_Point_Cloud_Multi-Frame_Non-Linear_CVPR_2023_paper.pdf">Neuralpci: Spatio-temporal neural field for 3d point cloud multi-frame non-linear interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Peng_PAPR_in_Motion_Seamless_Point-level_3D_Scene_Interpolation_CVPR_2024_paper.pdf">PAPR in Motion: Seamless Point-level 3D Scene Interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>





## 📊 Datasets & Benchmarks 

We include commonly used datasets for evaluating VFI performance.  
Datasets are categorized into **Triplet** and **Multi-frame** types depending on the supervision format.

---

### 🔹 Triplet Datasets

Early learning-based VFI approaches primarily rely on triplet datasets, where two input frames are used to predict the temporally centered GT frame.

- <a href="https://vision.middlebury.edu/flow/" target="_blank"><strong>Middlebury</strong></a>: Originally designed for optical flow, Middlebury contains short video clips with moderate complexity. Its small size limits scalability, but it remains a standard benchmark for consistency evaluation.

- <a href="https://www.crcv.ucf.edu/data/UCF101.php" target="_blank"><strong>UCF101</strong></a>: A human action dataset from which a small subset of triplets is used for VFI. Due to its low resolution and simple motion, it is mainly used for training or sanity checks.

- <a href="http://toflow.csail.mit.edu/" target="_blank"><strong>Vimeo90K</strong></a>: A widely adopted benchmark with diverse scenes and consistent format. It offers clean supervision and balanced motion complexity, making it ideal for comparative analysis.

- <a href="https://myungsub.github.io/CAIN/" target="_blank"><strong>SNU-FILM</strong></a>: Constructed from high-speed footage and categorized by motion difficulty, SNU-FILM enables evaluation across varying levels of motion, occlusion, and blur.

- <a href="https://github.com/cheind/atd" target="_blank"><strong>ATD-12K</strong></a>: A large-scale animation dataset with rich stylistic diversity. Its variation in artistic textures and motion patterns supports both general-purpose and domain-specific evaluation.

---

### 🔸 Multi-frame Datasets

Multi-frame datasets enable dense temporal supervision and are commonly used in both CTFI and ATFI settings. They support flexible frame sampling and evaluation under diverse temporal intervals.

- <a href="https://media.xiph.org/" target="_blank"><strong>Xiph</strong></a>: A curated set of 4K video sequences designed for assessing interpolation fidelity in subtle motion settings.

- <a href="http://www.cvlibs.net/datasets/kitti/" target="_blank"><strong>KITTI</strong></a>: Captured in autonomous driving scenarios, KITTI poses unique challenges with sparse GT and large ego-motion.

- <a href="http://sintel.is.tue.mpg.de/" target="_blank"><strong>Sintel</strong></a>: A synthetic dataset rendered from the Sintel film, offering photorealistic motion and structured flow annotations.

- <a href="https://davischallenge.org/" target="_blank"><strong>DAVIS</strong></a>: Originally for segmentation, DAVIS features complex object motion, occlusion, and deformation, offering rich dynamics for interpolation.

- <a href="http://www.cs.ubc.ca/labs/imager/tr/2017/DeepVideoDeblurring/DeepVideoDeblurring_Dataset.zip" target="_blank"><strong>Adobe240</strong></a>: Collected at 240fps, this dataset captures real-world motion blur and lighting changes, ideal for fine-grained temporal modeling.

- <a href="https://seungjunnah.github.io/Datasets/gopro" target="_blank"><strong>GOPRO</strong></a>: Featuring high-frame-rate recordings with handheld cameras, GOPRO provides realistic non-linear motion and defocus blur.

- <a href="https://github.com/JunHeum/Zooming-Slow-Mo" target="_blank"><strong>Youtube240</strong></a>: A large-scale, in-the-wild dataset collected from YouTube, encompassing varied content and challenging motion artifacts.

- <a href="https://media.xiph.org/" target="_blank"><strong>HD</strong></a>: A subset of high-resolution content from Xiph, with sharper motion content suited for realistic evaluation.

- <a href="https://github.com/CM-BF/X4K1000FPS" target="_blank"><strong>X4K1000FPS</strong></a>: A premier benchmark for ultra-slow motion and long-range interpolation, thanks to its dense 1000fps and 4K capture settings.

- <a href="https://m-bain.github.io/webvid-dataset/" target="_blank"><strong>WebVid-10M</strong></a>: A large-scale web video corpus originally built for text-video tasks. Its size and diversity support generative VFI when properly filtered.

- <a href="https://github.com/dingkeyan93/LAVIB" target="_blank"><strong>LAVIB</strong></a>: Designed for large-scale, diverse-domain evaluation with balanced splits and curated subsets for out-of-distribution testing.

- <a href="https://github.com/wgcban/OpenVid" target="_blank"><strong>OpenVid</strong></a>: A text-video dataset supporting multi-modal VFI and DM-based interpolation research via dense, aligned samples.

---

## 📈 Evaluation Metrics

This section summarizes commonly used metrics for evaluating the quality of video frame interpolation (VFI) results.

---

### 📷 Image-level Metrics

These metrics compare each interpolated frame to its ground truth (GT) reference on a pixel level.

- <a href="https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio" target="_blank"><strong>PSNR (Peak Signal-to-Noise Ratio)</strong></a>  
  Measures reconstruction fidelity via Mean Squared Error (MSE).  
  📌 Higher is better, but it often doesn't align with human perception, especially in high-frequency regions.

- <a href="https://en.wikipedia.org/wiki/Structural_similarity" target="_blank"><strong>SSIM (Structural Similarity Index)</strong></a>  
  Compares luminance, contrast, and texture to evaluate structural similarity.  
  📌 More perceptually aligned than PSNR. Higher SSIM indicates stronger similarity.

- <strong>IE (Interpolation Error)</strong>  
  Root-mean-square error between the interpolated and GT frame.  
  📌 Simple and intuitive but limited in perceptual relevance.

---

### 👁️ Perceptual Metrics

These metrics better reflect human perception by analyzing textures, semantics, and style.

- <a href="https://live.ece.utexas.edu/research/quality/niqe_release.zip" target="_blank"><strong>NIQE (Natural Image Quality Evaluator)</strong></a>  
  A no-reference metric using statistical deviations from natural images.  
  📌 Lower NIQE implies higher natural image quality.

- <a href="https://github.com/mseitzer/pytorch-fid" target="_blank"><strong>FID (Fréchet Inception Distance)</strong></a>  
  Measures distributional difference in features between generated and GT frames.  
  📌 Lower FID indicates better semantic alignment.

- <a href="https://github.com/richzhang/PerceptualSimilarity" target="_blank"><strong>LPIPS (Learned Perceptual Image Patch Similarity)</strong></a>  
  Uses deep features to assess perceptual similarity.  
  📌 Lower LPIPS = better perceptual similarity.

- <strong>FloLPIPS</strong>  
  Motion-aware LPIPS variant that uses optical flow for weighting.

- <strong>STLPIPS</strong>  
  Shift-tolerant version of LPIPS, robust to slight misalignments.

- <a href="https://github.com/dingkeyan93/DISTS" target="_blank"><strong>DISTS (Deep Image Structure and Texture Similarity)</strong></a>  
  Separately evaluates structure and texture using deep features.  
  📌 Balances local detail and global coherence.

---

### 🎞️ Video-level Metrics

These metrics evaluate spatiotemporal coherence across video sequences, important for smooth motion and consistency.

- <a href="https://github.com/zwx8981/VSFA" target="_blank"><strong>VSFA (Video Spatial-Feature Aggregation)</strong></a>  
  No-reference model estimating perceptual quality from human-labeled videos using deep recurrent features.  
  📌 Lower score = better perceived video quality.

- <strong>tOF (temporal Optical Flow consistency)</strong>  
  Measures how consistent optical flow is across frames.  
  📌 Lower tOF = smoother motion continuity.

- <a href="https://github.com/google-research/google-research/tree/master/frechet_video_distance" target="_blank"><strong>FVD (Fréchet Video Distance)</strong></a>  
  Uses I3D features to compare real vs generated video distributions.  
  📌 Lower FVD = better realism and temporal quality.

- <strong>FVMD (Fréchet Video Motion Distance)</strong>  
  Enhances FVD by disentangling motion from appearance for better motion consistency evaluation.

- <strong>VBench</strong>  
  Large-scale, no-reference benchmark for evaluating fidelity, coherence, and realism using semantic video representations.  
  📌 Ideal for reference-free evaluation.
