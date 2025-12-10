---
title: "Nemotron-Flash: Towards Latency-Optimal Hybrid Small Language Models"
collection: publications
permalink: /publication/2025-nemotron-flash
date: 2025-12-01
year: '2025'
venue: 'NeruIPS'
citation: 'Yonggan Fu*, Xin Dong*, Shizhe Diao, Matthijs Van keirsbilck, Hanrong Ye, <b> Wonmin Byeon </b>, Yashaswi Karnati, Lucas Liebenwein, Hannah Zhang, Nikolaus Binder, Maksim Khadkevich, Alexander Keller, Jan Kautz, Yingyan (Celine) Lin, Pavlo Molchanov</b> <b>|</b> <i> NeruIPS 2025 </i> '
paperurl: 'https://arxiv.org/pdf/2511.18890'
---
[[arxiv]](https://arxiv.org/abs/2511.18890)&nbsp;


## Abstract
Efficient deployment of small language models (SLMs) is essential for numerous real-world applications with stringent latency constraints. While previous work on SLM design has primarily focused on reducing the number of parameters to achieve parameter-optimal SLMs, parameter efficiency does not necessarily translate into proportional real-device speed-ups. This work aims to identify the key determinants of SLMs' real-device latency and offer generalizable principles and methodologies for SLM design and training when real-device latency is the primary consideration. Specifically, we identify two central architectural factors: depth-width ratios and operator choices. The former is crucial for small-batch-size latency, while the latter affects both latency and large-batch-size throughput. In light of this, we first study latency-optimal depth-width ratios, with the key finding that although deep-thin models generally achieve better accuracy under the same parameter budget, they may not lie on the accuracy-latency trade-off frontier. Next, we explore emerging efficient attention alternatives to evaluate their potential as candidate building operators. Using the identified promising operators, we construct an evolutionary search framework to automatically discover latency-optimal combinations of these operators within hybrid SLMs, thereby advancing the accuracy-latency frontier. In addition to architectural improvements, we further enhance SLM training using a weight normalization technique that enables more effective weight updates and improves final convergence. Combining these methods, we introduce a new family of hybrid SLMs, called Nemotron-Flash, which significantly advances the accuracy-efficiency frontier of state-of-the-art SLMs, e.g., achieving over +5.5% average accuracy, 1.3x/1.9x lower latency, and 18.7x/45.6x higher throughput compared to Qwen3-1.7B/0.6B, respectively.

```bib
@misc{fu2025nemotronflashlatencyoptimalhybridsmall,
      title={Nemotron-Flash: Towards Latency-Optimal Hybrid Small Language Models}, 
      author={Yonggan Fu and Xin Dong and Shizhe Diao and Matthijs Van keirsbilck and Hanrong Ye and Wonmin Byeon and Yashaswi Karnati and Lucas Liebenwein and Hannah Zhang and Nikolaus Binder and Maksim Khadkevich and Alexander Keller and Jan Kautz and Yingyan Celine Lin and Pavlo Molchanov},
      year={2025},
      eprint={2511.18890},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2511.18890}, 
}
```

