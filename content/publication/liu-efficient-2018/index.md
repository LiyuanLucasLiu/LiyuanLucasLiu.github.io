---
title: "Efficient Contextualized Representation: Language Model Pruning for Sequence Labeling"
date: 2018-10-01
authors: ["Liyuan Liu", "Xiang Ren", "Jingbo Shang", "Jian Peng", "Jiawei Han"]
publication_types: ["1"]
abstract: "Many efforts have been made to facilitate natural language processing tasks with pre-trained language models (PTLM), and brought significant improvements to various applications. To fully leverage the nearly unlimited corpora and capture linguistic information of multifarious levels, large-size LMs are required; but for a specific task, only parts of these information are useful. Such large models, even in the inference stage, lead to overwhelming computation workloads, thus making them too time-consuming for real-world applications. For a specific task, we aim to keep useful information while compressing bulky PTLM. Since layers of different depths keep different information, we can conduct the compression via layer selection. By introducing the dense connectivity, we can detach any layers without eliminating others, and stretch shallow and wide LMs to be deep and narrow. Moreover, PTLM are trained with layer-wise dropouts for better robustness, and are pruned by a sparse regularization which is customized for our goal. Experiments on benchmarks demonstrate the effectiveness of our proposed method."
featured: false
publication: "*the 2018 Conference on Empirical Methods in Natural Language Processing (EMNLP 2018)*"
tags: ["NER", "Language Model", "Sequence Labeling", "Pruning", "Selected"]
url_pdf: "http://arxiv.org/abs/1804.07827"
url_code: "https://github.com/LiyuanLucasLiu/LD-Net"
links:
- name: "Blog"
  url: "https://liyuanlucasliu.github.io/LD-Net/"
- name: "Doc"
  url: "https://ld-net.readthedocs.io/en/latest/?badge=latest"
---

