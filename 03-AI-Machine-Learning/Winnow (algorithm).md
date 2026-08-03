---
title: "Winnow (algorithm)"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Winnow_(algorithm)"
wikipedia_categories: ["Classification algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[AdaBoost]]", "[[ALOPEX]]", "[[Alternating decision tree]]", "[[Analogical modeling]]", "[[Boosting (machine learning)]]", "[[BrownBoost]]", "[[Calibration (statistics)]]", "[[Cascading classifiers]]", "[[Case-based reasoning]]"]
---

# Winnow (algorithm)

The winnow algorithm is a technique from machine learning for learning a linear classifier from labeled examples.  It is very similar to the perceptron algorithm.  However, the perceptron algorithm uses an additive weight-update scheme, while Winnow uses a multiplicative scheme that allows it to perform much better when many dimensions are irrelevant (hence its name winnow). It is a simple algorithm that scales well to high-dimensional data. During training, Winnow is shown a sequence of positive and negative examples. From these it learns a decision hyperplane that can then be used to label novel examples as positive or negative.  The algorithm can also be used in the online learning setting, where the learning and the classification phase are not clearly separated.

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

- Wikipedia: https://en.wikipedia.org/wiki/Winnow_(algorithm)