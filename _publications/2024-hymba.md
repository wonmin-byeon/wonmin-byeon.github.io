---
title: "Hymba: A Hybrid-head Architecture for Small Language Models"
collection: publications
permalink: /publication/2024-hymba
date: 2025-04-01
year: '2025'
venue: 'ICLR'
citation: 'Xin Dong, Yonggan Fu, Shizhe Diao, <b>Wonmin Byeon</b>, Zijia Chen, Ameya Sunil Mahabaleshwarkar, Shih-Yang Liu, Matthijs Van Keirsbilck, Min-Hung Chen, Yoshi Suhara, Yingyan Lin, Jan Kautz, Pavlo Molchanov <b>|</b> <i> ICLR 2025</i> '
paperurl: 'https://www.arxiv.org/abs/2411.13676'
---
[[arxiv]](https://www.arxiv.org/abs/2411.13676)&nbsp;
[[code]](https://github.com/NVlabs/hymba)&nbsp;
[[HF models]](https://huggingface.co/collections/nvidia/hymba-673c35516c12c4b98b5e845f)&nbsp;
[[blog]](https://developer.nvidia.com/blog/hymba-hybrid-head-architecture-boosts-small-language-model-performance/)&nbsp;
<!-- [[project page]](https://kuai-lab.github.io/cvpr2022sound/)  -->


## Abstract
We propose Hymba, a family of small language models featuring a hybrid-head parallel architecture that integrates transformer attention mechanisms with state space models (SSMs) for enhanced efficiency. Attention heads provide high-resolution recall, while SSM heads enable efficient context summarization. Additionally, we introduce learnable meta tokens that are prepended to prompts, storing critical information and alleviating the "forced-to-attend" burden associated with attention mechanisms. This model is further optimized by incorporating cross-layer key-value (KV) sharing and partial sliding window attention, resulting in a compact cache size. During development, we conducted a controlled study comparing various architectures under identical settings and observed significant advantages of our proposed architecture. Notably, Hymba achieves state-of-the-art results for small LMs: Our Hymba-1.5B-Base model surpasses all sub-2B public models in performance and even outperforms Llama-3.2-3B with 1.32% higher average accuracy, an 11.67x cache size reduction, and 3.49x throughput.


```bib
@misc{dong2024hymbahybridheadarchitecturesmall,
      title={Hymba: A Hybrid-head Architecture for Small Language Models}, 
      author={Xin Dong and Yonggan Fu and Shizhe Diao and Wonmin Byeon and Zijia Chen and Ameya Sunil Mahabaleshwarkar and Shih-Yang Liu and Matthijs Van Keirsbilck and Min-Hung Chen and Yoshi Suhara and Yingyan Lin and Jan Kautz and Pavlo Molchanov},
      year={2024},
      eprint={2411.13676},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2411.13676}, 
}
```

