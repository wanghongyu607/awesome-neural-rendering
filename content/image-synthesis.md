# Image Synthesis

## Table of Contents
- [Diving Deep into Image Synthesis](#diving-deep-into-image-synthesis)
- [Restoration or Enhancement with Unpair or Misaligned Data](#restoration-or-enhancement-with-unpair-or-misaligned-data)
- [Restoration or Enhancement](#restoration-or-enhancement)
- [Video Prediction and Future Prediction](#video-prediction-and-future-prediction)
- [Frame Interpolation and Videos Generation](#frame-interpolation-and-videos-generation)
- [Free-Hand Sketch](#free-hand-sketch)
- [Long-Tailed](#long-tailed)
- [Soft Segmentation and Background Matting](#soft-segmentation-and-background-matting)
- [DeepFake and Forensic](#deepfake-and-forensic)

## Diving Deep into Image Synthesis

**GANSpace: Discovering Interpretable GAN Controls.**<br>
*Erik Härkönen, Aaron Hertzmann, Jaakko Lehtinen, Sylvain Paris.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.02546)] [[Github](https://github.com/harskish/ganspace)]

**Image Processing Using Multi-Code GAN Prior.**<br>
*Jinjin Gu, Yujun Shen, Bolei Zhou.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.07116)] [[Project](https://genforce.github.io/mganprior/)] [[Github](https://github.com/genforce/mganprior)]

**Interpreting the Latent Space of GANs for Semantic Face Editing.**<br>
*[Yujun Shen](http://shenyujun.github.io/), [Jinjin Gu](http://www.jasongt.com/), [Xiaoou Tang](http://www.ie.cuhk.edu.hk/people/xotang.shtml), [Bolei Zhou](http://bzhou.ie.cuhk.edu.hk/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1907.10786)] [[Project](https://genforce.github.io/interfacegan/)] [[Github](https://github.com/genforce/interfacegan)]

**In-Domain GAN Inversion for Real Image Editing.**<br>
*Jiapeng Zhu, Yujun Shen, Deli Zhao, Bolei Zhou.*<br>
arrive2020. [[PDF](https://arxiv.org/abs/2004.00049)] [[Project](https://genforce.github.io/idinvert/)] [[Github](https://github.com/genforce/idinvert)]

**ConSinGAN: Improved Techniques for Training Single-Image GANs.**<br>
*Tobias Hinz, Matthew Fisher, Oliver Wang, Stefan Wermter.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.11512)]  [[Github](https://github.com/tohinz/ConSinGAN)]

**MSG-GAN: Multi-Scale Gradient GAN for Stable Image Synthesis.**<br>
*Animesh Karnewar, Oliver Wang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1903.06048)] [[Github](https://github.com/akanimax/msg-stylegan-tf)]

**ClearGrasp: 3D Shape Estimation of Transparent Objects for Manipulation.**<br>
*Shreeyak S. Sajjan, Matthew Moore, Mike Pan, Ganesh Nagaraja, Johnny Lee, Andy Zeng, Shuran Song.*<br>
[[PDF](https://arxiv.org/abs/1910.02550)] [[Github](https://github.com/Shreeyak/cleargrasp)] [[Project](https://sites.google.com/view/cleargrasp)]

**StyleGAN2 Distillation for Feed-forward Image Manipulation.**<br>
*Yuri Viazovetskyi, Vladimir Ivashkin, Evgeny Kashin.*<br>
arxiv, 7 Mar 2020. [[PDF](https://arxiv.org/abs/2003.03581)] [[Github](https://github.com/EvgenyKashin/stylegan2-distillation)]

**LAG: Creating High Resolution Images with a Latent Adversarial Generator.**<br>
*David Berthelot, Peyman Milanfar, Ian Goodfellow.*<br>
arxiv, 4 Mar 2020. [[PDF](https://arxiv.org/abs/2003.02365)] [[Github](https://github.com/google-research/lag)]

**StyleGAN2: Analyzing and Improving the Image Quality of StyleGAN.**<br>
*[Tero Karras](https://research.nvidia.com/person/tero-karras), [Samuli Laine](https://research.nvidia.com/person/samuli-laine), [Miika Aittala](https://research.nvidia.com/person/miika-aittala), Janne Hellsten, Jaakko Lehtinen, [Timo Aila](https://research.nvidia.com/person/timo-aila).*<br>
arxiv, 3 Dec 2019.
[[PDF](https://arxiv.org/abs/1912.04958)] 
[[Offical TF](https://github.com/NVlabs/stylegan2)]
[[PyTorch](https://github.com/rosinality/stylegan2-pytorch)]
[[Unoffical Tensorflow 2.0](https://github.com/manicman1999/StyleGAN2-Tensorflow-2.0)]

**A Style-Based Generator Architecture for Generative Adversarial Networks.**<br>
*Tero Karras, Samuli Laine, Timo Aila.*<br>
CVPR 2019. 
[[Paper](https://arxiv.org/abs/1812.04948)]
[[Video](https://youtu.be/kSLJriaOumA)]
[[Code](https://github.com/NVlabs/stylegan)]
[[FFHQ](https://github.com/NVlabs/ffhq-dataset)]

**Bayesian Reasoning with Deep-Learned Knowledge.**<br>
*Jakob Knollmüller, Torsten Enßlin.*<br>
arxiv, 29 Jan 2020. [[PDF](https://arxiv.org/abs/2001.11031v1)]

**Unsupervised Discovery of Interpretable Directions in the GAN Latent Space.**<br>
*Andrey Voynov, Artem Babenko.*<br>
arxiv, 10 Feb 2020. [[PDF](https://arxiv.org/abs/2002.03754)] [[Github](https://github.com/anvoynov/GANLatentDiscovery)]

**Overcoming the Disentanglement vs Reconstruction Trade-off via Jacobian Supervision.**<br>
*[José Lezama](https://iie.fing.edu.uy/~jlezama/).*<br>
ICLR 2019. [[PDF](https://openreview.net/pdf?id=Hkg4W2AcFm)] [[Github](https://github.com/jlezama/disentangling-jacobian)]

**SinGAN: Learning a Generative Model from a Single Natural Image.**<br>
*Tamar Rott Shaham, Tali Dekel, Tomer Michaeli.*<br>
ICCV 2019 (Best Paper). 
[[PDF](https://arxiv.org/abs/1905.01164)] [[UnOfficial](github.com/FriedRonaldo/SinGAN)] [[Official](github.com/tamarott/SinGAN)]

**InGAN: Capturing and Retargeting the DNA of a Natural Image.**<br>
ICCV 2019. [[PDF](http://www.wisdom.weizmann.ac.il/~vision/ingan/resources/ingan.pdf)] [[Project](http://www.wisdom.weizmann.ac.il/~vision/ingan/)] [[Github](https://github.com/assafshocher/InGAN)] 

**Image2StyleGAN: How to Embed Images Into the StyleGAN Latent Space?**<br>
*Rameen Abdal, Yipeng Qin, Peter Wonka.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1904.03189)]

**Image2StyleGAN++: How to Edit the Embedded Images?**<br>
*Rameen Abdal, Yipeng Qin, Peter Wonka.*<br>
arxiv, 26 Nov 2019. [[PDF](https://arxiv.org/abs/1911.11544)]

**Improving sample diversity of a pre-trained, class-conditional GAN by changing its class embeddings.**<br>
*Qi Li, Long Mai, Anh Nguyen.*<br>
arxiv, 10 Oct 2019. [[PDF](https://arxiv.org/abs/1910.04760)]

**Style Generator Inversion for Image Enhancement and Animation.**<br>
*[Aviv Gabbay](https://www.cse.huji.ac.il/~avivga/), [Yedid Hoshen](https://www.cse.huji.ac.il/~ydidh/).*<br>
arxiv, 5 Jun 2019. [[PDF](https://arxiv.org/abs/1906.11880)] [[Project](http://www.vision.huji.ac.il/style-image-prior)] [[Github](https://github.com/avivga/style-image-prior)]

**SEAN: Image Synthesis with Semantic Region-Adaptive Normalization.**<br>
*eihao Zhu, Rameen Abdal, Yipeng Qin, Peter Wonka.*<br>
arxiv, 28 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12861)]

**Unsupervised K-modal Styled Content Generation.**<br>
*Omry Sendik, Dani Lischinski, Daniel Cohen-Or.*<br>
arxiv, 10 Jan 2020. [[PDF](https://arxiv.org/pdf/2001.03640.pdf)]

**Deep Video-Based Performance Cloning.**<br>
*Kfir Aberman, Mingyi Shi, Jing Liao, Dani Lischinski, Daniel Cohen-Or, Chen Baoquan.*<br>
Eurographics 2019. [[PDF](https://arxiv.org/pdf/1808.06847.pdf)]

## Restoration or Enhancement with Unpair or Misaligned Data

**Unsupervised Real-world Image Super Resolution via Domain-distance Aware Training.**<br>
*Yunxuan Wei, [Shuhang Gu](https://shuhanggu.github.io/), Yawei Li, Longcun Jin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/pdf/2004.01178)] [[Github](https://github.com/ShuhangGu/DASR)]

**Robust Image Reconstruction with Misaligned Structural Information.**<br>
*Leon Bungert, Matthias J. Ehrhardt.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.00589)]

**Exploiting Deep Generative Prior for Versatile Image Restoration and Manipulation.**<br>
*Xingang Pan, Xiaohang Zhan, Bo Dai, Dahua Lin, Chen Change Loy, Ping Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.13659)] [[Github](https://github.com/XingangPan/deepgenerative-prior)]

**Closed-loop Matters: Dual Regression Networks for Single Image Super-Resolution.**<br>
*Yong Guo, Jian Chen, Jingdong Wang, Qi Chen, Jiezhang Cao, Zeshuai Deng, Yanwu Xu, Mingkui Tan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.07018)]

**Learning Invariant Representation for Unsupervised Image Restoration.**<br>
*Wenchao Du, Hu Chen, Hongyu Yang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12769)]

**Meta-Transfer Learning for Zero-Shot Super-Resolution.**<br>
*Jae Woong Soh, Sunwoo Cho, Nam Ik Cho.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.12213)]

**EnlightenGAN: Deep Light Enhancement without Paired Supervision.**<br>
*Yifan Jiang, Xinyu Gong, Ding Liu, Yu Cheng, Chen Fang, Xiaohui Shen, Jianchao Yang, Pan Zhou, Zhangyang Wang.*<br>
[[PDF](https://arxiv.org/abs/1906.06972)] [[Github](https://github.com/TAMU-VITA/EnlightenGAN)] [[Dataset](https://github.com/TAMU-VITA/EnlightenGAN/issues/28)] [[KinD](https://arxiv.org/abs/1905.04161)]

**Unpaired Image Enhancement Featuring Reinforcement-Learning-Controlled Image Editing Software.**<br>
*Satoshi Kosugi, Toshihiko Yamasaki.* <br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1912.07833)]

**Single Image Reflection Removal Exploiting Misaligned Training Data and Network Enhancements.**<br>
*Kaixuan Wei, Jiaolong Yang, Ying Fu, David Wipf, Hua Huang.* <br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.00637)] [[Project](https://github.com/Vandermode/ERRNet)]

**Unpaired Image Enhancement Featuring Reinforcement-Learning-Controlled Image Editing Software.**<br>
*Kosugi, Toshihiko Yamasaki.*<br>
ArXiV, 17 Dec 2019 [[PDF](https://arxiv.org/pdf/1912.07833.pdfSatoshi)]

**Deep Photo Enhancer: Unpaired Learning for Image Enhancement from Photographs with GANs.**<br>
*Yu-Sheng Chen, Yu-Ching Wang, Man-Hsin Kao, Yung-Yu Chuang.*<br>
CVPR 2018. [[PDF](https://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/CVPR-2018-DPE.pdf)] [[Supplementary Material](https://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/CVPR-2018-DPE-sm-compress.pdf)] [[Demo](http://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/)] [[Github](https://github.com/nothinglo/Deep-Photo-Enhancer)]  [[MIT-Adobe FiveK Dataset](https://data.csail.mit.edu/graphics/fivek/)] [[DSLR Photo Enhancement Dataset](http://people.ee.ethz.ch/~ihnatova/#demo)]

**PPN2V: Fully Unsupervised Probabilistic Noise2Void.**<br>
*Mangal Prakash, Manan Lalit, Pavel Tomancak, Alexander Krull, Florian Jug.*<br>
arxiv, 27 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12291)] [[GitHub](https://github.com/juglab/ppn2v)] [[MPI-CBG: Max-Planck Institute of Molecular Cell Biology and Genetics](https://www.mpi-cbg.de/home/)]

**PN2V:Probabilistic Noise2Void: Unsupervised Content-Aware Denoising.**<br>
*Alexander Krull, Tomas Vicar, Florian Jug.*<br>
arxiv, 3 Jun 2019. [[PDF](https://arxiv.org/abs/1906.00651)] [[Github](https://github.com/juglab/pn2v)]

## Restoration or Enhancement

**Deblurring using Analysis-Synthesis Networks Pair.**<br>
*Adam Kaufman, Raanan Fattal.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02956)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), [Xingang Pan](https://xingangpan.github.io/), Bo Dai, Ziwei Liu, Dahua Lin, Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Github](https://github.com/XiaohangZhan/deocclusion/)]

**CDVD-TSP: Cascaded Deep Video Deblurring Using Temporal Sharpness Prior.**<br>
*Jinshan Pan, Haoran Bai, Jinhui Tang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02501)] [[Github](https://github.com/csbhr/CDVD-TSP)]

**Deep White-Balance Editing.**<br>
*[Mahmoud Afifi](https://sites.google.com/view/mafifi), [Michael S. Brown](http://www.cse.yorku.ca/~mbrown/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01354)]

**What Else Can Fool Deep Learning? Addressing Color Constancy Errors on Deep Neural Network Performance.**<br>
*[Mahmoud Afifi](http://www.cse.yorku.ca/~mafifi/), Michael S. Brown.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Afifi_What_Else_Can_Fool_Deep_Learning_Addressing_Color_Constancy_Errors_ICCV_2019_paper.pdf)] [[Project](http://cvil.eecs.yorku.ca/projects/public_html/wb_emulation/index.html)] [[Github](https://github.com/mahmoudnafifi/WB_color_augmenter)]

**When Color Constancy Goes Wrong: Correcting Improperly White-Balanced Images.**<br>
*Mahmoud Afifi, Brian Price, Scott Cohen, and Michael S. Brown.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Afifi_When_Color_Constancy_Goes_Wrong_Correcting_Improperly_White-Balanced_Images_CVPR_2019_paper.pdf)] [[Github](https://github.com/mahmoudnafifi/WB_sRGB)] 

**Rethinking Data Augmentation for Image Super-resolution: A Comprehensive Analysis and a New Strategy.**<br>
*Jaejun Yoo, Namhyuk Ahn, Kyung-Ah Sohn.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00448)] [[Github](https://github.com/clovaai/cutblur)]

**Single-Image HDR Reconstruction by Learning to Reverse the Camera Pipeline.**<br>
*[Yu-Lun Liu](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/), Wei-Sheng Lai, Yu-Sheng Chen, Yi-Lung Kao, Ming-Hsuan Yang, Yung-Yu Chuang, Jia-Bin Huang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01179)] [[Github](https://github.com/alex04072000/SingleHDR)] [[Project](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/SingleHDR)]

**Learning to See Through Obstructions.**<br>
*Yu-Lun Liu, Wei-Sheng Lai, Ming-Hsuan Yang, Yung-Yu Chuang.*<br>
CVPR 2020. [[PDF](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/ObstructionRemoval_/02197.pdf)] [[Github](https://github.com/alex04072000/ObstructionRemoval)] [[Project](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/ObstructionRemoval)]

**DeepLPF: Deep Local Parametric Filters for Image Enhancement.**<br>
*Sean Moran, Pierre Marza, Steven McDonagh, Sarah Parisot, Gregory Slabaugh.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13985)]

**Replacing Mobile Camera ISP with a Single Deep Learning Model.**<br>
*Andrey Ignatov, Luc Van Gool, Radu Timofte.* <br>
arxiv, 13 Feb 2020. [[PDF](https://arxiv.org/abs/2002.05509)] [[Github](https://github.com/aiff22/PyNET)] [[Project](http://people.ee.ethz.ch/~ihnatova/pynet.html)]

**EEMEFN: Low-Light Image Enhancement via Edge-Enhanced Multi-Exposure Fusion Network.**<br>
*Minfeng Zhu, Pingbo Pan, Wei Chen, Yi Yang.*<br>
AAAI 2020. [[PDF](http://www.cad.zju.edu.cn/home/vagblog/VAG_Work/EEMEFN-Low%20Light%20Image%20Enhancement%20via%20Edge%20Enhanced%20MultiExposure%20Fusion%20Network.pdf)] [[Project](https://zjuvag.org/publications/eemefn/)]

## Video Prediction and Future Prediction

**Transformation-based Adversarial Video Prediction on Large-Scale Data.**<br>
*Pauline Luc, Aidan Clark, Sander Dieleman, Diego de Las Casas, Yotam Doron, Albin Cassirer, Karen Simonyan.*<br>
arxiv, 9 Mar 2020. [[PDF](https://arxiv.org/abs/2003.04035)]

**The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction.**<br>
*Junwei Liang, Lu Jiang, Kevin Murphy, Ting Yu, Alexander Hauptmann.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.06445)] [[Project](https://next.cs.cmu.edu/multiverse/index.html)] [[The Forking Paths Dataset](https://next.cs.cmu.edu/multiverse/index.html)]

**Learning to Generate Time-Lapse Videos Using Multi-Stage Dynamic Generative Adversarial Networks.**<br>
*[Wei Xiong](https://wxiong.me/), Wenhan Luo, Lin Ma, Wei Liu, Jiebo Luo.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1709.07592)] [[Github](https://github.com/weixiong-ur/mdgan)] [[Dataset](https://drive.google.com/open?id=1xWLiU-MBGN7MrsFHQm4_yXmfHBsMbJQo)] [[Project](https://sites.google.com/site/whluoimperial/mdgan)]

**Visual Dynamics: Stochastic Future Generation via Layered Cross Convolutional Networks.**<br>
*[Tianfan Xue](http://people.csail.mit.edu/tfxue/research_statement_tianfan.pdf), Jiajun Wu, Katherine L. Bouman, William T. Freeman.*<br>
TPAMI 2019 / NeurIPS 2016. [[PDF](https://arxiv.org/abs/1807.09245)] [[Project](visualdynamics.csail.mit.edu)] [[Github](https://github.com/tfxue/visual-dynamics)]

**Eidetic 3D LSTM: A Model for Video Prediction and Beyond.**<br>
*Yunbo Wang, Lu Jiang, Ming-Hsuan Yang, Li-Jia Li, Mingsheng Long, Li Fei-Fei.*<br>
ICLR 2019. [[PDF](https://openreview.net/forum?id=B1lKS2AqtX)] [[GitHub](https://github.com/google/e3d_lstm)]

**STGAT: Modeling Spatial-Temporal Interactions for Human Trajectory Prediction.**<br>
*Yingfan Huang, HuiKun Bi, Zhaoxin Li, Tianlu Mao, Zhaoqi Wang.*<br> 
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_STGAT_Modeling_Spatial-Temporal_Interactions_for_Human_Trajectory_Prediction_ICCV_2019_paper.pdf)]
[[GitHub](https://github.com/huang-xx/STGAT)] [[Social GAN](https://github.com/agrimgupta92/sgan)]

## Frame Interpolation and Videos Generation

**AdaCoF: Adaptive Collaboration of Flows for Video Frame Interpolation.**<br>
*[Hyeongmin Lee](https://hyeongminlee.github.io/), [Taeoh Kim](https://taeoh-kim.github.io/), Tae-young Chung, Daehyun Pak, Yuseok Ban, and Sangyoun Lee.*<br>
CVPR 2020.
[[PDF](https://arxiv.org/abs/1907.10244)] [[Video](https://www.youtube.com/watch?v=Z3q0YrBsNJc)] [[Github](https://github.com/HyeongminLEE/AdaCoF-pytorch)]

**Blurry Video Frame Interpolation.**<br>
*Wang Shen, Wenbo Bao, Guangtao Zhai, Li Chen, Xiongkuo Min, Zhiyong Gao.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.12259)]

**Zooming Slow-Mo: Fast and Accurate One-Stage Space-Time Video Super-Resolution.**<br>
*Xiaoyu Xiang, Yapeng Tian, Yulun Zhang, Yun Fu, Jan P. Allebach, Chenliang Xu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.11616)]

**DAIN: Depth-Aware Video Frame Interpolation.**<br>
*Wenbo Bao, Wei-Sheng Lai, Chao Ma, Xiaoyun Zhang, Zhiyong Gao, Ming-Hsuan Yang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.00830)]
[[Github](https://github.com/baowenbo/DAIN)]
[[Software](https://drive.google.com/file/d/1uuDkF4j4H1AI1ot88XdqzwMdvAPhxKN8/view)]

**Super SloMo: High Quality Estimation of Multiple Intermediate Frames for Video Interpolation.**<br>
*[Huaizu Jiang](http://jianghz.me/), [Deqing Sun](http://research.nvidia.com/person/deqing-sun), Varun Jampani, Ming-Hsuan Yang, Erik Learned-Miller, Jan Kautz.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1712.00080)] [[Project](https://people.cs.umass.edu/~hzjiang/projects/superslomo/)] [[Github](https://github.com/avinashpaliwal/Super-SloMo)]


## Soft Segmentation and Background Matting

**Background Matting: The World is Your Green Screen.**<br>
*[Soumyadip Sengupta](https://homes.cs.washington.edu/~soumya91/), [Vivek Jayaram](http://www.vivekjayaram.com/research), Brian Curless, Steve Seitz, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00626)] [[Github](https://github.com/senguptaumd/Background-Matting)] [[Project](https://grail.cs.washington.edu/projects/background-matting/)]

**Semantic Soft Segmentation.**<br>
*[Yagiz Aksoy](http://yaksoy.github.io/), Tae-Hyun Oh, Sylvain Paris, Marc Pollefeys and Wojciech Matusik.*<br>
ACM Transactions on Graphics (Proc. SIGGRAPH), 2018. [[PDF](http://cfg.mit.edu/sites/cfg.mit.edu/files/sss_3.pdf)] [[Project](http://yaksoy.github.io/sss/)] [[Github-Matlab](https://github.com/yaksoy/SemanticSoftSegmentation)] [[Github-Python](https://github.com/iyah4888/SIGGRAPH18SSS)]

## Free-Hand Sketch

**Synthesizing human-like sketches from natural images using a conditional convolutional decoder.**<br> 
*Moritz Kampelmühler, Axel Pinz.*<br> 
WACV 2020. [[PDF](https://arxiv.org/abs/2003.07101)] [[Github](https://github.com/kampelmuehler/synthesizing_human_like_sketches)]

**Image Generation from Freehand Scene Sketches.**<br> 
*Chengying Gao, Qi Liu, Qi Xu, Jianzhuang Liu, Limin Wang, Changqing Zou.*<br> 
arxiv，5 Mar 2020. [[PDF](https://arxiv.org/abs/2003.02683)]

**Sketch-to-Art: Synthesizing Stylized Art Images From Sketches.**<br> 
*Bingchen Liu, Kunpeng Song, Ahmed Elgammal.*<br> 
arxiv, 26 Feb 2020. [[PDF](https://arxiv.org/abs/2002.12888)]

**Deep Plastic Surgery: Robust and Controllable Image Editing with Human-Drawn Sketches.**<br>
*Shuai Yang, Zhangyang Wang, Jiaying Liu, Zongming Guo.*<br>
arxiv, 9 Jan 2020.
[[PDF](https://arxiv.org/abs/2001.02890)]

**Deep Learning for Free-Hand Sketch: A Survey.**<br>
*Peng Xu.*<br>
arxiv, 8 Jan 2020. [[PDF](https://arxiv.org/abs/2001.02600)]

**Interactive Sketch & Fill: Multiclass Sketch-to-Image Translation.**<br>
*[Arnab Ghosh](https://arnabgho.github.io/), [Richard Zhang](https://richzhang.github.io/), [Puneet K. Dokania](https://puneetkdokania.github.io/), [Oliver Wang](http://www.oliverwang.info/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Philip H.S. Torr](http://www.robots.ox.ac.uk/~tvg/index.php), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1909.11081v2)] [[Github](https://arnabgho.github.io/iSketchNFill/)]

**Examining Performance of Sketch-to-Image Translation Models with Multiclass Automatically Generated Paired Training Data.**<br>
*Dichao Hu.*<br>
arxiv, 2018. [[PDF](https://arxiv.org/abs/1811.00249)]

**Multi-Graph Transformer for Free-Hand Sketch Recognition.**<br>
*[Peng Xu](http://www.pengxu.net/), [Chaitanya K. Joshi](https://chaitjo.github.io/), [Xavier Bresson](https://www.ntu.edu.sg/home/xbresson/).*<br>
arxiv, 2019. [[PDF](https://arxiv.org/abs/1912.11258)] [[Github](https://github.com/PengBoXiangShang/multigraph_transformer)]

## Long-Tailed 

**Long-Tailed Recognition Using Class-Balanced Experts.**<br>
*Saurabh Sharma, Ning Yu, Mario Fritz, Bernt Schiele.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.03706)]

**BBN: Bilateral-Branch Network with Cumulative Learning for Long-Tailed Visual Recognition.**<br>
*Boyan Zhou, Quan Cui, Xiu-Shen Wei, Zhao-Min Chen.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.02413)] [[Github](https://github.com/Megvii-Nanjing/BBN)]

**Rethinking Class-Balanced Methods for Long-Tailed Visual Recognition from a Domain Adaptation Perspective.**<br>
*Muhammad Abdullah Jamal, Matthew Brown, Ming-Hsuan Yang, Liqiang Wang, Boqing Gong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.10780)]

**Domain Balancing: Face Recognition on Long-Tailed Domains.**<br>
*Dong Cao, Xiangyu Zhu, Xingyu Huang, Jianzhu Guo, Zhen Lei.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13791)]

**M2m: Imbalanced Classification via Major-to-minor Translation.**<br>
*Jaehyung Kim, Jongheon Jeong, Jinwoo Shin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00431)]

**OLTR: Large-Scale Long-Tailed Recognition in an Open World.**<br>
*[Ziwei Liu](https://liuziwei7.github.io/), [Zhongqi Miao](https://github.com/zhmiao), [Xiaohang Zhan](https://xiaohangzhan.github.io/), [Jiayun Wang](http://pwang.pw/), [Boqing Gong](http://boqinggong.info/), [Stella X. Yu](https://www1.icsi.berkeley.edu/~stellayu/).*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.05160)] [[Github](https://github.com/zhmiao/OpenLongTailRecognition-OLTR)] [[Project](https://liuziwei7.github.io/projects/LongTail.html)]

**Long-tail learning with attributes.**<br>
*Dvir Samuel, Yuval Atzmon, Gal Chechik.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.02235)]

**Learning to Segment the Tail.**<br>
*Xinting Hu, Yi Jiang, Kaihua Tang, Jingyuan Chen, Chunyan Miao, Hanwang Zhang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.00900)] [[Github](https://github.com/JoyHuYY1412/LST_LVIS)]

## DeepFake and Forensic

[[FaceForensics Benchmark](http://kaldir.vc.in.tum.de/faceforensics_benchmark/)]
[[awesome-deepfakes-materials](https://github.com/datamllab/awesome-deepfakes-materials)]

**Deep Spatial Gradient and Temporal Depth Learning for Face Anti-spoofing.**<br>
*Zezheng Wang, Zitong Yu, Chenxu Zhao, Xiangyu Zhu, Yunxiao Qin, Qiusheng Zhou, Feng Zhou, Zhen Lei.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.08061)]

**Evading Deepfake-Image Detectors with White- and Black-Box Attacks.**<br>
*Nicholas Carlini, Hany Farid.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.00622)]

**One-Shot GAN Generated Fake Face Detection.**<br>
*Hadi Mansourifar, Weidong Shi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.12244)]

**Global Texture Enhancement for Fake Face Detection in the Wild.**<br>
*Zhengzhe Liu, Xiaojuan Qi, Philip H.S. Torr.*<br>
CVPR 2020. [[PDF](https://xjqi.github.io/real_fake.pdf)]

**Leveraging Frequency Analysis for Deep Fake Image Recognition.**<br>
*Joel Frank, Thorsten Eisenhofer, Lea Schönherr, Asja Fischer, Dorothea Kolossa, Thorsten Holz.*<br>
arxiv, 19 Mar 2020. [[PDF](https://arxiv.org/abs/2003.08685)] [[Github](https://github.com/RUB-SysSec/GANDCTAnalysis)]

**Disrupting DeepFakes: Adversarial Attacks Against Conditional Image Translation Networks and Facial Manipulation Systems.**<br>
*[Nataniel Ruiz](https://natanielruiz.github.io/), [Sarah Adel Bargal](https://cs-people.bu.edu/sbargal/), [Stan Sclaroff](http://www.cs.bu.edu/~sclaroff/).*<br>
arxiv, 3 Mar 2020. [[PDF](https://arxiv.org/abs/2003.01279)] [[Github](https://github.com/natanielruiz/disrupting-deepfakes)]

**Adversarial Deepfakes: Evaluating Vulnerability of Deepfake Detectors to Adversarial Examples.**<br>
*Paarth Neekhara, Shehzeen Hussain, Malhar Jere, Farinaz Koushanfar, Julian McAuley.*<br>
arxiv,  9 Feb 2020. [[PDF](https://arxiv.org/abs/2002.12749)]

**Real or Not Real, that is the Question.**<br>
*Yuanbo Xiangli, Yubin Deng, Bo Dai, Chen Change Loy, Dahua Lin.*<br>
ICLR 2020. [[PDF](https://openreview.net/forum?id=B1lPaCNtPB)] [[Github](https://github.com/kam1107/RealnessGAN)] 

**Fawkes: Protecting Personal Privacy against Unauthorized Deep Learning Models.**<br>
*Shawn Shan, Emily Wenger, Jiayun Zhang, Huiying Li, Haitao Zheng, Ben Y. Zhao.*<br>
arxiv, 19 Feb 2020. [[PDF](https://arxiv.org/abs/2002.08327)]

**FakeLocator: Robust Localization of GAN-Based Face Manipulations via Semantic Segmentation Networks with Bells and Whistles.**<br>
*Yihao Huang, Felix Juefei-Xu, Run Wang, Xiaofei Xie, Lei Ma, Jianwen Li, Weikai Miao, Yang Liu, Geguang Pu.*<br>
arxiv, 27 Jan 2020. [[PDF](https://arxiv.org/abs/2001.09598)]

**DeeperForensics-1.0: A Large-Scale Dataset for Real-World Face Forgery Detection.**<br>
*[Liming Jiang](https://liming-jiang.com/), [Wayne Wu](https://wywu.github.io/), [Ren Li](https://liren2515.github.io/page/), [Chen Qian](https://scholar.google.com/citations?user=AerkT0YAAAAJ&hl=en), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/).*<br>
arxiv, 9 Jan 2020.
[[PDF](https://arxiv.org/abs/2001.03024)] 
[[Project](https://liming-jiang.com/projects/DrF1/DrF1.html)]
[[DeeperForensics-1.0 Dataset](https://github.com/EndlessSora/DeeperForensics-1.0)]
[[PDF](https://github.com/EndlessSora/DeeperForensics-1.0)]

**FaceForensics++: Learning to Detect Manipulated Facial Images.**<br>
*[Andreas Rössler](http://www.niessnerlab.org/members/andreas_roessler/profile.html), Davide Cozzolino, Luisa Verdoliva, Christian Riess, Justus Thies, [Matthias Nießner](http://www.niessnerlab.org/members/matthias_niessner/profile.html).*<br>
[[PDF](https://arxiv.org/abs/1901.08971)] [[Github](https://github.com/ondyari/FaceForensics)] [[Homepage & Dataset](http://www.niessnerlab.org/projects/roessler2018faceforensics.html)] [[Face Forensics  Image Recognition Suite](http://faceforensics.com/)]

**Face X-ray for More General Face Forgery Detection.**<br>
*Lingzhi Li, Jianmin Bao, Ting Zhang, Hao Yang, Dong Chen, Fang Wen, Baining Guo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.13458)]

**FaceShifter: Towards High Fidelity And Occlusion Aware Face Swapping.**<br>
*Lingzhi Li, Jianmin Bao, Hao Yang, Dong Chen, Fang Wen.*<br>
arxiv, 1 Dec 2019. [[PDF](https://arxiv.org/abs/1912.13457)]

**DeepFakes and Beyond: A Survey of Face Manipulation and Fake Detection.**<br>
*Ruben Tolosana, Ruben Vera-Rodriguez, Julian Fierrez, Aythami Morales, Javier Ortega-Garcia.*<br>
arxiv, 1 Jan 2020. [[PDF](https://arxiv.org/abs/2001.00179)]

**Scalable Fine-grained Generated Image Classification Based on Deep Metric Learning.**<br>
*Xinsheng Xuan, Bo Peng, Wei Wang, Jing Dong.*<br>
arxiv, 10 Dec 2019. [[PDF](https://arxiv.org/abs/1912.11082)]

**Attributing Fake Images to GANs: Learning and Analyzing GAN Fingerprints.**<br>
*Ning Yu, Larry Davis, [Mario Fritz](https://cispa.saarland/people/mario.fritz/).*<br>
ICCV 2019.
[[PDF](https://arxiv.org/abs/1811.08180)] [[Github](https://github.com/ningyu1991/GANFingerprints)] [[Group of Mario Fritz at CISPA](https://cispa.saarland/group/fritz/)] [[Media Coverage](https://mp.weixin.qq.com/s/se1ZyR_gfzliWB5X72OZ1Q)]

**CNNDetection: CNN-Generated Images Are Surprisingly Easy to Spot...For Now.**<br>
*[Sheng-Yu Wang](https://peterwang512.github.io), [Oliver Wang](http://www.oliverwang.info/), [Richard Zhang](http://richzhang.github.io/), [Andrew Owens](http://andrewowens.com/), [Alexei A. Efros](http://www.eecs.berkeley.edu/~efros/).*<br>
arxiv, 2019.
[[PDF](https://arxiv.org/abs/1906.05856)]  [[Code](https://github.com/peterwang512/FALdetector)]  [[Project](https://peterwang512.github.io/FALdetector)] 

**Detecting Photoshopped Faces by Scripting Photoshop.**<br>
*Sheng-Yu Wang, Oliver Wang, Andrew Owens, Richard Zhang, Alexei A. Efros.*<br>
ICCV, 2019.
[[PDF](https://arxiv.org/abs/1912.11035)]  [[Code](https://github.com/peterwang512/CNNDetection)]  [[Project](https://peterwang512.github.io/CNNDetection/)] [[Adobe Max](https://youtu.be/21lj8tCSMkg)]

**Fighting Fake News: Image Splice Detection via Learned Self-Consistency.**<br>
*Minyoung Huh, Andrew Liu, Andrew Owens, Alexei A. Efros.*<br>
ECCV 2018. [[Github](https://github.com/minyoungg/selfconsistency)] [[Project](https://minyoungg.github.io/selfconsistency/)]