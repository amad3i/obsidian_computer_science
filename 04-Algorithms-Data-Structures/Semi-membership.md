---
title: "Semi-membership"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Semi-membership"
wikipedia_categories: ["Computational complexity theory", "Theoretical computer science stubs"]
related: ["[[Compression theorem]]", "[[Effective complexity]]", "[[Generalized game]]", "[[Logical depth]]", "[[Transdichotomous model]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]"]
---

# Semi-membership

In mathematics and theoretical computer science, the semi-membership problem for a set is the problem of deciding which of two possible elements is logically more likely to belong to that set; alternatively, given two elements of which at least one is in the set, to distinguish the member from the non-member.
The semi-membership problem may be significantly easier than the membership problem.  For example, consider the set S(x) of finite-length binary strings representing the dyadic rationals less than some fixed real number x.  The semi-membership problem for a pair of strings is solved by taking the string representing the smaller dyadic rational, since if exactly one of the strings is an element, it must be the smaller, irrespective of the value of x.  However, the language S(x) may not even be a  recursive language, since there are uncountably many such x, but only countably many recursive languages.
A function f on ordered pairs (x,y) is a selector for a set S if f(x,y) is equal to either x or y and if f(x,y) is in S whenever at least one of x, y is in S.  A set is semi-recursive if it has a recursive selector, and is P-selective or semi-feasible if it is semi-recursive with a polynomial time selector.
Semi-feasible sets have small circuits; they are in the extended low hierarchy; and cannot be NP-complete unless P=NP.

## Related

- [[Compression theorem]]
- [[Effective complexity]]
- [[Generalized game]]
- [[Logical depth]]
- [[Transdichotomous model]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Semi-membership