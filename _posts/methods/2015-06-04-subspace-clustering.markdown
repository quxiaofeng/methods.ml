---
layout: post
title: "Subspace Clustering - 用稀疏子空间聚类做运动分割"
date: 2015-06-04 19:26:49
author: QU Xiaofeng
categories:
- methods
- vision
img: pisa.jpg
thumb: rssc.jpg
---

用子空间聚类算法来做运动分割，其中稀疏表示和低秩表示聚类比较多。

State-of-art 方法：

**SSC (Sparse Subspace Clustering)**

+ E. Elhamifar, R. Vidal, "[Sparse Subspace Clustering: Algorithm, Theory, and Applications](http://www.computer.org/csdl/trans/tp/2013/11/ttp2013112765-abs.html)," IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 35, no. 11, pp. 2765-2781, Nov., 2013 [[paper  (arXiv)]](http://arxiv.org/abs/1203.1005) [[代码]](http://vision.jhu.edu/code/)
+ [Vidal, R.][vidal], "[Subspace Clustering](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5714408&tag=1)," Signal Processing Magazine, IEEE , vol.28, no.2, pp.52,68, March 2011 [代码](http://vision.jhu.edu/code/)

**LRR (Low-Rank Representation)**

+ [Guangcan Liu][liu]; [Zhouchen Lin][lin]; Shuicheng Yan; Ju Sun; Yong Yu; Yi Ma, "[Robust Recovery of Subspace Structures by Low-Rank Representation](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6180173&isnumber=6353858)," Pattern Analysis and Machine Intelligence, IEEE Transactions on , vol.35, no.1, pp.171,184, Jan. 2013 [论文  (arXiv)](http://arxiv.org/abs/1010.2955) [代码 (google site)](https://sites.google.com/site/guangcanliu/) [论文 by Zhouchen Lin](http://www.cis.pku.edu.cn/faculty/vision/zlin/Publications/2013-TPAMI-LRR.pdf) [代码 by Zhouchen Lin]("http://www.cis.pku.edu.cn/faculty/vision/zlin/lrr(motion_face).zip") [论文 (ICML2000)](http://www.icml2010.org/papers/521.pdf)
+ Bin Cheng; [Guangcan Liu][liu]; [Jingdong Wang][wang]; Zhongyang Huang; Shuicheng Yan, "[Multi-task low-rank affinity pursuit for image segmentation](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6126528&isnumber=6126217)," Computer Vision (ICCV), 2011 IEEE International Conference on , vol., no., pp.2439,2446, 6-13 Nov. 2011 [[论文 (Microsoft)]](http://research.microsoft.com/en-us/um/people/jingdw/pubs/iccv11-segmentation.pdf)

> 刚性的 motion segmentation 基本上用 subspace clustering 解决，效果就挺好了。因为同一个刚性目标基本上可以看成是采样在同一个子空间中。如果是非刚性的话可能效果就不是特别好。

**RSSC (Reweighted Sparse Subspace Clustering)**

+ [Jun Xu][xu], Kui Xu, Ke Chen, Jishou Ruan, [Reweighted sparse subspace clustering](http://www.sciencedirect.com/science/article/pii/S1077314215000879), Computer Vision and Image Understanding, Available online 21 April 2015, ISSN 1077-3142 [[论文 (github)]](http://csjunxu.github.io/blog/paper/RSSC.pdf) [[代码 (github)]](http://csjunxu.github.io/blog/code/RSSC.zip) [[数据集 (github)]](http://csjunxu.github.io/blog/datasets/FBMS137.zip)

> 非刚性的 motion segmentation

[liu]:https://sites.google.com/site/guangcanliu/
[lin]:http://www.cis.pku.edu.cn/faculty/vision/zlin/zlin.htm
[vidal]:http://cis.jhu.edu/~rvidal/
[xu]:http://csjunxu.github.io/blog/
[wang]:http://research.microsoft.com/en-us/um/people/jingdw/