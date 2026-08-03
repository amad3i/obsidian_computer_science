---
title: "Yao's principle"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Yao's_principle"
wikipedia_categories: ["Computational complexity theory", "Randomized algorithms"]
related: ["[[Averaging argument]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Algorithmic information theory]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Baum–Welch algorithm]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]"]
---

# Yao's principle

In computational complexity theory, Yao's principle (also called Yao's minimax principle or Yao's lemma) relates the performance of randomized algorithms to deterministic (non-random) algorithms. It states that, for certain classes of algorithms, and certain measures of the performance of the algorithms, the following two quantities are equal:

The optimal performance that can be obtained by a deterministic algorithm on a random input (its average-case complexity), for a probability distribution on inputs chosen to be as hard as possible and for an algorithm chosen to work as well as possible against that distribution
The optimal performance that can be obtained by a random algorithm on a deterministic input (its expected complexity), for an algorithm chosen to have the best performance on its worst case inputs, and the worst case input to the algorithm
Yao's principle is often used to prove limitations on the performance of randomized algorithms, by finding a probability distribution on inputs that is difficult for deterministic algorithms, and inferring that randomized algorithms have the same limitation on their worst case performance.
This principle is named after Andrew Yao, who first proposed it in a 1977 paper. It is closely related to the minimax theorem in the theory of zero-sum games, and to the duality theory of linear programs.

## Related

- [[Averaging argument]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Algorithmic information theory]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Baum–Welch algorithm]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Yao's_principle