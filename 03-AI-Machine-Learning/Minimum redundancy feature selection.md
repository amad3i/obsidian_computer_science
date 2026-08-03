---
title: "Minimum redundancy feature selection"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Minimum_redundancy_feature_selection"
wikipedia_categories: ["Machine learning algorithms"]
related: ["[[Actor-critic algorithm]]", "[[AdaBoost]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Augmented Analytics]]", "[[Backpropagation]]", "[[Bootstrap aggregating]]", "[[CN2 algorithm]]", "[[Co-training]]", "[[Constructing skill trees]]"]
---

# Minimum redundancy feature selection

Minimum redundancy feature selection is an algorithm frequently used in a method to accurately identify characteristics of genes and phenotypes and narrow down their relevance and is usually described in its pairing with relevant feature selection as Minimum Redundancy Maximum Relevance (mRMR). This method was first proposed in 2003 by Hanchuan Peng and Chris Ding, followed by a theoretical formulation based on mutual information, along with the first definition of multivariate mutual information, published in IEEE Trans. Pattern Analysis and Machine Intelligence in 2005. 
Feature selection, one of the basic problems in pattern recognition and machine learning, identifies subsets of data that are relevant to the parameters used and is normally called Maximum Relevance. These subsets often contain material which is relevant but redundant and mRMR attempts to address this problem by removing those redundant subsets. mRMR has a variety of applications in many areas such as cancer diagnosis and speech recognition.
Features can be selected in many different ways. One scheme is to select features that correlate strongest to the classification variable. This has been called maximum-relevance selection. Many heuristic algorithms can be used, such as the sequential forward, backward, or floating selections.
On the other hand, features can be selected to be mutually far away from each other while still having "high" correlation to the classification variable. This scheme, termed as Minimum Redundancy Maximum Relevance (mRMR) selection has been found to be more powerful than the maximum relevance selection.
As a special case, the "correlation" can be replaced by the statistical dependency between variables. Mutual information can be used to quantify the dependency. In this case, it is shown that mRMR is an approximation to maximizing the dependency between the joint distribution of the selected features and the classification variable.
Studies have tried different measures for redundancy and relevance measures. A recent study compared several measures within the context of biomedical images.

## Related

- [[Actor-critic algorithm]]
- [[AdaBoost]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Augmented Analytics]]
- [[Backpropagation]]
- [[Bootstrap aggregating]]
- [[CN2 algorithm]]
- [[Co-training]]
- [[Constructing skill trees]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Minimum_redundancy_feature_selection