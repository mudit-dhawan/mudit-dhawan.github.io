---
title: "CROSS-JEM: Cross-encoder Joint Efficient Modeling for ranking in sponsored search"
collection: publications
tag: preprint
category: 'preprint'
permalink: /publication/2023-cross-jem
# date: 2021-12-10
venue: 'Under review at ACM The Web Conference 2024'
# paperurl: 
# link: ''
# github: ''
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
*Authors:* Bhawna Paliwal^, Deepak Saini^, **Mudit Dhawan^**, Jian Jiao, Manik Varma<br> 
*Keywords:* Recommendation Systems, Cross-Encoder Architecture, Efficient Machine Learning <br>
<details close> 
    <summary> 
      Abstract
    </summary>
      Large-scale search and recommendation systems like sponsored search are usually bifurcated into a selection and relevance stage for better efficiency. Candidate selection retrieves hundreds to thousands of items per query from diverse sources. These candidates are then ranked for relevance. Scoring query-item pairs is crucial for such large-scale applications to filter the candidates to a high-quality set. Transformer-based cross encoders are the de facto scoring approach but process query-item pairs separately, becoming infeasible for thousands of items per query. Due to such computational constraints, most industrial systems use simpler sparse models for online ranking despite reduced accuracy. We observe that previous works overlook the need to score multiple items jointly per query efficiently. In this work, we propose CROSS-JEM to score multiple items per query in one shot by exploiting redundancies in sequence modeling and token overlaps. By scoring items jointly, CROSS-JEM provides over 10x speedups over vanilla cross encoders with minimal accuracy drop. Our key contributions are: (i) highlighting the gap between real-world requirements of scoring thousands of items per query, and singular scoring limitations of current cross encoders; (ii) proposing CROSS-JEM for efficient joint scoring of multiple items per query; and (iii) demonstrating up to 10x faster scoring than cross encoders with under 1% accuracy drop on a large-scale sponsored search scoring task and also public benchmark. CROSS-JEM opens up new directions for the design of tailored early-attention-based ranking models that incorporate strict production constraints like item multiplicity and latency. It efficiently handles the real-world challenge of scoring multiple items per query in real time. We will release the CROSS-JEM code publicly upon paper acceptance.
</details>