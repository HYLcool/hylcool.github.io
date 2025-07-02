---
title: "Data-Juicer Sandbox: A Comprehensive Suite for Multimodal Data-Model Co-development"
collection: publications
permalink: /publication/2024-07-16-data-juicer-sandbox
date: 2024-07-16
venue: 'Forty-second International Conference on Machine Learning. 2025. Spotlight.'
citation: 'Chen, Daoyuan*, Haibin Wang*, <ins>Yilun Huang*</ins>, Ce Ge, Yaliang Li, Bolin Ding, and Jingren Zhou. "Data-juicer sandbox: A feedback-driven suite for multimodal data-model co-development." In Forty-second International Conference on Machine Learning. 2025. Spotlight.'
paperurl: 'https://arxiv.org/abs/2407.11784'
code: 'https://github.com/modelscope/data-juicer/blob/main/docs/Sandbox.md'
---

<strong>Abstraction</strong>: The emergence of multimodal large models has advanced artificial intelligence, introducing unprecedented levels of performance and functionality. However, optimizing these models remains challenging due to historically isolated paths of model-centric and data-centric developments, leading to suboptimal outcomes and inefficient resource utilization. In response, we present a new sandbox suite tailored for integrated data-model co-development. This sandbox provides a feedback-driven experimental platform, enabling cost-effective iteration and guided refinement of both data and models. Our proposed ``Probe-Analyze-Refine'' workflow, validated through practical use cases on multimodal tasks such as image-text pre-training with CLIP, image-to-text generation with LLaVA-like models, and text-to-video generation with DiT-based models, yields transferable and notable performance boosts, such as topping the VBench leaderboard. A comprehensive set of over 100 experiments demonstrated the suite's usability and extensibility, while also uncovering insights into the interplay between data quality, diversity, model behavior, and computational costs. All codes, datasets, and models are open-sourced to foster future research and applications that would otherwise be infeasible due to the lack of a dedicated co-development infrastructure.

- Download paper [here](https://arxiv.org/abs/2407.11784) or [here](https://openreview.net/forum?id=zIGIvysR1H)
- Code is available [here](https://github.com/modelscope/data-juicer/blob/main/docs/Sandbox.md)

- Data-Juicer Sandbox Workflow:
![Data-Juicer Sandbox Workflow](https://img.alicdn.com/imgextra/i2/O1CN01B3zR0t29noFoHGsyq_!!6000000008113-2-tps-3878-2212.png)

- T2V-based text-to-video model Data-Juicer-T2V acheives SOTA performance on [VBench](https://vchitect.github.io/VBench-project/) (2024.07.16):
![Data-Juicer-T2V acheives Top-1 on VBench](https://img.alicdn.com/imgextra/i2/O1CN01iKVDNE1SJYc42AqKD_!!6000000002226-2-tps-2966-1832.png)


