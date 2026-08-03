---
title: "Out-of-bag error"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Out-of-bag_error"
wikipedia_categories: ["Computational statistics", "Ensemble learning", "Machine learning algorithms"]
related: ["[[Bootstrap aggregating]]", "[[AdaBoost]]", "[[FastICA]]", "[[LogitBoost]]", "[[Stochastic gradient descent]]", "[[Actor-critic algorithm]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Artificial precision]]", "[[Augmented Analytics]]"]
---

# Out-of-bag error

Out-of-bag (OOB) error, also called out-of-bag estimate, is a method of measuring the prediction error of random forests, boosted decision trees, and other machine learning models utilizing bootstrap aggregating (bagging). Bagging uses subsampling with replacement to create training samples for the model to learn from. OOB error is the mean prediction error on each training sample xi, using only the trees that did not have xi in their bootstrap sample.
Bootstrap aggregating allows one to define an out-of-bag estimate of the prediction performance improvement by evaluating predictions on those observations that were not used in the building of the next base learner.

## Related

- [[Bootstrap aggregating]]
- [[AdaBoost]]
- [[FastICA]]
- [[LogitBoost]]
- [[Stochastic gradient descent]]
- [[Actor-critic algorithm]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Artificial precision]]
- [[Augmented Analytics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Out-of-bag_error