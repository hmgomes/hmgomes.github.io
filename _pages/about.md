---
permalink: /
title: "Heitor Murilo Gomes"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Machine Learning Researcher and Data Scientist. 
As of 2022, I became a Senior Lecturer (Assistant Professor) in AI at the Victoria University of Wellington (VuW), New Zealand. 
Before joining VuW, I worked at the University of Waikato as a Senior Researcher and Co-Director of the AI Institute. 
My main research area is on Adaptive Machine Learning, which includes machine learning for data streams and, more recently, online continual learning. 
For collaborations and inquires about PhD positions reach out through my institutional email. 
<!-- Previously, I am an associate researcher at the [AI Institute](https://ai.waikato.ac.nz) at the University of Waikato.  -->

(NEW) CapyMOA
=====

As of May 02, 2024 we launched a novel machine learning library for data streams! See more information about it below. 
We recently presented a tutorial on PAKDD 2024 (Taipei) about it, and there many more scheduled for 2024 (IJCAI, KDD, ECML, and more). 

* Website: [https://capymoa.org/](https://capymoa.org/)
* CapyMOA Github: [https://github.com/adaptive-machine-learning/CapyMOA](https://github.com/adaptive-machine-learning/CapyMOA)
* We had plenty of tutorials in 2024, including: PAKDD (Taipei, Taiwan), IJCAI (Jeju, South Korea), KDD (Barcelona, Spain), ECML (Vilnius, Lithuania), KiwiPycon (Wellington, NZ) and ICONIP (Auckland, NZ). Material is available on the CapyMOA discord [here](https://discord.gg/spd2gQJGAb)

Selected Publications
======

### Leveraging Plasticity in Incremental Decision Trees
M Heyden, H M Gomes, E Fouché, B Pfahringer, K Böhm
European Conference on Machine Learning (ECML PKDD), 2024. [Access paper](https://link.springer.com/chapter/10.1007/978-3-031-70362-1_3)

PLASTIC is a novel incremental decision tree that yields better predictive performance than other recent algorithms, such as the canonical Extremely Fast Decision Tree (EFDT). 
PLASTIC restructures the otherwise pruned subtree. This is possible due to decision tree plasticity: one can alter a tree’s structure without affecting its predictions.


### Gradient boosted trees for evolving data streams
N Gunasekara, B Pfahringer, H M Gomes, A Bifet. 
Machine Learning, Springer, 2024. [Access paper](https://link.springer.com/article/10.1007/s10994-024-06517-y)

Streaming Gradient Boosted Trees (SGBT) is trained using weighted squared loss elicited in XGBoost. SGBT employs a tree replacement strategy that detects and recovers from drifts, thus enabling the ensemble to adapt without sacrificing the predictive performance.

### Machine learning (in) security: A stream of problems
F Ceschin, M Botacin, A Bifet, B Pfahringer, L S Oliveira, H M Gomes, A Gregio
ACM Digital Threats: Research and Practice, 2024
[Access paper](https://dl.acm.org/doi/pdf/10.1145/3617897)

We identify, detail, and discuss the main challenges in the correct application of Stream ML techniques to cybersecurity data. We evaluate how concept drift, evolution, delayed labels, and adversarial ML impact the existing solutions. 

### A Survey on Semi-Supervised Learning for Delayed Partially Labelled Data Streams
H M Gomes, M Grzenda, R Mello, J Read, M H L Nguyen, A Bifet. ACM Computing Surveys, 2022.
DOI: [https://doi.org/10.1145/3523055](https://doi.org/10.1145/3523055)

We organise methods that leverage unlabelled data in a semi-supervised setting for streaming data. We also discuss the delayed labelling issue, which impacts both fully supervised and semi-supervised methods.

### Streaming Random Patches for Evolving Data Stream Classification
H M Gomes, J Read, A Bifet. IEEE International Conference on Data Mining (ICDM), 2019. DOI: [https://doi.org/10.1109/ICDM.2019.00034](https://doi.org/10.1109/ICDM.2019.00034)

The Streaming Random Patches (SRP) algorithm outperforms the current state-of-the-art ensemble methods for evolving data stream classification. [Access Paper](https://www.researchgate.net/publication/338943432_Streaming_Random_Patches_for_Evolving_Data_Stream_Classification)

### Machine learning for streaming data: state of the art, challenges, and opportunities
H M Gomes, J Read, A Bifet, J P Barddal, J Gama. SIGKDD Explorations Newsletter, ACM , 2019. DOI: [https://doi.org/10.1145/3373464.3373470](https://doi.org/10.1145/3373464.3373470)
 
In this work, we focus on elucidating the connections among the current stateof-the-art on related fields; and clarifying open challenges in both academia and industry. [Access Paper](https://www.researchgate.net/publication/337581742_Machine_learning_for_streaming_data_state_of_the_art_challenges_and_opportunities)

### A Survey on Ensemble Learning for Data Stream Classification
H M Gomes, J P Barddal, F Enembreck, A Bifet. ACM Computing Surveys 50, 2, Article 23, 2017. DOI: [https://doi.org/10.1145/3054925](https://doi.org/10.1145/3054925)
 
This paper contains a comprehensive survey about ensemble learning for data streams.  [Access Paper](https://www.researchgate.net/publication/315698712_A_Survey_on_Ensemble_Learning_for_Data_Stream_Classification)

### Adaptive random forests for evolving data stream classiﬁcation
H M Gomes, A Bifet, J Read, ..., B Pfahringer, G Holmes, T Abdessalem. Machine Learning, Springer, 2017. DOI: [https://doi.org/10.1007/s10994-017-5642-8](https://doi.org/10.1007/s10994-017-5642-8)
 
This paper presents an efficent version of the classical Random Forests algorithm for evolving data streams, namely the Adaptive Random Forest (ARF) algorithm. [Access Paper](https://www.researchgate.net/publication/317579226_Adaptive_random_forests_for_evolving_data_stream_classification)

