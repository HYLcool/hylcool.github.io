---
title: "A YOLO-based table detection method"
collection: publications
permalink: /publication/2019-09-20-yolov3_table_detection
date: 2019-09-20
venue: '2019 International Conference on Document Analysis and Recognition (ICDAR)'
citation: '<ins>Huang, Yilun</ins>, Qinqin Yan, Yibo Li, Yifan Chen, Xiong Wang, Liangcai Gao, and Zhi Tang. "A YOLO-based table detection method." In 2019 International Conference on Document Analysis and Recognition (ICDAR), pp. 813-818. IEEE, 2019.'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8978047'
---

<strong>Abstraction</strong>: Due to various table layouts and styles, table detection is always a difficult task in the field of document analysis. Inspired by the great progress of deep learning based methods on object detection, in this paper, we present a YOLO-based method for this task. Considering the large difference between document objects and natural objects, we introduce some adaptive adjustments to YOLOv3, including an anchor optimization strategy and two post processing methods. For anchor optimization, we use k-means clustering to find anchors which are more suitable for tables rather than natural objects and make it easier for our model to find exact positions of tables. In post-processing process, the extra whitespaces and noisy page objects (e.g. page headers, page footers) are removed from the predicted results, so that our model can get more accurate table margins and higher IoU scores. The proposed method is evaluated on two datasets from ICDAR 2013 Table Competition and ICDAR 2017 Page Object Detection (POD) Competition and achieves state-of-the-art performance.

- Download paper [here](https://ieeexplore.ieee.org/abstract/document/8978047)