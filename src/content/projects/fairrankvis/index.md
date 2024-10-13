---
title: "FairRankVis: Visualizing Fairness in Ranking"
description: "A visual analytics tool for reasoning about fairness in ranking."
date: "2024-05-26"
demoURL: "https://astro-micro.vercel.app"
repoURL: "https://github.com/tiankaixie/fairrankvis"
---

![FairRankVis](/fairrankvis.png)

## Abstract

Graph mining is an essential component of recommender systems and search engines. Outputs of graph mining models typically provide a ranked list sorted by each item's relevance or utility. However, recent research has identified issues of algorithmic bias in such models, and new graph mining algorithms have been proposed to correct for bias. As such, algorithm developers need tools that can help them uncover potential biases in their models while also exploring the impacts of correcting for biases when employing fairness-aware algorithms. In this paper, we present FairRankVis, a visual analytics framework designed to enable the exploration of multi-class bias in graph mining algorithms. We support both group and individual fairness levels of comparison. Our framework is designed to enable model developers to compare multi-class fairness between algorithms (for example, comparing PageRank with a debiased PageRank algorithm) to assess the impacts of algorithmic debiasing with respect to group and individual fairness. We demonstrate our framework through two usage scenarios inspecting algorithmic fairness.
