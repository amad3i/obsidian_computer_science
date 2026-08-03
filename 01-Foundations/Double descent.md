---
title: "Double descent"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Double_descent"
wikipedia_categories: ["Machine learning", "Model selection", "Statistical classification", "Statistics stubs"]
related: ["[[Probability matching]]", "[[Astrostatistics]]", "[[Binary classification]]", "[[Confusion matrix]]", "[[Cross-validation (statistics)]]", "[[Evaluation of binary classifiers]]", "[[Hyperparameter (machine learning)]]", "[[Hyperparameter optimization]]", "[[Leakage (machine learning)]]", "[[Learning curve (machine learning)]]"]
---

# Double descent

Double descent in statistics and machine learning is the phenomenon where a model's error rate on the test set initially decreases with the number of parameters, then peaks, then decreases again. This phenomenon has been considered surprising, as it contradicts assumptions about overfitting in classical machine learning.
The increase usually occurs near the interpolation threshold, where the number of parameters is the same as the number of training data points (the model is just large enough to fit the training data). Or, more precisely, it is the maximum number of samples on which the model/training procedure achieves approximately on average 0 training error.

## Related

- [[Probability matching]]
- [[Astrostatistics]]
- [[Binary classification]]
- [[Confusion matrix]]
- [[Cross-validation (statistics)]]
- [[Evaluation of binary classifiers]]
- [[Hyperparameter (machine learning)]]
- [[Hyperparameter optimization]]
- [[Leakage (machine learning)]]
- [[Learning curve (machine learning)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Double_descent