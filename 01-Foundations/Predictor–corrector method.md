---
title: "Predictor–corrector method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Predictor–corrector_method"
wikipedia_categories: ["Algorithms", "Numerical analysis"]
related: ["[[Least-squares spectral analysis]]", "[[Miller's recurrence algorithm]]", "[[Unrestricted algorithm]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive algorithm]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Algorism]]"]
---

# Predictor–corrector method

In numerical analysis, predictor–corrector methods belong to a class of algorithms designed to integrate ordinary differential equations – to find an unknown function that satisfies a given differential equation.  All such algorithms proceed in two steps: 

The initial, "prediction" step, starts from a function fitted to the function-values and derivative-values at a preceding set of points to extrapolate ("anticipate") this function's value at a subsequent, new point.
The next, "corrector" step refines the initial approximation by using the predicted value of the function and another method to interpolate that unknown function's value at the same subsequent point.

## Related

- [[Least-squares spectral analysis]]
- [[Miller's recurrence algorithm]]
- [[Unrestricted algorithm]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive algorithm]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Algorism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Predictor–corrector_method