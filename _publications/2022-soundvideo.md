---
title: "Sound-Guided Semantic Video Generation"
collection: publications
permalink: /publication/2022-soundvideo
date: 2022-04-20
year: '2022'
venue: 'ECCV'
citation: 'Seung Hyun Lee, Gyeongrok Oh, <b>Wonmin Byeon</b>, Jihyun Bae, Chanyoung Kim, Won Jeong Ryoo, Sang Ho Yoon, Jinkyu Kim, Sangpil Kim <b>|</b> <i>ECCV 2022</i> '
paperurl: 'https://arxiv.org/pdf/2112.00007.pdf'
---
[[arxiv]](https://arxiv.org/abs/2204.09273)&nbsp;
<!-- [[project page]](https://kuai-lab.github.io/cvpr2022sound/)  -->

## Abstract
The recent success in StyleGAN demonstrates that pre-trained StyleGAN latent space is useful for realistic video generation. However, the generated motion in the video is usually not semantically meaningful due to the difficulty of determining the direction and magnitude in the StyleGAN latent space. In this paper, we propose a framework to generate realistic videos by leveraging multimodal (sound-image-text) embedding space. As sound provides the temporal contexts of the scene, our framework learns to generate a video that is semantically consistent with sound. First, our sound inversion module maps the audio directly into the StyleGAN latent space. We then incorporate the CLIP-based multimodal embedding space to further provide the audio-visual relationships. Finally, the proposed frame generator learns to find the trajectory in the latent space which is coherent with the corresponding sound and generates a video in a hierarchical manner. We provide the new high-resolution landscape video dataset (audio-visual pair) for the sound-guided video generation task. The experiments show that our model outperforms the state-of-the-art methods in terms of video quality. We further show several applications including image and video editing to verify the effectiveness of our method. 


```bib
@misc{https://doi.org/10.48550/arxiv.2204.09273,
  doi = {10.48550/ARXIV.2204.09273},
  
  url = {https://arxiv.org/abs/2204.09273},
  
  author = {Lee, Seung Hyun and Oh, Gyeongrok and Byeon, Wonmin and Bae, Jihyun and Kim, Chanyoung and Ryoo, Won Jeong and Yoon, Sang Ho and Kim, Jinkyu and Kim, Sangpil},
  
  keywords = {Computer Vision and Pattern Recognition (cs.CV), Artificial Intelligence (cs.AI), FOS: Computer and information sciences, FOS: Computer and information sciences},
  
  title = {Sound-Guided Semantic Video Generation},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {Creative Commons Attribution 4.0 International}
}

```

