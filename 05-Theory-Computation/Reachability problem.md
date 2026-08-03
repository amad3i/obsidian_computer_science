---
title: "Reachability problem"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Reachability_problem"
wikipedia_categories: ["Theory of computation"]
related: ["[[Ackermann function]]", "[[Admissible numbering]]", "[[Andreas Brandstädt]]", "[[Blockhead (thought experiment)]]", "[[Bremermann's limit]]", "[[Brooks–Iyengar algorithm]]", "[[Busy beaver]]", "[[Byzantine fault]]", "[[Chain rule for Kolmogorov complexity]]", "[[Chaitin's constant]]"]
---

# Reachability problem

Reachability is a fundamental problem which can be formulated as follows: Given a computational system with a set of allowed rules or transformations, decide whether a certain state of a system is reachable from a given initial state of the system.
It appears in several different contexts: finite- and infinite-state concurrent systems, cellular automata and Petri nets, program analysis, discrete and continuous systems, time critical systems, hybrid systems, rewriting systems, probabilistic and parametric systems, and open systems modelled as games.
Variants of the reachability problem may result from additional constraints on the initial or final states, specific requirement for reachability paths as well as for iterative reachability or changing the questions into analysis of winning strategies in infinite games or unavoidability of some dynamics. 
Typically, for a fixed system description given in some form (reduction rules, systems of equations, logical formulas, etc.) a reachability problem consists of checking whether a given set of target states can be reached starting from a fixed set of initial states. The set of target states can be represented explicitly or via some implicit representation (e.g., a system of equations, a set of minimal elements with respect to some ordering on the states). Sophisticated quantitative and qualitative properties can often be reduced to basic reachability questions. Decidability and complexity boundaries, algorithmic solutions, and efficient heuristics are all important aspects to be considered in this context. Algorithmic solutions are often based on different combinations of exploration strategies, symbolic manipulations of sets of states, decomposition properties, or reduction to linear programming problems, and they often benefit from approximations, abstractions, accelerations and extrapolation heuristics. Ad hoc solutions as well as solutions based on general purpose constraint solvers and deduction engines are often combined in order to balance efficiency and flexibility.

## Related

- [[Ackermann function]]
- [[Admissible numbering]]
- [[Andreas Brandstädt]]
- [[Blockhead (thought experiment)]]
- [[Bremermann's limit]]
- [[Brooks–Iyengar algorithm]]
- [[Busy beaver]]
- [[Byzantine fault]]
- [[Chain rule for Kolmogorov complexity]]
- [[Chaitin's constant]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reachability_problem