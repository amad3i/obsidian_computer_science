---
title: "Baum–Welch algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Baum–Welch_algorithm"
wikipedia_categories: ["Bioinformatics algorithms", "Markov models", "Randomized algorithms"]
related: ["[[3D-Jury]]", "[[Algorithmic information theory]]", "[[Averaging argument]]", "[[Bernoulli scheme]]", "[[Burst error]]", "[[CLAWS (linguistics)]]", "[[Complete-linkage clustering]]", "[[Dependability state model]]", "[[Detailed balance]]", "[[Diffusion model]]"]
---

# Baum–Welch algorithm

In electrical engineering, statistical computing and bioinformatics, the Baum–Welch algorithm is a special case of the expectation–maximization algorithm used to find the unknown parameters of a hidden Markov model (HMM). It makes use of the forward-backward algorithm to compute the statistics for the expectation step. The Baum–Welch algorithm, the primary method for inference in hidden Markov models, is numerically unstable due to its recursive calculation of joint probabilities. As the number of variables grows, these joint probabilities become increasingly small, leading to the forward recursions rapidly approaching values below machine precision.

## Related

- [[3D-Jury]]
- [[Algorithmic information theory]]
- [[Averaging argument]]
- [[Bernoulli scheme]]
- [[Burst error]]
- [[CLAWS (linguistics)]]
- [[Complete-linkage clustering]]
- [[Dependability state model]]
- [[Detailed balance]]
- [[Diffusion model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Baum–Welch_algorithm