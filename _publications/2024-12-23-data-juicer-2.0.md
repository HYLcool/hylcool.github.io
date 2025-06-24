---
title: "Data-Juicer 2.0: Cloud-Scale Adaptive Data Processing for Foundation Models"
collection: publications
permalink: /publication/2024-12-23-data-juicer-2.0
date: 2024-12-23
venue: 'arXiv'
citation: 'Chen, Daoyuan*, <ins>Yilun Huang*</ins>, Xuchen Pan, Nana Jiang, Haibin Wang, Ce Ge, Yushuo Chen et al. "Data-Juicer 2.0: Cloud-Scale Adaptive Data Processing for Foundation Models." arXiv preprint arXiv:2501.14755 (2024).'
paperurl: 'https://arxiv.org/abs/2501.14755'
code: 'https://github.com/modelscope/data-juicer'
---

<strong>Abstraction</strong>: The burgeoning field of foundation models necessitates advanced data processing mechanisms capable of harnessing vast valuable data with varied types utilized by these models. Nevertheless, the current landscape presents unique challenges that traditional data processing frameworks cannot handle effectively, especially with multimodal intricacies. In response, we present Data-Juicer 2.0, a new system offering fruitful data processing capabilities backed by over a hundred operators spanning various modalities like text, image, audio, and video. With seamless compatibility and dedicated optimization to popular dataset hubs like Hugging Face and computing engines like Ray, Data-Juicer 2.0 enhances its predecessor in both usability, efficiency, and programmability. It features an easily accessible user interface layer that supports decoupled Python interactions, RESTful APIs, and conversational commands. Alongside this, it contains a core runtime layer optimized for adaptive execution and management across different dataset scales, processing demands, and computational environments, while shielding unnecessary system details. Extensive empirical evaluations demonstrate Data-Juicer 2.0's remarkable performance and scalability, highlighting its capability to efficiently process tens of billions of data samples with tens of thousands of CPU cores. The system is publicly available, actively maintained, and broadly adopted in diverse research endeavors, practical applications, and real-world products such as Alibaba Cloud PAI.

- Download paper [here](https://arxiv.org/abs/2501.14755)
- Code is available [here](https://github.com/modelscope/data-juicer)
