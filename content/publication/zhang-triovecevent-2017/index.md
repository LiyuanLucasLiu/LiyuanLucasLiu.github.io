---
title: "TrioVecEvent: Embedding-based Online Local Event Detection in Geo-tagged Tweet Streams"
date: 2017-08-01
authors: ["Chao Zhang", "Liyuan Liu", "Dongming Lei", "Quan Yuan", "Honglei Zhuang", "Tim Hanratty", "Jiawei Han"]
publication_types: ["1"]
abstract: "Detecting local events (e.g., protest, disaster) at their onsets is an important task for a wide spectrum of applications, ranging from disaster control to crime monitoring and place recommendation. Recent years have witnessed growing interest in leveraging geo-tagged tweet streams for online local event detection. Nevertheless, the accuracies of existing methods still remain unsatisfactory for building reliable local event detection systems. We propose TRIOVECEVENT, a method that leverages multimodal embeddings to achieve accurate online local event detection. The effectiveness of TRIOVECEVENT is underpinned by its two-step detection scheme. First, it ensures a high coverage of the underlying local events by dividing the tweets in the query window into coherent geo-topic clusters. To generate quality geo-topic clusters, we capture short-text semantics by learning multimodal embeddings of the location, time, and text, and then perform online clustering with a novel Bayesian mixture model. Second, TRIOVECEVENT considers the geo-topic clusters as candidate events and extracts a set of features for classifying the candidates. Leveraging the multimodal embeddings as background knowledge, we introduce discriminative features that can well characterize local events, which enable pinpointing true local events from the candidate pool with a small amount of training data. We have used crowdsourcing to evaluate TRIOVECEVENT, and found that it improves the performance of the state-of-the-art method by a large margin."
featured: false
publication: "*the 23rd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD 2017)*"
tags: ["Social Media", "Clustering", "Event Detection", "Embedding"]
url_pdf: "files/zhang-triovecevent-2017.pdf"
---

