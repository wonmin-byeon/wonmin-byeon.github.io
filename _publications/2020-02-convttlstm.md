---
title: "Convolutional Tensor-Train LSTM for Spatio-temporal Learning"
collection: publications
permalink: /publication/2020-02-convttlstm
date: 2020-02-21
venue: 'arXiv'
citation: 'J Su*, <b>W Byeon*</b>, F Huang, J Kautz, A Anandkumar  <b> (*) equal contributions </b> <b>|</b> <i>arXiv 2020</i> '
paperurl: 'https://arxiv.org/abs/2002.09131'
---
[[paper]](https://arxiv.org/abs/2002.09131) &nbsp;[[code]](https://github.com/NVlabs/conv-tt-lstm)

Abstract
==
Higher-order Recurrent Neural Networks (RNNs) are effective for long-term forecasting since such architectures can model higher-order correlations and long-term dynamics more effectively. However, higher-order models are expensive and require exponentially more parameters and operations compared with their first-order counterparts. This problem is particularly pronounced in multidimensional data such as videos. To address this issue, we propose Convolutional Tensor-Train Decomposition (CTTD), a novel tensor decomposition with convolutional operations. With CTTD, we construct Convolutional Tensor-Train LSTM (Conv-TT-LSTM) to capture higher-order space-time correlations in videos. We demonstrate that the proposed model outperforms the conventional (first-order) Convolutional LSTM (ConvLSTM) as well as the state-of-the-art ConvLSTM-based approaches in pixel-level video prediction tasks on Moving-MNIST and KTH action datasets, but with much fewer parameters.

Prediction Results
==
Moving-MNIST
![](http://wonmin-byeon.github.io/files/result-convttlstm20/mnist.gif)
%![](http://wonmin-byeon.github.io/files/result-convttlstm20/kth.gif)

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