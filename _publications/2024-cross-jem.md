---
title: "Accurate and Efficient Cross-encoders for Ranking"
collection: publications
tag: preprint
category: 'preprint'
permalink: /publication/2024-cross-jem
# date: 2021-12-10
venue: 'Under review at NeurIPS 2024'
# paperurl: 
# link: ''
# github: ''
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
*Authors:* Bhawna Paliwal^, Deepak Saini^, **Mudit Dhawan**, Siddarth Asokan, Nagarajan Natarajan, Surbhi Aggarwal, Pankaj Malhotra, Jian Jiao, Manik Varma <br> 
*Keywords:* Recommendation Systems, Cross-Encoder Architecture, Efficient Machine Learning <br>
<details close> 
    <summary> 
      Abstract
    </summary>
      Ranking a set of items based on their relevance to a given query is a core problem in search and recommendation pipelines. Transformer-based cross-encoders are state-of-the-art models for ranking tasks. These models process and assign a relevance score for each query-item pair separately, independent of other relevant items to be ranked. In this work, we identify a critical oversight in the cross-encoder ranking models, i.e., their inability to model multiple items jointly leads to sub-optimal ranking accuracy and high computational costs. In response, we propose Cross-encoders with Joint Efficient Modeling, referred to as CROSS-JEM. This new ranking approach allows the transformer-based architectures to rank multiple items for a given query together, maximizing parameter utilization. By leveraging redundancies and token overlaps in the joint ranking of multiple items and a novel training objective modeling ranking probabilities, CROSS-JEM achieves state-of-the-art accuracy and supports over 30x lower ranking latency than standard cross-encoders. Our contributions extend to three key aspects: (i) highlighting the disparity between ranking application's demand for scoring multiple (order of thousands) items per query and the limited capabilities of current cross encoders; (ii) introducing CROSS-JEM for efficient joint scoring of multiple items per query, and (iii) achieving state-of-the-art accuracy on standard public datasets as well as a proprietary dataset. CROSS-JEM opens up new directions for the design of tailored early-attention-based ranking models that incorporate strict production constraints such as item multiplicity and latency.
</details>
