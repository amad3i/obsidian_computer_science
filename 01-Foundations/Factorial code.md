---
title: "Factorial code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Factorial_code"
wikipedia_categories: ["Independence (probability theory)", "Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Factorial code

Most real world data sets consist of data vectors whose individual components are not statistically independent. In other words, knowing the value of an element will provide information about the value of elements in the data vector. When this occurs, it can be desirable to create a factorial code of the data, i.e., a new vector-valued representation of each data vector such that it gets uniquely encoded by the resulting code vector (loss-free coding), but the code components are statistically independent.
Later supervised learning usually works much better when the raw input data is first translated into such a factorial code. For example, suppose the final goal is to classify images with highly redundant pixels. A naive Bayes classifier will assume the pixels are statistically independent random variables and therefore fail to produce good results. If the data are first encoded in a factorial way, however, then the naive Bayes classifier will achieve its optimal performance (compare Schmidhuber et al. 1996).
To create factorial codes, Horace Barlow and co-workers suggested to minimize the sum of the bit entropies of the code components of binary codes (1989). Jürgen Schmidhuber (1992) re-formulated the problem in terms of predictors and  binary  feature detectors, each receiving the raw data as an input.  For each detector there is a predictor that sees the other detectors and learns to predict the output of its own detector in response to the various input vectors or images. But each detector uses a machine learning algorithm to become as unpredictable as possible. The global optimum of this objective function corresponds to a factorial code represented in a distributed fashion across the outputs of the feature detectors.
Painsky, Rosset and Feder (2016, 2017) further studied this problem in the context of independent component analysis over finite alphabet sizes. Through a series of theorems they show that the factorial coding problem can be accurately solved with a branch and bound search tree algorithm, or tightly approximated with a series of linear problems.  In addition, they introduce a simple transformation (namely, order permutation) which provides a greedy yet very effective approximation of the optimal solution. Practically, they show that with a careful implementation, the favorable properties of the order permutation may be achieved in an asymptotically optimal computational complexity. Importantly, they provide theoretical guarantees, showing that while not every random vector can be efficiently decomposed into independent components, the majority of vectors do decompose very well (that is, with a small constant cost), as the dimension increases. In addition, they demonstrate the use of factorial codes to data compression in multiple setups (2017).

## Related

- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]
- [[Argument (complex analysis)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Factorial_code