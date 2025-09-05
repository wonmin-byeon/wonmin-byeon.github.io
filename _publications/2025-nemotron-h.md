---
title: "Nemotron-H: A Family of Accurate and Efficient Hybrid Mamba-Transformer Models"
collection: publications
permalink: /publication/2025-nemotron-h
date: 2025-04-01
year: '2025'
venue: 'arXiv'
citation: 'NVIDIA <b>|</b> <i> arXiv </i> '
paperurl: 'https://arxiv.org/abs/2504.03624'
---
[[arxiv]](https://arxiv.org/abs/2504.03624)&nbsp;
[[blog]](https://research.nvidia.com/labs/adlr/nemotronh/)&nbsp;
[[Hugging Face]](https://huggingface.co/collections/nvidia/nemotron-h-67fd3d7ca332cdf1eb5a24bb)&nbsp;


## Abstract
As inference-time scaling becomes critical for enhanced reasoning capabilities, it is increasingly becoming important to build models that are efficient to infer. We introduce Nemotron-H, a family of 8B and 56B/47B hybrid Mamba-Transformer models designed to reduce inference cost for a given accuracy level. To achieve this goal, we replace the majority of self-attention layers in the common Transformer model architecture with Mamba layers that perform constant computation and require constant memory per generated token. We show that Nemotron-H models offer either better or on-par accuracy compared to other similarly-sized state-of-the-art open-sourced Transformer models (e.g., Qwen-2.5-7B/72B and Llama-3.1-8B/70B), while being up to 3× faster at inference. To further increase inference speed and reduce the memory required at inference time, we created Nemotron-H-47B-Base from the 56B model using a new compression via pruning and distillation technique called MiniPuzzle. Nemotron-H-47B-Base achieves similar accuracy to the 56B model, but is 20% faster to infer. In addition, we introduce an FP8-based training recipe and show that it can achieve on par results with BF16-based training. This recipe is used to train the 56B model. We are releasing Nemotron-H base model checkpoints with support in Hugging Face and NeMo.

```bib
@misc{nvidia2025nemotronhfamilyaccurateefficient,
      title={Nemotron-H: A Family of Accurate and Efficient Hybrid Mamba-Transformer Models}, 
      author={NVIDIA and : and Aaron Blakeman and Aarti Basant and Abhinav Khattar and Adithya Renduchintala and Akhiad Bercovich and Aleksander Ficek and Alexis Bjorlin and Ali Taghibakhshi and Amala Sanjay Deshmukh and Ameya Sunil Mahabaleshwarkar and Andrew Tao and Anna Shors and Ashwath Aithal and Ashwin Poojary and Ayush Dattagupta and Balaram Buddharaju and Bobby Chen and Boris Ginsburg and Boxin Wang and Brandon Norick and Brian Butterfield and Bryan Catanzaro and Carlo del Mundo and Chengyu Dong and Christine Harvey and Christopher Parisien and Dan Su and Daniel Korzekwa and Danny Yin and Daria Gitman and David Mosallanezhad and Deepak Narayanan and Denys Fridman and Dima Rekesh and Ding Ma and Dmytro Pykhtar and Dong Ahn and Duncan Riach and Dusan Stosic and Eileen Long and Elad Segal and Ellie Evans and Eric Chung and Erick Galinkin and Evelina Bakhturina and Ewa Dobrowolska and Fei Jia and Fuxiao Liu and Gargi Prasad and Gerald Shen and Guilin Liu and Guo Chen and Haifeng Qian and Helen Ngo and Hongbin Liu and Hui Li and Igor Gitman and Ilia Karmanov and Ivan Moshkov and Izik Golan and Jan Kautz and Jane Polak Scowcroft and Jared Casper and Jarno Seppanen and Jason Lu and Jason Sewall and Jiaqi Zeng and Jiaxuan You and Jimmy Zhang and Jing Zhang and Jining Huang and Jinze Xue and Jocelyn Huang and Joey Conway and John Kamalu and Jon Barker and Jonathan Cohen and Joseph Jennings and Jupinder Parmar and Karan Sapra and Kari Briski and Kateryna Chumachenko and Katherine Luna and Keshav Santhanam and Kezhi Kong and Kirthi Sivamani and Krzysztof Pawelec and Kumar Anik and Kunlun Li and Lawrence McAfee and Leon Derczynski and Lindsey Pavao and Luis Vega and Lukas Voegtle and Maciej Bala and Maer Rodrigues de Melo and Makesh Narsimhan Sreedhar and Marcin Chochowski and Markus Kliegl and Marta Stepniewska-Dziubinska and Matthieu Le and Matvei Novikov and Mehrzad Samadi and Michael Andersch and Michael Evans and Miguel Martinez and Mike Chrzanowski and Mike Ranzinger and Mikolaj Blaz and Misha Smelyanskiy and Mohamed Fawzy and Mohammad Shoeybi and Mostofa Patwary and Nayeon Lee and Nima Tajbakhsh and Ning Xu and Oleg Rybakov and Oleksii Kuchaiev and Olivier Delalleau and Osvald Nitski and Parth Chadha and Pasha Shamis and Paulius Micikevicius and Pavlo Molchanov and Peter Dykas and Philipp Fischer and Pierre-Yves Aquilanti and Piotr Bialecki and Prasoon Varshney and Pritam Gundecha and Przemek Tredak and Rabeeh Karimi and Rahul Kandu and Ran El-Yaniv and Raviraj Joshi and Roger Waleffe and Ruoxi Zhang and Sabrina Kavanaugh and Sahil Jain and Samuel Kriman and Sangkug Lym and Sanjeev Satheesh and Saurav Muralidharan and Sean Narenthiran and Selvaraj Anandaraj and Seonmyeong Bak and Sergey Kashirsky and Seungju Han and Shantanu Acharya and Shaona Ghosh and Sharath Turuvekere Sreenivas and Sharon Clay and Shelby Thomas and Shrimai Prabhumoye and Shubham Pachori and Shubham Toshniwal and Shyamala Prayaga and Siddhartha Jain and Sirshak Das and Slawek Kierat and Somshubra Majumdar and Song Han and Soumye Singhal and Sriharsha Niverty and Stefania Alborghetti and Suseella Panguluri and Swetha Bhendigeri and Syeda Nahida Akter and Szymon Migacz and Tal Shiri and Terry Kong and Timo Roman and Tomer Ronen and Trisha Saar and Tugrul Konuk and Tuomas Rintamaki and Tyler Poon and Ushnish De and Vahid Noroozi and Varun Singh and Vijay Korthikanti and Vitaly Kurin and Wasi Uddin Ahmad and Wei Du and Wei Ping and Wenliang Dai and Wonmin Byeon and Xiaowei Ren and Yao Xu and Yejin Choi and Yian Zhang and Ying Lin and Yoshi Suhara and Zhiding Yu and Zhiqi Li and Zhiyu Li and Zhongbo Zhu and Zhuolin Yang and Zijia Chen},
      year={2025},
      eprint={2504.03624},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2504.03624}, 
}
```

