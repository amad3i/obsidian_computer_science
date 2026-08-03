---
title: "Generalized filtering"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Generalized_filtering"
wikipedia_categories: ["Bayesian estimation", "Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Generalized filtering

Generalized filtering is a generic Bayesian filtering scheme for nonlinear state-space models. It is based on a variational principle of least action, formulated in generalized coordinates of motion. Note that "generalized coordinates of motion" are related to—but distinct from—generalized coordinates as used in (multibody) dynamical systems analysis. Generalized filtering furnishes posterior densities over hidden states (and parameters) generating observed data using a generalized gradient descent on variational free energy, under the Laplace assumption. Unlike classical (e.g. Kalman-Bucy or particle) filtering, generalized filtering eschews Markovian assumptions about random fluctuations. Furthermore, it operates online, assimilating data to approximate the posterior density  over unknown quantities, without the need for a backward pass. Special cases include variational filtering, dynamic expectation maximization and generalized predictive coding.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Generalized_filtering