---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Multi-Intent Combination In Session-Based Recommendation Systems using LLMs
Advisors:  Dr. Yashoteja Prabhu,Dr. Amit Sharma, Dr. Manik Varma
- Identified three properties of GPT-4 based models in session-based recommendations settings: (i) find diverse relevant intents in session history, (ii) combine intents to find sequential recommendations, and (iii) world knowledge.
- Performed task-specific distillation using Low-Rank Adaptation of desired properties to increase inference speedup by ∼ 100 times by using smaller LLMs (1-7 billion parameters).
- High alignment between GPT-4 and task-specific distilled model on relevance, and diversity indicated by high cosine similarity between recommendations.

* * *

## Efficient Modelling For Cross-Encoder based Ranking Systems 
Advisors: Dr. Manik Varma
- Highlighted the inconsistency in current research of pair-wise query-item ranking systems and the real-world need to rank thousands of items for a given query.
- Proposed a novel and efficient paradigm of jointly scoring multiple items per query in one shot.
- Proposed algorithm led to 10×faster scoring than pairwise, with negligible drop in performance (within 1% of pair-wise cross-encoders). Under review at the ACM Web Conference 2024, and would be submitted for a US patent.


* * * 
## Denoising Hard Negatives using LLMs For Robust Representation Learning in Dense Retrieval 
Advisors: Dr. Manik Varma
- Identified the problem of high probability of hard negatives being false negatives in large-scale dense retrieval datasets.
- Proposed a novel scoring method to use Large Language Models like GPT-4 as a large-scale oracle to denoise hard negatives, which led to 30×increase in the throughput and significantly reduced API costs.
- Led to ∼0.6% absolute gain in clicks and other system-specific metrics on a large scale search engine during online A-B tests in English markets.

* * * 

## Query Auto-Complete (QAC) using Extreme Classification and Statistical Language Models 
Advisors: Dr. Yashoteja Prabhu, Dr. Manish Gupta, Dr. Manik Varma
- Proposed an imporvement over XC based QAC solutions by replacing suffix classifiers with small localized statistical language models to improve performance on head and torso queries.
- Utilized Kneser-Ney smoothing and a weighted finite state transducer (FST) to represent the n-gram language model over queries containing a cluster of suffixes to better memorize frequency based patterns in the data.
- This framework led to a 6 point increase in Success Rate @ 10 and 5 point increase in Mean Reciprocal Rank @ 10 on publicly available dataset over XC baseline.

* * *

## Query Auto-Complete (QAC) using Extreme Classification 
Advisors: Dr. Yashoteja Prabhu, Dr. Manish Gupta, Dr. Manik Varma
- Proposed a novel reformulation of QAC as an XC task, which led to significant improvement over NLG based solutions.
- To overcome the sparsity of training data based on clicks, added popularity weighted augmentation to vanilla XC loss to improve performance on tail and torso prefixes.
- Our framework achieved SOTA performance while compared to NLG models with an improvement of ∼10% on Mean Reciprocal Rank@10 and ∼15% on Success rate@10 on publicly available dataset.
- When deployed in en-markets, our method led to 1% gain in CTR (Click Through Rate) and a 4% gain in the average number of suggestions in production. In non-en multilingual markets, it gave a relative increase of 0.8% increase in CTR and a 3% gain in suggestion density in production.
- On Bing AI Chat Platform let an 8% increase in KSPQ (keystrokes saved per query), and 6% increase in acceptance rate for long queries


* * *

## Graph Based Multimodal Fake News Detection [[code]](https://github.com/mudit-dhawan/GAME-ON/)
Advisors: Prof. Ponnurangam Kumaraguru, Prof. Rajesh Sharma
- Proposed a novel graph framework that allows for granular interactions across (inter)- and within (intra)- modalities to fuse them early in the framework, decreasing information loss.
- Our Graph-based approach using scenic graph for images and transformer representations for text nodes outperform by ∼11% sota models on publicly available dataset, with ∼91% fewer parameters than the best comparable baseline.

* * * 

## Legal AI [[code]](https://github.com/mudit-dhawan/HLDC)
Advisor: Prof. Ponnurangam Kumaraguru, Prof. Ashutosh Modi, Prof. Arnab Bhattacharya
- Helped release a corpus of ∼900K legal documents in Hindi.
- Proposed Bail prediction as a Multi-Task Learning Framework which used an auxiliary extractive summarization task to improve the main task’s performance.
- In training a model for predicting bail for a new district (previously unseen district during training), a Multi-Task end-to-end trained model achieved 78% Accuracy and 77% F1 score, which was around 2% more than our other competitive baselines.

* * *

## Hate-Speech Based User Characterization 
Advisors: Prof. Ponnurangam Kumaraguru and Prof. Srijan Kumar
- Analyze sentimentally charged tweets to study the effect of the network on the user’s posting activity.
- Studying the influence and susceptibility of a user based on their online neighborhood and how this network can be leveraged to determine the magnitude (or impact) of potential spreaders of hate or counter-hate on online social media platforms.

* * *

## Multimodal Fake News Detection [[code]](https://github.com/mudit-dhawan/FND) [[thesis]](https://drive.google.com/file/d/1-2MS3Sz4P8XnbP-mpAJrsDp8-wCS4m_-/view?usp=sharing) 
Advisors: Prof. Ponnurangam Kumaraguru, Prof. Rajiv Ratn Shah
- We proposed an inter-modality discordance based fake news detection framework based on the hypothesis that fabrication of either modality will lead to dissonance between the modalities.
- First ones to leverage information from different components of the news article (i.e., headline, body, and multiple images) for multimodal fake news detection.
- Conducted extensive experiments on the real-world datasets to show that our approach outperforms the state-of-the-art by an average F1-score of 6.3%.
- Released code to previous Multimodal Fake News detection frameworks to make previous state-of-the-art approaches in the field more accessible [[code]](https://github.com/mudit-dhawan/Multimodal-Fake-News-Detection-Systems)

* * *

## Language Model for Code-Mix Data [[code]](https://github.com/mudit-dhawan/Probing-LLMs-Code-Mix)
Advisor: Prof. Ponnurangam Kumaraguru
- Proposed changes in the sampling strategy and the Masked Language Modelling (MLM) Task and trained a modified XLM (Cross-Lingual  Language Model) from scratch on English-Hindi code-mixed data collected from social media.
- Weighted sampling strategy led to 15 point decrease in perplexity score on an online social media Hindi-English code mix data, and 2% increase in F1-score on the downstream POS-Tagging task on LINCE Dataset.

* * *

## Content Driven User Identity Linkage [[code]](https://github.com/mudit-dhawan/LinkingProfiles)
Advisor: Prof. Ponnurangam Kumaraguru
- Aimed at classifying whether different profiles on Social-Media-Platforms, belong to the same person or not.
- Created a heterogeneous graph-embedding with user-nodes and content-nodes based on NERTagging, Image-Captioning, and textual-stylometric techniques on the posted user-content

* * *

## Digital Image Processing Concepts From Scratch [[code]](https://github.com/mudit-dhawan/Digital-Image-Processing)
- **Keywords**: NumPy, SciPy, Scikit-Image, Scikit-Learn, Python
- Wrote code from scratch for Geomteric Transformation, Bi-Linear Interpolation, Histogram macthing and equalization, Constrained Least Squares Filtering, and many more.

* * *

## Computer Vision Concepts From Scratch [[code]](https://github.com/mudit-dhawan/Computer-Vision)
- **Keywords**: NumPy, SciPy, Scikit-Image, Scikit-Learn, OpenCV, PyTorch, Python
- Wrote code from scratch using no direct built-in function for 2D Convolution for Edge detection, Spatial Pyramid Pooling, Semantic segmentation, Circular Bounding Boxes, Super-pixel saliency, Interactive saliency, Otsu-Algorithm, Background subtraction from video, and many more.

* * *
## Machine Learning Concepts From Scratch [[code]](https://github.com/mudit-dhawan/Python-Maching-Learning-from-Scratch)
- **Keywords**: NumPy, SciPy, Scikit-Learn, PyTorch, Python
- Wrote code from scratch using just NumPy, SciPy for N-layer Neural Network, Grid Search, Bootstrapping, Gaussian Naive Bayes, Linear Regression and Logistic Regression. Experimented with PyTorch and wrote code for transfer learning using AlexNet architecture and experimented with different activation functions.

* * *
## Anomaly detection in building energy consumption [[code]](https://github.com/mudit-dhawan/AnomalyDetection_BuildingEnergy)
- **Keywords**: Seq2Seq models, Generative Adversarial Networks, Tensorflow, Python
- Trained a deep-learning based building load-line prediction/ anomaly detection model. Used data from Smart Buildings equipped with meters and sensors which are periodically collecting time-series data (ASHRAE Dataset – Kaggle).

* * *
## EEG Based Emotion Classification [[code]](https://github.com/mudit-dhawan/EEG)
- **Keywords**: CNN and LSTM based Architectures, Python, Tensorflow, MATLAB, Signal Processing
- Human emotion identification, classification, and analysis of EEG signals to various stimuli.

* * *
## Reddit Flair Detection NLP Based Web Application [[code]](https://github.com/mudit-dhawan/RedditFlairDetection)
- **Keywords**: TF-IDF Vectorization, Ensemble Techniques, MongoDB, Heroku, Flask, pushift.io, gensim
- Built a NLP based system that given a link, can detect the flair (category) of a Reddit post.

* * *