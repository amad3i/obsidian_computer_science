---
title: "CoBoosting"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/CoBoosting"
wikipedia_categories: ["Classification algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[AdaBoost]]", "[[ALOPEX]]", "[[Alternating decision tree]]", "[[Analogical modeling]]", "[[Boosting (machine learning)]]", "[[BrownBoost]]", "[[Calibration (statistics)]]", "[[Cascading classifiers]]", "[[Case-based reasoning]]"]
---

# CoBoosting

CoBoost is a semi-supervised training algorithm proposed by Collins and Singer in 1999. The original application for the algorithm was the task of named-entity recognition using very weak learners, but it can be used for performing semi-supervised learning in cases where data features may be redundant.
It may be seen as a combination of co-training and boosting. Each example is available in two views (subsections of the feature set), and boosting is applied iteratively in alternation with each view using predicted labels produced in the alternate view on the previous iteration. CoBoosting is not a valid boosting algorithm in the PAC learning sense.

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

- Wikipedia: https://en.wikipedia.org/wiki/CoBoosting