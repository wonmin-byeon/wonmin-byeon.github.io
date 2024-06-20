---
title: "An Empirical Study of Mamba-based Language Models"
collection: publications
permalink: /publication/2024-hybrid
date: 2024-06-10
year: '2024'
venue: 'arXiv'
citation: 'Roger Waleffe, <b>Wonmin Byeon</b>, Duncan Riach, Brandon Norick, Vijay Korthikanti, Tri Dao, Albert Gu, Ali Hatamizadeh, Sudhakar Singh, Deepak Narayanan, Garvit Kulshreshtha, Vartika Singh, Jared Casper, Jan Kautz, Mohammad Shoeybi, Bryan Catanzaro <b>|</b> <i> arXiv</i> '
paperurl: 'https://arxiv.org/pdf/2406.07887'
---
[[arxiv]](https://arxiv.org/abs/2406.07887)&nbsp;
[[code]](https://github.com/NVIDIA/megatron-LM/tree/ssm/examples/mamba)&nbsp;
[[checkpoints]](https://huggingface.co/collections/nvidia/ssms-666a362c5c3bb7e4a6bcfb9c)&nbsp;
<!-- [[project page]](https://kuai-lab.github.io/cvpr2022sound/)  -->


## Abstract
Selective state-space models (SSMs) like Mamba overcome some of the shortcomings of Transformers, such as quadratic computational complexity with sequence length and large inference-time memory requirements from the key-value cache. Moreover, recent studies have shown that SSMs can match or exceed the language modeling capabilities of Transformers, making them an attractive alternative. In a controlled setting (e.g., same data), however, studies so far have only presented small scale experiments comparing SSMs to Transformers. To understand the strengths and weaknesses of these architectures at larger scales, we present a direct comparison between 8B-parameter Mamba, Mamba-2, and Transformer models trained on the same datasets of up to 3.5T tokens. We also compare these models to a hybrid architecture consisting of 43% Mamba-2, 7% attention, and 50% MLP layers (Mamba-2-Hybrid). Using a diverse set of tasks, we answer the question of whether Mamba models can match Transformers at larger training budgets. Our results show that while pure SSMs match or exceed Transformers on many tasks, they lag behind Transformers on tasks which require strong copying or in-context learning abilities (e.g., 5-shot MMLU, Phonebook) or long-context reasoning. In contrast, we find that the 8B Mamba-2-Hybrid exceeds the 8B Transformer on all 12 standard tasks we evaluated (+2.65 points on average) and is predicted to be up to 8x faster when generating tokens at inference time. To validate long-context capabilities, we provide additional experiments evaluating variants of the Mamba-2-Hybrid and Transformer extended to support 16K, 32K, and 128K sequences. On an additional 23 long-context tasks, the hybrid model continues to closely match or exceed the Transformer on average. To enable further study, we release the checkpoints as well as the code used to train our models as part of NVIDIA's Megatron-LM project.


```bib
@misc{waleffe2024empirical,
      title={An Empirical Study of Mamba-based Language Models}, 
      author={Roger Waleffe and Wonmin Byeon and Duncan Riach and Brandon Norick and Vijay Korthikanti and Tri Dao and Albert Gu and Ali Hatamizadeh and Sudhakar Singh and Deepak Narayanan and Garvit Kulshreshtha and Vartika Singh and Jared Casper and Jan Kautz and Mohammad Shoeybi and Bryan Catanzaro},
      year={2024},
      eprint={2406.07887},
      archivePrefix={arXiv},
      primaryClass={id='cs.LG' full_name='Machine Learning' is_active=True alt_name=None in_archive='cs' is_general=False description='Papers on all aspects of machine learning research (supervised, unsupervised, reinforcement learning, bandit problems, and so on) including also robustness, explanation, fairness, and methodology. cs.LG is also an appropriate primary category for applications of machine learning methods.'}
}
```

