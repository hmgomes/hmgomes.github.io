---
permalink: /
title: "Heitor Murilo Gomes"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<a href="https://www.nzaiolympiad.org/"><img src="/images/nzaio-logo.png" alt="New Zealand AI Olympiad" style="float: right; width: 110px; max-width: 30%; margin: 0.75em 0 1em 1.5em;"></a>

I am a Machine Learning Researcher and Data Scientist. Currently, I am a Senior Lecturer (Associate Professor) in AI at the Victoria University of Wellington (VuW), New Zealand. 
Before joining VuW, I worked at the University of Waikato as a Senior Researcher and Co-Director of the AI Institute. 
My main research area is on Adaptive Machine Learning, which includes machine learning for data streams and, more recently, online continual learning. 
I also founded and currently chair the [New Zealand Artificial Intelligence Olympiad](https://www.nzaiolympiad.org/), a non-profit organisation established in December 2025. 
For collaborations and inquiries about PhD positions reach out through my institutional email (heitor.gomes at vuw.ac.nz). 
<!-- Previously, I am an associate researcher at the [AI Institute](https://ai.waikato.ac.nz) at the University of Waikato.  -->

CapyMOA
=====

<a href="https://capymoa.org/"><img src="/images/capymoa-logo.png" alt="CapyMOA" style="float: right; width: 130px; max-width: 32%; margin: 0.5em 0 1em 1.5em;"></a>

I lead the development of [CapyMOA](https://capymoa.org/), a machine learning library tailored for data streams. CapyMOA features a Python API that leverages [MOA's](https://moa.cms.waikato.ac.nz/) efficient implementations, [PyTorch](https://pytorch.org/) for [Online Continual Learning](https://capymoa.org/api/modules/capymoa.ocl.html) and neural networks support, and scikit-learn for integration with classical incremental learning algorithms. 

* Website: [https://capymoa.org/](https://capymoa.org/)
* CapyMOA Github: [https://github.com/adaptive-machine-learning/CapyMOA](https://github.com/adaptive-machine-learning/CapyMOA)
* Discord: [join here](https://discord.gg/spd2gQJGAb)

Adaptive AI Lab
=====

<a href="https://ecs.wgtn.ac.nz/Groups/AdaptiveAI/"><img src="/images/adaptive-ai-lab-logo.png" alt="Adaptive AI Lab" style="float: left; width: 210px; max-width: 45%; margin: 0.25em 1.5em 0.75em 0;"></a>

I founded the [Adaptive AI Lab](https://ecs.wgtn.ac.nz/Groups/AdaptiveAI/) at Victoria University of Wellington. Our research covers adaptive machine learning, which includes learning from data streams and online continual learning; agents, both agentic AI for software engineering and traditional multi-agent systems; and applications of these methods, especially in cybersecurity.

Research Focus
======

### Learning from evolving data streams

Models that keep training on data whose distribution keeps moving, under strict time and memory budgets. Much of this work is on ensembles: [Adaptive Random Forests](https://doi.org/10.1007/s10994-017-5642-8) (Machine Learning, 2017) and [Streaming Random Patches](https://doi.org/10.1109/ICDM.2019.00034) (ICDM, 2019) remain the baselines the area builds on.

In practice labels rarely arrive on time, or at all. [SLEADE](https://ieeexplore.ieee.org/document/11313633) (IEEE TKDE, 2025) learns from sparsely labelled streams through disagreement, our [survey on semi-supervised learning for delayed partially labelled data streams](https://doi.org/10.1145/3523055) (ACM Computing Surveys, 2022) maps the problem space, and [delayed labelling evaluation](https://link.springer.com/article/10.1007/s10618-019-00654-y) (DAMI, 2019) addresses how to measure any of it fairly.

### Concept drift: detection, evaluation, simulation and engineering

Drift research has a measurement problem: detectors are compared on benchmarks whose drifts are neither realistic nor known. Our [framework for evaluating and benchmarking concept drift detection methods](https://arxiv.org/abs/2606.07789) (ACM SIGKDD, 2026) is an attempt to fix that, alongside work on simulating drift that behaves like the real thing (Discovery Sciences, 2026) and on detectors that work without ground truth, such as [STUDD](https://link.springer.com/article/10.1007/s10994-022-06188-7) (Machine Learning, 2022) and [RMIDDM](https://doi.org/10.1007/s10618-025-01155-x) (DAMI, 2025).

The engineering side matters as much as the research: [CapyMOA](https://capymoa.org/api/modules/capymoa.drift.html) brings together the largest collection of drift detectors available behind a modern Python API, so that comparing them is a matter of a few lines of code.

### Online continual learning

Neural networks that learn from a stream without replaying everything they have seen. We showed that [Kolmogorov-Arnold Networks still catastrophically forget](https://ojs.aaai.org/index.php/AAAI/article/view/33986), but differently from MLPs (AAAI, 2025), and that anomaly detection ideas can drive class-incremental learning in [SurpriseNet](https://doi.org/10.1145/3583780.3615236) (CIKM, 2023). Our [survey on online streaming continual learning](https://www.ijcai.org/proceedings/2023/0743.pdf) (IJCAI, 2023) sits at the intersection of continual and streaming learning. The methods are available in [CapyMOA's OCL module](https://capymoa.org/api/modules/capymoa.ocl.html).

I chaired the Streaming Continual Learning bridge program at AAAI 2026 in Singapore, which brought the streaming learning and continual learning communities together around the problems they share: adapting to non-stationary data, learning under strict resource limits, and evaluating models that never stop training. The programme website is [streamingcl.capymoa.org](https://streamingcl.capymoa.org/).

### Machine learning for security and applied domains

Much of this work is driven by domains where the data never stops arriving and the conditions keep changing. In security, [machine learning (in) security: a stream of problems](https://dl.acm.org/doi/pdf/10.1145/3617897) (ACM DTRAP, 2024) argues that malware detection is a streaming problem that the field keeps evaluating as a static one, a point we followed up on with [label delays in malware detection pipelines](https://www.sciencedirect.com/science/article/abs/pii/S0167404824004279) (Computers & Security, 2025). Elsewhere the same methods apply to energy and the environment: real-time energy pricing in New Zealand (PRICAI, 2024), edge machine learning for solar power forecasting (FiCloud, 2025), and the [TAIAO](https://taiao.ai/) environmental data science programme.

A full list is available on the [publications page](/publications/).
