---
title: "Coupled Segmentation and Edge Learning via Dynamic Graph Propagation"
collection: publications
permalink: /publication/2021-coupledseg
date: 2021-12-07
year: '2021'
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
citation: 'Zhiding Yu, Rui Huang, <b>Wonmin Byeon</b>, Sifei Liu, Guilin Liu, Thomas Breuel, Anima Anandkumar, Jan Kautz <b>|</b> <i>NeurIPS 2021</i> '
paperurl: 'https://openreview.net/forum?id=vRwnHlAgK5x'
---
[[paper]](https://openreview.net/forum?id=vRwnHlAgK5x)

## Abstract
Image segmentation and edge detection are both central problems in perceptual grouping. It is therefore interesting to study how these two tasks can be coupled to benefit each other. Indeed, segmentation can be easily transformed into contour edges to guide edge learning. However, the converse is nontrivial since general edges may not always form closed contours. In this paper, we propose a principled end-to-end framework for coupled edge and segmentation learning, where edges are leveraged as pairwise similarity cues to guide segmentation. At the core of our framework is a recurrent module termed as dynamic graph propagation (DGP) layer that performs message passing on dynamically constructed graphs. The layer uses learned gating to dynamically select neighbors for message passing using max-pooling. The output from message passing is further gated with an edge signal to refine segmentation. Experiments demonstrate that the proposed framework is able to let both tasks mutually improve each other. On Cityscapes validation, our best model achieves 83.7% mIoU in semantic segmentation and 78.7% maximum F-score in semantic edge detection. Our method also leads to improved zero-shot robustness on Cityscapes with natural corruptions (Cityscapes-C).


```bib
@inproceedings{
yu2021coupled,
title={Coupled Segmentation and Edge Learning via Dynamic Graph Propagation},
author={Zhiding Yu and Rui Huang and Wonmin Byeon and Sifei Liu and Guilin Liu and Thomas Breuel and Anima Anandkumar and Jan Kautz},
booktitle={Thirty-Fifth Conference on Neural Information Processing Systems},
year={2021},
url={https://openreview.net/forum?id=vRwnHlAgK5x}
}
```

