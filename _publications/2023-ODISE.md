---
title: "Open-vocabulary panoptic segmentation with text-to-image diffusion models"
collection: publications
permalink: /publication/2023-ODSIE
date: 2023-06-01
year: '2023'
venue: 'CVPR'
citation: 'Jiarui Xu, Sifei Liu, Arash Vahdat, <b>Wonmin Byeon</b>, Xiaolong Wang, Shalini De Mello <b>|</b> <i>CVPR 2023 Highlight</i> '
paperurl: 'https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_Open-Vocabulary_Panoptic_Segmentation_With_Text-to-Image_Diffusion_Models_CVPR_2023_paper.pdf'
---
[[arxiv]](https://arxiv.org/abs/2303.04803)&nbsp;
[[project page]](https://jerryxu.net/ODISE/)&nbsp;
[[code]](https://github.com/NVlabs/ODISE)&nbsp;
[[demo]](https://huggingface.co/spaces/xvjiarui/ODISE)&nbsp;
[[talk]](https://www.youtube.com/watch?v=eW2vF8o_7p0&ab_channel=NVIDIADeveloper)

## Abstract
We present ODISE: Open-vocabulary DIffusion-based panoptic SEgmentation, which unifies pre-trained text-image diffusion and discriminative models to perform open-vocabulary panoptic segmentation. Text-to-image diffusion models have shown the remarkable capability of generating high-quality images with diverse open-vocabulary language descriptions. This demonstrates that their internal representation space is highly correlated with open concepts in the real world. Text-image discriminative models like CLIP, on the other hand, are good at classifying images into open-vocabulary labels. We propose to leverage the frozen representation of both these models to perform panoptic segmentation of any category in the wild. Our approach outperforms the previous state of the art by significant margins on both open-vocabulary panoptic and semantic segmentation tasks. In particular, with COCO training only, our method achieves 23.4 PQ and 30.0 mIoU on the ADE20K dataset, with 8.3 PQ and 7.9 mIoU absolute improvement over previous state of the art. 

```bib
@InProceedings{Xu_2023_CVPR,
    author    = {Xu, Jiarui and Liu, Sifei and Vahdat, Arash and Byeon, Wonmin and Wang, Xiaolong and De Mello, Shalini},
    title     = {Open-Vocabulary Panoptic Segmentation With Text-to-Image Diffusion Models},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2023},
    pages     = {2955-2966}
}
```

