# Awesome-Video-Frame-Interpolation
### Advances in Video Frame Interpolation: A Comprehensive Survey

<p align="center">
  <img src="./media/title.png" alt="Survey Title Image" width="800"/>
</p>

[![awesome](https://img.shields.io/badge/awesome-yes-critical?style=flat&logo=awesome-lists&labelColor=purple)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=your-org.your-repo)](https://github.com/your-org/your-repo)
[![arXiv](https://img.shields.io/badge/arXiv-Preprint-b31b1b.svg)](https://arxiv.org/abs/your-paper-id)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC--BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Stars](https://img.shields.io/github/stars/your-org/your-repo.svg?style=social&label=Star)](https://github.com/your-org/your-repo)


This repository provides a curated collection of papers, benchmarks, and resources from our survey:  
**"Advances in Video Frame Interpolation: A Comprehensive Survey"** (2025, submitted to [Journal/Conference]).

> 📝 **Authors**: Dahyeon Kye\*, Changhyun Roh, Hyeonjun Sim, Sukhun Ko, Chanho Eom, Jihyong Oh\†

> 🎓 **Institution**: Chung-Ang University, Department of Imaging Science, GSAIM  
> 🏢 **Affiliation**: Qualcomm 

---

## 📘 Abstract

Video Frame Interpolation (VFI) is a fundamental task in video processing that aims to synthesize intermediate frames between existing ones, enabling smooth slow-motion effects, frame rate conversion, and temporal video enhancement. This survey provides a comprehensive review of the latest advancements in VFI, covering traditional motion estimation techniques, deep learning-based approaches, and emerging paradigms such as transformer-based and diffusion-based models. We present a taxonomy of VFI methods, analyze their key components, compare quantitative benchmarks, and discuss current challenges and promising future directions.

---

## 📚 Contents

- [News](#news)
- [BibTeX](#bibtex)
- [Survey Paper](#survey-paper)
- [Paper List](#paper-list)
- [Benchmarks & Datasets](#benchmarks--datasets)
- [Metrics](#metrics)


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


## 🔍 Survey Paper

You can find the preprint of our survey here:  
📄 [arXiv:your-paper-id](https://arxiv.org/abs/your-paper-id)

---

## 📄 Paper List

We categorize recent VFI papers by methodology:
<details>
<summary><strong>feature extraction network</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Very deep convolutional networks for large-scale image recognition | arXiv preprint arXiv:1409.1556 | 2014 |
| U-net: Convolutional networks for biomedical image segmentation | Medical image computing and computer-assisted intervention--MICCAI 2015: 18th international conference, Munich, Germany, October 5-9, 2015, proceedings, part III 18 | 2015 |
| 3D U-Net: learning dense volumetric segmentation from sparse annotation | Medical Image Computing and Computer-Assisted Intervention--MICCAI 2016: 19th International Conference, Athens, Greece, October 17-21, 2016, Proceedings, Part II 19 | 2016 |

</details>

<details>
<summary><strong>VFI</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Efficient feature extraction for high-resolution video frame interpolation | arXiv preprint arXiv:2211.14005 | 2022 |

</details>

<details>
<summary><strong>Application</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Prediction error as a quality metric for motion and stereo | Proceedings of the Seventh IEEE International Conference on Computer Vision | 1999 |
| View synthesis by appearance flow | Computer Vision--ECCV 2016: 14th European Conference, Amsterdam, The Netherlands, October 11--14, 2016, Proceedings, Part IV 14 | 2016 |
| Deepstereo: Learning to predict new views from the world's imagery | Proceedings of the IEEE conference on computer vision and pattern recognition | 2016 |
| Video compression through image interpolation | Proceedings of the European conference on computer vision (ECCV) | 2018 |
| Super slomo: High quality estimation of multiple intermediate frames for video interpolation | Proceedings of the IEEE conference on computer vision and pattern recognition | 2018 |
| Video enhancement with task-oriented flow | International Journal of Computer Vision | 2019 |
| Depth-aware video frame interpolation | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2019 |
| Zooming slow-mo: Fast and accurate one-stage space-time video super-resolution | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2020 |
| Neural scene flow fields for space-time view synthesis of dynamic scenes | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2021 |
| Make-a-video: Text-to-video generation without text-video data | arXiv preprint arXiv:2209.14792 | 2022 |
| Neighbor correspondence matching for flow-based video frame synthesis | Proceedings of the 30th ACM International Conference on Multimedia | 2022 |
| Compressed video restoration using a generative adversarial network for subjective quality enhancement | IEIE Transactions on Smart Processing \& Computing | 2020 |
| Real-time video prediction with fast video interpolation model and prediction training | 2024 IEEE International Conference on Image Processing (ICIP) | 2024 |
| Tango: Co-speech gesture video reenactment with hierarchical audio motion embedding and diffusion interpolation | arXiv preprint arXiv:2410.04221 | 2024 |
| Video Motion Graphs | arXiv preprint arXiv:2503.20218 | 2025 |
| KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation | arXiv preprint arXiv:2503.01715 | 2025 |
| Dynamic Framerate SlowFast Network for Improving Autonomous Driving Performance | IEIE Transactions on Smart Processing \& Computing | 2023 |
| Scale-adaptive feature aggregation for efficient space-time video super-resolution | Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision | 2024 |
| Subjective and objective quality assessment of high frame rate videos | IEEE Access | 2021 |
| Perceptual quality assessment for video frame interpolation | 2023 IEEE International Conference on Visual Communications and Image Processing (VCIP) | 2023 |
| BVI-VFI: a video quality database for video frame interpolation | IEEE Transactions on Image Processing | 2023 |
| Comparing H. 265/HEVC and VP9: Impact of high frame rates on the perceptual quality of compressed videos | arXiv preprint arXiv:2006.02671 | 2020 |
| Subjective and objective quality assessment of high frame rate videos | IEEE Access | 2021 |
| A perceptual quality metric for video frame interpolation | European Conference on Computer Vision | 2022 |

</details>

<details>
<summary><strong>challenges</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Determining optical flow | Artificial intelligence | 1981 |

</details>

<details>
<summary><strong>Motion-compensated</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Fractional frame rate up-conversion using weighted median filters | IEEE Transactions on Consumer Electronics | 1989 |
| Motion compensation based on spatial transformations | IEEE Transactions on circuits and systems for video technology | 1994 |
| A method for motion adaptive frame rate up-conversion | IEEE Transactions on circuits and Systems for Video Technology | 1996 |
| Adaptive motion-compensated interpolation for frame rate up-conversion | IEEE Transactions on Consumer Electronics | 2002 |
| Motion compensated frame interpolation by new block-based motion estimation algorithm | IEEE Transactions on Consumer Electronics | 2004 |
| Motion-compensated frame interpolation using bilateral motion estimation and adaptive overlapped block motion compensation | IEEE Transactions on Circuits and Systems for Video Technology | 2007 |
| Motion compensated frame rate up-conversion using extended bilateral motion estimation | IEEE Transactions on Consumer Electronics | 2008 |
| A multistage motion vector processing method for motion-compensated frame interpolation | IEEE transactions on image processing | 2008 |
| Motion-compensated frame rate up-conversion—Part I: Fast multi-frame motion estimation | IEEE Transactions on Broadcasting | 2010 |
| Motion-compensated frame rate up-conversion—Part II: New algorithms for frame interpolation | IEEE Transactions on Broadcasting | 2010 |
| Frame rate up conversion based on variational image fusion | IEEE Transactions on Image Processing | 2013 |

</details>

<details>
<summary><strong>GAN-based</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Frame interpolation with multi-scale deep loss functions and generative adversarial networks | arXiv preprint arXiv:1711.06045 | 2017 |
| Frame interpolation using generative adversarial networks |  | 2017 |
| Multi-scale attention generative adversarial networks for video frame interpolation | IEEE Access | 2020 |
| Efficient video frame interpolation using generative adversarial networks | Applied Sciences | 2020 |
| Frame-GAN: Increasing the frame rate of gait videos with generative adversarial networks | Neurocomputing | 2020 |
| Video frame interpolation via down--up scale generative adversarial networks | Computer Vision and Image Understanding | 2022 |
| Generating realistic videos from keyframes with concatenated GANs | IEEE Transactions on Circuits and Systems for Video Technology | 2018 |
| St-mfnet: A spatio-temporal multi-flow network for frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2022 |
| Improved training of wasserstein gans | Advances in neural information processing systems | 2017 |
| Began: Boundary equilibrium generative adversarial networks | arXiv preprint arXiv:1703.10717 | 2017 |
| Wasserstein generative adversarial networks | International conference on machine learning | 2017 |
| Autoencoding beyond pixels using a learned similarity metric | International conference on machine learning | 2016 |
| Generative adversarial networks for video-to-video domain adaptation | Proceedings of the AAAI Conference on Artificial Intelligence | 2020 |

</details>

<details>
<summary><strong>Diffusion-based</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Novel view synthesis with diffusion models | arXiv preprint arXiv:2210.04628 | 2022 |
| Mcvd-masked conditional video diffusion for prediction, generation, and interpolation | Advances in neural information processing systems | 2022 |
| Ldmvfi: Video frame interpolation with latent diffusion models | Proceedings of the AAAI Conference on Artificial Intelligence | 2024 |
| Video interpolation with diffusion models | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |
| Motion-aware latent diffusion models for video frame interpolation | Proceedings of the 32nd ACM International Conference on Multimedia | 2024 |
| Dreammover: Leveraging the prior of diffusion models for image interpolation with large motion | European Conference on Computer Vision | 2024 |
| Generative inbetweening: Adapting image-to-video models for keyframe interpolation | arXiv preprint arXiv:2408.15239 | 2024 |
| Explorative inbetweening of time and space | European Conference on Computer Vision | 2024 |
| Frame Interpolation with Consecutive Brownian Bridge Diffusion | Proceedings of the 32nd ACM International Conference on Multimedia | 2024 |
| Generative Inbetweening through Frame-wise Conditions-Driven Video Generation | arXiv preprint arXiv:2412.11755 | 2024 |
| ViBiDSampler: Enhancing Video Interpolation Using Bidirectional Diffusion Sampler | arXiv preprint arXiv:2410.05651 | 2024 |
| Motion-Aware Generative Frame Interpolation | arXiv preprint arXiv:2501.03699 | 2025 |
| EDEN: Enhanced Diffusion for High-quality Large-motion Video Frame Interpolation | arXiv preprint arXiv:2503.15831 | 2025 |
| Hierarchical Flow Diffusion for Efficient Frame Interpolation | arXiv preprint arXiv:2504.00380 | 2025 |

</details>

<details>
<summary><strong>Flow-based</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Digital image warping |  | 1990 |
| Spatial transformer networks | Advances in neural information processing systems | 2015 |
| Video frame synthesis using deep voxel flow | Proceedings of the IEEE international conference on computer vision | 2017 |
| Deep video frame interpolation using cyclic frame generation | Proceedings of the AAAI Conference on Artificial Intelligence | 2019 |
| Zoom-in-to-check: Boosting video interpolation via instance-level discrimination | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2019 |
| Unsupervised video interpolation using cycle consistency | Proceedings of the IEEE/CVF international conference on computer Vision | 2019 |
| Quadratic video interpolation | Advances in Neural Information Processing Systems | 2019 |
| All at once: Temporally adaptive multi-frame interpolation with advanced motion modeling | Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part XXVII 16 | 2020 |
| Softmax splatting for video frame interpolation | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2020 |
| Enhanced quadratic video interpolation | Computer Vision--ECCV 2020 Workshops: Glasgow, UK, August 23--28, 2020, Proceedings, Part IV 16 | 2020 |
| A flexible recurrent residual pyramid network for video frame interpolation | European conference on computer vision | 2020 |
| Xvfi: extreme video frame interpolation | Proceedings of the IEEE/CVF international conference on computer vision | 2021 |
| Many-to-many splatting for efficient video frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2022 |
| Ifrnet: Intermediate feature refine network for efficient frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2022 |
| Asymmetric bilateral motion estimation for video frame interpolation | Proceedings of the IEEE/CVF international conference on computer vision | 2021 |
| Real-time intermediate flow estimation for video frame interpolation | European Conference on Computer Vision | 2022 |
| Learning cross-video neural representations for high-quality frame interpolation | European Conference on Computer Vision | 2022 |
| Film: Frame interpolation for large motion | European Conference on Computer Vision | 2022 |
| Splatting-based synthesis for video frame interpolation | Proceedings of the IEEE/CVF winter conference on applications of computer vision | 2023 |
| Enhanced bi-directional motion estimation for video frame interpolation | Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision | 2023 |
| Biformer: Learning bilateral motion estimation via bilateral transformer for 4k video frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |
| A unified pyramid recurrent network for video frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |
| Amt: All-pairs multi-field transforms for efficient frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |
| Extracting motion and appearance via inter-frame attention for efficient video frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |
| IQ-VFI: implicit quadratic motion estimation for video frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |
| Ocai: Improving optical flow estimation by occlusion and consistency aware interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |
| Generalizable implicit motion modeling for video frame interpolation | Advances in Neural Information Processing Systems | 2024 |
| Perception-oriented video frame interpolation via asymmetric blending | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |
| Clearer frames, anytime: Resolving velocity ambiguity in video frame interpolation | European Conference on Computer Vision | 2024 |
| BiM-VFI: directional Motion Field-Guided Frame Interpolation for Video with Non-uniform Motions | arXiv preprint arXiv:2412.11365 | 2024 |
| Unified Arbitrary-Time Video Frame Interpolation and Prediction | ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) | 2025 |

</details>

<details>
<summary><strong>Flow network</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Symmetric stereo matching for occlusion handling | 2005 IEEE Computer Society Conference on Computer Vision and Pattern Recognition (CVPR'05) | 2005 |
| Learning to estimate hidden motions with global motion aggregation | Proceedings of the IEEE/CVF international conference on computer vision | 2021 |
| DeepFlow: Large displacement optical flow with deep matching | Proceedings of the IEEE international conference on computer vision | 2013 |
| Flownet: Learning optical flow with convolutional networks | Proceedings of the IEEE international conference on computer vision | 2015 |
| Flownet 2.0: Evolution of optical flow estimation with deep networks | Proceedings of the IEEE conference on computer vision and pattern recognition | 2017 |
| Optical flow estimation using a spatial pyramid network | Proceedings of the IEEE conference on computer vision and pattern recognition | 2017 |
| Occlusion aware unsupervised learning of optical flow | Proceedings of the IEEE conference on computer vision and pattern recognition | 2018 |
| Pwc-net: Cnns for optical flow using pyramid, warping, and cost volume | Proceedings of the IEEE conference on computer vision and pattern recognition | 2018 |
| Liteflownet: A lightweight convolutional neural network for optical flow estimation | Proceedings of the IEEE conference on computer vision and pattern recognition | 2018 |
| Refined TV-L 1 optical flow estimation using joint filtering | IEEE Transactions on Multimedia | 2019 |
| Raft: Recurrent all-pairs field transforms for optical flow | Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part II 16 | 2020 |
| Flowformer: A transformer architecture for optical flow | European conference on computer vision | 2022 |
| Gmflow: Learning optical flow via global matching | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2022 |

</details>

<details>
<summary><strong>Kernel-based</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| ImageNet classification with deep convolutional neural networks | Communications of the ACM | 2017 |
| Deformable convolutional networks | Proceedings of the IEEE international conference on computer vision | 2017 |
| Deformable convnets v2: More deformable, better results | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2019 |
| Learning image matching by simply watching video | Computer Vision--ECCV 2016: 14th European Conference, Amsterdam, The Netherlands, October 11-14, 2016, Proceedings, Part VI 14 | 2016 |
| Video frame interpolation via adaptive convolution | Proceedings of the IEEE conference on computer vision and pattern recognition | 2017 |
| Video frame interpolation via adaptive separable convolution | Proceedings of the IEEE international conference on computer vision | 2017 |
| Im-net for high resolution video frame interpolation | Proceedings of the IEEE/CVF conference on computer vision and pattern Recognition | 2019 |
| Video frame interpolation via generalized deformable convolution | IEEE transactions on multimedia | 2021 |
| Channel attention is all you need for video frame interpolation | Proceedings of the AAAI conference on artificial intelligence | 2020 |
| Video frame interpolation via deformable separable convolution | Proceedings of the AAAI Conference on Artificial Intelligence | 2020 |
| Video frame interpolation via generalized deformable convolution | IEEE transactions on multimedia | 2021 |
| Multiple video frame interpolation via enhanced deformable separable convolution | IEEE Transactions on Pattern Analysis and Machine Intelligence | 2021 |
| Cdfi: Compression-driven network design for frame interpolation | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2021 |
| PDWN: Pyramid deformable warping network for video interpolation | IEEE Open Journal of Signal Processing | 2021 |
| Enhancing deformable convolution based video frame interpolation with coarse-to-fine 3D CNN | 2022 IEEE International Conference on Image Processing (ICIP) | 2022 |
| Video frame interpolation via local lightweight bidirectional encoding with channel attention cascade | ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) | 2022 |
| Flavr: Flow-agnostic video representations for fast frame interpolation | Proceedings of the IEEE/CVF winter conference on applications of computer vision | 2023 |
| Exploring motion ambiguity and alignment for high-quality video frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |

</details>

<details>
<summary><strong>Kernel-Flow combined</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Context-aware synthesis for video frame interpolation | Proceedings of the IEEE conference on computer vision and pattern recognition | 2018 |
| Memc-net: Motion estimation and motion compensation driven neural network for video interpolation and enhancement | IEEE transactions on pattern analysis and machine intelligence | 2019 |
| Bmbc: Bilateral motion estimation with bilateral cost volume for video interpolation | Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part XIV 16 | 2020 |
| Adacof: Adaptive collaboration of flows for video frame interpolation | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2020 |
| Featureflow: Robust video interpolation via structure-to-texture generation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2020 |
| Revisiting adaptive convolutions for video frame interpolation | Proceedings of the IEEE/CVF winter conference on applications of computer vision | 2021 |
| LADDER: An Efficient Framework for Video Frame Interpolation | arXiv preprint arXiv:2404.11108 | 2024 |

</details>

<details>
<summary><strong>Phase-based</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Shiftable multiscale transforms | IEEE transactions on Information Theory | 1992 |
| The steerable pyramid: A flexible architecture for multi-scale derivative computation | Proceedings., international conference on image processing | 1995 |
| A parametric texture model based on joint statistics of complex wavelet coefficients | International journal of computer vision | 2000 |
| Phase-based frame interpolation for video | Proceedings of the IEEE conference on computer vision and pattern recognition | 2015 |
| Phasenet for video frame interpolation | Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition | 2018 |
| Phase-based video motion processing | ACM Transactions on Graphics (ToG) | 2013 |
| Joint view expansion and filtering for automultiscopic 3D displays | ACM Transactions on Graphics (TOG) | 2013 |

</details>

<details>
<summary><strong>Transformer-based</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Learning phrase representations using RNN encoder-decoder for statistical machine translation | arXiv preprint arXiv:1406.1078 | 2014 |
| Attention is all you need | Advances in neural information processing systems | 2017 |
| Swin transformer: Hierarchical vision transformer using shifted windows | Proceedings of the IEEE/CVF international conference on computer vision | 2021 |
| Video frame interpolation with transformer | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2022 |
| Video frame interpolation transformer | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2022 |
| L2BEC2: Local lightweight bidirectional encoding and channel attention cascade for video frame interpolation | ACM Transactions on Multimedia Computing, Communications and Applications | 2023 |
| TTVFI: Learning trajectory-aware transformer for video frame interpolation | IEEE Transactions on Image Processing | 2023 |
| Sparse global matching for video frame interpolation with large motion | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |
| Restormer: Efficient transformer for high-resolution image restoration | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2022 |

</details>

<details>
<summary><strong>Mamba</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Unitary evolution recurrent neural networks | International conference on machine learning | 2016 |
| Efficiently modeling long sequences with structured state spaces | arXiv preprint arXiv:2111.00396 | 2021 |
| Mamba: Linear-time sequence modeling with selective state spaces | arXiv preprint arXiv:2312.00752 | 2023 |
| Vfimamba: Video frame interpolation with state space models | Advances in Neural Information Processing Systems | 2024 |
| Mambair: A simple baseline for image restoration with state-space model | European conference on computer vision | 2024 |
| MambaIRv2: Attentive State Space Restoration | arXiv preprint arXiv:2411.15269 | 2024 |
| IRSRMamba: Infrared Image Super-Resolution via Mamba-based Wavelet Transform Feature Modulation Model | arXiv preprint arXiv:2405.09873 | 2024 |
| Learning enriched features via selective state spaces model for efficient image deblurring | Proceedings of the 32nd ACM International Conference on Multimedia | 2024 |
| Efficient visual state space model for image deblurring | arXiv preprint arXiv:2405.14343 | 2024 |
| MaIR: A Locality-and Continuity-Preserving Mamba for Image Restoration | arXiv preprint arXiv:2412.20066 | 2024 |
| QMambaBSR: Burst Image Super-Resolution with Query State Space Model | arXiv preprint arXiv:2408.08665 | 2024 |
| MambaFlow: A Mamba-Centric Architecture for End-to-End Optical Flow Estimation | arXiv preprint arXiv:2503.07046 | 2025 |
| First-order State Space Model for Lightweight Image Super-resolution | ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) | 2025 |

</details>

<details>
<summary><strong>Deep learning-based vs. Generative</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Very deep convolutional neural network based image classification using small training sample size | 2015 3rd IAPR Asian conference on pattern recognition (ACPR) | 2015 |
| Visual quality assessment for interpolated slow-motion videos based on a novel database | 2020 Twelfth International Conference on Quality of Multimedia Experience (QoMEX) | 2020 |
| A subjective quality study for video frame interpolation | 2022 IEEE International Conference on Image Processing (ICIP) | 2022 |
| Cascaded diffusion models for high fidelity image generation | Journal of Machine Learning Research | 2022 |

</details>

<details>
<summary><strong>GAN</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Generative adversarial networks | Communications of the ACM | 2020 |
| Auto-encoding variational bayes |  | 2013 |
| Diffusion models beat gans on image synthesis | Advances in neural information processing systems | 2021 |

</details>

<details>
<summary><strong>DM-based</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Denoising diffusion probabilistic models | Advances in neural information processing systems | 2020 |
| Denoising diffusion implicit models | arXiv preprint arXiv:2010.02502 | 2020 |
| High-resolution image synthesis with latent diffusion models | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2022 |
| Video diffusion models | Advances in Neural Information Processing Systems | 2022 |
| Align your latents: High-resolution video synthesis with latent diffusion models | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2023 |
| Stable video diffusion: Scaling latent video diffusion models to large datasets | arXiv preprint arXiv:2311.15127 | 2023 |
| Consistency models |  | 2023 |
| Elucidating the design space of diffusion-based generative models | Advances in neural information processing systems | 2022 |
| Progressive distillation for fast sampling of diffusion models | arXiv preprint arXiv:2202.00512 | 2022 |
| Latent consistency models: Synthesizing high-resolution images with few-step inference | arXiv preprint arXiv:2310.04378 | 2023 |
| One-step diffusion with distribution matching distillation | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2024 |

</details>

<details>
<summary><strong>Adapters</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Adding conditional control to text-to-image diffusion models | Proceedings of the IEEE/CVF international conference on computer vision | 2023 |
| Controlnext: Powerful and efficient control for image and video generation | arXiv preprint arXiv:2408.06070 | 2024 |

</details>

<details>
<summary><strong>T2V and I2V</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Tune-a-video: One-shot tuning of image diffusion models for text-to-video generation | Proceedings of the IEEE/CVF International Conference on Computer Vision | 2023 |
| Cogvideox: Text-to-video diffusion models with an expert transformer | arXiv preprint arXiv:2408.06072 | 2024 |
| Identity-Preserving Text-to-Video Generation by Frequency Decomposition | arXiv preprint arXiv:2411.17440 | 2024 |
| Lumiere: A space-time diffusion model for video generation | SIGGRAPH Asia 2024 Conference Papers | 2024 |
| I2vgen-xl: High-quality image-to-video synthesis via cascaded diffusion models | arXiv preprint arXiv:2311.04145 | 2023 |
| Consisti2v: Enhancing visual consistency for image-to-video generation | arXiv preprint arXiv:2402.04324 | 2024 |
| Animate anyone: Consistent and controllable image-to-video synthesis for character animation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |

</details>

<details>
<summary><strong>Event-based</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| A 128 $\times$ 128 120 dB 15 $\mu$ s latency asynchronous temporal contrast vision sensor | IEEE journal of solid-state circuits | 2008 |
| Towards a framework for end-to-end control of a simulated vehicle with spiking neural networks | 2016 IEEE International Conference on Simulation, Modeling, and Programming for Autonomous Robots (SIMPAR) | 2016 |
| PIX2NVS: Parameterized conversion of pixel-domain video frames to neuromorphic vision streams | 2017 IEEE International Conference on Image Processing (ICIP) | 2017 |
| Esim: an open event camera simulator | Conference on robot learning | 2018 |
| Event-driven video frame synthesis | Proceedings of the IEEE/CVF International Conference on Computer Vision Workshops | 2019 |
| Learning event-driven video deblurring and interpolation | Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part VIII 16 | 2020 |
| Time lens: Event-based video frame interpolation | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2021 |
| Eventgan: Leveraging large scale image datasets for event cameras | 2021 IEEE international conference on computational photography (ICCP) | 2021 |
| Training weakly supervised video frame interpolation with events | Proceedings of the IEEE/CVF international conference on computer vision | 2021 |
| Unifying motion deblurring and frame interpolation with events | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2022 |
| Time lens++: Event-based frame interpolation with parametric non-linear flow and multi-scale fusion | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2022 |
| Timereplayer: Unlocking the potential of event cameras for video interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2022 |
| Video interpolation by event-driven anisotropic adjustment of optical flow | European Conference on Computer Vision | 2022 |
| A 2.97 $\mu$m-pitch event-based vision sensor with shared pixel front-end circuitry and low-noise intensity readout mode | 2023 IEEE International Solid-State Circuits Conference (ISSCC) | 2023 |
| Event-based video frame interpolation with cross-modal asymmetric bidirectional motion fields | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |
| Event-guided frame interpolation and dynamic range expansion of single rolling shutter image | Proceedings of the 31st ACM International Conference on Multimedia | 2023 |
| V2ce: Video to continuous events simulator | 2024 IEEE International Conference on Robotics and Automation (ICRA) | 2024 |
| Video frame interpolation via direct synthesis with the event-based reference | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |
| TimeLens-XL: Real-Time Event-Based Video Frame Interpolation with Large Motion | European Conference on Computer Vision | 2024 |
| Repurposing pre-trained video diffusion models for event-based video interpolation | arXiv preprint arXiv:2412.07761 | 2024 |
| EGVD: Event-Guided Video Diffusion Model for Physically Realistic Large-Motion Frame Interpolation | arXiv preprint arXiv:2503.20268 | 2025 |
| Coupled Video Frame Interpolation and Encoding with Hybrid Event Cameras for Low-Power High-Framerate Video | arXiv preprint arXiv:2503.22491 | 2025 |

</details>

<details>
<summary><strong>event + sr</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Turning frequency to resolution: Video super-resolution via event cameras | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2021 |
| Learning spatial-temporal implicit neural representations for event-guided video super-resolution | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |
| EvTexture: event-driven texture enhancement for video super-resolution | Forty-first International Conference on Machine Learning | 2024 |

</details>

<details>
<summary><strong>Medic</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| A spatiotemporal volumetric interpolation network for 4d dynamic medical image | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2020 |
| Data-efficient unsupervised interpolation without any intermediate frame for 4d medical images | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |
| CPT-Interp: Continuous sPatial and Temporal Motion Modeling for 4D Medical Image Interpolation | arXiv preprint arXiv:2405.15385 | 2024 |

</details>

<details>
<summary><strong>cartoon interpolation</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Deep animation video interpolation in the wild | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2021 |
| Improving the perceptual quality of 2d animation interpolation | European Conference on Computer Vision | 2022 |
| Deep sketch-guided cartoon video inbetweening | IEEE Transactions on Visualization and Computer Graphics | 2021 |
| Dynamicrafter: Animating open-domain images with video diffusion priors | European Conference on Computer Vision | 2024 |
| Tooncrafter: Generative cartoon interpolation | ACM Transactions on Graphics (TOG) | 2024 |
| Framer: Interactive frame interpolation | arXiv preprint arXiv:2410.18978 | 2024 |
| Anidoc: Animation creation made easier | arXiv preprint arXiv:2412.14173 | 2024 |
| LayerAnimate: Layer-specific control for animation | arXiv preprint arXiv:2501.08295 | 2025 |
| Learning inclusion matching for animation paint bucket colorization | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |
| PhysAnimator: Physics-Guided Generative Cartoon Animation | arXiv preprint arXiv:2501.16550 | 2025 |
| Time-adaptive Video Frame Interpolation based on Residual Diffusion | arXiv preprint arXiv:2504.05402 | 2025 |
| High-Resolution Frame Interpolation with Patch-based Cascaded Diffusion | Proceedings of the AAAI Conference on Artificial Intelligence | 2025 |

</details>

<details>
<summary><strong>game?</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| AnyMoLe: Any Character Motion In-betweening Leveraging Video Diffusion Models | arXiv preprint arXiv:2503.08417 | 2025 |

</details>

<details>
<summary><strong>Joint: SR</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Increasing space-time resolution in video | Computer Vision—ECCV 2002: 7th European Conference on Computer Vision Copenhagen, Denmark, May 28--31, 2002 Proceedings, Part I 7 | 2002 |
| Fisr: Deep joint frame interpolation and super-resolution with a multi-scale temporal loss | Proceedings of the AAAI Conference on Artificial Intelligence | 2020 |
| Space-time-aware multi-resolution video enhancement | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2020 |
| Temporal modulation network for controllable space-time video super-resolution | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2021 |
| Motif: Learning motion trajectories with local implicit neural functions for continuous space-time video super-resolution | Proceedings of the IEEE/CVF international conference on computer vision | 2023 |

</details>

<details>
<summary><strong>Joint: Deblur</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Video frame interpolation without temporal priors | Advances in Neural Information Processing Systems | 2020 |
| Video frame interpolation and enhancement via pyramid recurrent framework | IEEE Transactions on Image Processing | 2020 |
| Blurry video frame interpolation | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2020 |
| Animation from blur: Multi-modal blur decomposition with motion guidance | European Conference on Computer Vision | 2022 |
| Demfi: deep joint deblurring and multi-frame interpolation with flow-guided attentive correlation and recursive boosting | European Conference on Computer Vision | 2022 |
| Joint video multi-frame interpolation and deblurring under unknown exposure time | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |
| Latency correction for event-guided deblurring and frame interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |

</details>

<details>
<summary><strong>Loss Function</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Two deterministic half-quadratic regularization algorithms for computed imaging | Proceedings of 1st international conference on image processing | 1994 |
| Deep multi-scale video prediction beyond mean square error | arXiv preprint arXiv:1511.05440 | 2015 |
| Photo-realistic single image super-resolution using a generative adversarial network | CVPR | 2017 |
| Optimizing the latent space of generative networks | arXiv preprint arXiv:1707.05776 | 2017 |
| Non-parametric local transforms for computing visual correspondence | ECCV | 1994 |
| Unflow: Unsupervised learning of optical flow with a bidirectional census loss | AAAI | 2018 |
| Df-net: Unsupervised joint learning of depth and flow using cross-task consistency | ECCV | 2018 |

</details>

<details>
<summary><strong>Dataset</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Xiph.org video test media (derf's collection) |  | 1994 |
| A database and evaluation methodology for optical flow | Int. J. Comput. Vis. | 2011 |
| UCF101: A dataset of 101 human actions classes from videos in the wild | arXiv preprint arXiv:1212.0402 | 2012 |
| Are we ready for autonomous driving? the kitti vision benchmark suite | CVPR | 2012 |
| A naturalistic open source movie for optical flow evaluation | ECCV | 2012 |
| A benchmark dataset and evaluation methodology for video object segmentation | CVPR | 2016 |
| THUMOS challenge: Action recognition with a large number of classes |  | 2015 |
| Slow flow: Exploiting high-speed cameras for accurate and diverse optical flow reference data | Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition | 2017 |
| Deep video deblurring for hand-held cameras | CVPR | 2017 |
| Deep multi-scale convolutional neural network for dynamic scene deblurring | CVPR | 2017 |
| Frozen in time: A joint video and image encoder for end-to-end retrieval | Proceedings of the IEEE/CVF international conference on computer vision | 2021 |
| Lavib: A large-scale video interpolation benchmark | arXiv preprint arXiv:2406.09754 | 2024 |
| Openvid-1M: A large-scale high-quality dataset for text-to-video generation | arXiv preprint arXiv:2407.02371 | 2024 |

</details>

<details>
<summary><strong>Metric</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Image quality assessment: from error visibility to structural similarity | IEEE Trans. Image Process. | 2004 |
| A new objective quality metric for frame interpolation used in video compression | IEEE transactions on broadcasting | 2008 |
| Making a “completely blind” image quality analyzer | IEEE Signal processing letters | 2012 |
| Gans trained by a two time-scale update rule converge to a local nash equilibrium | Advances in neural information processing systems | 2017 |
| The unreasonable effectiveness of deep features as a perceptual metric | CVPR | 2018 |
| Towards accurate generative models of video: A new metric \& challenges | arXiv preprint arXiv:1812.01717 | 2018 |
| Fr$\backslash$'echet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos | arXiv preprint arXiv:2407.16124 | 2024 |
| Quality assessment of in-the-wild videos | Proceedings of the 27th ACM international conference on multimedia | 2019 |
| Image quality assessment: Unifying structure and texture similarity | IEEE transactions on pattern analysis and machine intelligence | 2020 |
| A loss function for generative neural networks based on watson’s perceptual model | Advances in Neural Information Processing Systems | 2020 |
| Learning transferable visual models from natural language supervision | International conference on machine learning | 2021 |
| Image super-resolution via iterative refinement | IEEE transactions on pattern analysis and machine intelligence | 2022 |
| FloLPIPS: A bespoke video quality metric for frame interpolation | 2022 Picture Coding Symposium (PCS) | 2022 |
| Vbench: Comprehensive benchmark suite for video generative models | CVPR | 2024 |

</details>

<details>
<summary><strong>future research direction</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Semantic-Aware Adaptive Video Streaming Using Latent Diffusion Models for Wireless Networks | arXiv preprint arXiv:2502.05695 | 2025 |
| Cadm: Codec-aware diffusion modeling for neural-enhanced video streaming | arXiv preprint arXiv:2211.08428 | 2022 |
| Improved conditional vrnns for video prediction | Proceedings of the IEEE/CVF international conference on computer vision | 2019 |

</details>

<details>
<summary><strong>All-in-One:Image</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| All-in-one image restoration for unknown corruption | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2022 |
| Content-Aware Transformer for All-in-one Image Restoration | arXiv preprint arXiv:2504.04869 | 2025 |
| Multimodal prompt perceiver: Empower adaptiveness generalizability and fidelity for all-in-one image restoration | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |

</details>

<details>
<summary><strong>All-in-One:Video</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| Edvr: Video restoration with enhanced deformable convolutional networks | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition workshops | 2019 |
| Edvr: Video restoration with enhanced deformable convolutional networks | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition workshops | 2019 |
| AverNet: All-in-one video restoration for time-varying unknown degradations | Advances in Neural Information Processing Systems | 2024 |

</details>

<details>
<summary><strong>4D</strong></summary>

| Title | Publication | Date |
|-------|-------------|------|
| In-2-4D: Inbetweening from Two Single-View Images to 4D Generation | arXiv preprint arXiv:2504.08366 | 2025 |
| Temporal interpolation is all you need for dynamic neural radiance fields | Proceedings of the IEEE/CVF conference on computer vision and pattern recognition | 2023 |
| Neuralpci: Spatio-temporal neural field for 3d point cloud multi-frame non-linear interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2023 |
| PAPR in Motion: Seamless Point-level 3D Scene Interpolation | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition | 2024 |

</details>


## 📊 Benchmarks & Datasets

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



