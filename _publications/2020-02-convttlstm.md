---
title: "Convolutional Tensor-Train LSTM for Spatio-temporal Learning"
collection: publications
permalink: /publication/2020-02-convttlstm
date: 2020-02-21
venue: 'arXiv'
citation: 'J Su*, <b>W Byeon*</b>, F Huang, J Kautz, A Anandkumar  <b> (*) equal contributions </b> <b>|</b> <i>arXiv 2020</i> '
paperurl: 'https://arxiv.org/abs/2002.09131'
---
[[paper]](https://arxiv.org/abs/2002.09131) &nbsp;[[code]](https://github.com/NVlabs/conv-tt-lstm) &nbsp;[[project page]](https://sites.google.com/nvidia.com/conv-tt-lstm) 

## Abstract
Learning from spatio-temporal data has numerous applications such as human-behavior analysis, object tracking, video compression, and physics simulation.However, existing methods still perform poorly on challenging video tasks suchas long-term forecasting. This is because these kinds of challenging tasks requirelearning long-term spatio-temporal correlations in the video sequence. In this paper, we propose a higher-order convolutional LSTM model that can efficientlylearn these correlations, along with a succinct representations of the history. This is accomplished through a novel tensor train module that performs prediction bycombining convolutional features across time. To make this feasible in terms ofcomputation and memory requirements, we propose a novel convolutional tensor-train decomposition of the higher-order model. This decomposition reduces themodel complexity by jointly approximating a sequence of convolutional kernels asa low-rank tensor-train factorization. As a result, our model outperforms existingapproaches, but uses only a fraction of parameters, including the baseline models.Our results achieve state-of-the-art performance in a wide range of applicationsand datasets, including the multi-steps video prediction on the Moving-MNIST-2and KTH action datasets as well as early activity recognition on the Something-Something V2 dataset.

## Prediction Results
![](http://wonmin-byeon.github.io/files/result-convttlstm20/mnist.gif)

## Prediction Results
![](http://wonmin-byeon.github.io/files/result-convttlstm20/early_activity_recognition_video1.gif)
![](http://wonmin-byeon.github.io/files/result-convttlstm20/early_activity_recognition_video2.gif)
<!-- KTH
--
![](http://wonmin-byeon.github.io/files/result-convttlstm20/kth.gif) -->

```
@misc{su2020convolutional,
    title={Convolutional Tensor-Train LSTM for Spatio-temporal Learning},
    author={Jiahao Su and Wonmin Byeon and Furong Huang and Jan Kautz and Animashree Anandkumar},
    year={2020},
    eprint={2002.09131},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}
```