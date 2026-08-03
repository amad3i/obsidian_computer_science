---
title: "Rounding"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Rounding"
wikipedia_categories: ["Arithmetic", "Computer arithmetic", "Statistical data transformation", "Theory of computation"]
related: ["[[Ackermann function]]", "[[Interval arithmetic]]", "[[Interval contractor]]", "[[Sudan function]]", "[[2Sum]]", "[[Adding machine]]", "[[Admissible numbering]]", "[[Andreas Brandstädt]]", "[[Arithmetic logic unit]]", "[[Blockhead (thought experiment)]]"]
---

# Rounding

Rounding or rounding off is the process of adjusting a number to an approximate, more convenient value, often with a shorter or simpler representation. For example, replacing $23.4476 with $23.45, the fraction 312/937 with 1/3, or the expression √2 with 1.414.
Rounding is often done to obtain a value that is easier to report and communicate than the original. Rounding can also be important to avoid misleadingly precise reporting of a computed number, measurement, or estimate; for example, a quantity that was computed as 123456 but is known to be accurate only to within a few hundred units is usually better stated as "about 123500".
On the other hand, rounding of exact numbers will introduce some round-off error in the reported result. Rounding is almost unavoidable when reporting many computations – especially when dividing two numbers in integer or fixed-point arithmetic; when computing mathematical functions such as square roots, logarithms, and sines; or when using a floating-point representation with a fixed number of significant digits. In a sequence of calculations, these rounding errors generally accumulate, and in certain ill-conditioned cases they may make the result meaningless.
Accurate rounding of transcendental mathematical functions is difficult because the number of extra digits that need to be calculated to resolve whether to round up or down cannot be known in advance. This problem is known as "the table-maker's dilemma".
Rounding has many similarities to the quantization that occurs when physical quantities must be encoded by numbers or digital signals.
A wavy equals sign (≈) is sometimes used to indicate rounding of exact numbers, e.g. 9.98 ≈ 10. This sign was introduced by Alfred George Greenhill in 1892.
Ideal characteristics of rounding methods include:

Rounding should be done by a function. This way, when the same input is rounded in different instances, the output is unchanged.
Calculations done with rounding should be close to those done without rounding.
As a result of (1) and (2), the output from rounding should be close to its input, often as close as possible.
To be considered rounding, the range will be a subset of the domain, often discrete. A classical range is the integers.
Rounding should preserve symmetries that already exist between the domain and range. With finite precision (or a discrete domain), this translates to removing bias.
A rounding method should have utility in computer science or human arithmetic where finite precision is used, and speed is a consideration.
Because it is not usually possible for a method to satisfy all ideal characteristics, many different rounding methods exist.
As a general rule, rounding is idempotent; i.e., once a number has been rounded, rounding it again to the same precision will not change its value. Rounding functions are also monotonic; i.e., rounding two numbers to the same absolute precision will not exchange their order (but may give the same value). In the general case of a discrete range, they are piecewise constant functions.

## Related

- [[Ackermann function]]
- [[Interval arithmetic]]
- [[Interval contractor]]
- [[Sudan function]]
- [[2Sum]]
- [[Adding machine]]
- [[Admissible numbering]]
- [[Andreas Brandstädt]]
- [[Arithmetic logic unit]]
- [[Blockhead (thought experiment)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rounding