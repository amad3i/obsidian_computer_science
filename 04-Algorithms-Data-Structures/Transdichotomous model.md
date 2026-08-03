---
title: "Transdichotomous model"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Transdichotomous_model"
wikipedia_categories: ["Computational complexity theory", "Models of computation", "Theoretical computer science stubs"]
related: ["[[Complexity and Real Computation]]", "[[Compression theorem]]", "[[Decision tree model]]", "[[Effective complexity]]", "[[Generalized game]]", "[[Glossary of quantum computing]]", "[[Logical depth]]", "[[Model of computation]]", "[[Quantum capacity]]", "[[Quantum computing]]"]
---

# Transdichotomous model

In computational complexity theory, and more specifically in the analysis of algorithms with integer data, the transdichotomous model is a variation of the random-access machine in which the machine word size is assumed to match the problem size. The model was proposed by Michael Fredman and Dan Willard, who chose its name "because the dichotomy between the machine model and the problem size is crossed in a reasonable manner."
In a problem such as integer sorting in which there are n integers to be sorted, the transdichotomous model assumes that each integer may be stored in a single word of computer memory, that operations on single words take constant time per operation, and that the number of bits that can be stored in a single word is at least log2n. The goal of complexity analysis in this model is to find time bounds that depend only on n and not on the actual size of the input values or the machine words. In modeling integer computation, it is necessary to assume that machine words are limited in size, because models with unlimited precision are unreasonably powerful (able to solve PSPACE-complete problems in polynomial time). The transdichotomous model makes a minimal assumption of this type: that there is some limit, and that the limit is large enough to allow random-access indexing into the input data.
As well as its application to integer sorting, the transdichotomous model has also been applied to the design of priority queues and to problems in computational geometry and graph algorithms.

## Related

- [[Complexity and Real Computation]]
- [[Compression theorem]]
- [[Decision tree model]]
- [[Effective complexity]]
- [[Generalized game]]
- [[Glossary of quantum computing]]
- [[Logical depth]]
- [[Model of computation]]
- [[Quantum capacity]]
- [[Quantum computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transdichotomous_model