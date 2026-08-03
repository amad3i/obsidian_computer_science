---
title: "Proper complexity function"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Proper_complexity_function"
wikipedia_categories: ["Computational complexity theory"]
related: ["[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]", "[[Boolean circuit]]", "[[Certificate (complexity)]]"]
---

# Proper complexity function

A proper complexity function is a function f mapping natural numbers to natural numbers such that:

f is nondecreasing;
there exists a k-string Turing machine M such that on any input of length n, M halts after O(n + f(n)) steps, uses O(f(n)) space, and outputs f(n) consecutive blanks.
If f and g are two proper complexity functions, then f + g, fg, and 2f are also proper complexity functions.
Similar notions include honest functions, space-constructible functions, and time-constructible functions.

## Related

- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Averaging argument]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]
- [[Boolean circuit]]
- [[Certificate (complexity)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Proper_complexity_function