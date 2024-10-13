---
title: "Visualizing the Impact of Graph Perturbations"
description: "A visual analytics tool for reasoning about the impact of graph perturbations."
date: "2021-05-01"
demoURL: "https://graph-auditing-demo.vercel.app"
repoURL: "https://github.com/trevortylerlee/graph-auditing"
---

![Graph Auditing](/graph-auditing.png)

## Abstract

Graph mining plays a pivotal role across a number of disciplines, and a variety of algorithms have been developed to answer who/what type questions. For example, what items shall we recommend to a given user on an e-commerce platform? The answers to such questions are typically returned in the form of a ranked list, and graph-based ranking methods are widely used in industrial information retrieval settings. However, these ranking algorithms have a variety of sensitivities, and even small changes in rank can lead to vast reductions in product sales and page hits. As such, there is a need for tools and methods that can help model developers and analysts explore the sensitivities of graph ranking algorithms with respect to perturbations within the graph structure. In this paper, we present a visual analytics framework for explaining and exploring the sensitivity of any graph-based ranking algorithm by performing perturbation-based what-if analysis. We demonstrate our framework through three case studies inspecting the sensitivity of two classic graph-based ranking algorithms (PageRank and HITS) as applied to rankings in political news media and social networks.
