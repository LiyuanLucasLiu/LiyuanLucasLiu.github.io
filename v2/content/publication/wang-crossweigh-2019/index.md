---
title: "CrossWeigh: Training Named Entity Tagger from Imperfect Annotations"
date: 2019-11-01
authors: ["Zihan Wang*", "Jingbo Shang*", "Liyuan Liu*", "Lihao Lu", "Jiacheng Liu", "Jiawei Han"]
publication_types: ["1"]
abstract: "Everyone makes mistakes. So do human annotators when curating labels for named entity recognition (NER). Such label mistakes might hurt model training and interfere model comparison. In this study, we dive deep into one of the widely-adopted NER benchmark datasets, CoNLL03 NER. We are able to identify label mistakes in about 5.38% test sentences, which is a significant ratio considering that the state-of-the-art test F1 score is already around 93%. Therefore, we manually correct these label mistakes and form a cleaner test set. Our re-evaluation of popular models on this corrected test set leads to more accurate assessments, compared to those on the original test set. More importantly, we propose a simple yet effective framework, CrossWeigh, to handle label mistakes during NER model training. Specifically, it partitions the training data into several folds and train independent NER models to identify potential mistakes in each fold. Then it adjusts the weights of training data accordingly to train the final NER model. Extensive experiments demonstrate significant improvements of plugging various NER models into our proposed framework on three datasets. All implementations and corrected test set are available at our Github repo: https://github.com/ZihanWangKi/CrossWeigh."
featured: false
publication: "*the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP 2019)*"
tags: ["NER", "Label Mistake", "CoNLL03", "Selected", "Evaluation"]
url_pdf: "http://arxiv.org/pdf/1909.01441"
url_code: "https://github.com/ZihanWangKi/CrossWeigh"
links:
- name: Blog (3rd-Party)
  url: "https://towardsdatascience.com/annotator-bias-and-incomplete-annotations-for-named-entity-recognition-ner-84819af730"
- name: Video (3rd-Party)
  url: "https://www.bilibili.com/video/av76582167?from=search&seid=12011291120542902679"
---

