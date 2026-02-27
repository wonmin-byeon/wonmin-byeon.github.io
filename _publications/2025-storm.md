---
title: "Token-Efficient Long Video Understanding for Multimodal LLMs"
collection: publications
permalink: /publication/2025-storm
date: 2025-03-01
year: '2025'
venue: 'arXiv'
citation: 'Jindong Jiang*, Xiuyu Li*, Zhijian Liu, Muyang Li, Guo Chen, Zhiqi Li, De-An Huang, Guilin Liu, Zhiding Yu, Kurt Keutzer, Sungjin Ahn, Jan Kautz, Hongxu Yin, Yao Lu, Song Han, <b>Wonmin Byeon</b> <b>|</b> <i> arXiv </i> '
paperurl: 'https://arxiv.org/pdf/2503.04130'
---
[[arxiv]](https://arxiv.org/abs/2503.04130)&nbsp;
[[website]](https://research.nvidia.com/labs/lpr/storm/)&nbsp;


## Abstract
Recent advances in video-based multimodal large language models (Video-LLMs) have significantly improved video understanding by processing videos as sequences of image frames. However, many existing methods treat frames independently in the vision backbone, lacking explicit temporal modeling, which limits their ability to capture dynamic patterns and efficiently handle long videos. To address these limitations, we introduce STORM (**S**patiotemporal **TO**ken **R**eduction for **M**ultimodal LLMs), a novel architecture incorporating a dedicated temporal encoder between the image encoder and the LLM. Our temporal encoder leverages the Mamba State Space Model to integrate temporal information into image tokens, generating enriched representations that preserve inter-frame dynamics across the entire video sequence. This enriched encoding not only enhances video reasoning capabilities but also enables effective token reduction strategies, including test-time sampling and training-based temporal and spatial pooling, substantially reducing computational demands on the LLM without sacrificing key temporal information. By integrating these techniques, our approach simultaneously reduces training and inference latency while improving performance, enabling efficient and robust video understanding over extended temporal contexts. Extensive evaluations show that STORM achieves state-of-the-art results across various long video understanding benchmarks (more than 5% improvement on MLVU and LongVideoBench) while reducing the computation costs by up to 8× and the decoding latency by 2.4-2.9× for the fixed numbers of input frames.

## STORM in the Spotlight

We are thrilled to see our recent paper gaining traction across the AI community. Several creators have developed insightful video deep-dives and summaries of our work.

Whether you're looking for a deep technical breakdown or a quick audio summary, these resources are excellent companions to the paper:

- [AI Coffee Break with Letitia](https://youtu.be/uMk3VN4S8TQ?si=Q0n8-pNlNYzsngcn)
- [Arxiv Papers](https://youtu.be/I_loecu6Gew?si=tB5hih9qfRtArQRk)
- [AI Papers Podcast Daily](https://youtu.be/ifqHBtpw7CM?si=Unq0UOp1azreElAs)
- [AI Paper Slop](https://youtu.be/pKObqY3msJk?si=L7jqh2wtzntPH_k-)

Thank you to all the creators for featuring our research!

```bib
@misc{jiang2025tokenefficientlongvideounderstanding,
      title={Token-Efficient Long Video Understanding for Multimodal LLMs}, 
      author={Jindong Jiang and Xiuyu Li and Zhijian Liu and Muyang Li and Guo Chen and Zhiqi Li and De-An Huang and Guilin Liu and Zhiding Yu and Kurt Keutzer and Sungjin Ahn and Jan Kautz and Hongxu Yin and Yao Lu and Song Han and Wonmin Byeon},
      year={2025},
      eprint={2503.04130},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2503.04130}, 
}
```

