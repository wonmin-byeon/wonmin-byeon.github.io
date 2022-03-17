---
title: "Displacement-Invariant Cost Computation for Efficient Stereo Matching"
collection: publications
permalink: /publication/2022-efficient-stereo-matching
date: 2022-03-16
year: '2022'
venue: 'IJCV'
citation: '    Yiran Zhong, Charles Loop, <b>Wonmin Byeon</b>, Stan Birchfield, Yuchao Dai, Kaihao Zhang, Alexey Kamenev, Thomas Breuel, Hongdong Li, Jan Kautz  <b>|</b> <i>IJCV 2022</i> '
paperurl: 'https://trebuchet.public.springernature.app/get_content/2067b03b-27d9-4f29-a55e-75f3fb3b6c28'
---
[[paper]](https://trebuchet.public.springernature.app/get_content/2067b03b-27d9-4f29-a55e-75f3fb3b6c28) &nbsp;
[[arxiv]](https://arxiv.org/abs/2012.00899) &nbsp;

## Abstract
Although deep learning-based methods have dominated stereo matching leaderboards by yielding unprecedented disparity
accuracy, their inference time is typically slow, i.e., less than 4 FPS for a pair of 540p images. The main reason is that the
leading methods employ time-consuming 3D convolutions applied to a 4D feature volume. A common way to speed up the
computation is to downsample the feature volume, but this loses high-frequency details. To overcome these challenges, we
propose a displacement-invariant cost computation module to compute the matching costs without needing a 4D feature
volume. Rather, costs are computed by applying the same 2D convolution network on each disparity-shifted feature map
pair independently. Unlike previous 2D convolution-based methods that simply perform context mapping between inputs and
disparity maps, our proposed approach learns to match features between the two images. We also propose an entropy-based
refinement strategy to refine the computed disparity map, which further improves the speed by avoiding the need to compute
a second disparity map on the right image. Extensive experiments on standard datasets (SceneFlow, KITTI, ETH3D, and
Middlebury) demonstrate that our method achieves competitive accuracy with much less inference time. On typical image
sizes (e.g., 540 × 960), our method processes over 100 FPS on a desktop GPU, making our method suitable for time-critical
applications such as autonomous driving. We also show that our approach generalizes well to unseen datasets, outperforming
4D-volumetric methods. We will release the source code to ensure the reproducibility.


```bib
@misc{zhong2020displacementinvariant,
      title={Displacement-Invariant Cost Computation for Efficient Stereo Matching}, 
      author={Yiran Zhong and Charles Loop and Wonmin Byeon and Stan Birchfield and Yuchao Dai and Kaihao Zhang and Alexey Kamenev and Thomas Breuel and Hongdong Li and Jan Kautz},
      year={2020},
      eprint={2012.00899},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

