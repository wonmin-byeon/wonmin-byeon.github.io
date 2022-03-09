---
title: "GroupViT: Semantic Segmentation Emerges from Text Supervision"
collection: publications
permalink: /publication/2022-groupvit
date: 2022-02-22
year: '2022'
venue: 'CVPR'
citation: 'Jiarui Xu, Shalini De Mello, Sifei Liu, <b>Wonmin Byeon</b>, Thomas Breuel, Jan Kautz, Xiaolong Wang <b>|</b> <i>CVPR 2022</i> '
paperurl: 'https://arxiv.org/pdf/2202.11094.pdf'
---
[[arxiv]](https://arxiv.org/abs/2202.11094) &nbsp;
[[video]](https://youtu.be/DtJsWIUTW-Y) &nbsp;
[[project page]](https://jerryxu.net/GroupViT/) 

## Abstract
Grouping and recognition are important components of visual scene understanding, e.g., for object detection and semantic segmentation. With end-to-end deep learning systems, grouping of image regions usually happens implicitly via top-down supervision from pixel-level recognition labels. Instead, in this paper, we propose to bring back the grouping mechanism into deep networks, which allows semantic segments to emerge automatically with only text supervision. We propose a hierarchical Grouping Vision Transformer (GroupViT), which goes beyond the regular grid structure representation and learns to group image regions into progressively larger arbitrary-shaped segments. We train GroupViT jointly with a text encoder on a large-scale image-text dataset via contrastive losses. With only text supervision and without any pixel-level annotations, GroupViT learns to group together semantic regions and successfully transfers to the task of semantic segmentation in a zero-shot manner, i.e., without any further fine-tuning. It achieves a zero-shot accuracy of 51.2% mIoU on the PASCAL VOC 2012 and 22.3% mIoU on PASCAL Context datasets, and performs competitively to state-of-the-art transfer-learning methods requiring greater levels of supervision. Project page is available at [[this https URL](https://jerryxu.net/GroupViT). 


```bib
@article{xu2022groupvit,
  title={GroupViT: Semantic Segmentation Emerges from Text Supervision},
  author={Xu, Jiarui and De Mello, Shalini and Liu, Sifei and Byeon, Wonmin and Breuel, Thomas and Kautz, Jan and Wang, Xiaolong},
  journal={arXiv preprint arXiv:2202.11094},
  year={2022}
}
```

