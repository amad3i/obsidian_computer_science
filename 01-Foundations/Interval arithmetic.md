---
title: "Interval arithmetic"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Interval_arithmetic"
wikipedia_categories: ["Arithmetic", "Computer arithmetic", "Data types", "Numerical analysis"]
related: ["[[Interval contractor]]", "[[2Sum]]", "[[CORDIC]]", "[[False precision]]", "[[Gal's accurate tables]]", "[[Grossone]]", "[[INTLAB]]", "[[Kahan summation algorithm]]", "[[Karlsruhe Accurate Arithmetic]]", "[[Numerical error]]"]
---

# Interval arithmetic

Interval arithmetic (also known as interval mathematics, interval analysis or interval computation) is a mathematical technique used to mitigate rounding and measurement errors in mathematical computation by computing function bounds. Numerical methods involving interval arithmetic can guarantee relatively reliable and mathematically correct results. Instead of representing a value as a single number, interval arithmetic or interval mathematics represents each value as a range of possibilities.
Mathematically, instead of working with an uncertain real-valued variable x, interval arithmetic works with an interval [a, b] that defines the range of values that x can have. In other words, any value of the variable x lies in the closed interval between a and b. A function f, when applied to x, produces an interval [c, d] which includes all the possible values for f(x) for all x ∈ [a, b].
Interval arithmetic is suitable for a variety of purposes; the most common use is in scientific works, particularly when the calculations are handled by software, where it is used to keep track of rounding errors in calculations and of uncertainties in the knowledge of the exact values of physical and technical parameters. The latter often arise from measurement errors and tolerances for components or due to limits on computational accuracy. Interval arithmetic also helps find guaranteed solutions to equations (such as differential equations) and optimization problems.

## Related

- [[Interval contractor]]
- [[2Sum]]
- [[CORDIC]]
- [[False precision]]
- [[Gal's accurate tables]]
- [[Grossone]]
- [[INTLAB]]
- [[Kahan summation algorithm]]
- [[Karlsruhe Accurate Arithmetic]]
- [[Numerical error]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interval_arithmetic