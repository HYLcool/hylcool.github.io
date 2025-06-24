---
title: "DetailMaster: Can Your Text-to-Image Model Handle Long Prompts?"
collection: publications
permalink: /publication/2025-05-22-detail-master
date: 2025-05-22
venue: 'arXiv'
citation: 'Jiao, Qirui, Daoyuan Chen, <ins>Yilun Huang</ins>, Xika Lin, Ying Shen, and Yaliang Li. "DetailMaster: Can Your Text-to-Image Model Handle Long Prompts?." arXiv preprint arXiv:2505.16915 (2025).'
paperurl: 'https://arxiv.org/abs/2505.16915'
code: 'https://github.com/modelscope/data-juicer/tree/DetailMaster'
---

<strong>Abstraction</strong>: While recent text-to-image (T2I) models show impressive capabilities in synthesizing images from brief descriptions, their performance significantly degrades when confronted with long, detail-intensive prompts required in professional applications. We present DetailMaster, the first comprehensive benchmark specifically designed to evaluate T2I models' systematical abilities to handle extended textual inputs that contain complex compositional requirements. Our benchmark introduces four critical evaluation dimensions: Character Attributes, Structured Character Locations, Multi-Dimensional Scene Attributes, and Explicit Spatial/Interactive Relationships. The benchmark comprises long and detail-rich prompts averaging 284.89 tokens, with high quality validated by expert annotators. Evaluation on 7 general-purpose and 5 long-prompt-optimized T2I models reveals critical performance limitations: state-of-the-art models achieve merely ~50% accuracy in key dimensions like attribute binding and spatial reasoning, while all models showing progressive performance degradation as prompt length increases. Our analysis highlights systemic failures in structural comprehension and detail overload handling, motivating future research into architectures with enhanced compositional reasoning. We open-source the dataset, data curation code, and evaluation tools to advance detail-rich T2I generation and enable broad applications that would otherwise be infeasible due to the lack of a dedicated benchmark.

- Download paper [here](https://arxiv.org/abs/2505.16915)
- Code is available [here](https://github.com/modelscope/data-juicer/tree/DetailMaster)
