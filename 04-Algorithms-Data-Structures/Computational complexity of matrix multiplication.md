---
title: "Computational complexity of matrix multiplication"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Computational_complexity_of_matrix_multiplication"
wikipedia_categories: ["Computational complexity theory", "Computer arithmetic algorithms", "Matrix theory", "Unsolved problems in computer science"]
related: ["[[Computational complexity of mathematical operations]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Computing the permanent]]", "[[Graph isomorphism problem]]", "[[Unique games conjecture]]", "[[3SUM]]", "[[Adjugate matrix]]", "[[Advice (complexity)]]", "[[Amitsur–Levitzki theorem]]", "[[Analysis of algorithms]]"]
---

# Computational complexity of matrix multiplication

In theoretical computer science, the computational complexity of matrix multiplication dictates how quickly the operation of matrix multiplication can be performed. Matrix multiplication algorithms are a central subroutine in theoretical and numerical algorithms for numerical linear algebra and optimization, so finding the fastest algorithm for matrix multiplication is of major practical relevance.
Directly applying the mathematical definition of matrix multiplication gives an algorithm that requires n3 field operations to multiply two n × n matrices over that field (Θ(n3) in big O notation). Surprisingly, algorithms exist that provide better running times than this straightforward "schoolbook algorithm". The first to be discovered was Strassen's algorithm, devised by Volker Strassen in 1969 and often referred to as "fast matrix multiplication". The optimal number of field operations needed to multiply two square n × n matrices up to constant factors is still unknown. This is a major open question in theoretical computer science.
As of January 2024, the best bound on the asymptotic complexity of a matrix multiplication algorithm is O(n2.371339). However, this and similar improvements to Strassen are not used in practice, because they are galactic algorithms: the constant coefficient hidden by the big O notation is so large that they are only worthwhile for matrices that are too large to handle on present-day computers.

## Related

- [[Computational complexity of mathematical operations]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Computing the permanent]]
- [[Graph isomorphism problem]]
- [[Unique games conjecture]]
- [[3SUM]]
- [[Adjugate matrix]]
- [[Advice (complexity)]]
- [[Amitsur–Levitzki theorem]]
- [[Analysis of algorithms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Computational_complexity_of_matrix_multiplication