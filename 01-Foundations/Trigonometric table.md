---
title: "Trigonometric table"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Trigonometric_table"
wikipedia_categories: ["Numerical analysis", "Trigonometry"]
related: ["[[CORDIC]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]"]
---

# Trigonometric table

In mathematics, tables of trigonometric functions are useful in a number of areas. Before the existence of pocket calculators, trigonometric tables were essential for navigation, science and engineering. The calculation of mathematical tables was an important area of study, which led to the development of the first mechanical computing devices. Trigonometric calculations played an important role in the early study of astronomy. Early tables were constructed by repeatedly applying trigonometric identities (like the half-angle and angle-sum identities) to compute new values from old ones.
Modern computers and pocket calculators now generate trigonometric function values on demand, using special libraries of mathematical code. Often, these libraries use pre-calculated tables internally, and compute the required value by using an appropriate interpolation method. Interpolation of simple look-up tables of trigonometric functions is still used in computer graphics, where only modest accuracy may be required and speed is often paramount.
Another important application of trigonometric tables and generation schemes is for fast Fourier transform (FFT) algorithms, where the same trigonometric function values (called twiddle factors) must be evaluated many times in a given transform, especially in the common case where many transforms of the same size are computed. In this case, calling generic library routines every time is unacceptably slow. One option is to call the library routines once, to build up a table of those trigonometric values that will be needed, but this requires significant memory to store the table. The other possibility, since a regular sequence of values is required, is to use a recurrence formula to compute the trigonometric values on the fly. Significant research has been devoted to finding accurate, stable recurrence schemes in order to preserve the accuracy of the FFT (which is very sensitive to trigonometric errors).
A trigonometry table is essentially a reference chart that presents the values of sine, cosine, tangent, and other trigonometric functions for various angles. These angles are usually arranged across the top row of the table, while the different trigonometric functions are labeled in the first column on the left. To locate the value of a specific trigonometric function at a certain angle, you would find the row for the function and follow it across to the column under the desired angle.

## Related

- [[CORDIC]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Trigonometric_table