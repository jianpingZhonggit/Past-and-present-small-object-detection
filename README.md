# Past and present of small object detection
Small object detection has long been a difficult and hot topic in computer vision. In order to promote the development of this field, I establish this repository to organize **the papers related to small object detection**. Any latest papers related to small object detection will be updated in this repository.  <br>
Chinese version: https://zhuanlan.zhihu.com/p/426047353

## Updates
- 2021/11/2
  - create the repository

## Table of Contents
[1. Multi-scale feature learning](#1)<br>
[2. Super resolution](#2)<br>
[3. Context-based](#3)<br>
[4. Data-based](#4)<br>
[5. Training strategy](#5)<br>
[6. Special design in detection pipeline](#6)<br>
[7. Loss reweight](#7)<br>

<h3 id="1">1. Multi-scale feature learning </h3>

- **Effective fusion factor in fpn for tiny object detection**[[Paper](https://arxiv.org/abs/2011.02298)][[Code](https://github.com/ucas-vg/Effective-Fusion-Factor)]
  -  Yuqi Gong, Xuehui Yu, Yao Ding, Xiaoke Peng, Jian Zhao, Zhenjun Han, **WACV 2021**.
- **Augfpn: Improving multi-scale feature learning for object detection**[[Paper](https://arxiv.org/abs/1912.05384)][[Code](https://github.com/Gus-Guo/AugFPN)]
  -  Chaoxu Guo, Bin Fan, Qian Zhang, Shiming Xiang, and Chunhong Pan, **CVPR 2020**.
- **Path aggregation network for instance segmentation**[[Paper](https://arxiv.org/abs/1803.01534)][[Code](https://github.com/ShuLiu1993/PANet)]
  - Shu Liu, Lu Qi, Haifang Qin, Jianping Shi, Jiaya Jia, **YouTuLab Tencent**,  **CVPR 2018**.
- **Feature Pyramid Networks for Object Detection**[[Paper](https://arxiv.org/abs/1612.03144)]
  - Tsung-Yi Lin, Piotr Dollar, Ross Girshick, Kaiming He, Bharath Harihara, and Serge Belongie, **Facebook AI**, **CVPR 2017**.

<h3 id="2">2.  Super resolution </h3>

- **Better to Follow, Follow to Be Better: Towards Precise Supervision of Feature Super-Resolution for Small Object Detection**[[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Noh_Better_to_Follow_Follow_to_Be_Better_Towards_Precise_Supervision_ICCV_2019_paper.pdf)]
  - Junhyug Noh, Wonho Bae, Wonhee Lee, Jinhwan Seo, Gunhee Kim, **ICCV 2019**.
- **SOD-MTGAN: Small Object Detection via Multi-Task Generative Adversarial Network**[[Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yongqiang_Zhang_SOD-MTGAN_Small_Object_ECCV_2018_paper.pdf)]
  - Yancheng Bai, Yongqiang Zhang, Mingli Ding, and Bernard Ghanem, **ECCV 2018**.
- **Perceptual Generative Adversarial Networks for Small Object Detection**[[Paper](https://arxiv.org/abs/1706.05274)]
  - Jianan Li, Xiaodan Liang, Yunchao Wei, Tingfa Xu, Jiashi Feng, Shuicheng Yan, **CVPR 2017**.

<h3 id="3">3. Context-based </h3>

- **Relation Networks for Object Detection**[[Paper](https://arxiv.org/abs/1711.11575)][[Code](https://github.com/msracver/Relation-Networks-for-Object-Detection)]
  - Han Hu, Jiayuan Gu2, Zheng Zhang, Jifeng Dai, Yichen Wei, **Microsoft Research Asia**, **CVPR 2018**.
- **PyramidBox: A Context-assisted Single Shot Face Detector**[[Paper](https://arxiv.org/abs/1803.07737)][[Code]( https://github.com/PaddlePaddle/models/tree/develop/fluid/face_detection.)]
  - Xu Tang, Daniel K. Du, Zeqiang He, and Jingtuo Liu, **Baidu Inc**, **ECCV 2018**.
- **Inside-Outside Net: Detecting objects in context with skip pooling and recurrent neural networks**[[Paper](https://arxiv.org/abs/1512.04143)] 
  - Sean Bell, C. Lawrence Zitnick, Kavita Bala, Ross Girshick, **Microsoft Research**, **CVPR 2016**.

<h3 id="4">4. Data-based </h3>

- **Stitcher: Feedback-driven Data Provider for Object Detection**[[Paper](https://ui.adsabs.harvard.edu/abs/2020arXiv200412432C/abstract)][[Code](https://github.com/yukang2017/Stitcher)]
  - Yukang Chen, Peizhen Zhang, Zeming Li, Yanwei Li, Xiangyu Zhang, Gaofeng Meng, Shiming Xiang, Jian Sun, Jiaya Jia, **Megvii Technology**, **CVPR 2020**.
- **Augmentation for small object detection.**[[Paper](https://arxiv.org/abs/1902.07296)][[Code](https://github.com/gmayday1997/SmallObjectAugmentation)]
  - Mate Kisantal, Zbigniew Wojna, Jakub Murawski, Jacek Naruniec, Kyunghyun Cho, **CVPR 2019**.

<h3 id="5">5. Training strategy </h3>

- **SNIPER: Efficient Multi-Scale Training**[[Paper](https://arxiv.org/abs/1805.09300)][[Code](https://github.com/mahyarnajibi/SNIPER/)]
  - Bharat Singh, Mahyar Najibi, Larry S. Davis, **NIPS 2018**.
- **An Analysis of Scale Invariance in Object Detection – SNIP**[[Paper](https://arxiv.org/abs/1711.08189)]
  - Bharat Singh, Larry S. Davis, **CVPR 2018**.

<h3 id="6">6. Special design in detection pipeline </h3>

- **S3FD: Single Shot Scale-invariant Face Detector**[[Paper](https://arxiv.org/abs/1708.05237)][[Code](https://github.com/sfzhang15/SFD)]
  - Shifeng Zhang, Xiangyu Zhu, Zhen Lei∗, Hailin Shi, Xiaobo Wang, Stan Z. Li, **ICCV 2017**.
- **FaceBoxes: A CPU Real-time Face Detector with High Accuracy**[[Paper](https://arxiv.org/abs/1708.05234)][[Code](https://github.com/sfzhang15/FaceBoxes)]
  - Shifeng Zhang, Xiangyu Zhu, Zhen Lei, Hailin Shi, Xiaobo Wang, Stan Z. Li, **IJCB 2017**.

<h3 id="7">7. Loss reweight </h3>

- **Feedback-driven loss function for small object detection**[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0262885621001025)]
  - Gen Liu, Jin Han, Wenzhong Rong, **Image Vison Computing 2021**.