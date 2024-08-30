---
title: "Feature Selection in High-dimensional Spaces Using Graph-Based Methods"
collection: publications
permalink: /publication/2020-08-paper-stat
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 11 Aug 2024
venue: 'arxiv'
paperurl: 'https://doi.org/10.48550/arXiv.2108.12682'
citation: 'arXiv:2108.12682 [stat.ME]'
---
High-dimensional feature selection is a central problem in a variety of application domains such as machine learning, 
image analysis, and genomics. In this paper, we propose graph-based tests as a useful basis for feature selection. 
We describe an algorithm for selecting informative features in high-dimensional data, 
where each observation comes from one of K different distributions. 
Our algorithm can be applied in a completely nonparametric setup without any distributional assumptions on the data, 
and it aims at outputting those features in the data, that contribute the most to the overall distributional variation. 
At the heart of our method is the recursive application of distribution-free graph-based tests on subsets of the feature set, 
located at different depths of a hierarchical clustering tree constructed from the data. 
Our algorithm recovers all truly contributing features with high probability, while ensuring optimal control on false-discovery. 
We show the superior performance of our method over other existing ones through synthetic data, 
and demonstrate the utility of this method on several real-life datasets from the domains of climate change and biology, 
wherein our algorithm is not only able to detect known features expected to be associated with the underlying process, 
but also discovers novel targets that can be subsequently studied.


[Download paper here](https://arxiv.org/abs/2108.12682#)

Recommended citation: arXiv:2108.12682 [stat.ME]
