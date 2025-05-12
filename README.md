# Awesome-Video-Frame-Interpolation
### Advances in Video Frame Interpolation: A Comprehensive Survey

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

> 📝 **Authors**: Dahyeon Kye\*, Changhyun Roh, Hyeonjun Sim, Sukhun Ko, Chanho Eom, Jihyong Oh†

> 🎓 **Institution**: Chung-Ang University, Department of Imaging Science, GSAIM  
> 🏢 **Affiliation**: Qualcomm 

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
- [📊 Benchmarks & Datasets](#benchmarks-datasets)
- [📈 Metrics](#metrics)


---

## 📣 News

- 📌 2025-05-01: Paper submitted to TPAMI!
- 🧪 2025-04-20: Benchmarked latest diffusion-based VFI models.
- 🚀 2025-03-15: Repository initialized.

---

## 🔖 BibTeX

If you find this survey helpful, please consider citing us:

```bibtex
@article{your2025vfi,
  title={Advances in Video Frame Interpolation: A Comprehensive Survey},
  author={Your Name and Collaborator 1 and Collaborator 2},
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
<details>
<summary><strong>Feature Extraction Network</strong></summary>

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

</details>

<details>
<summary><strong>VFI</strong></summary>

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

</details>

<details>
<summary><strong>Application</strong></summary>

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
<tr><td align="left"><a href="#">Video compression through image interpolation</a></td><td align="center">ECCV</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Super slomo: High quality estimation of multiple intermediate frames for video interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Video enhancement with task-oriented flow</a></td><td align="center">International Journal of Computer Vision</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Depth-aware video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Zooming slow-mo: Fast and accurate one-stage space-time video super-resolution</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Neural scene flow fields for space-time view synthesis of dynamic scenes</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Make-a-video: Text-to-video generation without text-video data</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Neighbor correspondence matching for flow-based video frame synthesis</a></td><td align="center">Proceedings of the 30th ACM International Conference on Multimedia</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Compressed video restoration using a generative adversarial network for subjective quality enhancement</a></td><td align="center">IEIE Transactions on Smart Processing \& Computing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Real-time video prediction with fast video interpolation model and prediction training</a></td><td align="center">2024 IEEE International Conference on Image Processing (ICIP)</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Tango: Co-speech gesture video reenactment with hierarchical audio motion embedding and diffusion interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Video Motion Graphs</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">Dynamic Framerate SlowFast Network for Improving Autonomous Driving Performance</a></td><td align="center">IEIE Transactions on Smart Processing \& Computing</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Scale-adaptive feature aggregation for efficient space-time video super-resolution</a></td><td align="center">Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Subjective and objective quality assessment of high frame rate videos</a></td><td align="center">IEEE</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Perceptual quality assessment for video frame interpolation</a></td><td align="center">2023 IEEE International Conference on Visual Communications and Image Processing (VCIP)</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">BVI-VFI: a video quality database for video frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Comparing H. 265/HEVC and VP9: Impact of high frame rates on the perceptual quality of compressed videos</a></td><td align="center">arXiv</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Subjective and objective quality assessment of high frame rate videos</a></td><td align="center">IEEE</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">A perceptual quality metric for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Challenges</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Determining optical flow</a></td><td align="center">Artificial intelligence</td><td align="center">1981</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Motion-Compensated</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Fractional frame rate up-conversion using weighted median filters</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">1989</td></tr>
<tr><td align="left"><a href="#">Motion compensation based on spatial transformations</a></td><td align="center">IEEE on circuits and systems for video technology</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="#">A method for motion adaptive frame rate up-conversion</a></td><td align="center">IEEE on circuits and Systems for Video Technology</td><td align="center">1996</td></tr>
<tr><td align="left"><a href="#">Adaptive motion-compensated interpolation for frame rate up-conversion</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2002</td></tr>
<tr><td align="left"><a href="#">Motion compensated frame interpolation by new block-based motion estimation algorithm</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2004</td></tr>
<tr><td align="left"><a href="#">Motion-compensated frame interpolation using bilateral motion estimation and adaptive overlapped block motion compensation</a></td><td align="center">IEEE on Circuits and Systems for Video Technology</td><td align="center">2007</td></tr>
<tr><td align="left"><a href="#">Motion compensated frame rate up-conversion using extended bilateral motion estimation</a></td><td align="center">IEEE on Consumer Electronics</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="#">A multistage motion vector processing method for motion-compensated frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="#">Motion-compensated frame rate up-conversion—Part I: Fast multi-frame motion estimation</a></td><td align="center">IEEE on Broadcasting</td><td align="center">2010</td></tr>
<tr><td align="left"><a href="#">Motion-compensated frame rate up-conversion—Part II: New algorithms for frame interpolation</a></td><td align="center">IEEE on Broadcasting</td><td align="center">2010</td></tr>
<tr><td align="left"><a href="#">Frame rate up conversion based on variational image fusion</a></td><td align="center">IEEE TIP</td><td align="center">2013</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>GAN-Based</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Frame interpolation with multi-scale deep loss functions and generative adversarial networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Frame interpolation using generative adversarial networks</a></td><td align="center"></td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Multi-scale attention generative adversarial networks for video frame interpolation</a></td><td align="center">IEEE</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Efficient video frame interpolation using generative adversarial networks</a></td><td align="center">Applied Sciences</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Frame-GAN: Increasing the frame rate of gait videos with generative adversarial networks</a></td><td align="center">Neurocomputing</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation via down--up scale generative adversarial networks</a></td><td align="center">Computer Vision and Image Understanding</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Generating realistic videos from keyframes with concatenated GANs</a></td><td align="center">IEEE on Circuits and Systems for Video Technology</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">St-mfnet: A spatio-temporal multi-flow network for frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Improved training of wasserstein gans</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Began: Boundary equilibrium generative adversarial networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Wasserstein generative adversarial networks</a></td><td align="center">ICML</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Autoencoding beyond pixels using a learned similarity metric</a></td><td align="center">ICML</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="#">Generative adversarial networks for video-to-video domain adaptation</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Diffusion-Based</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Novel view synthesis with diffusion models</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Mcvd-masked conditional video diffusion for prediction, generation, and interpolation</a></td><td align="center">NeurIPS</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Ldmvfi: Video frame interpolation with latent diffusion models</a></td><td align="center">AAAI</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Video interpolation with diffusion models</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Motion-aware latent diffusion models for video frame interpolation</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Dreammover: Leveraging the prior of diffusion models for image interpolation with large motion</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Generative inbetweening: Adapting image-to-video models for keyframe interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Explorative inbetweening of time and space</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Frame Interpolation with Consecutive Brownian Bridge Diffusion</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Generative Inbetweening through Frame-wise Conditions-Driven Video Generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">ViBiDSampler: Enhancing Video Interpolation Using Bidirectional Diffusion Sampler</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Motion-Aware Generative Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">EDEN: Enhanced Diffusion for High-quality Large-motion Video Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">Hierarchical Flow Diffusion for Efficient Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Flow-Based</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Digital image warping</a></td><td align="center"></td><td align="center">1990</td></tr>
<tr><td align="left"><a href="#">Spatial transformer networks</a></td><td align="center">NeurIPS</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="#">Video frame synthesis using deep voxel flow</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Deep video frame interpolation using cyclic frame generation</a></td><td align="center">AAAI</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Zoom-in-to-check: Boosting video interpolation via instance-level discrimination</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Unsupervised video interpolation using cycle consistency</a></td><td align="center">ICCV</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Quadratic video interpolation</a></td><td align="center">NeurIPS</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">All at once: Temporally adaptive multi-frame interpolation with advanced motion modeling</a></td><td align="center">ECCV, Glasgow, UK, August 23--28, 2020, Proceedings, Part XXVII 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Softmax splatting for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Enhanced quadratic video interpolation</a></td><td align="center">Computer Vision--ECCV 2020 Workshops: Glasgow, UK, August 23--28, 2020, Proceedings, Part IV 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">A flexible recurrent residual pyramid network for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Xvfi: extreme video frame interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Many-to-many splatting for efficient video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Ifrnet: Intermediate feature refine network for efficient frame interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Asymmetric bilateral motion estimation for video frame interpolation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Real-time intermediate flow estimation for video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Learning cross-video neural representations for high-quality frame interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Film: Frame interpolation for large motion</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Splatting-based synthesis for video frame interpolation</a></td><td align="center">Proceedings of the IEEE/CVF winter conference on applications of computer vision</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Enhanced bi-directional motion estimation for video frame interpolation</a></td><td align="center">Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Biformer: Learning bilateral motion estimation via bilateral transformer for 4k video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">A unified pyramid recurrent network for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Amt: All-pairs multi-field transforms for efficient frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Extracting motion and appearance via inter-frame attention for efficient video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">IQ-VFI: implicit quadratic motion estimation for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Ocai: Improving optical flow estimation by occlusion and consistency aware interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Generalizable implicit motion modeling for video frame interpolation</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Perception-oriented video frame interpolation via asymmetric blending</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Clearer frames, anytime: Resolving velocity ambiguity in video frame interpolation</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">BiM-VFI: directional Motion Field-Guided Frame Interpolation for Video with Non-uniform Motions</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Unified Arbitrary-Time Video Frame Interpolation and Prediction</a></td><td align="center">ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</td><td align="center">2025</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Flow Network</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Symmetric stereo matching for occlusion handling</a></td><td align="center">2005 IEEE Computer Society Conference on Computer Vision and Pattern Recognition (CVPR'05)</td><td align="center">2005</td></tr>
<tr><td align="left"><a href="#">Learning to estimate hidden motions with global motion aggregation</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">DeepFlow: Large displacement optical flow with deep matching</a></td><td align="center">ICCV</td><td align="center">2013</td></tr>
<tr><td align="left"><a href="#">Flownet: Learning optical flow with convolutional networks</a></td><td align="center">ICCV</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="#">Flownet 2.0: Evolution of optical flow estimation with deep networks</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Optical flow estimation using a spatial pyramid network</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Occlusion aware unsupervised learning of optical flow</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Pwc-net: Cnns for optical flow using pyramid, warping, and cost volume</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Liteflownet: A lightweight convolutional neural network for optical flow estimation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Refined TV-L 1 optical flow estimation using joint filtering</a></td><td align="center">IEEE on Multimedia</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Raft: Recurrent all-pairs field transforms for optical flow</a></td><td align="center">ECCV, Glasgow, UK, August 23--28, 2020, Proceedings, Part II 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Flowformer: A transformer architecture for optical flow</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Gmflow: Learning optical flow via global matching</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Kernel-Based</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">ImageNet classification with deep convolutional neural networks</a></td><td align="center">Communications of the ACM</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Deformable convolutional networks</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Deformable convnets v2: More deformable, better results</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Learning image matching by simply watching video</a></td><td align="center">ECCV, Amsterdam, The Netherlands, October 11-14, 2016, Proceedings, Part VI 14</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation via adaptive convolution</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation via adaptive separable convolution</a></td><td align="center">ICCV</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Im-net for high resolution video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation via generalized deformable convolution</a></td><td align="center">IEEE on multimedia</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Channel attention is all you need for video frame interpolation</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation via deformable separable convolution</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation via generalized deformable convolution</a></td><td align="center">IEEE on multimedia</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Multiple video frame interpolation via enhanced deformable separable convolution</a></td><td align="center">TPAMI</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Cdfi: Compression-driven network design for frame interpolation</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">PDWN: Pyramid deformable warping network for video interpolation</a></td><td align="center">IEEE of Signal Processing</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Enhancing deformable convolution based video frame interpolation with coarse-to-fine 3D CNN</a></td><td align="center">2022 IEEE International Conference on Image Processing (ICIP)</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation via local lightweight bidirectional encoding with channel attention cascade</a></td><td align="center">ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Flavr: Flow-agnostic video representations for fast frame interpolation</a></td><td align="center">Proceedings of the IEEE/CVF winter conference on applications of computer vision</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Exploring motion ambiguity and alignment for high-quality video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Kernel-Flow Combined</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Context-aware synthesis for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Memc-net: Motion estimation and motion compensation driven neural network for video interpolation and enhancement</a></td><td align="center">TPAMI</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Bmbc: Bilateral motion estimation with bilateral cost volume for video interpolation</a></td><td align="center">ECCV, Glasgow, UK, August 23--28, 2020, Proceedings, Part XIV 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Adacof: Adaptive collaboration of flows for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Featureflow: Robust video interpolation via structure-to-texture generation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Revisiting adaptive convolutions for video frame interpolation</a></td><td align="center">Proceedings of the IEEE/CVF winter conference on applications of computer vision</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">LADDER: An Efficient Framework for Video Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Phase-Based</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Shiftable multiscale transforms</a></td><td align="center">IEEE on Information Theory</td><td align="center">1992</td></tr>
<tr><td align="left"><a href="#">The steerable pyramid: A flexible architecture for multi-scale derivative computation</a></td><td align="center">Proceedings., international conference on image processing</td><td align="center">1995</td></tr>
<tr><td align="left"><a href="#">A parametric texture model based on joint statistics of complex wavelet coefficients</a></td><td align="center">International journal of computer vision</td><td align="center">2000</td></tr>
<tr><td align="left"><a href="#">Phase-based frame interpolation for video</a></td><td align="center">CVPR</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="#">Phasenet for video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Phase-based video motion processing</a></td><td align="center">TOG (ToG)</td><td align="center">2013</td></tr>
<tr><td align="left"><a href="#">Joint view expansion and filtering for automultiscopic 3D displays</a></td><td align="center">TOG (TOG)</td><td align="center">2013</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Transformer-Based</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Learning phrase representations using RNN encoder-decoder for statistical machine translation</a></td><td align="center">arXiv</td><td align="center">2014</td></tr>
<tr><td align="left"><a href="#">Attention is all you need</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Swin transformer: Hierarchical vision transformer using shifted windows</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation with transformer</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation transformer</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">L2BEC2: Local lightweight bidirectional encoding and channel attention cascade for video frame interpolation</a></td><td align="center">ACM Transactions on Multimedia Computing, Communications and Applications</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">TTVFI: Learning trajectory-aware transformer for video frame interpolation</a></td><td align="center">IEEE TIP</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Sparse global matching for video frame interpolation with large motion</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Restormer: Efficient transformer for high-resolution image restoration</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Mamba</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Unitary evolution recurrent neural networks</a></td><td align="center">ICML</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="#">Efficiently modeling long sequences with structured state spaces</a></td><td align="center">arXiv</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Mamba: Linear-time sequence modeling with selective state spaces</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Vfimamba: Video frame interpolation with state space models</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Mambair: A simple baseline for image restoration with state-space model</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">MambaIRv2: Attentive State Space Restoration</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">IRSRMamba: Infrared Image Super-Resolution via Mamba-based Wavelet Transform Feature Modulation Model</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Learning enriched features via selective state spaces model for efficient image deblurring</a></td><td align="center">ACM MM</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Efficient visual state space model for image deblurring</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">MaIR: A Locality-and Continuity-Preserving Mamba for Image Restoration</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">QMambaBSR: Burst Image Super-Resolution with Query State Space Model</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">MambaFlow: A Mamba-Centric Architecture for End-to-End Optical Flow Estimation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">First-order State Space Model for Lightweight Image Super-resolution</a></td><td align="center">ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</td><td align="center">2025</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Deep learning-Based vs. Generative</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Very deep convolutional neural network based image classification using small training sample size</a></td><td align="center">2015 3rd IAPR Asian conference on pattern recognition (ACPR)</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="#">Visual quality assessment for interpolated slow-motion videos based on a novel database</a></td><td align="center">2020 Twelfth International Conference on Quality of Multimedia Experience (QoMEX)</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">A subjective quality study for video frame interpolation</a></td><td align="center">2022 IEEE International Conference on Image Processing (ICIP)</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Cascaded diffusion models for high fidelity image generation</a></td><td align="center">JMLR</td><td align="center">2022</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>GAN</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Generative adversarial networks</a></td><td align="center">Communications of the ACM</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Auto-encoding variational bayes</a></td><td align="center"></td><td align="center">2013</td></tr>
<tr><td align="left"><a href="#">Diffusion models beat gans on image synthesis</a></td><td align="center">NeurIPS</td><td align="center">2021</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>DM-Based</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Denoising diffusion probabilistic models</a></td><td align="center">NeurIPS</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Denoising diffusion implicit models</a></td><td align="center">arXiv</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">High-resolution image synthesis with latent diffusion models</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Video diffusion models</a></td><td align="center">NeurIPS</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Align your latents: High-resolution video synthesis with latent diffusion models</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Stable video diffusion: Scaling latent video diffusion models to large datasets</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Consistency models</a></td><td align="center"></td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Elucidating the design space of diffusion-based generative models</a></td><td align="center">NeurIPS</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Progressive distillation for fast sampling of diffusion models</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Latent consistency models: Synthesizing high-resolution images with few-step inference</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">One-step diffusion with distribution matching distillation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Adapters</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Adding conditional control to text-to-image diffusion models</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Controlnext: Powerful and efficient control for image and video generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>T2V and I2V</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Tune-a-video: One-shot tuning of image diffusion models for text-to-video generation</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Cogvideox: Text-to-video diffusion models with an expert transformer</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Identity-Preserving Text-to-Video Generation by Frequency Decomposition</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Lumiere: A space-time diffusion model for video generation</a></td><td align="center">SIGGRAPH Asia 2024 Conference Papers</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">I2vgen-xl: High-quality image-to-video synthesis via cascaded diffusion models</a></td><td align="center">arXiv</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Consisti2v: Enhancing visual consistency for image-to-video generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Animate anyone: Consistent and controllable image-to-video synthesis for character animation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Event-Based</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">A 128 $\times$ 128 120 dB 15 $\mu$ s latency asynchronous temporal contrast vision sensor</a></td><td align="center">IEEE of solid-state circuits</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="#">Towards a framework for end-to-end control of a simulated vehicle with spiking neural networks</a></td><td align="center">2016 IEEE International Conference on Simulation, Modeling, and Programming for Autonomous Robots (SIMPAR)</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="#">PIX2NVS: Parameterized conversion of pixel-domain video frames to neuromorphic vision streams</a></td><td align="center">2017 IEEE International Conference on Image Processing (ICIP)</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Esim: an open event camera simulator</a></td><td align="center">Conference on robot learning</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Event-driven video frame synthesis</a></td><td align="center">ICCV Workshops</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Learning event-driven video deblurring and interpolation</a></td><td align="center">ECCV, Glasgow, UK, August 23--28, 2020, Proceedings, Part VIII 16</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Time lens: Event-based video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Eventgan: Leveraging large scale image datasets for event cameras</a></td><td align="center">2021 IEEE international conference on computational photography (ICCP)</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Training weakly supervised video frame interpolation with events</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Unifying motion deblurring and frame interpolation with events</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Time lens++: Event-based frame interpolation with parametric non-linear flow and multi-scale fusion</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Timereplayer: Unlocking the potential of event cameras for video interpolation</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Video interpolation by event-driven anisotropic adjustment of optical flow</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">A 2.97 $\mu$m-pitch event-based vision sensor with shared pixel front-end circuitry and low-noise intensity readout mode</a></td><td align="center">2023 IEEE International Solid-State Circuits Conference (ISSCC)</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Event-based video frame interpolation with cross-modal asymmetric bidirectional motion fields</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Event-guided frame interpolation and dynamic range expansion of single rolling shutter image</a></td><td align="center">Proceedings of the 31st ACM International Conference on Multimedia</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">V2ce: Video to continuous events simulator</a></td><td align="center">2024 IEEE International Conference on Robotics and Automation (ICRA)</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation via direct synthesis with the event-based reference</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">TimeLens-XL: Real-Time Event-Based Video Frame Interpolation with Large Motion</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Repurposing pre-trained video diffusion models for event-based video interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">EGVD: Event-Guided Video Diffusion Model for Physically Realistic Large-Motion Frame Interpolation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">Coupled Video Frame Interpolation and Encoding with Hybrid Event Cameras for Low-Power High-Framerate Video</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Event + SR</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Turning frequency to resolution: Video super-resolution via event cameras</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Learning spatial-temporal implicit neural representations for event-guided video super-resolution</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">EvTexture: event-driven texture enhancement for video super-resolution</a></td><td align="center">Forty-first ICML</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Medic</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">A spatiotemporal volumetric interpolation network for 4d dynamic medical image</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Data-efficient unsupervised interpolation without any intermediate frame for 4d medical images</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">CPT-Interp: Continuous sPatial and Temporal Motion Modeling for 4D Medical Image Interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Cartoon Interpolation</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Deep animation video interpolation in the wild</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Improving the perceptual quality of 2d animation interpolation</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Deep sketch-guided cartoon video inbetweening</a></td><td align="center">IEEE on Visualization and Computer Graphics</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Dynamicrafter: Animating open-domain images with video diffusion priors</a></td><td align="center">ECCV</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Tooncrafter: Generative cartoon interpolation</a></td><td align="center">TOG (TOG)</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Framer: Interactive frame interpolation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Anidoc: Animation creation made easier</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">LayerAnimate: Layer-specific control for animation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">Learning inclusion matching for animation paint bucket colorization</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">PhysAnimator: Physics-Guided Generative Cartoon Animation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">Time-adaptive Video Frame Interpolation based on Residual Diffusion</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">High-Resolution Frame Interpolation with Patch-based Cascaded Diffusion</a></td><td align="center">AAAI</td><td align="center">2025</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Game?</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">AnyMoLe: Any Character Motion In-betweening Leveraging Video Diffusion Models</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Joint: SR</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Increasing space-time resolution in video</a></td><td align="center">Computer Vision—ECCV 2002: 7th ECCV Copenhagen, Denmark, May 28--31, 2002 Proceedings, Part I 7</td><td align="center">2002</td></tr>
<tr><td align="left"><a href="#">Fisr: Deep joint frame interpolation and super-resolution with a multi-scale temporal loss</a></td><td align="center">AAAI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Space-time-aware multi-resolution video enhancement</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Temporal modulation network for controllable space-time video super-resolution</a></td><td align="center">CVPR</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Motif: Learning motion trajectories with local implicit neural functions for continuous space-time video super-resolution</a></td><td align="center">ICCV</td><td align="center">2023</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Joint: Deblur</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Video frame interpolation without temporal priors</a></td><td align="center">NeurIPS</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Video frame interpolation and enhancement via pyramid recurrent framework</a></td><td align="center">IEEE TIP</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Blurry video frame interpolation</a></td><td align="center">CVPR</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Animation from blur: Multi-modal blur decomposition with motion guidance</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Demfi: deep joint deblurring and multi-frame interpolation with flow-guided attentive correlation and recursive boosting</a></td><td align="center">ECCV</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Joint video multi-frame interpolation and deblurring under unknown exposure time</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Latency correction for event-guided deblurring and frame interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Loss Function</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Two deterministic half-quadratic regularization algorithms for computed imaging</a></td><td align="center">Proceedings of 1st international conference on image processing</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="#">Deep multi-scale video prediction beyond mean square error</a></td><td align="center">arXiv</td><td align="center">2015</td></tr>
<tr><td align="left"><a href="#">Photo-realistic single image super-resolution using a generative adversarial network</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Optimizing the latent space of generative networks</a></td><td align="center">arXiv</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Non-parametric local transforms for computing visual correspondence</a></td><td align="center">ECCV</td><td align="center">1994</td></tr>
<tr><td align="left"><a href="#">Unflow: Unsupervised learning of optical flow with a bidirectional census loss</a></td><td align="center">AAAI</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Df-net: Unsupervised joint learning of depth and flow using cross-task consistency</a></td><td align="center">ECCV</td><td align="center">2018</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Dataset</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Xiph.org video test media (derf's collection)</a></td><td align="center"></td><td align="center">1994</td></tr>
<tr><td align="left"><a href="#">A database and evaluation methodology for optical flow</a></td><td align="center">Int. J. Comput. Vis.</td><td align="center">2011</td></tr>
<tr><td align="left"><a href="#">UCF101: A dataset of 101 human actions classes from videos in the wild</a></td><td align="center">arXiv</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="#">Are we ready for autonomous driving? the kitti vision benchmark suite</a></td><td align="center">CVPR</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="#">A naturalistic open source movie for optical flow evaluation</a></td><td align="center">ECCV</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="#">A benchmark dataset and evaluation methodology for video object segmentation</a></td><td align="center">CVPR</td><td align="center">2016</td></tr>
<tr><td align="left"><a href="#">THUMOS challenge: Action recognition with a large number of classes</a></td><td align="center"></td><td align="center">2015</td></tr>
<tr><td align="left"><a href="#">Slow flow: Exploiting high-speed cameras for accurate and diverse optical flow reference data</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Deep video deblurring for hand-held cameras</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Deep multi-scale convolutional neural network for dynamic scene deblurring</a></td><td align="center">CVPR</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">Frozen in time: A joint video and image encoder for end-to-end retrieval</a></td><td align="center">ICCV</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Lavib: A large-scale video interpolation benchmark</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Openvid-1M: A large-scale high-quality dataset for text-to-video generation</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Metric</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Image quality assessment: from error visibility to structural similarity</a></td><td align="center">IEEE Trans. Image Process.</td><td align="center">2004</td></tr>
<tr><td align="left"><a href="#">A new objective quality metric for frame interpolation used in video compression</a></td><td align="center">IEEE on broadcasting</td><td align="center">2008</td></tr>
<tr><td align="left"><a href="#">Making a “completely blind” image quality analyzer</a></td><td align="center">IEEE Signal processing letters</td><td align="center">2012</td></tr>
<tr><td align="left"><a href="#">Gans trained by a two time-scale update rule converge to a local nash equilibrium</a></td><td align="center">NeurIPS</td><td align="center">2017</td></tr>
<tr><td align="left"><a href="#">The unreasonable effectiveness of deep features as a perceptual metric</a></td><td align="center">CVPR</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Towards accurate generative models of video: A new metric \& challenges</a></td><td align="center">arXiv</td><td align="center">2018</td></tr>
<tr><td align="left"><a href="#">Fr$\backslash$'echet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos</a></td><td align="center">arXiv</td><td align="center">2024</td></tr>
<tr><td align="left"><a href="#">Quality assessment of in-the-wild videos</a></td><td align="center">Proceedings of the 27th ACM international conference on multimedia</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">Image quality assessment: Unifying structure and texture similarity</a></td><td align="center">TPAMI</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">A loss function for generative neural networks based on watson’s perceptual model</a></td><td align="center">NeurIPS</td><td align="center">2020</td></tr>
<tr><td align="left"><a href="#">Learning transferable visual models from natural language supervision</a></td><td align="center">ICML</td><td align="center">2021</td></tr>
<tr><td align="left"><a href="#">Image super-resolution via iterative refinement</a></td><td align="center">TPAMI</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">FloLPIPS: A bespoke video quality metric for frame interpolation</a></td><td align="center">2022 Picture Coding Symposium (PCS)</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Vbench: Comprehensive benchmark suite for video generative models</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>Future Research Direction</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Semantic-Aware Adaptive Video Streaming Using Latent Diffusion Models for Wireless Networks</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">Cadm: Codec-aware diffusion modeling for neural-enhanced video streaming</a></td><td align="center">arXiv</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Improved conditional vrnns for video prediction</a></td><td align="center">ICCV</td><td align="center">2019</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>All-in-One: Image</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">All-in-one image restoration for unknown corruption</a></td><td align="center">CVPR</td><td align="center">2022</td></tr>
<tr><td align="left"><a href="#">Content-Aware Transformer for All-in-one Image Restoration</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">Multimodal prompt perceiver: Empower adaptiveness generalizability and fidelity for all-in-one image restoration</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>All-in-One: Video</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">Edvr: Video restoration with enhanced deformable convolutional networks</a></td><td align="center">CVPR workshops</td><td align="center">2019</td></tr>
<tr><td align="left"><a href="#">AverNet: All-in-one video restoration for time-varying unknown degradations</a></td><td align="center">NeurIPS</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>

<details>
<summary><strong>4D</strong></summary>

<table>
<thead>
<tr>
<th align="left">Title</th>
<th align="center">Publication</th>
<th align="center">Date</th>
</tr>
</thead>
<tbody>
<tr><td align="left"><a href="#">In-2-4D: Inbetweening from Two Single-View Images to 4D Generation</a></td><td align="center">arXiv</td><td align="center">2025</td></tr>
<tr><td align="left"><a href="#">Temporal interpolation is all you need for dynamic neural radiance fields</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">Neuralpci: Spatio-temporal neural field for 3d point cloud multi-frame non-linear interpolation</a></td><td align="center">CVPR</td><td align="center">2023</td></tr>
<tr><td align="left"><a href="#">PAPR in Motion: Seamless Point-level 3D Scene Interpolation</a></td><td align="center">CVPR</td><td align="center">2024</td></tr>
</tbody>
</table>

</details>



### 📊 <a name="benchmarks-datasets"></a>Benchmarks & Datasets

Includes commonly used datasets:

- Vimeo90K  
- UCF101  
- DAVIS  
- SNU-FILM  
- Adobe240/60fps  

And evaluation metrics:

- PSNR / SSIM  
- LPIPS / tOF  
- Interpolation Error (IE)  


---





### 📈 <a name="metrics"></a>Metrics

(Provide detailed descriptions or references of metrics like PSNR, SSIM, LPIPS, tOF, and Interpolation Error here if needed.)

