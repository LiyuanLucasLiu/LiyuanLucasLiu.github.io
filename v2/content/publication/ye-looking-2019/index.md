---
title: "Looking Beyond Label Noise: Shifted Label Distribution Matters in Distantly Supervised Relation Extraction"
date: 2019-11-01
authors: ["Qinyuan Ye*", "Liyuan Liu*", "Maosen Zhang", "Xiang Ren"]
publication_types: ["1"]
abstract: "In recent years there is a surge of interest in applying distant supervision (DS) to automatically generate training data for relation extraction (RE). In this paper, we study the problem what limits the performance of DS-trained neural models, conduct thorough analyses, and identify a factor that can influence the performance greatly, shifted label distribution. Specifically, we found this problem commonly exists in real-world DS datasets, and without special handing, typical DS-RE models cannot automatically adapt to this shift, thus achieving deteriorated performance. To further validate our intuition, we develop a simple yet effective adaptation method for DS-trained models, bias adjustment, which updates models learned over the source domain (i.e., DS training set) with a label distribution estimated on the target domain (i.e., test set). Experiments demonstrate that bias adjustment achieves consistent performance gains on DS-trained models, especially on neural models, with an up to 23% relative F1 improvement, which verifies our assumptions. Our code and data can be found at https://github.com/INK-USC/shifted-label-distribution."
featured: false
publication: "*the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP 2019)*"
tags: ["Shifted Label Distribution", "Relation Extraction", "Distant Supervision", "Selected"]
url_pdf: "https://www.aclweb.org/anthology/D19-1397.pdf"
url_code: "https://github.com/INK-USC/shifted-label-distribution"
links: 
- name: Blog (3rd-Party)
  url: "https://github.com/BrambleXu/knowledge-graph-learning/issues/184"
---

