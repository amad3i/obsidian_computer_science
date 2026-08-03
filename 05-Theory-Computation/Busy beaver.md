---
title: "Busy beaver"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Busy_beaver"
wikipedia_categories: ["Computability theory", "Large integers", "Metaphors referring to aquatic life", "Metaphors referring to rodents", "Theory of computation"]
related: ["[[Ackermann function]]", "[[Admissible numbering]]", "[[Chain rule for Kolmogorov complexity]]", "[[Church–Turing thesis]]", "[[Church–Turing–Deutsch principle]]", "[[Computability]]", "[[Computable function]]", "[[Computable number]]", "[[Computable set]]", "[[Computably enumerable set]]"]
---

# Busy beaver

In theoretical computer science, the busy beaver game aims to find a terminating program of a given size that (depending on definition) either produces the most output possible, or runs for the longest number of steps. Since an endlessly looping program producing infinite output or running for infinite time is easily conceived, such programs are excluded from the game. Rather than traditional programming languages, the programs used in the game are n-state Turing machines, one of the first mathematical models of computation.
Turing machines consist of an infinite tape, and a finite set of states which serve as the program's "source code". Producing the most output is defined as writing the largest number of 1s on the tape, also referred to as achieving the highest score, and running for the longest time is defined as taking the longest number of steps to halt. The n-state busy beaver game consists of finding the longest-running or highest-scoring Turing machine which has n states and eventually halts. Such machines are assumed to start on a blank tape, and the tape is assumed to contain only zeros and ones (a binary Turing machine). The objective of the game is to program a set of transitions between states aiming for the highest score or longest running time while making sure the machine will halt eventually.
Deciding the running time or score of the nth busy beaver is noncomputable. In fact, both the functions Σ(n) and S(n) eventually become larger than any computable function. This has implications in computability theory, the halting problem, and complexity theory. The concept of a busy beaver was first introduced by Tibor Radó in his 1962 paper, "On Non-Computable Functions".
An implication of the busy beaver game is that, if it were possible to compute the functions Σ(n) and S(n) for all n, then this would resolve all mathematical conjectures that can be reduced to a halting problem, e.g., into a form of "does ⟨this Turing machine⟩ halt". For example, there is a 25-state Turing machine that checks Goldbach's conjecture for each number and halts on a counterexample; if this machine did not halt after running for S(25) steps, then it must run forever, resolving the conjecture. Many other problems, including the Riemann hypothesis (744 states) and the consistency of ZF set theory (745 states), can be expressed in a similar form, where at most a countably infinite number of cases need to be checked.

## Related

- [[Ackermann function]]
- [[Admissible numbering]]
- [[Chain rule for Kolmogorov complexity]]
- [[Church–Turing thesis]]
- [[Church–Turing–Deutsch principle]]
- [[Computability]]
- [[Computable function]]
- [[Computable number]]
- [[Computable set]]
- [[Computably enumerable set]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Busy_beaver