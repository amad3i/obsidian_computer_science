---
title: "Nonuniform sampling"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Nonuniform_sampling"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Nonuniform sampling

Nonuniform sampling is a branch of sampling theory involving results related to the Nyquist–Shannon sampling theorem. Nonuniform sampling is based on Lagrange interpolation and the relationship between itself and the (uniform) sampling theorem. Nonuniform sampling is a generalisation of the Whittaker–Shannon–Kotelnikov (WSK) sampling theorem.
The sampling theory of Shannon can be generalized for the case of nonuniform samples, that is, samples not taken equally spaced in time. The Shannon sampling theory for non-uniform sampling states that a band-limited signal can be perfectly reconstructed from its samples if the average sampling rate satisfies the Nyquist condition. Therefore, although uniformly spaced samples may result in easier reconstruction algorithms, it is not a necessary condition for perfect reconstruction.
The general theory for non-baseband and nonuniform samples was developed in 1967 by Henry Landau.  He proved that the average sampling rate (uniform or otherwise) must be twice the occupied bandwidth of the signal, assuming it is a priori known what portion of the spectrum was occupied.
In the late 1990s, this work was partially extended to cover signals for which the amount of occupied bandwidth was known, but the actual occupied portion of the spectrum was unknown.  In the 2000s, a complete theory was developed
(see the section Beyond Nyquist below) using compressed sensing.  In particular, the theory, using signal processing language, is described in this 2009 paper.  They show, among other things, that if the frequency locations are unknown, then it is necessary to sample at least at twice the Nyquist criteria; in other words, you must pay at least a factor of 2 for not knowing the location of the spectrum.  Note that minimum sampling requirements do not necessarily guarantee numerical stability.

## Related

- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]
- [[Aliasing]]
- [[All-pass filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nonuniform_sampling