---
title: EMNLP 2017 Report (draft)
layout: post
category: Report
tag: 
 - emnlp
 - 2017
 - report
 - conference
 - rehession
---

I would attend the EMNLP 2017 conference and present our Relation Extraction Paper (see below). Also I'm planning to write a EMNLP 2017 report later.

>Both human experts and public knowledge bases can provide (indirect, weak) supervision for information extraction (e.g., hand-crafted rules, distant supervision, etc.). How to leverage these heterogenous supervisions (on same set of instances) in a principled way? Our EMNLP 2017 paper with Liu Lucas Liyuan, Heng Ji, Jiawei Han formulates a joint objective to unify representation learning (on relation extraction) and truth finding (on labels).  
>Project page: https://liyuanlucasliu.github.io/ReHession/  
>Paper: https://arxiv.org/pdf/1707.00166.pdf  
>Github: https://github.com/LiyuanLucasLiu/ReHession

Now let's quickly go-through some interesting papers of this EMNLP conference.

### RotatedWord Vector Representations and their Interpretability
Basic Idea: rotate embedding vectors into a new space, and improve the interpretability
Rotation is conducted by matrix rotation, and trained to encourage the sparsity of vectors.
Interesting thing is the objective function they used is not l1 norm, but another techniques (called the row and the column complexity of the matrix).
The author says the l1 norm is used in a previous study for similar scenario, but they have not tried it here

### Learning Chinese Word Representations From Glyphs Of Characters.
Basic Idea: treat Chinese character as image and use CNN to extract features. 
Not like other languages, ChineseWord has the hint of its semantic meaning on the way it looks.
This method proposed to used autoencoder/decoder framework to train the CNN, and add its representation to word embedding and char embedding.
The case study is quite cool, but the improvement is not very significant.
Besides, the author did not compare to embedding of higher dimension, which i guess would be not better or even worse.
Related Work: Learning Character-level Compositionality with Visual Features

### Ngram2vec: Learning Improved Word Representations from Ngram Co-occurrence Statistics
Basic Idea: incorporating phrase-manner information by means of Ngram.

### VecShare: A Framework for Sharing Word Representation Vectors
Basic Idea: a software, maybe should give some try

### Word Embeddings based on Fixed-Size Ordinally Forgetting Encoding
Basic Idea: encode recurrent information by means of encoding, interesting paper.
Cons: cannot capture long-term dependency
Pros: could be efficient

### Unsupervised Pretraining for Sequence to Sequence Learning
Basic Idea: use language model to pretrain autoencoder/decoder, and conducts the fine-tuning
Definitely would check this paper from Google Brain

### Incremental Skip-gram Model with Negative Sampling
Basic Idea: conduct sgns learning in an incremental manner. Not sure why original method cannot, maybe the author induced some bounds.

### Learning What's Easy: Fully Differentiable Neural Easy-First Taggers
Basic Idea: first generate a sketch, then conduct the decoding based on the order indicated by the sketch.
Seems complicated, asked the author about some details, but still have lots of things to check from the paper.
Related work: Easy-first pos tagging and dependency parsing with beam search (ACL 13)
Related work: Bidirectional inference with the easiest-first strategy for tagging sequence data (HLT-EMNLP 05)

### Segmentation-Free Word Embedding for Unsegmented Languages
Basic Idea: replacing chunking with n-gram

### Word-Context Character Embeddings for Chinese Word Segmentation
Basic Idea: use not only word but also labels as the context information. The resulting embeddings are used as pre-trained embedding layer.
It also leveraging automatically labeled large-scale data

### Cross-lingual, Character-Level Neural Morphological Tagging
Basic Idea: LSTMs not generalize well from limited data, so train a low-resource tagger jointly on related high-resource language. 
Techs: Language-specific softmax for tag prediction, predict not only the tag, but also the language (similar to GAN?)

### Evaluating Hierarchies of Verb Argument Structure with Hierarchical Clustering
Basic Idea: hierarchy obtained from Bayesian Hierarchical Clustering
related works (on EMNLP 2017):
* A Short Survey on Taxonomy Learning from Text Corpora: Issues, Resources and Recent Advances
* Grasping the Finer Point: A Supervised Similarity Network for Metaphor Detection
* Adapting Topic Models using Lexical Associations with Tree Priors

### Neural Machine Translation Leveraging Phrase-based Models in a Hybird Search
Basic Idea: Beam search on two buckets, on corresponding word, the other corresponding to phrases

### Relation Extraction
* Adversarial Training for Relation Extraction
	using adversarial training to improve the ability to generalize, similar to dropout, but more intelligent
* Global Normalization of Convolutional Neural Networks for Joint Entity and Relation Classification
* Deep Residual Learning for Weakly-Supervised Relation Extraction
* Noise-Clustered Distant Supervision for Relation Extraction: A Nonparametric Bayesian Perspective 

### Inducing Semantic Micro-Clusters from Deep Multi-View Representation of Novels
Basic Idea: clustering from multi-view embedding

### Syllable-Aware Neural Language Model: A Failure to Beat Character-Aware Ones

### CROWD-IN-THE-LOOP: A Hybrid Approach for Annotating Semantic Roles
Basic Idea: Improvement over crowd-sourcing, which identify the difficulty of tasks, and decide to assigning to experts or crowd

### Reference-Aware Lanugage Models
Basic Idea: Leveraging Reference

### When to Finish? Optimal Beams Search for Neural Text Generation

### Steering Output Style and Topics in Neural Response Generation


