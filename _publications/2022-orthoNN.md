---
title: "Scaling-up Diverse Orthogonal Convolutional Networks with a Paraunitary Framework"
collection: publications
permalink: /publication/2022-orthoNN
date: 2022-07-01
year: '2022'
venue: 'ICML'
citation: 'Jiahao Su, <b>Wonmin Byeon</b>, Furong Huang <b>|</b> <i>ICML 2022</i> '
paperurl: 'https://arxiv.org/pdf/2106.09121.pdf'
---
[[arxiv]](https://arxiv.org/abs/2106.09121) &nbsp;
[[ICML talk]](https://slideslive.com/38983702/scalingup-diverse-orthogonal-convolutional-networks-by-a-paraunitary-framework)

## Abstract
Enforcing orthogonality in neural networks is an antidote for gradient vanishing/exploding problems, sensitivity by adversarial perturbation, and bounding generalization errors. However, many previous approaches are heuristic, and the orthogonality of convolutional layers is not systematically studied: some of these designs are not exactly orthogonal, while others only consider standard convolutional layers and propose specific classes of their realizations. To address this problem, we propose a theoretical framework for orthogonal convolutional layers, which establishes the equivalence between various orthogonal convolutional layers in the spatial domain and the paraunitary systems in the spectral domain. Since there exists a complete spectral factorization of paraunitary systems, any orthogonal convolution layer can be parameterized as convolutions of spatial filters. Our framework endows high expressive power to various convolutional layers while maintaining their exact orthogonality. Furthermore, our layers are memory and computationally efficient for deep networks compared to previous designs. Our versatile framework, for the first time, enables the study of architecture designs for deep orthogonal networks, such as choices of skip connection, initialization, stride, and dilation. Consequently, we scale up orthogonal networks to deep architectures, including ResNet, WideResNet, and ShuffleNet, substantially increasing the performance over the traditional shallow orthogonal networks. 


```bib
@misc{su2021scalingup,
      title={Scaling-up Diverse Orthogonal Convolutional Networks with a Paraunitary Framework}, 
      author={Jiahao Su and Wonmin Byeon and Furong Huang},
      year={2021},
      eprint={2106.09121},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

