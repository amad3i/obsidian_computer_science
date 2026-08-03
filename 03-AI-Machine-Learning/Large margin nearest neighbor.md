---
title: "Large margin nearest neighbor"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Large_margin_nearest_neighbor"
wikipedia_categories: ["Classification algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[AdaBoost]]", "[[ALOPEX]]", "[[Alternating decision tree]]", "[[Analogical modeling]]", "[[Boosting (machine learning)]]", "[[BrownBoost]]", "[[Calibration (statistics)]]", "[[Cascading classifiers]]", "[[Case-based reasoning]]"]
---

# Large margin nearest neighbor

Large margin nearest neighbor (LMNN) classification is a statistical machine learning algorithm for metric learning. It learns a pseudometric designed for k-nearest neighbor classification. The algorithm is based on semidefinite programming, a sub-class of convex optimization.
The goal of supervised learning (more specifically classification) is to learn a decision rule that can categorize data instances into pre-defined classes. The  k-nearest neighbor rule assumes a training data set of labeled instances (i.e. the classes are known). It classifies a new data instance with the class obtained from the majority vote of the k closest (labeled) training instances. Closeness is measured with a pre-defined metric. Large margin nearest neighbors is an algorithm that learns this global (pseudo-)metric in a supervised fashion to improve the classification accuracy of the k-nearest neighbor rule.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[AdaBoost]]
- [[ALOPEX]]
- [[Alternating decision tree]]
- [[Analogical modeling]]
- [[Boosting (machine learning)]]
- [[BrownBoost]]
- [[Calibration (statistics)]]
- [[Cascading classifiers]]
- [[Case-based reasoning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Large_margin_nearest_neighbor