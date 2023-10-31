---
title: "Convolutional State Space Models for Long-Range Spatiotemporal Modeling"
collection: publications
permalink: /publication/2023-convssm
date: 2023-11-01
year: '2023'
venue: 'NeurIPS'
citation: 'Jimmy T.H. Smith, Shalini De Mello, Jan Kautz, Scott W. Linderman, <b>Wonmin Byeon</b> <b>|</b> <i>NeurIPS 2023</i> '
paperurl: 'https://arxiv.org/pdf/2310.19694.pdf'
---
[[arxiv]](https://arxiv.org/abs/2310.19694) &nbsp;
<!-- [[NeurIPS talk]](https://slideslive.com/38983702/scalingup-diverse-orthogonal-convolutional-networks-by-a-paraunitary-framework) -->

## Abstract
Effectively modeling long spatiotemporal sequences is challenging due to the need to model complex spatial correlations and long-range temporal dependencies simultaneously. ConvLSTMs attempt to address this by updating tensor-valued states with recurrent neural networks, but their sequential computation makes them slow to train. In contrast, Transformers can process an entire spatiotemporal sequence, compressed into tokens, in parallel. However, the cost of attention scales quadratically in length, limiting their scalability to longer sequences. Here, we address the challenges of prior methods and introduce convolutional state space models (ConvSSM) that combine the tensor modeling ideas of ConvLSTM with the long sequence modeling approaches of state space methods such as S4 and S5. First, we demonstrate how parallel scans can be applied to convolutional recurrences to achieve subquadratic parallelization and fast autoregressive generation. We then establish an equivalence between the dynamics of ConvSSMs and SSMs, which motivates parameterization and initialization strategies for modeling long-range dependencies. The result is ConvS5, an efficient ConvSSM variant for long-range spatiotemporal modeling. ConvS5 significantly outperforms Transformers and ConvLSTM on a long horizon Moving-MNIST experiment while training 3X faster than ConvLSTM and generating samples 400X faster than Transformers. In addition, ConvS5 matches or exceeds the performance of state-of-the-art methods on challenging DMLab, Minecraft and Habitat prediction benchmarks and enables new directions for modeling long spatiotemporal sequences. 


```bib
@misc{smith2023convolutional,
      title={Convolutional State Space Models for Long-Range Spatiotemporal Modeling}, 
      author={Jimmy T. H. Smith and Shalini De Mello and Jan Kautz and Scott W. Linderman and Wonmin Byeon},
      year={2023},
      eprint={2310.19694},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

