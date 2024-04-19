---
title: "Robust Sound-Guided Image Manipulation"
collection: publications
permalink: /publication/2022-robustsoundimage
date: 2024-03-30
year: '2024'
venue: 'Neural Networks'
citation: 'Seung Hyun Lee, Chanyoung Kim, <b> Wonmin Byeon </b>, Gyeongrok Oh, Jooyoung Lee, Sang Ho Yoon, Jinkyu Kim, Sangpil Kim <b>|</b> <i> Neural Networks </i> '
paperurl: 'https://arxiv.org/pdf/2112.00007.pdf'
---
[[arxiv]](https://arxiv.org/abs/2208.14114)&nbsp;
[[paper]](https://doi.org/10.1016/j.neunet.2024.106271)&nbsp;
<!-- [[project page]](https://kuai-lab.github.io/cvpr2022sound/)  -->


## Abstract
Recent successes suggest that an image can be manipulated by a text prompt, e.g., a landscape scene on a sunny day is manipulated into the same scene on a rainy day driven by a text input "raining". These approaches often utilize a StyleCLIP-based image generator, which leverages multi-modal (text and image) embedding space. However, we observe that such text inputs are often bottlenecked in providing and synthesizing rich semantic cues, e.g., differentiating heavy rain from rain with thunderstorms. To address this issue, we advocate leveraging an additional modality, sound, which has notable advantages in image manipulation as it can convey more diverse semantic cues (vivid emotions or dynamic expressions of the natural world) than texts. In this paper, we propose a novel approach that first extends the image-text joint embedding space with sound and applies a direct latent optimization method to manipulate a given image based on audio input, e.g., the sound of rain. Our extensive experiments show that our sound-guided image manipulation approach produces semantically and visually more plausible manipulation results than the state-of-the-art text and sound-guided image manipulation methods, which are further confirmed by our human evaluations. Our downstream task evaluations also show that our learned image-text-sound joint embedding space effectively encodes sound inputs. 


```bib
@article{LEE2024106271,
title = {Robust sound-guided image manipulation},
journal = {Neural Networks},
volume = {175},
pages = {106271},
year = {2024},
issn = {0893-6080},
doi = {https://doi.org/10.1016/j.neunet.2024.106271},
url = {https://www.sciencedirect.com/science/article/pii/S0893608024001953},
author = {Seung Hyun Lee and Hyung-gun Chi and Gyeongrok Oh and Wonmin Byeon and Sang Ho Yoon and Hyunje Park and Wonjun Cho and Jinkyu Kim and Sangpil Kim},
}


```

