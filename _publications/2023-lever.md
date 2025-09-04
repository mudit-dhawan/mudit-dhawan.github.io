---
title: "Enhancing Tail Performance in Extreme Classifiers by Label Variance Reduction"
collection: publications
tag: conference
category: 'conference'
permalink: /publication/2023-lever
# date: 2021-12-10
venue: 'Accepted at at International Conference on Learning Representations 2024 (ICLR)'
# paperurl: 
link: 'https://openreview.net/pdf?id=6ARlSgun7J'
# github: ''
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
*Authors:* Anirudh Buvanesh, Rahul Chand, Jatin Prakash, Bhawna Paliwal, **Mudit Dhawan**, Neelabh Madan, Deepesh Hada, Vidit Jain, Sonu Mehta, Yashoteja Prabhu, Manish Gupta, Ramachandran Ramjee, Manik Varma <br> 
*Keywords:* Extreme Classification, Supervised Representation Learning, Label Smoothing <br>
[pdf](https://openreview.net/pdf?id=6ARlSgun7J)
<details close> 
    <summary> 
      Abstract
    </summary>
      Extreme Classification (XC) architectures, which utilize a massive one-vs-all classifier layer at the output, have demonstrated remarkable performance on problems with large label sets. Nonetheless, these have also been observed to falter on tail labels with few representative samples. This phenomenon has been attributed to factors such as classifier over-fitting and missing label bias, and solutions involving regularization and loss re-calibration have been developed. This paper explores the impact of label variance, a previously unexamined factor, on the tail performance in extreme classifiers. Label variance refers to the imprecision introduced in the ground truth when sampling it from a complex underlying distribution - a common phenomenon in most XC datasets. This compromises the quality of trained models, with a pronounced impact on the classifiers for infrequently sampled tail labels. This paper presents a method to systematically reduce label variance in XC by effectively utilizing the capabilities of an additional, tail-robust teacher model. It proposes a principled knowledge distillation framework, \model, which enhances tail performance in extreme classifiers, with formal guarantees on generalization. Finally, we introduce an effective instantiation of this framework that employs a specialized Siamese teacher model. This model excels in tail accuracy and significantly enhances the quality of student one-vs-all classifiers. Comprehensive experiments are conducted on a diverse set of XC datasets which demonstrate that \model can enhance tail performance by around 5% and 6% points in PSP and Coverage metrics respectively when integrated with leading extreme classifiers. Moreover, when added to the top-performing Renée classifier, it establishes a new state-of-the-art. Extensive ablations and analysis substantiate the efficacy of our design choices. Code and datasets will be released for research purposes.
</details>
