---
title: "Weakly-Supervised Physically Unconstrained Gaze Estimation"
collection: publications
permalink: /publication/2021-gaze-cvpr21
date: 2021-05-20
year: '2021'
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR)'
citation: 'Rakshit Kothari, Shalini De Mello, Umar Iqbal, <b>Wonmin Byeon</b>, Seonwook Park, Jan Kautz <b>|</b> <i>CVPR 2021 (oral)</i> '
paperurl: 'https://arxiv.org/pdf/2105.09803.pdf'
---
[[paper]](https://arxiv.org/pdf/2105.09803.pdf) &nbsp;[[code]](https://github.com/NVlabs/weakly-supervised-gaze)

## Abstract
A major challenge for physically unconstrained gaze estimation is acquiring training data with 3D gaze annotations for in-the-wild and outdoor scenarios. In contrast, videos of human interactions in unconstrained environments are abundantly available and can be much more easily annotated with frame-level activity labels. In this work, we tackle the previously unexplored problem of weakly-supervised gaze estimation from videos of human interactions. We leverage the insight that strong gaze-related geometric constraints exist when people perform the activity of "looking at each other" (LAEO). To acquire viable 3D gaze supervision from LAEO labels, we propose a training algorithm along with several novel loss functions especially designed for the task. With weak supervision from two large scale CMU-Panoptic and AVA-LAEO activity datasets, we show significant improvements in (a) the accuracy of semi-supervised gaze estimation and (b) cross-domain generalization on the state-of-the-art physically unconstrained in-the-wild Gaze360 gaze estimation benchmark. We open source our code at [this https URL](https://github.com/NVlabs/weakly-supervised-gaze). 


```bib
@misc{kothari2021weaklysupervised,
      title={Weakly-Supervised Physically Unconstrained Gaze Estimation}, 
      author={Rakshit Kothari and Shalini De Mello and Umar Iqbal and Wonmin Byeon and Seonwook Park and Jan Kautz},
      year={2021},
      eprint={2105.09803},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

