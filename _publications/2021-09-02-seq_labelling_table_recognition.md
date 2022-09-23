---
title: "Rethinking table structure recognition using sequence labeling methods"
collection: publications
permalink: /publication/2021-09-05-seq_labelling_table_recognition
date: 2021-09-02
venue: 'International Conference on Document Analysis and Recognition'
citation: 'Li, Yibo, <ins>Yilun Huang</ins>, Ziyi Zhu, Lemeng Pan, Yongshuai Huang, Lin Du, Zhi Tang, and Liangcai Gao. "Rethinking table structure recognition using sequence labeling methods." In International Conference on Document Analysis and Recognition, pp. 541-553. Springer, Cham, 2021.'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-86331-9_35'
code: 'https://www.github.com/L597383845/row-col-table-recognition'
---

<strong>Abstraction</strong>: Table structure recognition is an important task in document analysis and attracts the attention of many researchers. However, due to the diversity of table types and the complexity of table structure, the performances of table structure recognition methods are still not well enough in practice. Row and column separators play a significant role in the two-stage table structure recognition and a better row and column separator segmentation result can improve the final recognition results. Therefore, in this paper, we present a novel deep learning model to detect row and column separators. This model contains a convolution encoder and two parallel row and column decoders. The encoder can extract the visual features by using convolution blocks; the decoder formulates the feature map as a sequence and uses a sequence labeling model, bidirectional long short-term memory networks (BiLSTM) to detect row and column separators. Experiments have been conducted on PubTabNet and the model is benchmarked on several available datasets, including PubTabNet, UNLV ICDAR13, ICDAR19. The results show that our model has a state-of-the-art performance than other strong models. In addition, our model shows a better generalization ability. The code is available on [this site](https://www.github.com/L597383845/row-col-table-recognition).

- Download paper [here](https://link.springer.com/chapter/10.1007/978-3-030-86331-9_35)
- Code is available [here](https://www.github.com/L597383845/row-col-table-recognition)