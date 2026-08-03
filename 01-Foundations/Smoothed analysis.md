---
title: "Smoothed analysis"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Smoothed_analysis"
wikipedia_categories: ["Analysis of algorithms", "Computational complexity theory", "Mathematical optimization"]
related: ["[[Analysis of algorithms]]", "[[Best, worst and average case]]", "[[Combinatorial search]]", "[[Computational complexity]]", "[[Half-exponential function]]", "[[Klee–Minty cube]]", "[[Pseudo-polynomial time]]", "[[Quasi-polynomial time]]", "[[Time complexity]]", "[[Aanderaa–Karp–Rosenberg conjecture]]"]
---

# Smoothed analysis

In theoretical computer science, smoothed analysis is a way of measuring the complexity of an algorithm. Since its introduction in 2001, smoothed analysis has been used as a basis for considerable research, for problems ranging from mathematical programming, numerical analysis, machine learning, and data mining. It can give a more realistic analysis of the practical performance (e.g., running time, success rate, approximation quality) of the algorithm compared to analysis that uses worst-case or average-case scenarios.
Smoothed analysis is a hybrid of worst-case and average-case analyses that inherits advantages of both. It measures the expected performance of algorithms under slight random perturbations of worst-case inputs. If the smoothed complexity of an algorithm is low, then it is unlikely that the algorithm will take a long time to solve practical instances whose data are subject to slight noises and imprecisions. Smoothed complexity results are strong probabilistic results, roughly stating that, in every large enough neighbourhood of the space of inputs, most inputs are easily solvable. Thus, a low smoothed complexity means that the hardness of inputs is a "brittle" property.
Although worst-case complexity has been widely successful in explaining the practical performance of many algorithms,  this style of analysis gives misleading results for a number of problems. Worst-case complexity measures the time it takes to solve any input, although hard-to-solve inputs might never come up in practice. In such cases, the worst-case running time can be much worse than the observed running time in practice. For example, the worst-case complexity of solving a linear program using the simplex algorithm is exponential, although the observed number of steps in practice is roughly linear. The simplex algorithm is in fact much faster than the ellipsoid method in practice, although the latter has polynomial-time worst-case complexity.
Average-case analysis was first introduced to overcome the limitations of worst-case analysis. However, the resulting average-case complexity depends heavily on the probability distribution that is chosen over the input. The actual inputs and distribution of inputs may be different in practice from the assumptions made during the analysis: a random input may be very unlike a typical input. Because of this choice of data model, a theoretical average-case result might say little about practical performance of the algorithm.
Smoothed analysis generalizes both worst-case and average-case analysis and inherits strengths of both. It is intended to be much more general than average-case complexity, while still allowing low complexity bounds to be proven.

## Related

- [[Analysis of algorithms]]
- [[Best, worst and average case]]
- [[Combinatorial search]]
- [[Computational complexity]]
- [[Half-exponential function]]
- [[Klee–Minty cube]]
- [[Pseudo-polynomial time]]
- [[Quasi-polynomial time]]
- [[Time complexity]]
- [[Aanderaa–Karp–Rosenberg conjecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Smoothed_analysis