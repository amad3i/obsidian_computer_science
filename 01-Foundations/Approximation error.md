---
title: "Approximation error"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Approximation_error"
wikipedia_categories: ["Numerical analysis"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation theory]]", "[[Arc-length method]]", "[[Artificial precision]]"]
---

# Approximation error

The approximation error in a given data value represents the significant discrepancy that arises when an exact, true value is compared against some approximation derived for it. This inherent error in approximation can be quantified and expressed in two principal ways: as an absolute error, which denotes the direct numerical magnitude of this discrepancy irrespective of the true value's scale, or as a relative error, which provides a scaled measure of the error by considering the absolute error in proportion to the exact data value, thus offering a context-dependent assessment of the error's significance.
An approximation error can manifest due to a multitude of diverse reasons. Prominent among these are limitations related to computing machine precision, where digital systems cannot represent all real numbers with perfect accuracy, leading to unavoidable truncation or rounding. Another common source is inherent measurement error, stemming from the practical limitations of instruments, environmental factors, or observational processes (for instance, if the actual length of a piece of paper is precisely 4.53 cm, but the measuring ruler only permits an estimation to the nearest 0.1 cm, this constraint could lead to a recorded measurement of 4.5 cm, thereby introducing an error).
In the mathematical field of numerical analysis, the crucial concept of numerical stability associated with an algorithm serves to indicate the extent to which initial errors or perturbations present in the input data of the algorithm are likely to propagate and potentially amplify into substantial errors in the final output. Algorithms that are characterized as numerically stable are robust in the sense that they do not yield a significantly magnified error in their output even when the input is slightly malformed or contains minor inaccuracies; conversely, numerically unstable algorithms may exhibit dramatic error growth from small input changes, rendering their results unreliable.

## Related

- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation theory]]
- [[Arc-length method]]
- [[Artificial precision]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Approximation_error