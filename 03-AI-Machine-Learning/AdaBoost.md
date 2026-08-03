---
title: "AdaBoost"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/AdaBoost"
wikipedia_categories: ["Classification algorithms", "Ensemble learning", "Machine learning algorithms"]
related: ["[[LogitBoost]]", "[[Boosting (machine learning)]]", "[[Bootstrap aggregating]]", "[[BrownBoost]]", "[[Cascading classifiers]]", "[[Co-training]]", "[[Decision tree learning]]", "[[Gradient boosting]]", "[[Hyper basis function network]]", "[[IDistance]]"]
---

# AdaBoost

AdaBoost (short for Adaptive Boosting) is a statistical classification meta-algorithm formulated by Yoav Freund and Robert Schapire in 1995, who won the 2003 Gödel Prize for their work. It can be used in conjunction with many types of learning algorithm to improve performance. The output of multiple weak learners is combined into a weighted sum that represents the final output of the boosted classifier. Usually, AdaBoost is presented for binary classification, although it can be generalized to multiple classes or bounded intervals of real values.
AdaBoost is adaptive in the sense that subsequent weak learners (models) are adjusted in favor of instances misclassified by previous models. In some problems, it can be less susceptible to overfitting than other learning algorithms. The individual learners can be weak, but as long as the performance of each one is slightly better than random guessing, the final model can be proven to converge to a strong learner.
Although AdaBoost is typically used to combine weak base learners (such as decision stumps), it has been shown to also effectively combine strong base learners (such as deeper decision trees), producing an even more accurate model.
Every learning algorithm tends to suit some problem types better than others, and typically has many different parameters and configurations to adjust before it achieves optimal performance on a dataset. AdaBoost (with decision trees as the weak learners) is often referred to as the best out-of-the-box classifier. When used with decision tree learning, information gathered at each stage of the AdaBoost algorithm about the relative 'hardness' of each training sample is fed into the tree-growing algorithm such that later trees tend to focus on harder-to-classify examples.

## Related

- [[LogitBoost]]
- [[Boosting (machine learning)]]
- [[Bootstrap aggregating]]
- [[BrownBoost]]
- [[Cascading classifiers]]
- [[Co-training]]
- [[Decision tree learning]]
- [[Gradient boosting]]
- [[Hyper basis function network]]
- [[IDistance]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/AdaBoost