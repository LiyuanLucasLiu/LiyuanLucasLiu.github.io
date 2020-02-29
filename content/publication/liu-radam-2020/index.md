---
title: "On the Variance of the Adaptive Learning Rate and Beyond"
date: 2020-02-01
authors: ["Liyuan Liu", "Haoming Jiang", "Pengcheng He", "Weizhu Chen", "Xiaodong Liu", "Jianfeng Gao", "Jiawei Han"]
publication_types: ["1"]
abstract: "The learning rate warmup heuristic achieves remarkable success in stabilizing training, accelerating convergence and improving generalization for adaptive stochastic optimization algorithms like RMSprop and Adam. Here, we study its mechanism in details. Pursuing the theory behind warmup, we identify a problem of the adaptive learning rate (i.e., it has problematically large variance in the early stage), suggest warmup works as a variance reduction technique, and provide both empirical and theoretical evidence to verify our hypothesis. We further propose RAdam, a new variant of Adam, by introducing a term to rectify the variance of the adaptive learning rate. Extensive experimental results on image classification, language modeling, and neural machine translation verify our intuition and demonstrate the effectiveness and robustness of our proposed method. All implementations are available at: https://github.com/LiyuanLucasLiu/RAdam."
featured: false
publication: "*the Eighth International Conference on Learning Representations (ICLR 2020)*"
tags: ["Warmup", "Optimization", "Selected"]
url_pdf: "http://arxiv.org/pdf/1908.03265"
url_code: "https://github.com/LiyuanLucasLiu/RAdam"

---

