---
title: "Feature-based Graph Attention Networks Improve Online Continual Learning"
collection: publications
permalink: /publication/2025-gatcl
date: 2025-02-13
year: '2025'
venue: 'arXiv'
citation: 'Adjovi Sim, Zhengkui Wang, Aik Beng Ng, Shalini De Mello, Simon See, <b>Wonmin Byeon</b> <b>|</b> <i> arXiv </i> '
paperurl: 'https://arxiv.org/pdf/2502.09143'
---
[[arxiv]](https://arxiv.org/abs/2502.09143)&nbsp;


## Abstract
Online continual learning for image classification is crucial for models to adapt to new data while retaining knowledge of previously learned tasks. This capability is essential to address real-world challenges involving dynamic environments and evolving data distributions. Traditional approaches predominantly employ Convolutional Neural Networks, which are limited to processing images as grids and primarily capture local patterns rather than relational information. Although the emergence of transformer architectures has improved the ability to capture relationships, these models often require significantly larger resources. In this paper, we present a novel online continual learning framework based on Graph Attention Networks (GATs), which effectively capture contextual relationships and dynamically update the task-specific representation via learned attention weights. Our approach utilizes a pre-trained feature extractor to convert images into graphs using hierarchical feature maps, representing information at varying levels of granularity. These graphs are then processed by a GAT and incorporate an enhanced global pooling strategy to improve classification performance for continual learning. In addition, we propose the rehearsal memory duplication technique that improves the representation of the previous tasks while maintaining the memory budget. Comprehensive evaluations on benchmark datasets, including SVHN, CIFAR10, CIFAR100, and MiniImageNet, demonstrate the superiority of our method compared to the state-of-the-art methods.

```bib
@misc{sim2025featurebasedgraphattentionnetworks,
      title={Feature-based Graph Attention Networks Improve Online Continual Learning}, 
      author={Adjovi Sim and Zhengkui Wang and Aik Beng Ng and Shalini De Mello and Simon See and Wonmin Byeon},
      year={2025},
      eprint={2502.09143},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2502.09143}, 
}
```

