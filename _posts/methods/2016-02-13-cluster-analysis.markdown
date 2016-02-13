---
layout: post
title: "Cluster Analysis 聚类分析"
date: 2016-02-13 20:09:17
author: QU Xiaofeng
categories:
- methods
- clustering
img:
thumb:
---

度量学习是学习一个距离表达函数。

### 经典方法和代码

基于 Python 的度量学习包 `metric-learn`: [Metric Learning in Python][metric-learn]。该包包含优化过的 LMNN，ITML，SDML，LSML，NCA，LFDA 和 RCA 代码。
可以直接通过 `pip install metric-learn` 下载，`python setup.py install` 安装，`python setup.py test` 测试。代码在 [github][metric-learn-repo].

### Survey

[Liu Yang][liu-yang] [06 年的 Survey][06-survey] 和 [07 年的 Overview][07-overview]。以及相应的[工具箱][distlearn]。

[metric-learn]: http://all-umass.github.io/metric-learn/index.html
[metric-learn-repo]: https://github.com/all-umass/metric-learn
[liu-yang]: http://www.cs.cmu.edu/~liuy/
[06-survey]: http://www.cs.cmu.edu/~liuy/frame_survey_v2.pdf
[07-overview]: http://www.cs.cmu.edu/~liuy/dist_overview.pdf
[distlearn]: http://www.cs.cmu.edu/~liuy/distlearn.htm