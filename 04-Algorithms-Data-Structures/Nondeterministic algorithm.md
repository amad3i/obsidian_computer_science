---
title: "Nondeterministic algorithm"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Nondeterministic_algorithm"
wikipedia_categories: ["Computational complexity theory", "Theory of computation"]
related: ["[[Introduction to the Theory of Computation]]", "[[Transcomputational problem]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Ackermann function]]", "[[Admissible numbering]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Andreas Brandstädt]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]"]
---

# Nondeterministic algorithm

In computer science and computer programming, a nondeterministic algorithm is an algorithm that, even for the same input, can exhibit different behaviors on different runs, as opposed to a deterministic algorithm.
Different models of computation give rise to different reasons that an algorithm may be non-deterministic, and different ways to evaluate its performance or correctness:

A concurrent algorithm can perform differently on different runs due to a race condition. This can happen even with a single-threaded algorithm when it interacts with resources external to it. In general, such an algorithm is considered to perform correctly only when all possible runs produce the desired results.
A probabilistic algorithm's behavior depends on a random number generator called by the algorithm. These are subdivided into Las Vegas algorithms, for which (like concurrent algorithms) all runs must produce correct output, and Monte Carlo algorithms which are allowed to fail or produce incorrect results with low probability. The performance of such an algorithm is often measured probabilistically, for instance using an analysis of its expected time.
In computational complexity theory, nondeterminism is often modeled using an explicit mechanism for making a nondeterministic choice, such as in a nondeterministic Turing machine. For these models, a nondeterministic algorithm is considered to perform correctly when, for each input, there exists a run that produces the desired result, even when other runs produce incorrect results. This existential power makes nondeterministic algorithms of this sort more efficient than known deterministic algorithms for many problems. The P versus NP problem encapsulates this conjectured greater efficiency available to nondeterministic algorithms. Algorithms of this sort are used to define complexity classes based on nondeterministic time and nondeterministic space complexity. They may be simulated using nondeterministic programming, a method for specifying nondeterministic algorithms and searching for the choices that lead to a correct run, often using a backtracking search.

## Related

- [[Introduction to the Theory of Computation]]
- [[Transcomputational problem]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Ackermann function]]
- [[Admissible numbering]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Andreas Brandstädt]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nondeterministic_algorithm