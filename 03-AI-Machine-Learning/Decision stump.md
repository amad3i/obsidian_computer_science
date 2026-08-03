---
title: "Decision stump"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Decision_stump"
wikipedia_categories: ["Decision trees"]
related: ["[[Alternating decision tree]]", "[[Decision tree]]", "[[Decision tree learning]]", "[[Decision tree model]]", "[[Decision tree pruning]]", "[[Fast-and-frugal trees]]", "[[Gradient boosting]]", "[[Grafting (decision trees)]]", "[[ID3 algorithm]]", "[[Incremental decision tree]]"]
---

# Decision stump

A decision stump is a machine learning model consisting of a one-level decision tree. That is, it is a decision tree with one internal node (the root) which is immediately connected to the terminal nodes (its leaves). A decision stump makes a prediction based on the value of just a single input feature. Sometimes they are also called 1-rules.
Depending on the type of the input feature, several variations are possible. For nominal features, one may build a stump which contains a leaf for each possible feature value or a stump with the two leaves, one of which corresponds to some chosen category, and the other leaf to all the other categories. For binary features these two schemes are identical. A missing value may be treated as a yet another category.
For continuous features, usually, some threshold feature value is selected, and the stump contains two leaves — for values below and above the threshold. However, rarely, multiple thresholds may be chosen and the stump therefore contains three or more leaves.
Decision stumps are often used as components (called "weak learners" or "base learners") in machine learning ensemble techniques such as bagging and boosting. For example, a Viola–Jones face detection algorithm employs AdaBoost with decision stumps as weak learners.
The term "decision stump" was coined in a 1992 ICML paper by Wayne Iba and Pat Langley.

## Related

- [[Alternating decision tree]]
- [[Decision tree]]
- [[Decision tree learning]]
- [[Decision tree model]]
- [[Decision tree pruning]]
- [[Fast-and-frugal trees]]
- [[Gradient boosting]]
- [[Grafting (decision trees)]]
- [[ID3 algorithm]]
- [[Incremental decision tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Decision_stump