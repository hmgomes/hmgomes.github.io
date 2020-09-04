---
title: "Machine learning for nonstationary streaming data using Structured Streaming and StreamDM"
collection: talks
type: "Talk"
permalink: /talks/2018-Strata-NY
venue: "Javits Center"
date: 2018-09-13
location: "New York, USA"
---

The main difference between batch machine learning implementations in Spark (MLlib and Spark ML) and StreamDM is that the latter focus on algorithms that can be trained and adapted incrementally. This can be a huge advantage in some domains as it enables automatically updating the learning models. StreamDM is currently under development by Huawei Noah’s Ark Lab and Télécom ParisTech.

There is a vast literature on the topic of addressing concept drift and learning from streaming data. Still, these methods can be complex to implement and integrate. Heitor Murilo Gomes and Albert Bifet explain how to use StreamDM to develop, apply, and evaluate learning models specially for nonstationary streams (i.e., those with concept drifts). Heitor and Albert also introduce a simple yet powerful methodology to address concept drifts using active strategies like combining ensemble models and drift detectors and reactive strategies and reactive strategies like forgetting mechanisms and periodical resets (windowed approaches).

[More information here](https://conferences.oreilly.com/strata/strata-ny-2018/public/schedule/detail/69412.html)

