---
title: "ContextVP: Fully Context-Aware Video Prediction"
collection: publications
permalink: /publication/2018-contextvp
date: 2018-09-13
venue: 'European Conference on Computer Vision (ECCV)'
citation: '<b>W Byeon</b>, Q Wang, R K Srivastava, P Koumoutsakos <b>|</b> <i>ECCV 2018</i> '
paperurl: 'http://openaccess.thecvf.com/content_ECCV_2018/papers/Wonmin_Byeon_ContextVP_Fully_Context-Aware_ECCV_2018_paper.pdf'
---
[[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Wonmin_Byeon_ContextVP_Fully_Context-Aware_ECCV_2018_paper.pdf) &nbsp;[[slides]](http://wonmin-byeon.github.io/files/byeon-contextvp-eccv18-oral.pdf) &nbsp;[[video]](https://www.youtube.com/watch?time_continue=431&v=9ncoStGl4VA)

* ECCV oral presentation, Sep. 2018. [[slides]](http://wonmin-byeon.github.io/files/byeon-contextvp-eccv18-oral.pdf) [[talk]](https://www.youtube.com/watch?time_continue=431&v=9ncoStGl4VA)

* Some parts of this paper were presented at CVPR'18 Workshop (oral): Brave New Ideas for Video Understanding. [[program]](https://bivu2018.github.io/#program) [[paper]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w19/Byeon_ContextVP_Fully_Context-Aware_CVPR_2018_paper.pdf)

* The experimental results on Caltech Pedestrian and UCF-101 datasets [[zip]](https://www.dropbox.com/sh/1tjmaom76fumbou/AABkF7_AVRU7Be6d2OwtnfM7a?dl=0)

## Abstract
Video prediction models based on convolutional networks,recurrent networks, and their  combinations often result in blurry  pre-dictions. We identify an important contributing factor for imprecise pre-dictions that has not been studied adequately in the literature: blindspots, i.e., lack of access to all relevant past information for accuratelypredicting the future. To address this issue, we introduce a fully context-aware architecture that captures the entire available past context for eachpixel using Parallel Multi-Dimensional LSTM units and aggregates it us-ing blending units. Our model outperforms a strong baseline network of 20 recurrent convolutional layers and yields state-of-the-art performancefor next step prediction on three challenging real-world video datasets:Human 3.6M, Caltech Pedestrian, and UCF-101. Moreover, it does so with fewer parameters than several recently proposed models, and doesnot rely on deep convolutional networks, multi-scale architectures, sepa-ration of background and foreground modeling, motion flow learning, oradversarial training. These results highlight that full awareness of pastcontext is of crucial importance for video prediction. 

## Multi-Frame Prediction Results
![](http://wonmin-byeon.github.io/files/result-contextvp18/eccv-2.gif)
![](http://wonmin-byeon.github.io/files/result-contextvp18/eccv-3.gif)
![](http://wonmin-byeon.github.io/files/result-contextvp18/eccv-1.gif)

```
@inproceedings{byeon2018contextvp,
  title={ContextVP: Fully Context-Aware Video Prediction},
  author={Byeon, Wonmin and Wang, Qin and Srivastava, Rupesh Kumar and Koumoutsakos, Petros},
  booktitle = {Proceedings of the European Conference on Computer Vision ({ECCV})},
  year={2018}
}
```