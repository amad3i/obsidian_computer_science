---
title: "Rapidly exploring random tree"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Rapidly_exploring_random_tree"
wikipedia_categories: ["Path planning", "Probabilistic data structures", "Robot navigation", "Search algorithms"]
related: ["[[Locality-sensitive hashing]]", "[[Nearest neighbor search]]", "[[Theta-]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]"]
---

# Rapidly exploring random tree

A rapidly exploring random tree (RRT) is an algorithm designed to efficiently search nonconvex, high-dimensional spaces by randomly building a space-filling tree. The tree is constructed incrementally from samples drawn randomly from the search space and is inherently biased to grow towards large unsearched areas of the problem. RRTs were developed by Steven M. LaValle and James J. Kuffner Jr.
They easily handle problems with obstacles and differential constraints (nonholonomic and kinodynamic) and have been widely used in autonomous robotic motion planning.
RRTs can be viewed as a technique to generate open-loop trajectories for nonlinear systems with state constraints. An RRT can also be considered as a Monte-Carlo method to bias search into the largest Voronoi regions of a graph in a configuration space. Some variations can even be considered stochastic fractals.
RRTs can be used to compute approximate control policies to control high dimensional nonlinear systems with state and action constraints.

## Related

- [[Locality-sensitive hashing]]
- [[Nearest neighbor search]]
- [[Theta-]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rapidly_exploring_random_tree