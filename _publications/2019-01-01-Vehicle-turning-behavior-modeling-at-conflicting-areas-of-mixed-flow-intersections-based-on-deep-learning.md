---
title: "Vehicle turning behavior modeling at conflicting areas of mixed-flow intersections based on deep learning"
collection: publications
category: manuscripts
permalink: /publication/2019-01-01-Vehicle-turning-behavior-modeling-at-conflicting-areas-of-mixed-flow-intersections-based-on-deep-learning
excerpt: ''
date: 2019-01-01
venue: 'IEEE transactions on intelligent transportation systems'
---

Performing a left turn in a non-protected phase at mixed-flow intersections is one of the most challenging driving maneuvers. In general, there are three typical behavioral features during this turning process: multiple conflicting objects, multi-layer interaction between vehicles, non-motorized vehicles, and pedestrians, and long-term interaction event chains. In current studies, few models consider the impact of these three typical features simultaneously. This paper proposes a Conv-LSTM model to predict the positions of turning vehicles at each moment during the turning process in these complicated environments. The model uses convolution, which is an essential part of a convolutional neural network (CNN), to extract higher-level features across different time segments. Afterward, a long short-term memory (LSTM) network is employed to obtain the feature sequence with long-term dependence on the features of historical periods. Finally, the initial prediction of the Conv-LSTM is modified by the non-holonomic constraints of vehicles. Left-turning trajectories extracted from a simulation environment are used for model training and testing. As a result, the Conv-LSTM model performs better compared with the CNN and LSTM models. The average offset of every point on the trajectories is reduced by 50.4% and 37.1%, respectively, relative to the CNN and LSTM, and the interactive behaviors during the left-turn process are well reproduced by the proposed model. Another round of testing shows that the generalization ability of proposed model to real environments was initially proved to be feasible with the extracted ground-truth trajectories in the field environment.

Citation: ' Jian Sun,  Xiao Qi,  Yiming Xu,  Ye Tian, &quot;Vehicle turning behavior modeling at conflicting areas of mixed-flow intersections based on deep learning.&quot; IEEE transactions on intelligent transportation systems, 2019.'

Use [Google Scholar](https://scholar.google.com/scholar?q=Vehicle+turning+behavior+modeling+at+conflicting+areas+of+mixed+flow+intersections+based+on+deep+learning){:target="_blank"} for full citation