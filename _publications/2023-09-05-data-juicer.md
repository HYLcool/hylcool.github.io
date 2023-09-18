---
title: "Data-Juicer: A One-Stop Data Processing System for Large Language Models"
collection: publications
permalink: /publication/2023-09-05-data-juicer
date: 2023-09-05
venue: 'arXiv'
citation: 'Chen, Daoyuan*, <ins>Yilun Huang*</ins>, Zhijian Ma*, Hesen Chen*, Xuchen Pan, Ce Ge, Dawei Gao et al. "Data-Juicer: A One-Stop Data Processing System for Large Language Models." arXiv preprint arXiv:2309.02033 (2023).'
paperurl: 'https://arxiv.org/abs/2309.02033'
code: 'https://github.com/alibaba/data-juicer'
---

<strong>Abstraction</strong>: The immense evolution in Large Language Models (LLMs) has underscored the importance of massive, diverse, and high-quality data. Despite this, existing open-source tools for LLM data processing remain limited and mostly tailored to specific datasets, with an emphasis on the reproducibility of released data over adaptability and usability, inhibiting potential applications. In response, we propose a one-stop, powerful yet flexible and user-friendly LLM data processing system named Data-Juicer. Our system offers over 50 built-in versatile operators and pluggable tools, which synergize modularity, composability, and extensibility dedicated to diverse LLM data processing needs. By incorporating visualized and automatic evaluation capabilities, Data-Juicer enables a timely feedback loop to accelerate data processing and gain data insights. To enhance usability, Data-Juicer provides out-of-the-box components for users with various backgrounds, and fruitful data recipes for LLM pre-training and post-tuning usages. Further, we employ multi-facet system optimization and seamlessly integrate Data-Juicer with both LLM and distributed computing ecosystems, to enable efficient and scalable data processing. Empirical validation of the generated data recipes reveals considerable improvements in LLaMA performance for various pre-training and post-tuning cases, demonstrating up to 7.45% relative improvement of averaged score across 16 LLM benchmarks and 16.25% higher win rate using pair-wise GPT-4 evaluation. The system's efficiency and scalability are also validated, supported by up to 88.7% reduction in single-machine processing time, 77.1% and 73.1% less memory and CPU usage respectively, and 7.91x processing acceleration when utilizing distributed computing ecosystems. Our system, data recipes, and multiple tutorial demos are released, calling for broader research centered on LLM data.

- Download paper [here](https://arxiv.org/abs/2309.02033)
- Code is available [here](https://github.com/alibaba/data-juicer)

- Overview of Data-Juicer:
![Overview of Data-Juicer](https://img.alicdn.com/imgextra/i4/O1CN01uvLL0T1VIaX28dMLg_!!6000000002630-2-tps-2509-1192.png)

- Data processing feedback of Data-Juicer:
![Data processing feedback of Data-Juicer](https://img.alicdn.com/imgextra/i1/O1CN011E99C01ndLZ55iCUS_!!6000000005112-0-tps-2701-1050.jpg)