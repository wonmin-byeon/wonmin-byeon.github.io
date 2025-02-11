---
title: "NVIDIA SimNet: an AI-accelerated multi-physics simulation framework"
collection: publications
permalink: /publication/2020-simnet
date: 2021-06-15
year: '2021'
venue: 'ICCS'
citation: 'Oliver Hennigh, Susheela Narasimhan, Mohammad Amin Nabian, Akshay Subramaniam, Kaustubh Tangsali, Zhiwei Fang, Max Rietmann, <b>Wonmin Byeon</b>, Sanjay Choudhry <b>|</b> <i>ICCS 2021</i> '
paperurl: 'https://arxiv.org/pdf/2012.07938.pdf'
---
[[arxiv]](https://arxiv.org/abs/2012.07938.pdf) &nbsp;[[paper]](https://link.springer.com/epdf/10.1007/978-3-030-77977-1_36?sharing_token=0W5gk5Wz7uwn7wVSsOfH7fe4RwlQNchNByi7wbcMAY7nv7nWD0YReyanOIjHEHpAW4s7PSMqqHouVhQg_GYCNPHl8_yHBWipX5LfgCfR0QviXp19FTuSfW_Np8qLXSayV9i0-E7XRFZHI6F4aufH2JZREqKsNhb3iSgSaaqwcJg%3D) &nbsp;[[code]](https://developer.nvidia.com/simnet)

## Abstract
We present SimNet, an AI-driven multi-physics simulation framework, to accelerate simulations across a wide range of disciplines in science and engineering. Compared to traditional numerical solvers, SimNet addresses a wide range of use cases - coupled forward simulations without any training data, inverse and data assimilation problems. SimNet offers fast turnaround time by enabling parameterized system representation that solves for multiple configurations simultaneously, as opposed to the traditional solvers that solve for one configuration at a time. SimNet is integrated with parameterized constructive solid geometry as well as STL modules to generate point clouds. Furthermore, it is customizable with APIs that enable user extensions to geometry, physics and network architecture. It has advanced network architectures that are optimized for high-performance GPU computing, and offers scalable performance for multi-GPU and multi-Node implementation with accelerated linear algebra as well as FP32, FP64 and TF32 computations. In this paper we review the neural network solver methodology, the SimNet architecture, and the various features that are needed for effective solution of the PDEs. We present real-world use cases that range from challenging forward multi-physics simulations with turbulence and complex 3D geometries, to industrial design optimization and inverse problems that are not addressed efficiently by the traditional solvers. Extensive comparisons of SimNet results with open source and commercial solvers show good correlation. 


```bib
@misc{hennigh2020nvidia,
      title={NVIDIA SimNet^{TM}: an AI-accelerated multi-physics simulation framework}, 
      author={Oliver Hennigh and Susheela Narasimhan and Mohammad Amin Nabian and Akshay Subramaniam and Kaustubh Tangsali and Max Rietmann and Jose del Aguila Ferrandis and Wonmin Byeon and Zhiwei Fang and Sanjay Choudhry},
      year={2020},
      eprint={2012.07938},
      archivePrefix={arXiv},
      primaryClass={physics.flu-dyn}
}
```

