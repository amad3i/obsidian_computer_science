---
title: "Iterative compression"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Iterative_compression"
wikipedia_categories: ["Analysis of algorithms", "Graph algorithms", "Parameterized complexity"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Analysis of algorithms]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Best, worst and average case]]", "[[Bianconi–Barabási model]]"]
---

# Iterative compression

In computer science, iterative compression is an algorithmic technique for the design of fixed-parameter tractable algorithms, in which one element (such as a vertex of a graph) is added to the problem in each step, and a small solution for the problem prior to the addition is used to help find a small solution to the problem after the step.
The technique was invented by Reed, Smith and Vetta to show that the odd cycle transversal problem was solvable in time O(3k kmn), for a graph with n vertices, m edges, and odd cycle transversal number k.  Odd cycle transversal is the problem of finding the smallest set of vertices of a graph that includes at least one vertex from every odd cycle; its parameterized complexity was a longstanding open question.  This technique later proved very useful in showing fixed-parameter tractability results.  It is now considered to be one of the fundamental techniques in the area of parameterized algorithmics.
Iterative compression has been used successfully in many problems, for instance odd cycle transversal (see below) and edge bipartization, feedback vertex set, and cluster vertex deletion.  It has also been used successfully for exact exponential time algorithms for independent set.

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Analysis of algorithms]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Best, worst and average case]]
- [[Bianconi–Barabási model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Iterative_compression