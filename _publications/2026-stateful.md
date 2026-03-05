---
title: "Stateful Token Reduction for Long-Video Hybrid VLMs"
collection: publications
permalink: /publication/2026-stateful
date: 2026-03-05
year: '2026'
venue: 'arXiv'
citation: 'Jindong Jiang*, Amala Sanjay Deshmukh, Kateryna Chumachenko, Karan Sapra, Zhiding Yu, Guilin Liu, Andrew Tao, Pavlo Molchanov, Jan Kautz, <b>Wonmin Byeon*</b> <b>|</b> <i> arXiv </i> '
paperurl: 'https://arxiv.org/pdf/2603.00198'
---
[[arxiv]](https://arxiv.org/abs/2603.00198)&nbsp;


## Abstract
Token reduction is an effective way to accelerate long-video vision-language models (VLMs), but most existing methods are designed for dense Transformers and do not directly account for hybrid architectures that interleave attention with linear-time state-space blocks (e.g., Mamba). We study query-conditioned token reduction for hybrid video VLMs and analyze reduction behavior through two properties: layerwise sparsity (how many tokens capture query-relevant information) and importance stability (whether token-importance rankings persist across depth). Although token importance is sparse within each layer, the set of important tokens changes across layers, so aggressive early pruning is unreliable. Motivated by this, we propose a low-to-high progressive reduction schedule and a unified language-aware scoring mechanism for both attention and Mamba blocks (using an implicit-attention proxy for Mamba), enabling all-layer token reduction in hybrids. Under an aggressive compression setting (retaining 25% of visual tokens), our approach delivers substantial prefilling speedups (3.8--4.2x) with near-baseline accuracy at test time, and light finetuning under reduction further improves performance on long-context video benchmarks.

```bib
@misc{jiang2026statefultokenreductionlongvideo,
      title={Stateful Token Reduction for Long-Video Hybrid VLMs}, 
      author={Jindong Jiang and Amala Sanjay Deshmukh and Kateryna Chumachenko and Karan Sapra and Zhiding Yu and Guilin Liu and Andrew Tao and Pavlo Molchanov and Jan Kautz and Wonmin Byeon},
      year={2026},
      eprint={2603.00198},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2603.00198}, 
}
```

