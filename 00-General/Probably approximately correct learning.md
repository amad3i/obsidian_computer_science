---
title: "Probably approximately correct learning"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Probably_approximately_correct_learning"
wikipedia_categories: ["Computational learning theory"]
related: ["[[Algorithmic learning theory]]", "[[Bondy's theorem]]", "[[Concept class]]", "[[Distribution learning theory]]", "[[Error tolerance (PAC learning)]]", "[[Growth function]]", "[[Induction of regular languages]]", "[[Language identification in the limit]]", "[[Occam learning]]", "[[Open weights]]"]
---

# Probably approximately correct learning

In computational learning theory, probably approximately correct (PAC) learning is a framework for mathematical analysis of machine learning. It was proposed in 1984 by Leslie Valiant.
In this framework, the learner receives samples and must select a generalization function (called the hypothesis) from a certain class of possible functions. The goal is that, with high probability (the "probably" part), the selected function will have low generalization error (the "approximately correct" part). The learner must be able to learn the concept given any arbitrary approximation ratio, probability of success, or distribution of the samples.
The model was later extended to treat noise (misclassified samples). 
An important innovation of the PAC framework is the introduction of computational complexity theory concepts to machine learning. In particular, the learner is expected to find efficient functions (time and space requirements bounded to a polynomial of the example size), and the learner itself must implement an efficient procedure (requiring an example count bounded to a polynomial of the concept size, modified by the approximation and likelihood bounds).

## Related

- [[Algorithmic learning theory]]
- [[Bondy's theorem]]
- [[Concept class]]
- [[Distribution learning theory]]
- [[Error tolerance (PAC learning)]]
- [[Growth function]]
- [[Induction of regular languages]]
- [[Language identification in the limit]]
- [[Occam learning]]
- [[Open weights]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Probably_approximately_correct_learning