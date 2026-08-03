---
title: "Hidden semi-Markov model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hidden_semi-Markov_model"
wikipedia_categories: ["Hidden Markov models", "Statistics stubs"]
related: ["[[Accuracy paradox]]", "[[Adaptive sampling]]", "[[Aggregate pattern]]", "[[Artificial precision]]", "[[Astrostatistics]]", "[[Bayesian inference using Gibbs sampling]]", "[[Blumenthal's zero–one law]]", "[[Brown clustering]]", "[[Canonical correspondence analysis]]", "[[Combinatorial data analysis]]"]
---

# Hidden semi-Markov model

A hidden semi-Markov model (HSMM) is a statistical model with the same structure as a hidden Markov model except that the unobservable process is semi-Markov rather than Markov. This means that the probability of there being a change in the hidden state depends on the amount of time that has elapsed since entry into the current state. This is in contrast to hidden Markov models where there is a constant probability of changing state given survival in the state up to that time.
For instance Sansom & Thomson (2001) modelled daily rainfall using a hidden semi-Markov model. If the underlying process (e.g. weather system) does not have a geometrically distributed duration, an HSMM may be more appropriate.
Hidden semi-Markov models can be used in implementations of statistical parametric speech synthesis to model the probabilities of transitions between different states of encoded speech representations. They are often used along with other tools such artificial neural networks, connecting with other components of a full parametric speech synthesis system to generate the output waveforms.
The model was first published by Leonard E. Baum and Ted Petrie in 1966.
Statistical inference for hidden semi-Markov models is more difficult than in hidden Markov models, since algorithms like the Baum–Welch algorithm are not directly applicable, and must be adapted requiring more resources.

## Related

- [[Accuracy paradox]]
- [[Adaptive sampling]]
- [[Aggregate pattern]]
- [[Artificial precision]]
- [[Astrostatistics]]
- [[Bayesian inference using Gibbs sampling]]
- [[Blumenthal's zero–one law]]
- [[Brown clustering]]
- [[Canonical correspondence analysis]]
- [[Combinatorial data analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hidden_semi-Markov_model