---
title: "Least mean squares filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Least_mean_squares_filter"
wikipedia_categories: ["Digital signal processing", "Filter theory", "Statistical algorithms"]
related: ["[[Filter design]]", "[[Finite impulse response]]", "[[FIR transfer function]]", "[[Impulse invariance]]", "[[Infinite impulse response]]", "[[Matched Z-transform method]]", "[[Parks–McClellan filter design algorithm]]", "[[Quadrature mirror filter]]", "[[Recursive least squares filter]]", "[[Similarities between Wiener and LMS]]"]
---

# Least mean squares filter

Least mean squares (LMS) algorithms are a class of adaptive filter used to mimic a desired filter by finding the filter coefficients that relate to producing the least mean square of the error signal (difference between the desired and the actual signal). It is a stochastic gradient descent method in that the filter is only adapted based on the error at the current time.  It was invented in 1960 by Stanford University professor Bernard Widrow and his first Ph.D. student, Ted Hoff, based on their research into single-layer neural networks. Specifically, they used gradient descent to train an ADALINE to recognize patterns, and called the algorithm "delta rule". They applied the rule to filters, resulting in the LMS algorithm.

## Related

- [[Filter design]]
- [[Finite impulse response]]
- [[FIR transfer function]]
- [[Impulse invariance]]
- [[Infinite impulse response]]
- [[Matched Z-transform method]]
- [[Parks–McClellan filter design algorithm]]
- [[Quadrature mirror filter]]
- [[Recursive least squares filter]]
- [[Similarities between Wiener and LMS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Least_mean_squares_filter