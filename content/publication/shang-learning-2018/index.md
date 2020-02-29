---
title: "Learning Named Entity Tagger using Domain-Specific Dictionary"
date: 2018-10-01
authors: ["Jingbo Shang*", "Liyuan Liu*", "Xiaotao Gu", "Xiang Ren", "Teng Ren", "Jiawei Han"]
publication_types: ["1"]
abstract: "Recent advances in deep neural models allow us to build reliable named entity recognition (NER) systems without handcrafting features. However, such methods require large amounts of manually-labeled training data. There have been efforts on replacing human annotations with distant supervision (in conjunction with external dictionaries), but the generated noisy labels pose significant challenges on learning effective neural models. Here we propose two neural models to suit noisy distant supervision from the dictionary. First, under the traditional sequence labeling framework, we propose a revised fuzzy CRF layer to handle tokens with multiple possible labels. After identifying the nature of noisy labels in distant supervision, we go beyond the traditional framework and propose a novel, more effective neural model AutoNER with a new Tie or Break scheme. In addition, we discuss how to refine distant supervision for better NER performance. Extensive experiments on three benchmark datasets demonstrate that AutoNER achieves the best performance when only using dictionaries with no additional human effort, and delivers competitive results with state-of-the-art supervised benchmarks."
featured: false
publication: "*the 2018 Conference on Empirical Methods in Natural Language Processing (EMNLP 2018)*"
tags: ["NER", "Distant Supervision", "Selected"]
url_pdf: "https://arxiv.org/pdf/1809.03599"
url_code: "https://github.com/shangjingbo1226/AutoNER"
links:
- name: Blog
  url: "https://shangjingbo1226.github.io/AutoNER/"
- name: Blog (Chinese)
  url: "https://www.zhihu.com/question/294189189/answer/494208998"
- name: Doc
  url: "https://autoner.readthedocs.io/en/latest/?badge=latest"
---

