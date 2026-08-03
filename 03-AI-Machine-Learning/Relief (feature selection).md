---
title: "Relief (feature selection)"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Relief_(feature_selection)"
wikipedia_categories: ["Dimension reduction", "Model selection"]
related: ["[[Feature selection]]", "[[Canonical correspondence analysis]]", "[[Correspondence analysis]]", "[[Cross-validation (statistics)]]", "[[Detrended correspondence analysis]]", "[[Double descent]]", "[[Generalized canonical correlation]]", "[[Generalized multidimensional scaling]]", "[[Hyperparameter (machine learning)]]", "[[Hyperparameter optimization]]"]
---

# Relief (feature selection)

Relief is an algorithm developed by Kenji Kira and Larry Rendell in 1992 that takes a filter-method approach to feature selection that is notably sensitive to feature interactions.  It was originally designed for application to binary classification problems with discrete or numerical features.  Relief calculates a feature score for each feature which can then be applied to rank and select top scoring features for feature selection.  Alternatively, these scores may be applied as feature weights to guide downstream modeling. Relief feature scoring is based on the identification of feature value differences between nearest neighbor instance pairs. If a feature value difference is observed in a neighboring instance pair with the same class (a 'hit'), the feature score decreases.  Alternatively, if a feature value difference is observed in a neighboring instance pair with different class values (a 'miss'), the feature score increases. The original Relief algorithm has since inspired a family of Relief-based feature selection algorithms (RBAs), including the ReliefF algorithm.  Beyond the original Relief algorithm, RBAs have been adapted to (1) perform more reliably in noisy problems, (2) generalize to multi-class problems  (3) generalize to numerical outcome (i.e. regression) problems, and (4) to make them robust to incomplete (i.e. missing) data.
To date, the development of RBA variants and extensions has focused on four areas; (1) improving performance of the 'core' Relief algorithm, i.e. examining strategies for neighbor selection and instance weighting, (2) improving scalability of the 'core' Relief algorithm to larger feature spaces through iterative approaches, (3) methods for flexibly adapting Relief to different data types, and (4) improving Relief run efficiency.
Their strengths are that they are not dependent on heuristics, they run in low-order polynomial time, and they are noise-tolerant and robust to feature interactions, as well as being applicable for binary or continuous data; however, it does not discriminate between redundant features, and low numbers of training instances fool the algorithm.

## Related

- [[Feature selection]]
- [[Canonical correspondence analysis]]
- [[Correspondence analysis]]
- [[Cross-validation (statistics)]]
- [[Detrended correspondence analysis]]
- [[Double descent]]
- [[Generalized canonical correlation]]
- [[Generalized multidimensional scaling]]
- [[Hyperparameter (machine learning)]]
- [[Hyperparameter optimization]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Relief_(feature_selection)