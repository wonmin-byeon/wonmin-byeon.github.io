---
title: "Physics Informed RNN-DCT Networks for Time-Dependent Partial Differential Equations"
collection: publications
permalink: /publication/2021-rnndct
date: 2021-12-13
year: '2021'
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
citation: 'Benjamin Wu* · Oliver Hennigh · Jan Kautz · Sanjay Choudhry · <b>Wonmin Byeon*</b> <b> (*) equal contributions </b> <b>|</b> <i>Workshop: ML and the Physical Science at NeurIPS 2021</i> '
paperurl: 'https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_121.pdf'
---
[[arxiv]](https://arxiv.org/abs/2202.12358) &nbsp;
[[paper]](https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_121.pdf) &nbsp;
[[poster]](https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_121_poster.png) &nbsp;
[[workshop page]](https://ml4physicalsciences.github.io/2021/)


## Abstract
 Physics-informed neural networks allow models to be trained by physical laws described by general nonlinear partial differential equations. However, traditional architectures struggle to solve more challenging time-dependent problems due to their architectural nature. In this work, we present a novel physics-informed framework for solving time-dependent partial differential equations. Using only the governing differential equations and problem initial and boundary conditions, we generate a latent representation of the problem's spatio-temporal dynamics. Our model utilizes discrete cosine transforms to encode spatial frequencies and recurrent neural networks to process the time evolution. This efficiently and flexibly produces a compressed representation which is used for additional conditioning of physics-informed models. We show experimental results on the Taylor-Green vortex solution to the Navier-Stokes equations. Our proposed model achieves state-of-the-art performance on the Taylor-Green vortex relative to other physics-informed baseline models.


```bib
@misc{wu2022physics,
      title={Physics Informed RNN-DCT Networks for Time-Dependent Partial Differential Equations}, 
      author={Benjamin Wu and Oliver Hennigh and Jan Kautz and Sanjay Choudhry and Wonmin Byeon},
      year={2022},
      eprint={2202.12358},
      archivePrefix={arXiv},
      primaryClass={physics.comp-ph}
}
```
