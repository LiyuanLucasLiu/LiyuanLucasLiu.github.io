---
title: "Empower Sequence Labeling with Task-Aware Neural Language Model"
date: 2018-02-02
authors: ["Liyuan Liu", "Jingbo Shang", "Xiang Ren", "Frank Fangzheng Xu", "Huan Gui", "Jian Peng", "Jiawei Han"]
publication_types: ["1"]
abstract: "Linguistic sequence labeling is a general approach encompassing a variety of problems, such as part-of-speech tagging and named entity recognition. Recent advances in neural networks (NNs) make it possible to build reliable models without handcrafted features. However, in many cases, it is hard to obtain sufficient annotations to train these models. In this study, we develop a neural framework to extract knowledge from raw texts and empower the sequence labeling task. Besides word-level knowledge contained in pre-trained word embeddings, character-aware neural language models are incorporated to extract character-level knowledge. Transfer learning techniques are further adopted to mediate different components and guide the language model towards the key knowledge. Comparing to previous methods, these task-specific knowledge allows us to adopt a more concise model and conduct more efficient training. Different from most transfer learning methods, the proposed framework does not rely on any additional supervision. It extracts knowledge from self-contained order information of training sequences. Extensive experiments on benchmark datasets demonstrate the effectiveness of leveraging character-level knowledge and the efficiency of co-training. For example, on the CoNLL03 NER task, model training completes in about 6 hours on a single GPU, reaching F_1 score of 91.71+/-0.10 without using any extra annotations."
featured: false
publication: "*Proceedings of the Thirty-Second AAAI Conference on Artificial Intelligence (AAAI 2018)*"
tags: ["NER", "Language Model", "Character-level",  "Sequence Labeling", "Selected"]
url_pdf: "https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17123"
links:
 - name: "Code (new)"
   url: "https://github.com/LiyuanLucasLiu/Vanilla_NER"
 - name: "Code (old)"
   url: "https://github.com/LiyuanLucasLiu/LM-LSTM-CRF"
 - name: "Blog"
   url: "https://liyuanlucasliu.github.io/LM-LSTM-CRF/"

---

