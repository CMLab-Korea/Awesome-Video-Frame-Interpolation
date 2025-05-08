# Awesome-Video-Frame-Interpolation
### Advances in Video Frame Interpolation: A Comprehensive Survey

<p align="center">
  <img src="./media/title.png" alt="Survey Title Image" width="800"/>
</p>

[![arXiv](https://img.shields.io/badge/arXiv-Preprint-b31b1b.svg)](https://arxiv.org/abs/your-paper-id)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC--BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Stars](https://img.shields.io/github/stars/your-org/your-repo.svg?style=social&label=Star)](https://github.com/your-org/your-repo)

This repository provides a curated collection of papers, benchmarks, and resources from our survey:  
**"Advances in Video Frame Interpolation: A Comprehensive Survey"** (2025, submitted to [Journal/Conference]).

> 📝 Authors: Your Name, Collaborator 1, Collaborator 2  
> 🎓 Institution: Your University / Lab Name

---

## 📘 Abstract

Video Frame Interpolation (VFI) is a fundamental task in video processing that aims to synthesize intermediate frames between existing ones, enabling smooth slow-motion effects, frame rate conversion, and temporal video enhancement. This survey provides a comprehensive review of the latest advancements in VFI, covering traditional motion estimation techniques, deep learning-based approaches, and emerging paradigms such as transformer-based and diffusion-based models. We present a taxonomy of VFI methods, analyze their key components, compare quantitative benchmarks, and discuss current challenges and promising future directions.

---

## 📚 Contents

- [Survey Paper](#survey-paper)
- [Paper List](#paper-list)
- [Benchmarks & Datasets](#benchmarks--datasets)
- [Metrics](#metrics)
- [News](#news)
- [BibTeX](#bibtex)

---

## 🔍 Survey Paper

You can find the preprint of our survey here:  
📄 [arXiv:your-paper-id](https://arxiv.org/abs/your-paper-id)

---

## 📄 Paper List

We categorize recent VFI papers by methodology:

### feature extraction network

| Title | Conference | Year |
|-------|------------|------|
| @article{simonyan2014very, |  |  |
| title={Very deep convolutional networks for large-scale image recognition}, |  |  |
| author={Simonyan, Karen and Zisserman, Andrew}, |  |  |
| journal={arXiv preprint arXiv:1409.1556}, |  |  |
| year={2014} |  |  |
| } |  |  |
| @inproceedings{ronneberger2015u, |  |  |
| title={U-net: Convolutional networks for biomedical image segmentation}, |  |  |
| author={Ronneberger, Olaf and Fischer, Philipp and Brox, Thomas}, |  |  |
| booktitle={Medical image computing and computer-assisted intervention--MICCAI 2015: 18th international conference, Munich, Germany, October 5-9, 2015, proceedings, part III 18}, |  |  |
| pages={234--241}, |  |  |
| year={2015}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{cciccek20163d, |  |  |
| title={3D U-Net: learning dense volumetric segmentation from sparse annotation}, |  |  |
| author={{\c{C}}i{\c{c}}ek, {\"O}zg{\"u}n and Abdulkadir, Ahmed and Lienkamp, Soeren S and Brox, Thomas and Ronneberger, Olaf}, |  |  |
| booktitle={Medical Image Computing and Computer-Assisted Intervention--MICCAI 2016: 19th International Conference, Athens, Greece, October 17-21, 2016, Proceedings, Part II 19}, |  |  |
| pages={424--432}, |  |  |
| year={2016}, |  |  |
| organization={Springer} |  |  |
| } |  |  |

### VFI

| Title | Conference | Year |
|-------|------------|------|
| @article{nottebaum2022efficient, |  |  |
| title={Efficient feature extraction for high-resolution video frame interpolation}, |  |  |
| author={Nottebaum, Moritz and Roth, Stefan and Schaub-Meyer, Simone}, |  |  |
| journal={arXiv preprint arXiv:2211.14005}, |  |  |
| year={2022} |  |  |
| } |  |  |

### Application

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{szeliski1999prediction, |  |  |
| title={Prediction error as a quality metric for motion and stereo}, |  |  |
| author={Szeliski, Richard}, |  |  |
| booktitle={Proceedings of the Seventh IEEE International Conference on Computer Vision}, |  |  |
| volume={2}, |  |  |
| pages={781--788}, |  |  |
| year={1999}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{zhou2016view, |  |  |
| title={View synthesis by appearance flow}, |  |  |
| author={Zhou, Tinghui and Tulsiani, Shubham and Sun, Weilun and Malik, Jitendra and Efros, Alexei A}, |  |  |
| booktitle={Computer Vision--ECCV 2016: 14th European Conference, Amsterdam, The Netherlands, October 11--14, 2016, Proceedings, Part IV 14}, |  |  |
| pages={286--301}, |  |  |
| year={2016}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{flynn2016deepstereo, |  |  |
| title={Deepstereo: Learning to predict new views from the world's imagery}, |  |  |
| author={Flynn, John and Neulander, Ivan and Philbin, James and Snavely, Noah}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={5515--5524}, |  |  |
| year={2016} |  |  |
| } |  |  |
| @inproceedings{wu2018video, |  |  |
| title={Video compression through image interpolation}, |  |  |
| author={Wu, Chao-Yuan and Singhal, Nayan and Krahenbuhl, Philipp}, |  |  |
| booktitle={Proceedings of the European conference on computer vision (ECCV)}, |  |  |
| pages={416--431}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @inproceedings{jiang2018super, |  |  |
| title={Super slomo: High quality estimation of multiple intermediate frames for video interpolation}, |  |  |
| author={Jiang, Huaizu and Sun, Deqing and Jampani, Varun and Yang, Ming-Hsuan and Learned-Miller, Erik and Kautz, Jan}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={9000--9008}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @article{xue2019TOFlow, |  |  |
| title={Video enhancement with task-oriented flow}, |  |  |
| author={Xue, Tianfan and Chen, Baian and Wu, Jiajun and Wei, Donglai and Freeman, William T}, |  |  |
| journal={International Journal of Computer Vision}, |  |  |
| volume={127}, |  |  |
| pages={1106--1125}, |  |  |
| year={2019}, |  |  |
| publisher={Springer} |  |  |
| } |  |  |
| @inproceedings{bao2019depth, |  |  |
| title={Depth-aware video frame interpolation}, |  |  |
| author={Bao, Wenbo and Lai, Wei-Sheng and Ma, Chao and Zhang, Xiaoyun and Gao, Zhiyong and Yang, Ming-Hsuan}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={3703--3712}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @inproceedings{xiang2020zooming, |  |  |
| title={Zooming slow-mo: Fast and accurate one-stage space-time video super-resolution}, |  |  |
| author={Xiang, Xiaoyu and Tian, Yapeng and Zhang, Yulun and Fu, Yun and Allebach, Jan P and Xu, Chenliang}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={3370--3379}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{li2021neural, |  |  |
| title={Neural scene flow fields for space-time view synthesis of dynamic scenes}, |  |  |
| author={Li, Zhengqi and Niklaus, Simon and Snavely, Noah and Wang, Oliver}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={6498--6508}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @article{singer2022make, |  |  |
| title={Make-a-video: Text-to-video generation without text-video data}, |  |  |
| author={Singer, Uriel and Polyak, Adam and Hayes, Thomas and Yin, Xi and An, Jie and Zhang, Songyang and Hu, Qiyuan and Yang, Harry and Ashual, Oron and Gafni, Oran and others}, |  |  |
| journal={arXiv preprint arXiv:2209.14792}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{jia2022neighbor, |  |  |
| title={Neighbor correspondence matching for flow-based video frame synthesis}, |  |  |
| author={Jia, Zhaoyang and Lu, Yan and Li, Houqiang}, |  |  |
| booktitle={Proceedings of the 30th ACM International Conference on Multimedia}, |  |  |
| pages={5389--5397}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @article{chun2020compressed, |  |  |
| title={Compressed video restoration using a generative adversarial network for subjective quality enhancement}, |  |  |
| author={Chun, Dayoung and Kim, Tae Sung and Lee, Kyujoong and Lee, Hyuk-Jae}, |  |  |
| journal={IEIE Transactions on Smart Processing \& Computing}, |  |  |
| volume={9}, |  |  |
| number={1}, |  |  |
| pages={1--6}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{hirose2024real, |  |  |
| title={Real-time video prediction with fast video interpolation model and prediction training}, |  |  |
| author={Hirose, Shota and Kotoyori, Kazuki and Arunruangsirilert, Kasidis and Lin, Fangzheng and Sun, Heming and Katto, Jiro}, |  |  |
| booktitle={2024 IEEE International Conference on Image Processing (ICIP)}, |  |  |
| pages={2015--2021}, |  |  |
| year={2024}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @article{liu2024tango, |  |  |
| title={Tango: Co-speech gesture video reenactment with hierarchical audio motion embedding and diffusion interpolation}, |  |  |
| author={Liu, Haiyang and Yang, Xingchao and Akiyama, Tomoya and Huang, Yuantian and Li, Qiaoge and Kuriyama, Shigeru and Taketomi, Takafumi}, |  |  |
| journal={arXiv preprint arXiv:2410.04221}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{liu2025video, |  |  |
| title={Video Motion Graphs}, |  |  |
| author={Liu, Haiyang and Xu, Zhan and Hong, Fa-Ting and Huang, Hsin-Ping and Zhou, Yi and Zhou, Yang}, |  |  |
| journal={arXiv preprint arXiv:2503.20218}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @article{bigata2025keyface, |  |  |
| title={KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation}, |  |  |
| author={Bigata, Antoni and Mira, Rodrigo and Bounareli, Stella and Vougioukas, Konstantinos and Landgraf, Zoe and Drobyshev, Nikita and Zieba, Maciej and Petridis, Stavros and Pantic, Maja and others}, |  |  |
| journal={arXiv preprint arXiv:2503.01715}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @article{jeon2023dynamic, |  |  |
| title={Dynamic Framerate SlowFast Network for Improving Autonomous Driving Performance}, |  |  |
| author={Jeon, Byeong-Uk and Chung, Kyungyong}, |  |  |
| journal={IEIE Transactions on Smart Processing \& Computing}, |  |  |
| volume={12}, |  |  |
| number={3}, |  |  |
| pages={261--268}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{huang2024scale, |  |  |
| title={Scale-adaptive feature aggregation for efficient space-time video super-resolution}, |  |  |
| author={Huang, Zhewei and Huang, Ailin and Hu, Xiaotao and Hu, Chen and Xu, Jun and Zhou, Shuchang}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision}, |  |  |
| pages={4228--4239}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{madhusudana2020hfr, |  |  |
| title={Subjective and objective quality assessment of high frame rate videos}, |  |  |
| author={Madhusudana, Pavan C and Yu, Xiangxu and Birkbeck, Neil and Wang, Yilin and Adsumilli, Balu and Bovik, Alan C}, |  |  |
| journal={IEEE Access}, |  |  |
| volume={9}, |  |  |
| pages={108069--108082}, |  |  |
| year={2021}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{han2023vfiqa, |  |  |
| title={Perceptual quality assessment for video frame interpolation}, |  |  |
| author={Han, Jinliang and Min, Xiongkuo and Gao, Yixuan and Jia, Jun and Sun, Lei and Cao, Zuowei and Luo, Yonglin and Zhai, Guangtao}, |  |  |
| booktitle={2023 IEEE International Conference on Visual Communications and Image Processing (VCIP)}, |  |  |
| pages={1--5}, |  |  |
| year={2023}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @article{danier2022bvivfi, |  |  |
| title={BVI-VFI: a video quality database for video frame interpolation}, |  |  |
| author={Danier, Duolikun and Zhang, Fan and Bull, David R}, |  |  |
| journal={IEEE Transactions on Image Processing}, |  |  |
| volume={32}, |  |  |
| pages={6004--6019}, |  |  |
| year={2023}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{rahim2020hfr, |  |  |
| title={Comparing H. 265/HEVC and VP9: Impact of high frame rates on the perceptual quality of compressed videos}, |  |  |
| author={Rahim, Tariq and Usman, Muhammad Arslan and Shin, Soo Young}, |  |  |
| journal={arXiv preprint arXiv:2006.02671}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @article{madhusudana2021subjective, |  |  |
| title={Subjective and objective quality assessment of high frame rate videos}, |  |  |
| author={Madhusudana, Pavan C and Yu, Xiangxu and Birkbeck, Neil and Wang, Yilin and Adsumilli, Balu and Bovik, Alan C}, |  |  |
| journal={IEEE Access}, |  |  |
| volume={9}, |  |  |
| pages={108069--108082}, |  |  |
| year={2021}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{hou2022vfiqa, |  |  |
| title={A perceptual quality metric for video frame interpolation}, |  |  |
| author={Hou, Qiqi and Ghildyal, Abhijay and Liu, Feng}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={234--253}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |

### challenges

| Title | Conference | Year |
|-------|------------|------|
| @article{horn1981determining, |  |  |
| title={Determining optical flow}, |  |  |
| author={Horn, Berthold KP and Schunck, Brian G}, |  |  |
| journal={Artificial intelligence}, |  |  |
| volume={17}, |  |  |
| number={1-3}, |  |  |
| pages={185--203}, |  |  |
| year={1981}, |  |  |
| publisher={Elsevier} |  |  |
| } |  |  |

### Motion-compensated

| Title | Conference | Year |
|-------|------------|------|
| @article{haavisto1989fractional, |  |  |
| title={Fractional frame rate up-conversion using weighted median filters}, |  |  |
| author={Haavisto, Petri and Juhola, Janne and Neuvo, Yrj{\"o}}, |  |  |
| journal={IEEE Transactions on Consumer Electronics}, |  |  |
| volume={35}, |  |  |
| number={3}, |  |  |
| pages={272--278}, |  |  |
| year={1989}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{nakaya1994motion, |  |  |
| title={Motion compensation based on spatial transformations}, |  |  |
| author={Nakaya, Yuichiro and Harashima, Hiroshi}, |  |  |
| journal={IEEE Transactions on circuits and systems for video technology}, |  |  |
| volume={4}, |  |  |
| number={3}, |  |  |
| pages={339--356}, |  |  |
| year={1994}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{castagno1996method, |  |  |
| title={A method for motion adaptive frame rate up-conversion}, |  |  |
| author={Castagno, Roberto and Haavisto, Petri and Ramponi, Giovanni}, |  |  |
| journal={IEEE Transactions on circuits and Systems for Video Technology}, |  |  |
| volume={6}, |  |  |
| number={5}, |  |  |
| pages={436--446}, |  |  |
| year={1996}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{lee2002adaptive, |  |  |
| title={Adaptive motion-compensated interpolation for frame rate up-conversion}, |  |  |
| author={Lee, Sung-Hee and Shin, Yoon-Cheol and Yang, Seungjoon and Moon, Heon-Hee and Park, Rae-Hong}, |  |  |
| journal={IEEE Transactions on Consumer Electronics}, |  |  |
| volume={48}, |  |  |
| number={3}, |  |  |
| pages={444--450}, |  |  |
| year={2002}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{ha2004motion, |  |  |
| title={Motion compensated frame interpolation by new block-based motion estimation algorithm}, |  |  |
| author={Ha, Taehyeun and Lee, Seongjoo and Kim, Jaeseok}, |  |  |
| journal={IEEE Transactions on Consumer Electronics}, |  |  |
| volume={50}, |  |  |
| number={2}, |  |  |
| pages={752--759}, |  |  |
| year={2004}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{choi2007motion, |  |  |
| title={Motion-compensated frame interpolation using bilateral motion estimation and adaptive overlapped block motion compensation}, |  |  |
| author={Choi, Byeong-Doo and Han, Jong-Woo and Kim, Chang-Su and Ko, Sung-Jea}, |  |  |
| journal={IEEE Transactions on Circuits and Systems for Video Technology}, |  |  |
| volume={17}, |  |  |
| number={4}, |  |  |
| pages={407--416}, |  |  |
| year={2007}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{kang2008motion, |  |  |
| title={Motion compensated frame rate up-conversion using extended bilateral motion estimation}, |  |  |
| author={Kang, Suk-Ju and Cho, Kyoung-Rok and Kim, Young Hwan}, |  |  |
| journal={IEEE Transactions on Consumer Electronics}, |  |  |
| volume={53}, |  |  |
| number={4}, |  |  |
| pages={1759--1767}, |  |  |
| year={2008}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{huang2008multistage, |  |  |
| title={A multistage motion vector processing method for motion-compensated frame interpolation}, |  |  |
| author={Huang, Ai-Mei and Nguyen, Truong Q}, |  |  |
| journal={IEEE transactions on image processing}, |  |  |
| volume={17}, |  |  |
| number={5}, |  |  |
| pages={694--708}, |  |  |
| year={2008}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{wang2010motion1, |  |  |
| title={Motion-compensated frame rate up-conversion—Part I: Fast multi-frame motion estimation}, |  |  |
| author={Wang, Demin and Zhang, Liang and Vincent, Andr{\'e}}, |  |  |
| journal={IEEE Transactions on Broadcasting}, |  |  |
| volume={56}, |  |  |
| number={2}, |  |  |
| pages={133--141}, |  |  |
| year={2010}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{wang2010motion2, |  |  |
| author={Wang, D. and Vincent, A. and Blanchfield, P. and Klepko, R.}, |  |  |
| title={Motion-compensated frame rate up-conversion—Part II: New algorithms for frame interpolation}, |  |  |
| journal={IEEE Transactions on Broadcasting}, |  |  |
| volume = {56}, |  |  |
| number={2}, |  |  |
| pages={142--149}, |  |  |
| year={2010}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{lee2013frame, |  |  |
| author={Lee, Won Hee and Choi, Kyuha and Ra, Jong Beom}, |  |  |
| title={Frame rate up conversion based on variational image fusion}, |  |  |
| journal={IEEE Transactions on Image Processing}, |  |  |
| year={2013} |  |  |
| } |  |  |

### GAN-based

| Title | Conference | Year |
|-------|------------|------|
| @article{van2017FIGAN, |  |  |
| title={Frame interpolation with multi-scale deep loss functions and generative adversarial networks}, |  |  |
| author={Van Amersfoort, Joost and Shi, Wenzhe and Acosta, Alejandro and Massa, Francisco and Totz, Johannes and Wang, Zehan and Caballero, Jose}, |  |  |
| journal={arXiv preprint arXiv:1711.06045}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @techreport{koren2017frame, |  |  |
| title={Frame interpolation using generative adversarial networks}, |  |  |
| author={Koren, Mark and Menda, Kunal and Sharma, Apoorva}, |  |  |
| year={2017}, |  |  |
| publisher={Stanford University: Stanford, CA, USA} |  |  |
| } |  |  |
| @article{xiao2020multi, |  |  |
| title={Multi-scale attention generative adversarial networks for video frame interpolation}, |  |  |
| author={Xiao, Jian and Bi, Xiaojun}, |  |  |
| journal={IEEE Access}, |  |  |
| volume={8}, |  |  |
| pages={94842--94851}, |  |  |
| year={2020}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{tran2020efficient, |  |  |
| title={Efficient video frame interpolation using generative adversarial networks}, |  |  |
| author={Tran, Quang Nhat and Yang, Shih-Hsuan}, |  |  |
| journal={Applied Sciences}, |  |  |
| volume={10}, |  |  |
| number={18}, |  |  |
| pages={6245}, |  |  |
| year={2020}, |  |  |
| publisher={MDPI} |  |  |
| } |  |  |
| @article{xue2020frame, |  |  |
| title={Frame-GAN: Increasing the frame rate of gait videos with generative adversarial networks}, |  |  |
| author={Xue, Wei and Ai, Hong and Sun, Tianyu and Song, Chunfeng and Huang, Yan and Wang, Liang}, |  |  |
| journal={Neurocomputing}, |  |  |
| volume={380}, |  |  |
| pages={95--104}, |  |  |
| year={2020}, |  |  |
| publisher={Elsevier} |  |  |
| } |  |  |
| @article{tran2022video, |  |  |
| title={Video frame interpolation via down--up scale generative adversarial networks}, |  |  |
| author={Tran, Quang Nhat and Yang, Shih-Hsuan}, |  |  |
| journal={Computer Vision and Image Understanding}, |  |  |
| volume={220}, |  |  |
| pages={103434}, |  |  |
| year={2022}, |  |  |
| publisher={Elsevier} |  |  |
| } |  |  |
| @article{wen2018generating, |  |  |
| title={Generating realistic videos from keyframes with concatenated GANs}, |  |  |
| author={Wen, Shiping and Liu, Weiwei and Yang, Yin and Huang, Tingwen and Zeng, Zhigang}, |  |  |
| journal={IEEE Transactions on Circuits and Systems for Video Technology}, |  |  |
| volume={29}, |  |  |
| number={8}, |  |  |
| pages={2337--2348}, |  |  |
| year={2018}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{danier2022stmfnet, |  |  |
| title={St-mfnet: A spatio-temporal multi-flow network for frame interpolation}, |  |  |
| author={Danier, Duolikun and Zhang, Fan and Bull, David}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={3521--3531}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{gulrajani2017improved, |  |  |
| title={Improved training of wasserstein gans}, |  |  |
| author={Gulrajani, Ishaan and Ahmed, Faruk and Arjovsky, Martin and Dumoulin, Vincent and Courville, Aaron C}, |  |  |
| journal={Advances in neural information processing systems}, |  |  |
| volume={30}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @article{berthelot2017began, |  |  |
| title={Began: Boundary equilibrium generative adversarial networks}, |  |  |
| author={Berthelot, David and Schumm, Thomas and Metz, Luke}, |  |  |
| journal={arXiv preprint arXiv:1703.10717}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{arjovsky2017wasserstein, |  |  |
| title={Wasserstein generative adversarial networks}, |  |  |
| author={Arjovsky, Martin and Chintala, Soumith and Bottou, L{\'e}on}, |  |  |
| booktitle={International conference on machine learning}, |  |  |
| pages={214--223}, |  |  |
| year={2017}, |  |  |
| organization={PMLR} |  |  |
| } |  |  |
| @inproceedings{larsen2016autoencoding, |  |  |
| title={Autoencoding beyond pixels using a learned similarity metric}, |  |  |
| author={Larsen, Anders Boesen Lindbo and S{\o}nderby, S{\o}ren Kaae and Larochelle, Hugo and Winther, Ole}, |  |  |
| booktitle={International conference on machine learning}, |  |  |
| pages={1558--1566}, |  |  |
| year={2016}, |  |  |
| organization={PMLR} |  |  |
| } |  |  |
| @inproceedings{chen2020generative, |  |  |
| title={Generative adversarial networks for video-to-video domain adaptation}, |  |  |
| author={Chen, Jiawei and Li, Yuexiang and Ma, Kai and Zheng, Yefeng}, |  |  |
| booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, |  |  |
| volume={34}, |  |  |
| number={04}, |  |  |
| pages={3462--3469}, |  |  |
| year={2020} |  |  |
| } |  |  |

### Diffusion-based

| Title | Conference | Year |
|-------|------------|------|
| @article{watson2022novel, |  |  |
| title={Novel view synthesis with diffusion models}, |  |  |
| author={Watson, Daniel and Chan, William and Martin-Brualla, Ricardo and Ho, Jonathan and Tagliasacchi, Andrea and Norouzi, Mohammad}, |  |  |
| journal={arXiv preprint arXiv:2210.04628}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{voleti2022mcvd, |  |  |
| title={Mcvd-masked conditional video diffusion for prediction, generation, and interpolation}, |  |  |
| author={Voleti, Vikram and Jolicoeur-Martineau, Alexia and Pal, Chris}, |  |  |
| journal={Advances in neural information processing systems}, |  |  |
| volume={35}, |  |  |
| pages={23371--23385}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{danier2024ldmvfi, |  |  |
| title={Ldmvfi: Video frame interpolation with latent diffusion models}, |  |  |
| author={Danier, Duolikun and Zhang, Fan and Bull, David}, |  |  |
| booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, |  |  |
| volume={38}, |  |  |
| number={2}, |  |  |
| pages={1472--1480}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{jain2024video, |  |  |
| title={Video interpolation with diffusion models}, |  |  |
| author={Jain, Siddhant and Watson, Daniel and Tabellion, Eric and Poole, Ben and Kontkanen, Janne and others}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={7341--7351}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{huang2024motion, |  |  |
| title={Motion-aware latent diffusion models for video frame interpolation}, |  |  |
| author={Huang, Zhilin and Yu, Yijie and Yang, Ling and Qin, Chujun and Zheng, Bing and Zheng, Xiawu and Zhou, Zikun and Wang, Yaowei and Yang, Wenming}, |  |  |
| booktitle={Proceedings of the 32nd ACM International Conference on Multimedia}, |  |  |
| pages={1043--1052}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{shen2024dreammover, |  |  |
| title={Dreammover: Leveraging the prior of diffusion models for image interpolation with large motion}, |  |  |
| author={Shen, Liao and Liu, Tianqi and Sun, Huiqiang and Ye, Xinyi and Li, Baopu and Zhang, Jianming and Cao, Zhiguo}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={336--353}, |  |  |
| year={2024}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @article{wang2024generative, |  |  |
| title={Generative inbetweening: Adapting image-to-video models for keyframe interpolation}, |  |  |
| author={Wang, Xiaojuan and Zhou, Boyang and Curless, Brian and Kemelmacher-Shlizerman, Ira and Holynski, Aleksander and Seitz, Steven M}, |  |  |
| journal={arXiv preprint arXiv:2408.15239}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{feng2024explorative, |  |  |
| title={Explorative inbetweening of time and space}, |  |  |
| author={Feng, Haiwen and Ding, Zheng and Xia, Zhihao and Niklaus, Simon and Abrevaya, Victoria and Black, Michael J and Zhang, Xuaner}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={378--395}, |  |  |
| year={2024}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{lyu2024brownian, |  |  |
| title={Frame Interpolation with Consecutive Brownian Bridge Diffusion}, |  |  |
| author={Lyu, Zonglin and Li, Ming and Jiao, Jianbo and Chen, Chen}, |  |  |
| booktitle={Proceedings of the 32nd ACM International Conference on Multimedia}, |  |  |
| pages={3449--3458}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{zhu2024generative, |  |  |
| title={Generative Inbetweening through Frame-wise Conditions-Driven Video Generation}, |  |  |
| author={Zhu, Tianyi and Ren, Dongwei and Wang, Qilong and Wu, Xiaohe and Zuo, Wangmeng}, |  |  |
| journal={arXiv preprint arXiv:2412.11755}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{yang2024vibidsampler, |  |  |
| title={ViBiDSampler: Enhancing Video Interpolation Using Bidirectional Diffusion Sampler}, |  |  |
| author={Yang, Serin and Kwon, Taesung and Ye, Jong Chul}, |  |  |
| journal={arXiv preprint arXiv:2410.05651}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{zhang2025motion, |  |  |
| title={Motion-Aware Generative Frame Interpolation}, |  |  |
| author={Zhang, Guozhen and Zhu, Yuhan and Cui, Yutao and Zhao, Xiaotong and Ma, Kai and Wang, Limin}, |  |  |
| journal={arXiv preprint arXiv:2501.03699}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @article{zhang2025eden, |  |  |
| title={EDEN: Enhanced Diffusion for High-quality Large-motion Video Frame Interpolation}, |  |  |
| author={Zhang, Zihao and Chen, Haoran and Zhao, Haoyu and Lu, Guansong and Fu, Yanwei and Xu, Hang and Wu, Zuxuan}, |  |  |
| journal={arXiv preprint arXiv:2503.15831}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @article{hai2025hierarchical, |  |  |
| title={Hierarchical Flow Diffusion for Efficient Frame Interpolation}, |  |  |
| author={Hai, Yang and Wang, Guo and Su, Tan and Jiang, Wenjie and Hu, Yinlin}, |  |  |
| journal={arXiv preprint arXiv:2504.00380}, |  |  |
| year={2025} |  |  |
| } |  |  |

### Flow-based

| Title | Conference | Year |
|-------|------------|------|
| @book{wolberg1990digital, |  |  |
| title={Digital image warping}, |  |  |
| author={Wolberg, George}, |  |  |
| volume={10662}, |  |  |
| year={1990}, |  |  |
| publisher={IEEE computer society press Los Alamitos, CA} |  |  |
| } |  |  |
| @inproceedings{jaderberg2015spatial, |  |  |
| title={Spatial transformer networks}, |  |  |
| author={Jaderberg, Max and Simonyan, Karen and Zisserman, Andrew and others}, |  |  |
| journal={Advances in neural information processing systems}, |  |  |
| volume={28}, |  |  |
| year={2015} |  |  |
| } |  |  |
| @inproceedings{liu2017DVF, |  |  |
| title={Video frame synthesis using deep voxel flow}, |  |  |
| author={Liu, Ziwei and Yeh, Raymond A and Tang, Xiaoou and Liu, Yiming and Agarwala, Aseem}, |  |  |
| booktitle={Proceedings of the IEEE international conference on computer vision}, |  |  |
| pages={4463--4471}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{liu2019cyclicgen, |  |  |
| title={Deep video frame interpolation using cyclic frame generation}, |  |  |
| author={Liu, Yu-Lun and Liao, Yi-Tung and Lin, Yen-Yu and Chuang, Yung-Yu}, |  |  |
| booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, |  |  |
| volume={33}, |  |  |
| number={01}, |  |  |
| pages={8794--8802}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @inproceedings{yuan2019zoom, |  |  |
| title={Zoom-in-to-check: Boosting video interpolation via instance-level discrimination}, |  |  |
| author={Yuan, Liangzhe and Chen, Yibo and Liu, Hantian and Kong, Tao and Shi, Jianbo}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={12183--12191}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @inproceedings{reda2019unsupervised, |  |  |
| title={Unsupervised video interpolation using cycle consistency}, |  |  |
| author={Reda, Fitsum A and Sun, Deqing and Dundar, Aysegul and Shoeybi, Mohammad and Liu, Guilin and Shih, Kevin J and Tao, Andrew and Kautz, Jan and Catanzaro, Bryan}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer Vision}, |  |  |
| pages={892--900}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @inproceedings{xu2019quadratic, |  |  |
| title={Quadratic video interpolation}, |  |  |
| author={Xu, Xiangyu and Siyao, Li and Sun, Wenxiu and Yin, Qian and Yang, Ming-Hsuan}, |  |  |
| journal={Advances in Neural Information Processing Systems}, |  |  |
| volume={32}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @inproceedings{chi2020all, |  |  |
| title={All at once: Temporally adaptive multi-frame interpolation with advanced motion modeling}, |  |  |
| author={Chi, Zhixiang and Mohammadi Nasiri, Rasoul and Liu, Zheng and Lu, Juwei and Tang, Jin and Plataniotis, Konstantinos N}, |  |  |
| booktitle={Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part XXVII 16}, |  |  |
| pages={107--123}, |  |  |
| year={2020}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{niklaus2020softmax, |  |  |
| title={Softmax splatting for video frame interpolation}, |  |  |
| author={Niklaus, Simon and Liu, Feng}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={5437--5446}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{liu2020enhanced, |  |  |
| title={Enhanced quadratic video interpolation}, |  |  |
| author={Liu, Yihao and Xie, Liangbin and Siyao, Li and Sun, Wenxiu and Qiao, Yu and Dong, Chao}, |  |  |
| booktitle={Computer Vision--ECCV 2020 Workshops: Glasgow, UK, August 23--28, 2020, Proceedings, Part IV 16}, |  |  |
| pages={41--56}, |  |  |
| year={2020}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{zhang2020flexible, |  |  |
| title={A flexible recurrent residual pyramid network for video frame interpolation}, |  |  |
| author={Zhang, Haoxian and Zhao, Yang and Wang, Ronggang}, |  |  |
| booktitle={European conference on computer vision}, |  |  |
| pages={474--491}, |  |  |
| year={2020}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{sim2021xvfi, |  |  |
| title={Xvfi: extreme video frame interpolation}, |  |  |
| author={Sim, Hyeonjun and Oh, Jihyong and Kim, Munchurl}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={14489--14498}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{hu2022many, |  |  |
| title={Many-to-many splatting for efficient video frame interpolation}, |  |  |
| author={Hu, Ping and Niklaus, Simon and Sclaroff, Stan and Saenko, Kate}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={3553--3562}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{kong2022ifrnet, |  |  |
| title={Ifrnet: Intermediate feature refine network for efficient frame interpolation}, |  |  |
| author={Kong, Lingtong and Jiang, Boyuan and Luo, Donghao and Chu, Wenqing and Huang, Xiaoming and Tai, Ying and Wang, Chengjie and Yang, Jie}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={1969--1978}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{park2021asymmetric, |  |  |
| title={Asymmetric bilateral motion estimation for video frame interpolation}, |  |  |
| author={Park, Junheum and Lee, Chul and Kim, Chang-Su}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={14539--14548}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{huang2022rife, |  |  |
| title={Real-time intermediate flow estimation for video frame interpolation}, |  |  |
| author={Huang, Zhewei and Zhang, Tianyuan and Heng, Wen and Shi, Boxin and Zhou, Shuchang}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={624--642}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{shangguan2022learning, |  |  |
| title={Learning cross-video neural representations for high-quality frame interpolation}, |  |  |
| author={Shangguan, Wentao and Sun, Yu and Gan, Weijie and Kamilov, Ulugbek S}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={511--528}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{reda2022film, |  |  |
| title={Film: Frame interpolation for large motion}, |  |  |
| author={Reda, Fitsum and Kontkanen, Janne and Tabellion, Eric and Sun, Deqing and Pantofaru, Caroline and Curless, Brian}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={250--266}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{niklaus2023splatting, |  |  |
| title={Splatting-based synthesis for video frame interpolation}, |  |  |
| author={Niklaus, Simon and Hu, Ping and Chen, Jiawen}, |  |  |
| booktitle={Proceedings of the IEEE/CVF winter conference on applications of computer vision}, |  |  |
| pages={713--723}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{jin2023enhanced, |  |  |
| title={Enhanced bi-directional motion estimation for video frame interpolation}, |  |  |
| author={Jin, Xin and Wu, Longhai and Shen, Guotao and Chen, Youxin and Chen, Jie and Koo, Jayoon and Hahm, Cheul-hee}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision}, |  |  |
| pages={5049--5057}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{park2023biformer, |  |  |
| title={Biformer: Learning bilateral motion estimation via bilateral transformer for 4k video frame interpolation}, |  |  |
| author={Park, Junheum and Kim, Jintae and Kim, Chang-Su}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={1568--1577}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{jin2023unified, |  |  |
| title={A unified pyramid recurrent network for video frame interpolation}, |  |  |
| author={Jin, Xin and Wu, Longhai and Chen, Jie and Chen, Youxin and Koo, Jayoon and Hahm, Cheul-hee}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={1578--1587}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{li2023amt, |  |  |
| title={Amt: All-pairs multi-field transforms for efficient frame interpolation}, |  |  |
| author={Li, Zhen and Zhu, Zuo-Liang and Han, Ling-Hao and Hou, Qibin and Guo, Chun-Le and Cheng, Ming-Ming}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={9801--9810}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{zhang2023extracting, |  |  |
| title={Extracting motion and appearance via inter-frame attention for efficient video frame interpolation}, |  |  |
| author={Zhang, Guozhen and Zhu, Yuhan and Wang, Haonan and Chen, Youxin and Wu, Gangshan and Wang, Limin}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={5682--5692}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{hu2024iqvfi, |  |  |
| title={IQ-VFI: implicit quadratic motion estimation for video frame interpolation}, |  |  |
| author={Hu, Mengshun and Jiang, Kui and Zhong, Zhihang and Wang, Zheng and Zheng, Yinqiang}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={6410--6419}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{jeong2024ocai, |  |  |
| title={Ocai: Improving optical flow estimation by occlusion and consistency aware interpolation}, |  |  |
| author={Jeong, Jisoo and Cai, Hong and Garrepalli, Risheek and Lin, Jamie Menjay and Hayat, Munawar and Porikli, Fatih}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={19352--19362}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{guo2024generalizable, |  |  |
| title={Generalizable implicit motion modeling for video frame interpolation}, |  |  |
| author={Guo, Zujin and Li, Wei and Loy, Chen Change}, |  |  |
| journal={Advances in Neural Information Processing Systems}, |  |  |
| volume={37}, |  |  |
| pages={63747--63770}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{wu2024perception, |  |  |
| title={Perception-oriented video frame interpolation via asymmetric blending}, |  |  |
| author={Wu, Guangyang and Tao, Xin and Li, Changlin and Wang, Wenyi and Liu, Xiaohong and Zheng, Qingqing}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={2753--2762}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{zhong2024clearer, |  |  |
| title={Clearer frames, anytime: Resolving velocity ambiguity in video frame interpolation}, |  |  |
| author={Zhong, Zhihang and Krishnan, Gurunandan and Sun, Xiao and Qiao, Yu and Ma, Sizhuo and Wang, Jian}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={346--363}, |  |  |
| year={2024}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @article{seo2024bim, |  |  |
| title={BiM-VFI: directional Motion Field-Guided Frame Interpolation for Video with Non-uniform Motions}, |  |  |
| author={Seo, Wonyong and Oh, Jihyong and Kim, Munchurl}, |  |  |
| journal={arXiv preprint arXiv:2412.11365}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{jin2025unified, |  |  |
| title={Unified Arbitrary-Time Video Frame Interpolation and Prediction}, |  |  |
| author={Jin, Xin and Wu, Longhai and Chen, Jie and Cho, Ilhyun and Hahm, Cheul-Hee}, |  |  |
| booktitle={ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, |  |  |
| pages={1--5}, |  |  |
| year={2025}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |

### Flow network

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{jian2005symmetric, |  |  |
| title={Symmetric stereo matching for occlusion handling}, |  |  |
| author={Sun, Jian and Li, Yin and Kang, Sing Bing and Shum, Heung-Yeung}, |  |  |
| booktitle={2005 IEEE Computer Society Conference on Computer Vision and Pattern Recognition (CVPR'05)}, |  |  |
| volume={2}, |  |  |
| pages={399--406}, |  |  |
| year={2005}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{jiang2021learning, |  |  |
| title={Learning to estimate hidden motions with global motion aggregation}, |  |  |
| author={Jiang, Shihao and Campbell, Dylan and Lu, Yao and Li, Hongdong and Hartley, Richard}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={9772--9781}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{weinzaepfel2013deepflow, |  |  |
| title={DeepFlow: Large displacement optical flow with deep matching}, |  |  |
| author={Weinzaepfel, Philippe and Revaud, Jerome and Harchaoui, Zaid and Schmid, Cordelia}, |  |  |
| booktitle={Proceedings of the IEEE international conference on computer vision}, |  |  |
| pages={1385--1392}, |  |  |
| year={2013} |  |  |
| } |  |  |
| @inproceedings{dosovitskiy2015flownet, |  |  |
| title={Flownet: Learning optical flow with convolutional networks}, |  |  |
| author={Dosovitskiy, Alexey and Fischer, Philipp and Ilg, Eddy and Hausser, Philip and Hazirbas, Caner and Golkov, Vladimir and Van Der Smagt, Patrick and Cremers, Daniel and Brox, Thomas}, |  |  |
| booktitle={Proceedings of the IEEE international conference on computer vision}, |  |  |
| pages={2758--2766}, |  |  |
| year={2015} |  |  |
| } |  |  |
| @inproceedings{ilg2017flownet, |  |  |
| title={Flownet 2.0: Evolution of optical flow estimation with deep networks}, |  |  |
| author={Ilg, Eddy and Mayer, Nikolaus and Saikia, Tonmoy and Keuper, Margret and Dosovitskiy, Alexey and Brox, Thomas}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={2462--2470}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{ranjan2017optical, |  |  |
| title={Optical flow estimation using a spatial pyramid network}, |  |  |
| author={Ranjan, Anurag and Black, Michael J}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={4161--4170}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{wang2018occlusionaware, |  |  |
| title={Occlusion aware unsupervised learning of optical flow}, |  |  |
| author={Wang, Yang and Yang, Yi and Yang, Zhenheng and Zhao, Liang and Wang, Peng and Xu, Wei}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={4884--4893}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @inproceedings{sun2018pwc, |  |  |
| title={Pwc-net: Cnns for optical flow using pyramid, warping, and cost volume}, |  |  |
| author={Sun, Deqing and Yang, Xiaodong and Liu, Ming-Yu and Kautz, Jan}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={8934--8943}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @inproceedings{hui2018liteflownet, |  |  |
| title={Liteflownet: A lightweight convolutional neural network for optical flow estimation}, |  |  |
| author={Hui, Tak-Wai and Tang, Xiaoou and Loy, Chen Change}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={8981--8989}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @article{zhang2019tvl, |  |  |
| title={Refined TV-L 1 optical flow estimation using joint filtering}, |  |  |
| author={Zhang, Congxuan and Ge, Liyue and Chen, Zhen and Li, Ming and Liu, Wen and Chen, Hao}, |  |  |
| journal={IEEE Transactions on Multimedia}, |  |  |
| volume={22}, |  |  |
| number={2}, |  |  |
| pages={349--364}, |  |  |
| year={2019}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{teed2020raft, |  |  |
| title={Raft: Recurrent all-pairs field transforms for optical flow}, |  |  |
| author={Teed, Zachary and Deng, Jia}, |  |  |
| booktitle={Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part II 16}, |  |  |
| pages={402--419}, |  |  |
| year={2020}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{huang2022flowformer, |  |  |
| title={Flowformer: A transformer architecture for optical flow}, |  |  |
| author={Huang, Zhaoyang and Shi, Xiaoyu and Zhang, Chao and Wang, Qiang and Cheung, Ka Chun and Qin, Hongwei and Dai, Jifeng and Li, Hongsheng}, |  |  |
| booktitle={European conference on computer vision}, |  |  |
| pages={668--685}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{xu2022gmflow, |  |  |
| title={Gmflow: Learning optical flow via global matching}, |  |  |
| author={Xu, Haofei and Zhang, Jing and Cai, Jianfei and Rezatofighi, Hamid and Tao, Dacheng}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={8121--8130}, |  |  |
| year={2022} |  |  |
| } |  |  |

### Kernel-based

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{krizhevsky2012cnn, |  |  |
| title={ImageNet classification with deep convolutional neural networks}, |  |  |
| author={Krizhevsky, Alex and Sutskever, Ilya and Hinton, Geoffrey E}, |  |  |
| journal={Communications of the ACM}, |  |  |
| volume={60}, |  |  |
| number={6}, |  |  |
| pages={84--90}, |  |  |
| year={2017}, |  |  |
| publisher={AcM New York, NY, USA} |  |  |
| } |  |  |
| @inproceedings{dai2017dcn, |  |  |
| title={Deformable convolutional networks}, |  |  |
| author={Dai, Jifeng and Qi, Haozhi and Xiong, Yuwen and Li, Yi and Zhang, Guodong and Hu, Han and Wei, Yichen}, |  |  |
| booktitle={Proceedings of the IEEE international conference on computer vision}, |  |  |
| pages={764--773}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{zhu2019deformable, |  |  |
| title={Deformable convnets v2: More deformable, better results}, |  |  |
| author={Zhu, Xizhou and Hu, Han and Lin, Stephen and Dai, Jifeng}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={9308--9316}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @inproceedings{long2016learning, |  |  |
| title={Learning image matching by simply watching video}, |  |  |
| author={Long, Gucan and Kneip, Laurent and Alvarez, Jose M and Li, Hongdong and Zhang, Xiaohu and Yu, Qifeng}, |  |  |
| booktitle={Computer Vision--ECCV 2016: 14th European Conference, Amsterdam, The Netherlands, October 11-14, 2016, Proceedings, Part VI 14}, |  |  |
| pages={434--450}, |  |  |
| year={2016}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{niklaus2017adaconv, |  |  |
| title={Video frame interpolation via adaptive convolution}, |  |  |
| author={Niklaus, Simon and Mai, Long and Liu, Feng}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={670--679}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{niklaus2017sepconv, |  |  |
| title={Video frame interpolation via adaptive separable convolution}, |  |  |
| author={Niklaus, Simon and Mai, Long and Liu, Feng}, |  |  |
| booktitle={Proceedings of the IEEE international conference on computer vision}, |  |  |
| pages={261--270}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{peleg2019net, |  |  |
| title={Im-net for high resolution video frame interpolation}, |  |  |
| author={Peleg, Tomer and Szekely, Pablo and Sabo, Doron and Sendik, Omry}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern Recognition}, |  |  |
| pages={2398--2407}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @article{shi2020video, |  |  |
| title={Video frame interpolation via generalized deformable convolution}, |  |  |
| author={Shi, Zhihao and Liu, Xiaohong and Shi, Kangdi and Dai, Linhui and Chen, Jun}, |  |  |
| journal={IEEE transactions on multimedia}, |  |  |
| volume={24}, |  |  |
| pages={426--439}, |  |  |
| year={2021}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{choi2020cain, |  |  |
| title={Channel attention is all you need for video frame interpolation}, |  |  |
| author={Choi, Myungsub and Kim, Heewon and Han, Bohyung and Xu, Ning and Lee, Kyoung Mu}, |  |  |
| booktitle={Proceedings of the AAAI conference on artificial intelligence}, |  |  |
| volume={34}, |  |  |
| number={07}, |  |  |
| pages={10663--10671}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{cheng2020video, |  |  |
| title={Video frame interpolation via deformable separable convolution}, |  |  |
| author={Cheng, Xianhang and Chen, Zhenzhong}, |  |  |
| booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, |  |  |
| volume={34}, |  |  |
| number={07}, |  |  |
| pages={10607--10614}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @article{shi2021video, |  |  |
| title={Video frame interpolation via generalized deformable convolution}, |  |  |
| author={Shi, Zhihao and Liu, Xiaohong and Shi, Kangdi and Dai, Linhui and Chen, Jun}, |  |  |
| journal={IEEE transactions on multimedia}, |  |  |
| volume={24}, |  |  |
| pages={426--439}, |  |  |
| year={2021}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{cheng2021multiple, |  |  |
| title={Multiple video frame interpolation via enhanced deformable separable convolution}, |  |  |
| author={Cheng, Xianhang and Chen, Zhenzhong}, |  |  |
| journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, |  |  |
| volume={44}, |  |  |
| number={10}, |  |  |
| pages={7029--7045}, |  |  |
| year={2021}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{ding2021cdfi, |  |  |
| title={Cdfi: Compression-driven network design for frame interpolation}, |  |  |
| author={Ding, Tianyu and Liang, Luming and Zhu, Zhihui and Zharkov, Ilya}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={8001--8011}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @article{chen2021pdwn, |  |  |
| title={PDWN: Pyramid deformable warping network for video interpolation}, |  |  |
| author={Chen, Zhiqi and Wang, Ran and Liu, Haojie and Wang, Yao}, |  |  |
| journal={IEEE Open Journal of Signal Processing}, |  |  |
| volume={2}, |  |  |
| pages={413--424}, |  |  |
| year={2021}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{danier2022enhancing, |  |  |
| title={Enhancing deformable convolution based video frame interpolation with coarse-to-fine 3D CNN}, |  |  |
| author={Danier, Duolikun and Zhang, Fan and Bull, David}, |  |  |
| booktitle={2022 IEEE International Conference on Image Processing (ICIP)}, |  |  |
| pages={1396--1400}, |  |  |
| year={2022}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{ding2022MSEConv, |  |  |
| title={Video frame interpolation via local lightweight bidirectional encoding with channel attention cascade}, |  |  |
| author={Ding, Xiangling and Huang, Pu and Zhang, Dengyong and Zhao, Xianfeng}, |  |  |
| booktitle={ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, |  |  |
| pages={1915--1919}, |  |  |
| year={2022}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{kalluri2023flavr, |  |  |
| title={Flavr: Flow-agnostic video representations for fast frame interpolation}, |  |  |
| author={Kalluri, Tarun and Pathak, Deepak and Chandraker, Manmohan and Tran, Du}, |  |  |
| booktitle={Proceedings of the IEEE/CVF winter conference on applications of computer vision}, |  |  |
| pages={2071--2082}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{zhou2023exploring, |  |  |
| title={Exploring motion ambiguity and alignment for high-quality video frame interpolation}, |  |  |
| author={Zhou, Kun and Li, Wenbo and Han, Xiaoguang and Lu, Jiangbo}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={22169--22179}, |  |  |
| year={2023} |  |  |
| } |  |  |

### Kernel-Flow combined

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{niklaus2018context, |  |  |
| title={Context-aware synthesis for video frame interpolation}, |  |  |
| author={Niklaus, Simon and Liu, Feng}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={1701--1710}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @article{bao2019memc, |  |  |
| title={Memc-net: Motion estimation and motion compensation driven neural network for video interpolation and enhancement}, |  |  |
| author={Bao, Wenbo and Lai, Wei-Sheng and Zhang, Xiaoyun and Gao, Zhiyong and Yang, Ming-Hsuan}, |  |  |
| journal={IEEE transactions on pattern analysis and machine intelligence}, |  |  |
| volume={43}, |  |  |
| number={3}, |  |  |
| pages={933--948}, |  |  |
| year={2019}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{park2020bmbc, |  |  |
| title={Bmbc: Bilateral motion estimation with bilateral cost volume for video interpolation}, |  |  |
| author={Park, Junheum and Ko, Keunsoo and Lee, Chul and Kim, Chang-Su}, |  |  |
| booktitle={Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part XIV 16}, |  |  |
| pages={109--125}, |  |  |
| year={2020}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{lee2020adacof, |  |  |
| title={Adacof: Adaptive collaboration of flows for video frame interpolation}, |  |  |
| author={Lee, Hyeongmin and Kim, Taeoh and Chung, Tae-young and Pak, Daehyun and Ban, Yuseok and Lee, Sangyoun}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={5316--5325}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{gui2020featureflow, |  |  |
| title={Featureflow: Robust video interpolation via structure-to-texture generation}, |  |  |
| author={Gui, Shurui and Wang, Chaoyue and Chen, Qihua and Tao, Dacheng}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={14004--14013}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{niklaus2021revisiting, |  |  |
| title={Revisiting adaptive convolutions for video frame interpolation}, |  |  |
| author={Niklaus, Simon and Mai, Long and Wang, Oliver}, |  |  |
| booktitle={Proceedings of the IEEE/CVF winter conference on applications of computer vision}, |  |  |
| pages={1099--1109}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @article{shen2024ladder, |  |  |
| title={LADDER: An Efficient Framework for Video Frame Interpolation}, |  |  |
| author={Shen, Tong and Li, Dong and Gao, Ziheng and Tian, Lu and Barsoum, Emad}, |  |  |
| journal={arXiv preprint arXiv:2404.11108}, |  |  |
| year={2024} |  |  |
| } |  |  |

### Phase-based

| Title | Conference | Year |
|-------|------------|------|
| @article{simon1992shiftable, |  |  |
| title={Shiftable multiscale transforms}, |  |  |
| author={Simoncelli, Eero P and Freeman, William T and Adelson, Edward H and Heeger, David J}, |  |  |
| journal={IEEE transactions on Information Theory}, |  |  |
| volume={38}, |  |  |
| number={2}, |  |  |
| pages={587--607}, |  |  |
| year={1992}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{simon1995steerable, |  |  |
| title={The steerable pyramid: A flexible architecture for multi-scale derivative computation}, |  |  |
| author={Simoncelli, Eero P and Freeman, William T}, |  |  |
| booktitle={Proceedings., international conference on image processing}, |  |  |
| volume={3}, |  |  |
| pages={444--447}, |  |  |
| year={1995}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @article{portilla2000parametric, |  |  |
| title={A parametric texture model based on joint statistics of complex wavelet coefficients}, |  |  |
| author={Portilla, Javier and Simoncelli, Eero P}, |  |  |
| journal={International journal of computer vision}, |  |  |
| volume={40}, |  |  |
| pages={49--70}, |  |  |
| year={2000}, |  |  |
| publisher={Springer} |  |  |
| } |  |  |
| @inproceedings{meyer2015phase, |  |  |
| title={Phase-based frame interpolation for video}, |  |  |
| author={Meyer, Simone and Wang, Oliver and Zimmer, Henning and Grosse, Max and Sorkine-Hornung, Alexander}, |  |  |
| booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, |  |  |
| pages={1410--1418}, |  |  |
| year={2015} |  |  |
| } |  |  |
| @inproceedings{meyer2018phasenet, |  |  |
| title={Phasenet for video frame interpolation}, |  |  |
| author={Meyer, Simone and Djelouah, Abdelaziz and McWilliams, Brian and Sorkine-Hornung, Alexander and Gross, Markus and Schroers, Christopher}, |  |  |
| booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={498--507}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @article{wadhwa2013phasebase, |  |  |
| title={Phase-based video motion processing}, |  |  |
| author={Wadhwa, Neal and Rubinstein, Michael and Durand, Fr{\'e}do and Freeman, William T}, |  |  |
| journal={ACM Transactions on Graphics (ToG)}, |  |  |
| volume={32}, |  |  |
| number={4}, |  |  |
| pages={1--10}, |  |  |
| year={2013}, |  |  |
| publisher={ACM New York, NY, USA} |  |  |
| } |  |  |
| @article{didyk2013jointview, |  |  |
| title={Joint view expansion and filtering for automultiscopic 3D displays}, |  |  |
| author={Didyk, Piotr and Sitthi-Amorn, Pitchaya and Freeman, William and Durand, Fr{\'e}do and Matusik, Wojciech}, |  |  |
| journal={ACM Transactions on Graphics (TOG)}, |  |  |
| volume={32}, |  |  |
| number={6}, |  |  |
| pages={1--8}, |  |  |
| year={2013}, |  |  |
| publisher={ACM New York, NY, USA} |  |  |
| } |  |  |

### Transformer-based

| Title | Conference | Year |
|-------|------------|------|
| @article{cho2014learning, |  |  |
| title={Learning phrase representations using RNN encoder-decoder for statistical machine translation}, |  |  |
| author={Cho, Kyunghyun and Van Merri{\"e}nboer, Bart and Gulcehre, Caglar and Bahdanau, Dzmitry and Bougares, Fethi and Schwenk, Holger and Bengio, Yoshua}, |  |  |
| journal={arXiv preprint arXiv:1406.1078}, |  |  |
| year={2014} |  |  |
| } |  |  |
| @inproceedings{vaswani2017attention, |  |  |
| title={Attention is all you need}, |  |  |
| author={Vaswani, Ashish and Shazeer, Noam and Parmar, Niki and Uszkoreit, Jakob and Jones, Llion and Gomez, Aidan N and Kaiser, {\L}ukasz and Polosukhin, Illia}, |  |  |
| journal={Advances in neural information processing systems}, |  |  |
| volume={30}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{liu2021swin, |  |  |
| title={Swin transformer: Hierarchical vision transformer using shifted windows}, |  |  |
| author={Liu, Ze and Lin, Yutong and Cao, Yue and Hu, Han and Wei, Yixuan and Zhang, Zheng and Lin, Stephen and Guo, Baining}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={10012--10022}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{lu2022video, |  |  |
| title={Video frame interpolation with transformer}, |  |  |
| author={Lu, Liying and Wu, Ruizheng and Lin, Huaijia and Lu, Jiangbo and Jia, Jiaya}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={3532--3542}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{shi2022video, |  |  |
| title={Video frame interpolation transformer}, |  |  |
| author={Shi, Zhihao and Xu, Xiangyu and Liu, Xiaohong and Chen, Jun and Yang, Ming-Hsuan}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={17482--17491}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @article{zhang2023L2BEC2, |  |  |
| title={L2BEC2: Local lightweight bidirectional encoding and channel attention cascade for video frame interpolation}, |  |  |
| author={Zhang, Dengyong and Huang, Pu and Ding, Xiangling and Li, Feng and Zhu, Wenjie and Song, Yun and Yang, Gaobo}, |  |  |
| journal={ACM Transactions on Multimedia Computing, Communications and Applications}, |  |  |
| volume={19}, |  |  |
| number={2}, |  |  |
| pages={1--19}, |  |  |
| year={2023}, |  |  |
| publisher={ACM New York, NY} |  |  |
| } |  |  |
| @article{liu2023ttvfi, |  |  |
| title={TTVFI: Learning trajectory-aware transformer for video frame interpolation}, |  |  |
| author={Liu, Chengxu and Yang, Huan and Fu, Jianlong and Qian, Xueming}, |  |  |
| journal={IEEE Transactions on Image Processing}, |  |  |
| volume={32}, |  |  |
| pages={4728--4741}, |  |  |
| year={2023}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{liu2024sparse, |  |  |
| title={Sparse global matching for video frame interpolation with large motion}, |  |  |
| author={Liu, Chunxu and Zhang, Guozhen and Zhao, Rui and Wang, Limin}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={19125--19134}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{zamir2022restormer, |  |  |
| title={Restormer: Efficient transformer for high-resolution image restoration}, |  |  |
| author={Zamir, Syed Waqas and Arora, Aditya and Khan, Salman and Hayat, Munawar and Khan, Fahad Shahbaz and Yang, Ming-Hsuan}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={5728--5739}, |  |  |
| year={2022} |  |  |
| } |  |  |

### Mamba

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{arjovsky2016unitary, |  |  |
| title={Unitary evolution recurrent neural networks}, |  |  |
| author={Arjovsky, Martin and Shah, Amar and Bengio, Yoshua}, |  |  |
| booktitle={International conference on machine learning}, |  |  |
| pages={1120--1128}, |  |  |
| year={2016}, |  |  |
| organization={PMLR} |  |  |
| } |  |  |
| @article{gu2021efficiently, |  |  |
| author={Gu, A. and Goel, K. and Ré, C.}, |  |  |
| title={Efficiently modeling long sequences with structured state spaces}, |  |  |
| journal={arXiv preprint arXiv:2111.00396}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @article{gu2023mamba, |  |  |
| author={Gu, A. and Dao, T.}, |  |  |
| title={Mamba: Linear-time sequence modeling with selective state spaces}, |  |  |
| journal={arXiv preprint arXiv:2312.00752}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{zhang2024vfimamba, |  |  |
| title={Vfimamba: Video frame interpolation with state space models}, |  |  |
| author={Zhang, Guozhen and Liu, Chuxnu and Cui, Yutao and Zhao, Xiaotong and Ma, Kai and Wang, Limin}, |  |  |
| journal={Advances in Neural Information Processing Systems}, |  |  |
| volume={37}, |  |  |
| pages={107225--107248}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{guo2024mambair, |  |  |
| title={Mambair: A simple baseline for image restoration with state-space model}, |  |  |
| author={Guo, Hang and Li, Jinmin and Dai, Tao and Ouyang, Zhihao and Ren, Xudong and Xia, Shu-Tao}, |  |  |
| booktitle={European conference on computer vision}, |  |  |
| pages={222--241}, |  |  |
| year={2024}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @article{guo2024mambairv2, |  |  |
| title={MambaIRv2: Attentive State Space Restoration}, |  |  |
| author={Guo, Hang and Guo, Yong and Zha, Yaohua and Zhang, Yulun and Li, Wenbo and Dai, Tao and Xia, Shu-Tao and Li, Yawei}, |  |  |
| journal={arXiv preprint arXiv:2411.15269}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{huang2024irsrmamba, |  |  |
| author={Huang, Yongsong and Miyazaki, Tomo and Liu, Xiaofeng and Omachi, Shinichiro}, |  |  |
| title={IRSRMamba: Infrared Image Super-Resolution via Mamba-based Wavelet Transform Feature Modulation Model}, |  |  |
| journal={arXiv preprint arXiv:2405.09873}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{gao2024learning, |  |  |
| title={Learning enriched features via selective state spaces model for efficient image deblurring}, |  |  |
| author={Gao, Hu and Ma, Bowen and Zhang, Ying and Yang, Jingfan and Yang, Jing and Dang, Depeng}, |  |  |
| booktitle={Proceedings of the 32nd ACM International Conference on Multimedia}, |  |  |
| pages={710--718}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{kong2024efficient, |  |  |
| author={Kong, Lingshun and Dong, Jiangxin and Yang, Ming-Hsuan and Pan, Jinshan}, |  |  |
| title={Efficient visual state space model for image deblurring}, |  |  |
| journal={arXiv preprint arXiv:2405.14343}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{li2024mair, |  |  |
| title={MaIR: A Locality-and Continuity-Preserving Mamba for Image Restoration}, |  |  |
| author={Li, Boyun and Zhao, Haiyu and Wang, Wenxin and Hu, Peng and Gou, Yuanbiao and Peng, Xi}, |  |  |
| journal={arXiv preprint arXiv:2412.20066}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{di2024qmambabsr, |  |  |
| title={QMambaBSR: Burst Image Super-Resolution with Query State Space Model}, |  |  |
| author={Di, Xin and Peng, Long and Xia, Peizhe and Li, Wenbo and Pei, Renjing and Cao, Yang and Wang, Yang and Zha, Zheng-Jun}, |  |  |
| journal={arXiv preprint arXiv:2408.08665}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{du2025mambaflow, |  |  |
| title={MambaFlow: A Mamba-Centric Architecture for End-to-End Optical Flow Estimation}, |  |  |
| author={Du, Juntian and Sun, Yuan and Zhou, Zhihu and Chen, Pinyi and Zhang, Runzhe and Mao, Keji}, |  |  |
| journal={arXiv preprint arXiv:2503.07046}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @inproceedings{zhu2025first, |  |  |
| title={First-order State Space Model for Lightweight Image Super-resolution}, |  |  |
| author={Zhu, Yujie and Zhang, Xinyi and Lu, Yekai and Yang, Guang and Fang, Faming and Zhang, Guixu}, |  |  |
| booktitle={ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, |  |  |
| pages={1--5}, |  |  |
| year={2025}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |

### Deep learning-based vs. Generative

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{liu2015vgg, |  |  |
| title={Very deep convolutional neural network based image classification using small training sample size}, |  |  |
| author={Liu, Shuying and Deng, Weihong}, |  |  |
| booktitle={2015 3rd IAPR Asian conference on pattern recognition (ACPR)}, |  |  |
| pages={730--734}, |  |  |
| year={2015}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{men2020VQA, |  |  |
| title={Visual quality assessment for interpolated slow-motion videos based on a novel database}, |  |  |
| author={Men, Hui and Hosu, Vlad and Lin, Hanhe and Bruhn, Andr{\'e}s and Saupe, Dietmar}, |  |  |
| booktitle={2020 Twelfth International Conference on Quality of Multimedia Experience (QoMEX)}, |  |  |
| pages={1--6}, |  |  |
| year={2020}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{danier2022VQA, |  |  |
| title={A subjective quality study for video frame interpolation}, |  |  |
| author={Danier, Duolikun and Zhang, Fan and Bull, David}, |  |  |
| booktitle={2022 IEEE International Conference on Image Processing (ICIP)}, |  |  |
| pages={1361--1365}, |  |  |
| year={2022}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @article{ho2022cascaded, |  |  |
| title={Cascaded diffusion models for high fidelity image generation}, |  |  |
| author={Ho, Jonathan and Saharia, Chitwan and Chan, William and Fleet, David J and Norouzi, Mohammad and Salimans, Tim}, |  |  |
| journal={Journal of Machine Learning Research}, |  |  |
| volume={23}, |  |  |
| number={47}, |  |  |
| pages={1--33}, |  |  |
| year={2022} |  |  |
| } |  |  |

### GAN

| Title | Conference | Year |
|-------|------------|------|
| @article{goodfellow2020generative, |  |  |
| title={Generative adversarial networks}, |  |  |
| author={Goodfellow, Ian and Pouget-Abadie, Jean and Mirza, Mehdi and Xu, Bing and Warde-Farley, David and Ozair, Sherjil and Courville, Aaron and Bengio, Yoshua}, |  |  |
| journal={Communications of the ACM}, |  |  |
| volume={63}, |  |  |
| number={11}, |  |  |
| pages={139--144}, |  |  |
| year={2020}, |  |  |
| publisher={ACM New York, NY, USA} |  |  |
| } |  |  |
| @inproceedings{kingma2013auto, |  |  |
| title={Auto-encoding variational bayes}, |  |  |
| author={Kingma, Diederik P and Welling, Max and others}, |  |  |
| year={2013}, |  |  |
| publisher={Banff, Canada} |  |  |
| } |  |  |
| @inproceedings{dhariwal2021diffusion, |  |  |
| title={Diffusion models beat gans on image synthesis}, |  |  |
| author={Dhariwal, Prafulla and Nichol, Alexander}, |  |  |
| journal={Advances in neural information processing systems}, |  |  |
| volume={34}, |  |  |
| pages={8780--8794}, |  |  |
| year={2021} |  |  |
| } |  |  |

### DM-based

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{ho2020denoising, |  |  |
| title={Denoising diffusion probabilistic models}, |  |  |
| author={Ho, Jonathan and Jain, Ajay and Abbeel, Pieter}, |  |  |
| journal={Advances in neural information processing systems}, |  |  |
| volume={33}, |  |  |
| pages={6840--6851}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @article{song2020denoising, |  |  |
| title={Denoising diffusion implicit models}, |  |  |
| author={Song, Jiaming and Meng, Chenlin and Ermon, Stefano}, |  |  |
| journal={arXiv preprint arXiv:2010.02502}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{rombach2022high, |  |  |
| title={High-resolution image synthesis with latent diffusion models}, |  |  |
| author={Rombach, Robin and Blattmann, Andreas and Lorenz, Dominik and Esser, Patrick and Ommer, Bj{\"o}rn}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={10684--10695}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{ho2022video, |  |  |
| title={Video diffusion models}, |  |  |
| author={Ho, Jonathan and Salimans, Tim and Gritsenko, Alexey and Chan, William and Norouzi, Mohammad and Fleet, David J}, |  |  |
| journal={Advances in Neural Information Processing Systems}, |  |  |
| volume={35}, |  |  |
| pages={8633--8646}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{blattmann2023align, |  |  |
| title={Align your latents: High-resolution video synthesis with latent diffusion models}, |  |  |
| author={Blattmann, Andreas and Rombach, Robin and Ling, Huan and Dockhorn, Tim and Kim, Seung Wook and Fidler, Sanja and Kreis, Karsten}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={22563--22575}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @article{blattmann2023stable, |  |  |
| author={Blattmann, Andreas and Dockhorn, Tim and Kulal, Sumith and Mendelevitch, Daniel and Kilian, Maciej and Lorenz, Dominik and Levi, Yam and English, Zion and Voleti, Vikram and Letts, Adam and others}, |  |  |
| title={Stable video diffusion: Scaling latent video diffusion models to large datasets}, |  |  |
| journal={arXiv preprint arXiv:2311.15127}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @article{song2023consistency, |  |  |
| title={Consistency models}, |  |  |
| author={Song, Yang and Dhariwal, Prafulla and Chen, Mark and Sutskever, Ilya}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @article{karras2022elucidating, |  |  |
| title={Elucidating the design space of diffusion-based generative models}, |  |  |
| author={Karras, Tero and Aittala, Miika and Aila, Timo and Laine, Samuli}, |  |  |
| journal={Advances in neural information processing systems}, |  |  |
| volume={35}, |  |  |
| pages={26565--26577}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @article{salimans2022progressive, |  |  |
| author={Salimans, T. and Ho, J.}, |  |  |
| title={Progressive distillation for fast sampling of diffusion models}, |  |  |
| journal={arXiv preprint arXiv:2202.00512}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @article{luo2023latent, |  |  |
| title={Latent consistency models: Synthesizing high-resolution images with few-step inference}, |  |  |
| author={Luo, Simian and Tan, Yiqin and Huang, Longbo and Li, Jian and Zhao, Hang}, |  |  |
| journal={arXiv preprint arXiv:2310.04378}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{yin2024onestep, |  |  |
| title={One-step diffusion with distribution matching distillation}, |  |  |
| author={Yin, Tianwei and Gharbi, Micha{\"e}l and Zhang, Richard and Shechtman, Eli and Durand, Fredo and Freeman, William T and Park, Taesung}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={6613--6623}, |  |  |
| year={2024} |  |  |
| } |  |  |

### Adapters

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{zhang2023adding, |  |  |
| title={Adding conditional control to text-to-image diffusion models}, |  |  |
| author={Zhang, Lvmin and Rao, Anyi and Agrawala, Maneesh}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={3836--3847}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @article{peng2024controlnext, |  |  |
| title={Controlnext: Powerful and efficient control for image and video generation}, |  |  |
| author={Peng, Bohao and Wang, Jian and Zhang, Yuechen and Li, Wenbo and Yang, Ming-Chang and Jia, Jiaya}, |  |  |
| journal={arXiv preprint arXiv:2408.06070}, |  |  |
| year={2024} |  |  |
| } |  |  |

### T2V and I2V

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{wu2023tune, |  |  |
| title={Tune-a-video: One-shot tuning of image diffusion models for text-to-video generation}, |  |  |
| author={Wu, Jay Zhangjie and Ge, Yixiao and Wang, Xintao and Lei, Stan Weixian and Gu, Yuchao and Shi, Yufei and Hsu, Wynne and Shan, Ying and Qie, Xiaohu and Shou, Mike Zheng}, |  |  |
| booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision}, |  |  |
| pages={7623--7633}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @article{yang2024cogvideox, |  |  |
| title={Cogvideox: Text-to-video diffusion models with an expert transformer}, |  |  |
| author={Yang, Zhuoyi and Teng, Jiayan and Zheng, Wendi and Ding, Ming and Huang, Shiyu and Xu, Jiazheng and Yang, Yuanming and Hong, Wenyi and Zhang, Xiaohan and Feng, Guanyu and others}, |  |  |
| journal={arXiv preprint arXiv:2408.06072}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{yuan2024idpreserve, |  |  |
| author={Yuan, S. and others}, |  |  |
| title={Identity-Preserving Text-to-Video Generation by Frequency Decomposition}, |  |  |
| journal={arXiv preprint arXiv:2411.17440}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{bar2024lumiere, |  |  |
| title={Lumiere: A space-time diffusion model for video generation}, |  |  |
| author={Bar-Tal, Omer and Chefer, Hila and Tov, Omer and Herrmann, Charles and Paiss, Roni and Zada, Shiran and Ephrat, Ariel and Hur, Junhwa and Liu, Guanghui and Raj, Amit and others}, |  |  |
| booktitle={SIGGRAPH Asia 2024 Conference Papers}, |  |  |
| pages={1--11}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{zhang2023i2vgenxl, |  |  |
| author={Zhang, S. and others}, |  |  |
| title={I2vgen-xl: High-quality image-to-video synthesis via cascaded diffusion models}, |  |  |
| journal={arXiv preprint arXiv:2311.04145}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @article{ren2024consisti2v, |  |  |
| author={Ren, W. and others}, |  |  |
| title={Consisti2v: Enhancing visual consistency for image-to-video generation}, |  |  |
| journal={arXiv preprint arXiv:2402.04324}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{hu2024animateanyone, |  |  |
| title={Animate anyone: Consistent and controllable image-to-video synthesis for character animation}, |  |  |
| author={Hu, Li}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={8153--8163}, |  |  |
| year={2024} |  |  |
| } |  |  |

### Event-based

| Title | Conference | Year |
|-------|------------|------|
| @article{lich2008eventcamera, |  |  |
| title={A 128 $\times$ 128 120 dB 15 $\mu$ s latency asynchronous temporal contrast vision sensor}, |  |  |
| author={Lichtsteiner, Patrick and Posch, Christoph and Delbruck, Tobi}, |  |  |
| journal={IEEE journal of solid-state circuits}, |  |  |
| volume={43}, |  |  |
| number={2}, |  |  |
| pages={566--576}, |  |  |
| year={2008}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{kaiser2016towards, |  |  |
| title={Towards a framework for end-to-end control of a simulated vehicle with spiking neural networks}, |  |  |
| author={Kaiser, Jacques and Tieck, J Camilo Vasquez and Hubschneider, Christian and Wolf, Peter and Weber, Michael and Hoff, Michael and Friedrich, Alexander and Wojtasik, Konrad and Roennau, Arne and Kohlhaas, Ralf and others}, |  |  |
| booktitle={2016 IEEE International Conference on Simulation, Modeling, and Programming for Autonomous Robots (SIMPAR)}, |  |  |
| pages={127--134}, |  |  |
| year={2016}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{bi2017pix2nvs, |  |  |
| title={PIX2NVS: Parameterized conversion of pixel-domain video frames to neuromorphic vision streams}, |  |  |
| author={Bi, Yin and Andreopoulos, Yiannis}, |  |  |
| booktitle={2017 IEEE International Conference on Image Processing (ICIP)}, |  |  |
| pages={1990--1994}, |  |  |
| year={2017}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{rebecq2018esim, |  |  |
| title={Esim: an open event camera simulator}, |  |  |
| author={Rebecq, Henri and Gehrig, Daniel and Scaramuzza, Davide}, |  |  |
| booktitle={Conference on robot learning}, |  |  |
| pages={969--982}, |  |  |
| year={2018}, |  |  |
| organization={PMLR} |  |  |
| } |  |  |
| @inproceedings{wang2019event, |  |  |
| title={Event-driven video frame synthesis}, |  |  |
| author={Wang, Zihao W and Jiang, Weixin and He, Kuan and Shi, Boxin and Katsaggelos, Aggelos and Cossairt, Oliver}, |  |  |
| booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision Workshops}, |  |  |
| pages={0--0}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @inproceedings{lin2020learning, |  |  |
| title={Learning event-driven video deblurring and interpolation}, |  |  |
| author={Lin, Songnan and Zhang, Jiawei and Pan, Jinshan and Jiang, Zhe and Zou, Dongqing and Wang, Yongtian and Chen, Jing and Ren, Jimmy}, |  |  |
| booktitle={Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part VIII 16}, |  |  |
| pages={695--710}, |  |  |
| year={2020}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{tulyakov2021time, |  |  |
| title={Time lens: Event-based video frame interpolation}, |  |  |
| author={Tulyakov, Stepan and Gehrig, Daniel and Georgoulis, Stamatios and Erbach, Julius and Gehrig, Mathias and Li, Yuanyou and Scaramuzza, Davide}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={16155--16164}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{zhu2021eventgan, |  |  |
| title={Eventgan: Leveraging large scale image datasets for event cameras}, |  |  |
| author={Zhu, Alex Zihao and Wang, Ziyun and Khant, Kaung and Daniilidis, Kostas}, |  |  |
| booktitle={2021 IEEE international conference on computational photography (ICCP)}, |  |  |
| pages={1--11}, |  |  |
| year={2021}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{yu2021training, |  |  |
| title={Training weakly supervised video frame interpolation with events}, |  |  |
| author={Yu, Zhiyang and Zhang, Yu and Liu, Deyuan and Zou, Dongqing and Chen, Xijun and Liu, Yebin and Ren, Jimmy S}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={14589--14598}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{zhang2022unifying, |  |  |
| title={Unifying motion deblurring and frame interpolation with events}, |  |  |
| author={Zhang, Xiang and Yu, Lei}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={17765--17774}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{tulyakov2022time, |  |  |
| title={Time lens++: Event-based frame interpolation with parametric non-linear flow and multi-scale fusion}, |  |  |
| author={Tulyakov, Stepan and Bochicchio, Alfredo and Gehrig, Daniel and Georgoulis, Stamatios and Li, Yuanyou and Scaramuzza, Davide}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={17755--17764}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{he2022timereplayer, |  |  |
| title={Timereplayer: Unlocking the potential of event cameras for video interpolation}, |  |  |
| author={He, Weihua and You, Kaichao and Qiao, Zhendong and Jia, Xu and Zhang, Ziyang and Wang, Wenhui and Lu, Huchuan and Wang, Yaoyuan and Liao, Jianxing}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={17804--17813}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{wu2022video, |  |  |
| title={Video interpolation by event-driven anisotropic adjustment of optical flow}, |  |  |
| author={Wu, Song and You, Kaichao and He, Weihua and Yang, Chen and Tian, Yang and Wang, Yaoyuan and Zhang, Ziyang and Liao, Jianxing}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={267--283}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{niwa2023, |  |  |
| title={A 2.97 $\mu$m-pitch event-based vision sensor with shared pixel front-end circuitry and low-noise intensity readout mode}, |  |  |
| author={Niwa, Atsumi and Mochizuki, Futa and Berner, Raphael and Maruyarma, Takuya and Terano, Toshio and Takamiya, Kenichi and Kimura, Yasutaka and Mizoguchi, Kyoji and Miyazaki, Takahiro and Kaizu, Shun and others}, |  |  |
| booktitle={2023 IEEE International Solid-State Circuits Conference (ISSCC)}, |  |  |
| pages={4--6}, |  |  |
| year={2023}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{kim2023event, |  |  |
| title={Event-based video frame interpolation with cross-modal asymmetric bidirectional motion fields}, |  |  |
| author={Kim, Taewoo and Chae, Yujeong and Jang, Hyun-Kurl and Yoon, Kuk-Jin}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={18032--18042}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{lin2023event, |  |  |
| title={Event-guided frame interpolation and dynamic range expansion of single rolling shutter image}, |  |  |
| author={Lin, Guixu and Han, Jin and Cao, Mingdeng and Zhong, Zhihang and Zheng, Yinqiang}, |  |  |
| booktitle={Proceedings of the 31st ACM International Conference on Multimedia}, |  |  |
| pages={3078--3088}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{zhang2024v2ce, |  |  |
| title={V2ce: Video to continuous events simulator}, |  |  |
| author={Zhang, Zhongyang and Cui, Shuyang and Chai, Kaidong and Yu, Haowen and Dasgupta, Subhasis and Mahbub, Upal and Rahman, Tauhidur}, |  |  |
| booktitle={2024 IEEE International Conference on Robotics and Automation (ICRA)}, |  |  |
| pages={12455--12461}, |  |  |
| year={2024}, |  |  |
| organization={IEEE} |  |  |
| } |  |  |
| @inproceedings{liu2024video, |  |  |
| title={Video frame interpolation via direct synthesis with the event-based reference}, |  |  |
| author={Liu, Yuhan and Deng, Yongjian and Chen, Hao and Yang, Zhen}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={8477--8487}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{ma2024timelens, |  |  |
| title={TimeLens-XL: Real-Time Event-Based Video Frame Interpolation with Large Motion}, |  |  |
| author={Ma, Yongrui and Guo, Shi and Chen, Yutian and Xue, Tianfan and Gu, Jinwei}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={178--194}, |  |  |
| year={2024}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @article{chen2024repurposing, |  |  |
| author={Chen, J. and others}, |  |  |
| title={Repurposing pre-trained video diffusion models for event-based video interpolation}, |  |  |
| journal={arXiv preprint arXiv:2412.07761}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{zhang2025egvd, |  |  |
| author={Zhang, Z. and others}, |  |  |
| title={EGVD: Event-Guided Video Diffusion Model for Physically Realistic Large-Motion Frame Interpolation}, |  |  |
| journal={arXiv preprint arXiv:2503.20268}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @article{takahashi2025coupled, |  |  |
| author={Takahashi, Hidekazu and Nagumo, Takefumi and Jo, Kensei and Andreas, Aumiller and Rad, Saeed and Daudt, Rodrigo Caye and Miyatani, Yoshitaka and Wakabayashi, Hayato and Brandli, Christian}, |  |  |
| title={Coupled Video Frame Interpolation and Encoding with Hybrid Event Cameras for Low-Power High-Framerate Video}, |  |  |
| journal={arXiv preprint arXiv:2503.22491}, |  |  |
| year={2025} |  |  |
| } |  |  |

### event + sr

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{chen2021turning, |  |  |
| title={Turning frequency to resolution: Video super-resolution via event cameras}, |  |  |
| author={Jing, Yongcheng and Yang, Yiding and Wang, Xinchao and Song, Mingli and Tao, Dacheng}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={7772--7781}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{lu2023learning, |  |  |
| title={Learning spatial-temporal implicit neural representations for event-guided video super-resolution}, |  |  |
| author={Lu, Yunfan and Wang, Zipeng and Liu, Minjie and Wang, Hongjian and Wang, Lin}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={1557--1567}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{kai2024evtexture, |  |  |
| title={EvTexture: event-driven texture enhancement for video super-resolution}, |  |  |
| author={Kai, Dachun and Lu, Jiayao and Zhang, Yueyi and Sun, Xiaoyan}, |  |  |
| booktitle={Forty-first International Conference on Machine Learning}, |  |  |
| year={2024} |  |  |
| } |  |  |

### Medic

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{guo2020spatiotemporal, |  |  |
| title={A spatiotemporal volumetric interpolation network for 4d dynamic medical image}, |  |  |
| author={Guo, Yuyu and Bi, Lei and Ahn, Euijoon and Feng, Dagan and Wang, Qian and Kim, Jinman}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={4726--4735}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{kim2024data, |  |  |
| title={Data-efficient unsupervised interpolation without any intermediate frame for 4d medical images}, |  |  |
| author={Kim, JungEun and Yoon, Hangyul and Park, Geondo and Kim, Kyungsu and Yang, Eunho}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={11353--11364}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{li2024cpt, |  |  |
| title={CPT-Interp: Continuous sPatial and Temporal Motion Modeling for 4D Medical Image Interpolation}, |  |  |
| author={Li, Xia and Yang, Runzhao and Li, Xiangtai and Lomax, Antony and Zhang, Ye and Buhmann, Joachim}, |  |  |
| journal={arXiv preprint arXiv:2405.15385}, |  |  |
| year={2024} |  |  |
| } |  |  |

### cartoon interpolation

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{siyao2021deep, |  |  |
| title={Deep animation video interpolation in the wild}, |  |  |
| author={Siyao, Li and Zhao, Shiyu and Yu, Weijiang and Sun, Wenxiu and Metaxas, Dimitris and Loy, Chen Change and Liu, Ziwei}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={6587--6595}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{chen2022improving, |  |  |
| title={Improving the perceptual quality of 2d animation interpolation}, |  |  |
| author={Chen, Shuhong and Zwicker, Matthias}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={271--287}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @article{li2021deep, |  |  |
| title={Deep sketch-guided cartoon video inbetweening}, |  |  |
| author={Li, Xiaoyu and Zhang, Bo and Liao, Jing and Sander, Pedro V}, |  |  |
| journal={IEEE Transactions on Visualization and Computer Graphics}, |  |  |
| volume={28}, |  |  |
| number={8}, |  |  |
| pages={2938--2952}, |  |  |
| year={2021}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{xing2024dynamicrafter, |  |  |
| title={Dynamicrafter: Animating open-domain images with video diffusion priors}, |  |  |
| author={Xing, Jinbo and Xia, Menghan and Zhang, Yong and Chen, Haoxin and Yu, Wangbo and Liu, Hanyuan and Liu, Gongye and Wang, Xintao and Shan, Ying and Wong, Tien-Tsin}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={399--417}, |  |  |
| year={2024}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @article{xing2024tooncrafter, |  |  |
| title={Tooncrafter: Generative cartoon interpolation}, |  |  |
| author={Xing, Jinbo and Liu, Hanyuan and Xia, Menghan and Zhang, Yong and Wang, Xintao and Shan, Ying and Wong, Tien-Tsin}, |  |  |
| journal={ACM Transactions on Graphics (TOG)}, |  |  |
| volume={43}, |  |  |
| number={6}, |  |  |
| pages={1--11}, |  |  |
| year={2024}, |  |  |
| publisher={ACM New York, NY, USA} |  |  |
| } |  |  |
| @article{wang2024framer, |  |  |
| title={Framer: Interactive frame interpolation}, |  |  |
| author={Wang, Wen and Wang, Qiuyu and Zheng, Kecheng and Ouyang, Hao and Chen, Zhekai and Gong, Biao and Chen, Hao and Shen, Yujun and Shen, Chunhua}, |  |  |
| journal={arXiv preprint arXiv:2410.18978}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{meng2024anidoc, |  |  |
| title={Anidoc: Animation creation made easier}, |  |  |
| author={Meng, Yihao and Ouyang, Hao and Wang, Hanlin and Wang, Qiuyu and Wang, Wen and Cheng, Ka Leong and Liu, Zhiheng and Shen, Yujun and Qu, Huamin}, |  |  |
| journal={arXiv preprint arXiv:2412.14173}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{yang2025layeranimate, |  |  |
| author={Yang, Y. and Fan, L. and Lin, Z. and Wang, F. and Zhang, Z.}, |  |  |
| title={LayerAnimate: Layer-specific control for animation}, |  |  |
| journal={arXiv preprint arXiv:2501.08295}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @inproceedings{dai2024paintbucket, |  |  |
| title={Learning inclusion matching for animation paint bucket colorization}, |  |  |
| author={Dai, Yuekun and Zhou, Shangchen and Li, Qinyue and Li, Chongyi and Loy, Chen Change}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={25544--25553}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{xie2025physanimator, |  |  |
| title={PhysAnimator: Physics-Guided Generative Cartoon Animation}, |  |  |
| author={Xie, Tianyi and Zhao, Yiwei and Jiang, Ying and Jiang, Chenfanfu}, |  |  |
| journal={arXiv preprint arXiv:2501.16550}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @article{chavez2025time, |  |  |
| author={Chavez, Victor Fonte and Esteves, Claudia and Hayet, Jean-Bernard}, |  |  |
| title={Time-adaptive Video Frame Interpolation based on Residual Diffusion}, |  |  |
| journal={arXiv preprint arXiv:2504.05402}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @inproceedings{hur2025high, |  |  |
| title={High-Resolution Frame Interpolation with Patch-based Cascaded Diffusion}, |  |  |
| author={Hur, Junhwa and Herrmann, Charles and Saxena, Saurabh and Kontkanen, Janne and Lai, Wei-Sheng and Shih, Yichang and Rubinstein, Michael and Fleet, David J and Sun, Deqing}, |  |  |
| booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, |  |  |
| volume={39}, |  |  |
| number={4}, |  |  |
| pages={3868--3876}, |  |  |
| year={2025} |  |  |
| } |  |  |

### game?

| Title | Conference | Year |
|-------|------------|------|
| @article{yun2025anymole, |  |  |
| title={AnyMoLe: Any Character Motion In-betweening Leveraging Video Diffusion Models}, |  |  |
| author={Yun, Kwan and Hong, Seokhyeon and Kim, Chaelin and Noh, Junyong}, |  |  |
| journal={arXiv preprint arXiv:2503.08417}, |  |  |
| year={2025} |  |  |
| } |  |  |

### Joint: SR

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{shechtman2002stsr, |  |  |
| title={Increasing space-time resolution in video}, |  |  |
| author={Shechtman, Eli and Caspi, Yaron and Irani, Michal}, |  |  |
| booktitle={Computer Vision—ECCV 2002: 7th European Conference on Computer Vision Copenhagen, Denmark, May 28--31, 2002 Proceedings, Part I 7}, |  |  |
| pages={753--768}, |  |  |
| year={2002}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{kim2020fisr, |  |  |
| title={Fisr: Deep joint frame interpolation and super-resolution with a multi-scale temporal loss}, |  |  |
| author={Kim, Soo Ye and Oh, Jihyong and Kim, Munchurl}, |  |  |
| booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, |  |  |
| volume={34}, |  |  |
| number={07}, |  |  |
| pages={11278--11286}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{haris2020space, |  |  |
| title={Space-time-aware multi-resolution video enhancement}, |  |  |
| author={Haris, Muhammad and Shakhnarovich, Greg and Ukita, Norimichi}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={2859--2868}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{xu2021temporal, |  |  |
| title={Temporal modulation network for controllable space-time video super-resolution}, |  |  |
| author={Xu, Gang and Xu, Jun and Li, Zhen and Wang, Liang and Sun, Xing and Cheng, Ming-Ming}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={6388--6397}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @inproceedings{chen2023motif, |  |  |
| title={Motif: Learning motion trajectories with local implicit neural functions for continuous space-time video super-resolution}, |  |  |
| author={Chen, Yi-Hsin and Chen, Si-Cun and Lin, Yen-Yu and Peng, Wen-Hsiao}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={23131--23141}, |  |  |
| year={2023} |  |  |
| } |  |  |

### Joint: Deblur

| Title | Conference | Year |
|-------|------------|------|
| @article{zhang2020video, |  |  |
| title={Video frame interpolation without temporal priors}, |  |  |
| author={Zhang, Youjian and Wang, Chaoyue and Tao, Dacheng}, |  |  |
| journal={Advances in Neural Information Processing Systems}, |  |  |
| volume={33}, |  |  |
| pages={13308--13318}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @article{shen2020video, |  |  |
| title={Video frame interpolation and enhancement via pyramid recurrent framework}, |  |  |
| author={Shen, Wang and Bao, Wenbo and Zhai, Guangtao and Chen, Li and Min, Xiongkuo and Gao, Zhiyong}, |  |  |
| journal={IEEE Transactions on Image Processing}, |  |  |
| volume={30}, |  |  |
| pages={277--292}, |  |  |
| year={2020}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{shen2020blurry, |  |  |
| title={Blurry video frame interpolation}, |  |  |
| author={Shen, Wang and Bao, Wenbo and Zhai, Guangtao and Chen, Li and Min, Xiongkuo and Gao, Zhiyong}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={5114--5123}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{zhong2022animation, |  |  |
| title={Animation from blur: Multi-modal blur decomposition with motion guidance}, |  |  |
| author={Zhong, Zhihang and Sun, Xiao and Wu, Zhirong and Zheng, Yinqiang and Lin, Stephen and Sato, Imari}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={599--615}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{oh2022demfi, |  |  |
| title={Demfi: deep joint deblurring and multi-frame interpolation with flow-guided attentive correlation and recursive boosting}, |  |  |
| author={Oh, Jihyong and Kim, Munchurl}, |  |  |
| booktitle={European Conference on Computer Vision}, |  |  |
| pages={198--215}, |  |  |
| year={2022}, |  |  |
| organization={Springer} |  |  |
| } |  |  |
| @inproceedings{shang2023joint, |  |  |
| title={Joint video multi-frame interpolation and deblurring under unknown exposure time}, |  |  |
| author={Shang, Wei and Ren, Dongwei and Yang, Yi and Zhang, Hongzhi and Ma, Kede and Zuo, Wangmeng}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={13935--13944}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{yang2024latency, |  |  |
| title={Latency correction for event-guided deblurring and frame interpolation}, |  |  |
| author={Yang, Yixin and Liang, Jinxiu and Yu, Bohan and Chen, Yan and Ren, Jimmy S and Shi, Boxin}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={24977--24986}, |  |  |
| year={2024} |  |  |
| } |  |  |

### Loss Function

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{charbonnier1994two, |  |  |
| title={Two deterministic half-quadratic regularization algorithms for computed imaging}, |  |  |
| author={Charbonnier, Pierre and Blanc-Feraud, Laure and Aubert, Gilles and Barlaud, Michel}, |  |  |
| booktitle={Proceedings of 1st international conference on image processing}, |  |  |
| year={1994} |  |  |
| } |  |  |
| @article{mathieu2015deep, |  |  |
| title={Deep multi-scale video prediction beyond mean square error}, |  |  |
| author={Mathieu, Michael and Couprie, Camille and LeCun, Yann}, |  |  |
| journal={arXiv preprint arXiv:1511.05440}, |  |  |
| year={2015} |  |  |
| } |  |  |
| @inproceedings{ledig2017photo, |  |  |
| title={Photo-realistic single image super-resolution using a generative adversarial network}, |  |  |
| author={Ledig, Christian and Theis, Lucas and Husz{\'a}r, Ferenc and Caballero, Jose and Cunningham, Andrew and Acosta, Alejandro and Aitken, Andrew and Tejani, Alykhan and Totz, Johannes and Wang, Zehan and others}, |  |  |
| booktitle={CVPR}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @article{bojanowski2017optimizing, |  |  |
| title={Optimizing the latent space of generative networks}, |  |  |
| author={Bojanowski, Piotr and Joulin, Armand and Lopez-Paz, David and Szlam, Arthur}, |  |  |
| journal={arXiv preprint arXiv:1707.05776}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{zabih1994non, |  |  |
| author={Zabih, Ramin and Woodfill, John}, |  |  |
| title={Non-parametric local transforms for computing visual correspondence}, |  |  |
| booktitle={ECCV}, |  |  |
| year={1994} |  |  |
| } |  |  |
| @inproceedings{meister2018unflow, |  |  |
| title={Unflow: Unsupervised learning of optical flow with a bidirectional census loss}, |  |  |
| author={Meister, Simon and Hur, Junhwa and Roth, Stefan}, |  |  |
| booktitle={AAAI}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @inproceedings{zou2018df, |  |  |
| author={Zou, Yuliang and Luo, Zelun and Huang, Jia-Bin}, |  |  |
| title={Df-net: Unsupervised joint learning of depth and flow using cross-task consistency}, |  |  |
| booktitle={ECCV}, |  |  |
| year={2018} |  |  |
| } |  |  |

### Dataset

| Title | Conference | Year |
|-------|------------|------|
| @misc{montgomery1994xiph, |  |  |
| author={Montgomery, C.}, |  |  |
| title={Xiph.org video test media (derf's collection)}, |  |  |
| howpublished={Online, Available: https://media.xiph.org/video/derf/}, |  |  |
| year={1994} |  |  |
| } |  |  |
| @article{baker2011middlebury, |  |  |
| author={Baker, S. and Scharstein, D. and Lewis, J. P. and Roth, S. and Black, M. J. and Szeliski, R.}, |  |  |
| title={A database and evaluation methodology for optical flow}, |  |  |
| journal={Int. J. Comput. Vis.}, |  |  |
| year={2011} |  |  |
| } |  |  |
| @article{soomro2012ucf101, |  |  |
| author={Soomro, K. and Zamir, A. R. and Shah, M.}, |  |  |
| title={UCF101: A dataset of 101 human actions classes from videos in the wild}, |  |  |
| journal={arXiv preprint arXiv:1212.0402}, |  |  |
| year={2012} |  |  |
| } |  |  |
| @inproceedings{geiger2012kitti, |  |  |
| author={Geiger, A. and Lenz, P. and Urtasun, R.}, |  |  |
| title={Are we ready for autonomous driving? the kitti vision benchmark suite}, |  |  |
| booktitle={CVPR}, |  |  |
| year={2012} |  |  |
| } |  |  |
| @inproceedings{butler2012naturalistic, |  |  |
| author={Butler, Daniel J and Wulff, Jonas and Stanley, Garrett B and Black, Michael J}, |  |  |
| title={A naturalistic open source movie for optical flow evaluation}, |  |  |
| booktitle={ECCV}, |  |  |
| year={2012} |  |  |
| } |  |  |
| @inproceedings{perazzi2016benchmark, |  |  |
| author={Perazzi, F. and Pont-Tuset, J. and McWilliams, B. and Van Gool, L. and Gross, M. and Sorkine-Hornung, A.}, |  |  |
| title={A benchmark dataset and evaluation methodology for video object segmentation}, |  |  |
| booktitle={CVPR}, |  |  |
| year={2016} |  |  |
| } |  |  |
| @misc{gorban2015thumos, |  |  |
| author       = {A. Gorban and H. Idrees and Y.-G. Jiang and A. Roshan Zamir and I. Laptev and M. Shah and R. Sukthankar}, |  |  |
| title        = {THUMOS challenge: Action recognition with a large number of classes}, |  |  |
| year         = {2015}, |  |  |
| howpublished = {\url{http://www.thumos.info/}}, |  |  |
| note         = {Accessed: 2025-04-24} |  |  |
| } |  |  |
| @inproceedings{janai2017slow, |  |  |
| title={Slow flow: Exploiting high-speed cameras for accurate and diverse optical flow reference data}, |  |  |
| author={Janai, Joel and Guney, Fatma and Wulff, Jonas and Black, Michael J and Geiger, Andreas}, |  |  |
| booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={3597--3607}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{su2017adobe, |  |  |
| author={Su, S. and Delbracio, M. and Wang, J. and Sapiro, G. and Heidrich, W. and Wang, O.}, |  |  |
| title={Deep video deblurring for hand-held cameras}, |  |  |
| booktitle={CVPR}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{nah2017gopro, |  |  |
| author={Nah, Seungjun and Hyun Kim, Tae and Mu Lee, Kyoung}, |  |  |
| title={Deep multi-scale convolutional neural network for dynamic scene deblurring}, |  |  |
| booktitle={CVPR}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{bain2021frozen, |  |  |
| title={Frozen in time: A joint video and image encoder for end-to-end retrieval}, |  |  |
| author={Bain, Max and Nagrani, Arsha and Varol, G{\"u}l and Zisserman, Andrew}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={1728--1738}, |  |  |
| year={2021} |  |  |
| } |  |  |
| @article{stergiou2024lavib, |  |  |
| author={Stergiou, A.}, |  |  |
| title={Lavib: A large-scale video interpolation benchmark}, |  |  |
| journal={arXiv preprint arXiv:2406.09754}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @article{nan2024openvid, |  |  |
| author={Nan, K. and Xie, R. and Zhou, P. and Fan, T. and Yang, Z. and Chen, Z. and Li, X. and Yang, J. and Tai, Y.}, |  |  |
| title={Openvid-1M: A large-scale high-quality dataset for text-to-video generation}, |  |  |
| journal={arXiv preprint arXiv:2407.02371}, |  |  |
| year={2024} |  |  |
| } |  |  |

### Metric

| Title | Conference | Year |
|-------|------------|------|
| @article{wang2004image, |  |  |
| title={Image quality assessment: from error visibility to structural similarity}, |  |  |
| author={Wang, Zhou and Bovik, Alan C and Sheikh, Hamid R and Simoncelli, Eero P}, |  |  |
| journal={IEEE Trans. Image Process.}, |  |  |
| year={2004} |  |  |
| } |  |  |
| @article{yang2008new, |  |  |
| title={A new objective quality metric for frame interpolation used in video compression}, |  |  |
| author={Yang, Kai-Chieh and Huang, Ai-Mei and Nguyen, Truong Q and Guest, Clark C and Das, Pankaj K}, |  |  |
| journal={IEEE transactions on broadcasting}, |  |  |
| volume={54}, |  |  |
| number={3}, |  |  |
| pages={680--11}, |  |  |
| year={2008}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{mittal2012making, |  |  |
| title={Making a “completely blind” image quality analyzer}, |  |  |
| author={Mittal, Anish and Soundararajan, Rajiv and Bovik, Alan C}, |  |  |
| journal={IEEE Signal processing letters}, |  |  |
| volume={20}, |  |  |
| number={3}, |  |  |
| pages={209--212}, |  |  |
| year={2012}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{heusel2017gans, |  |  |
| author={Heusel, Martin and Ramsauer, Hubert and Unterthiner, Thomas and Nessler, Bernhard and Hochreiter, Sepp}, |  |  |
| title={Gans trained by a two time-scale update rule converge to a local nash equilibrium}, |  |  |
| journal={Advances in neural information processing systems}, |  |  |
| year={2017} |  |  |
| } |  |  |
| @inproceedings{zhang2018lpips, |  |  |
| author={Zhang, Richard and Isola, Phillip and Efros, Alexei A and Shechtman, Eli and Wang, Oliver}, |  |  |
| title={The unreasonable effectiveness of deep features as a perceptual metric}, |  |  |
| booktitle={CVPR}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @article{unterthiner2018fvd, |  |  |
| title={Towards accurate generative models of video: A new metric \& challenges}, |  |  |
| author={Unterthiner, Thomas and Van Steenkiste, Sjoerd and Kurach, Karol and Marinier, Raphael and Michalski, Marcin and Gelly, Sylvain}, |  |  |
| journal={arXiv preprint arXiv:1812.01717}, |  |  |
| year={2018} |  |  |
| } |  |  |
| @article{liu2024fr, |  |  |
| title={Fr$\backslash$'echet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos}, |  |  |
| author={Liu, Jiahe and Qu, Youran and Yan, Qi and Zeng, Xiaohui and Wang, Lele and Liao, Renjie}, |  |  |
| journal={arXiv preprint arXiv:2407.16124}, |  |  |
| year={2024} |  |  |
| } |  |  |
| @inproceedings{li2019quality, |  |  |
| title={Quality assessment of in-the-wild videos}, |  |  |
| author={Li, Dingquan and Jiang, Tingting and Jiang, Ming}, |  |  |
| booktitle={Proceedings of the 27th ACM international conference on multimedia}, |  |  |
| pages={2351--2359}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @article{ding2020image, |  |  |
| title={Image quality assessment: Unifying structure and texture similarity}, |  |  |
| author={Ding, Keyan and Ma, Kede and Wang, Shiqi and Simoncelli, Eero P}, |  |  |
| journal={IEEE transactions on pattern analysis and machine intelligence}, |  |  |
| volume={44}, |  |  |
| number={5}, |  |  |
| pages={2567--2581}, |  |  |
| year={2020}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @article{czolbe2020watson, |  |  |
| title={A loss function for generative neural networks based on watson’s perceptual model}, |  |  |
| author={Czolbe, Steffen and Krause, Oswin and Cox, Ingemar and Igel, Christian}, |  |  |
| journal={Advances in Neural Information Processing Systems}, |  |  |
| volume={33}, |  |  |
| pages={2051--2061}, |  |  |
| year={2020} |  |  |
| } |  |  |
| @inproceedings{radford2021learning, |  |  |
| title={Learning transferable visual models from natural language supervision}, |  |  |
| author={Radford, Alec and Kim, Jong Wook and Hallacy, Chris and Ramesh, Aditya and Goh, Gabriel and Agarwal, Sandhini and Sastry, Girish and Askell, Amanda and Mishkin, Pamela and Clark, Jack and others}, |  |  |
| booktitle={International conference on machine learning}, |  |  |
| pages={8748--8763}, |  |  |
| year={2021}, |  |  |
| organization={PmLR} |  |  |
| } |  |  |
| @article{saharia2022image, |  |  |
| title={Image super-resolution via iterative refinement}, |  |  |
| author={Saharia, Chitwan and Ho, Jonathan and Chan, William and Salimans, Tim and Fleet, David J and Norouzi, Mohammad}, |  |  |
| journal={IEEE transactions on pattern analysis and machine intelligence}, |  |  |
| volume={45}, |  |  |
| number={4}, |  |  |
| pages={4713--4726}, |  |  |
| year={2022}, |  |  |
| publisher={IEEE} |  |  |
| } |  |  |
| @inproceedings{danier2022flolpips, |  |  |
| author={Danier, Duolikun and Zhang, Fan and Bull, David}, |  |  |
| title={FloLPIPS: A bespoke video quality metric for frame interpolation}, |  |  |
| booktitle={2022 Picture Coding Symposium (PCS)}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{huang2024vbench, |  |  |
| author={Huang, Ziqi and He, Yinan and Yu, Jiashuo and Zhang, Fan and Si, Chenyang and Jiang, Yuming and Zhang, Yuanhan and Wu, Tianxing and Jin, Qingyang and Chanpaisit, Nattapol and others}, |  |  |
| title={Vbench: Comprehensive benchmark suite for video generative models}, |  |  |
| booktitle={CVPR}, |  |  |
| year={2024} |  |  |
| } |  |  |

### future research direction

| Title | Conference | Year |
|-------|------------|------|
| @article{yan2025semantic, |  |  |
| title={Semantic-Aware Adaptive Video Streaming Using Latent Diffusion Models for Wireless Networks}, |  |  |
| author={Yan, Zijiang and Pei, Jianhua and Wu, Hongda and Tabassum, Hina and Wang, Ping}, |  |  |
| journal={arXiv preprint arXiv:2502.05695}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @article{zhou2022cadm, |  |  |
| title={Cadm: Codec-aware diffusion modeling for neural-enhanced video streaming}, |  |  |
| author={Zhou, Qihua and Li, Ruibin and Guo, Song and Dong, Peiran and Liu, Yi and Guo, Jingcai and Xu, Zhenda}, |  |  |
| journal={arXiv preprint arXiv:2211.08428}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @inproceedings{castrejon2019improved, |  |  |
| title={Improved conditional vrnns for video prediction}, |  |  |
| author={Castrejon, Lluis and Ballas, Nicolas and Courville, Aaron}, |  |  |
| booktitle={Proceedings of the IEEE/CVF international conference on computer vision}, |  |  |
| pages={7608--7617}, |  |  |
| year={2019} |  |  |
| } |  |  |

### All-in-One:Image

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{li2022all, |  |  |
| title={All-in-one image restoration for unknown corruption}, |  |  |
| author={Li, Boyun and Liu, Xiao and Hu, Peng and Wu, Zhongqin and Lv, Jiancheng and Peng, Xi}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={17452--17462}, |  |  |
| year={2022} |  |  |
| } |  |  |
| @article{wu2025content, |  |  |
| title={Content-Aware Transformer for All-in-one Image Restoration}, |  |  |
| author={Wu, Gang and Jiang, Junjun and Jiang, Kui and Liu, Xianming}, |  |  |
| journal={arXiv preprint arXiv:2504.04869}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @inproceedings{ai2024multimodal, |  |  |
| title={Multimodal prompt perceiver: Empower adaptiveness generalizability and fidelity for all-in-one image restoration}, |  |  |
| author={Ai, Yuang and Huang, Huaibo and Zhou, Xiaoqiang and Wang, Jiexiang and He, Ran}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={25432--25444}, |  |  |
| year={2024} |  |  |
| } |  |  |

### All-in-One:Video

| Title | Conference | Year |
|-------|------------|------|
| @inproceedings{wang2019edvr, |  |  |
| title={Edvr: Video restoration with enhanced deformable convolutional networks}, |  |  |
| author={Wang, Xintao and Chan, Kelvin CK and Yu, Ke and Dong, Chao and Change Loy, Chen}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition workshops}, |  |  |
| pages={0--0}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @inproceedings{wang2019edvr, |  |  |
| title={Edvr: Video restoration with enhanced deformable convolutional networks}, |  |  |
| author={Wang, Xintao and Chan, Kelvin CK and Yu, Ke and Dong, Chao and Change Loy, Chen}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition workshops}, |  |  |
| pages={0--0}, |  |  |
| year={2019} |  |  |
| } |  |  |
| @article{zhao2024avernet, |  |  |
| title={AverNet: All-in-one video restoration for time-varying unknown degradations}, |  |  |
| author={Zhao, Haiyu and Tian, Lei and Xiao, Xinyan and Hu, Peng and Gou, Yuanbiao and Peng, Xi}, |  |  |
| journal={Advances in Neural Information Processing Systems}, |  |  |
| volume={37}, |  |  |
| pages={127296--127316}, |  |  |
| year={2024} |  |  |
| } |  |  |

### 4D

| Title | Conference | Year |
|-------|------------|------|
| @article{nag20252, |  |  |
| title={In-2-4D: Inbetweening from Two Single-View Images to 4D Generation}, |  |  |
| author={Nag, Sauradip and Cohen-Or, Daniel and Zhang, Hao and Mahdavi-Amiri, Ali}, |  |  |
| journal={arXiv preprint arXiv:2504.08366}, |  |  |
| year={2025} |  |  |
| } |  |  |
| @inproceedings{park2023temporal, |  |  |
| title={Temporal interpolation is all you need for dynamic neural radiance fields}, |  |  |
| author={Park, Sungheon and Son, Minjung and Jang, Seokhwan and Ahn, Young Chun and Kim, Ji-Yeon and Kang, Nahyup}, |  |  |
| booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition}, |  |  |
| pages={4212--4221}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{zheng2023neuralpci, |  |  |
| title={Neuralpci: Spatio-temporal neural field for 3d point cloud multi-frame non-linear interpolation}, |  |  |
| author={Zheng, Zehan and Wu, Danni and Lu, Ruisi and Lu, Fan and Chen, Guang and Jiang, Changjun}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={909--918}, |  |  |
| year={2023} |  |  |
| } |  |  |
| @inproceedings{peng2024papr, |  |  |
| title={PAPR in Motion: Seamless Point-level 3D Scene Interpolation}, |  |  |
| author={Peng, Shichong and Zhang, Yanshu and Li, Ke}, |  |  |
| booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition}, |  |  |
| pages={21007--21016}, |  |  |
| year={2024} |  |  |
| } |  |  |


---

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

