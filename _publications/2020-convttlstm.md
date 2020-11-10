---
title: "Convolutional Tensor-Train LSTM for Spatio-temporal Learning"
collection: publications
permalink: /publication/2020-02-convttlstm
date: 2020-02-21
year: '2020'
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
citation: 'J Su*, <b>W Byeon*</b>, F Huang, J Kautz, A Anandkumar  <b> (*) equal contributions </b> <b>|</b> <i>NeurIPS 2020</i> '
paperurl: 'https://proceedings.neurips.cc/paper/2020/file/9e1a36515d6704d7eb7a30d783400e5d-Paper.pdf'
---
[[paper]](https://proceedings.neurips.cc/paper/2020/file/9e1a36515d6704d7eb7a30d783400e5d-Paper.pdf) &nbsp;[[Supp]](https://proceedings.neurips.cc/paper/2020/file/9e1a36515d6704d7eb7a30d783400e5d-Supplemental.pdf) &nbsp;[[code]](https://github.com/NVlabs/conv-tt-lstm) &nbsp;[[project page]](https://sites.google.com/nvidia.com/conv-tt-lstm) 

* ECCV 2020 Tutorial on Accelerating Computer Vision with Mixed Precision, August 2020. [[program]](https://nvlabs.github.io/eccv2020-mixed-precision-tutorial/) [[slides]](https://nvlabs.github.io/eccv2020-mixed-precision-tutorial/files/wonmin_byeon-mixed-precision-training-for-convolutional-tensor-train-lstm.pdf) [[video]](https://www.youtube.com/watch?v=1XuD-ozHTLY&feature=youtu.be)

## Abstract
Learning from spatio-temporal data has numerous applications such as human-behavior analysis, object tracking, video compression, and physics simulation.However, existing methods still perform poorly on challenging video tasks suchas long-term forecasting. This is because these kinds of challenging tasks requirelearning long-term spatio-temporal correlations in the video sequence. In this paper, we propose a higher-order convolutional LSTM model that can efficientlylearn these correlations, along with a succinct representations of the history. This is accomplished through a novel tensor train module that performs prediction bycombining convolutional features across time. To make this feasible in terms ofcomputation and memory requirements, we propose a novel convolutional tensor-train decomposition of the higher-order model. This decomposition reduces themodel complexity by jointly approximating a sequence of convolutional kernels asa low-rank tensor-train factorization. As a result, our model outperforms existingapproaches, but uses only a fraction of parameters, including the baseline models.Our results achieve state-of-the-art performance in a wide range of applicationsand datasets, including the multi-steps video prediction on the Moving-MNIST-2and KTH action datasets as well as early activity recognition on the Something-Something V2 dataset.

## Video Prediction Results
![](http://wonmin-byeon.github.io/files/result-convttlstm20/mnist.gif)

## Early Activity Recognition Results
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
