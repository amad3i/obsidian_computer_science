---
title: "Proof complexity"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Proof_complexity"
wikipedia_categories: ["Automated theorem proving", "Computational complexity theory", "Logic in computer science"]
related: ["[[Propositional proof system]]", "[[Automated reasoning]]", "[[Boolean circuit]]", "[[Model elimination]]", "[[Proof (truth)]]", "[[Unification (computer science)]]", "[[WalkSAT]]", "[[1-in-3-SAT]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Abstract rewriting system]]"]
---

# Proof complexity

In logic and theoretical computer science, and specifically proof theory and computational complexity theory, proof complexity is the field aiming to understand and analyse the computational resources that are required to prove or refute statements. Research in proof complexity is predominantly concerned with proving proof-length lower and upper bounds in various propositional proof systems. For example, among the major challenges of proof complexity is showing that the Frege system, the usual propositional calculus, does not admit polynomial-size proofs of all tautologies. Here the size of the proof is simply the number of symbols in it, and a proof is said to be of polynomial size if it is polynomial in the size of the tautology it proves.
Systematic study of proof complexity began with the work of Stephen Cook and Robert Reckhow (1979), who provided the basic definition of a propositional proof system from the perspective of computational complexity. Specifically, Cook and Reckhow observed that proving proof size lower bounds on stronger and stronger propositional proof systems can be viewed as a step towards separating NP from co-NP (and thus P from NP), since the existence of a propositional proof system that admits polynomial size proofs for all tautologies is equivalent to NP = co-NP.
Contemporary proof complexity research draws ideas and methods from many areas in computational complexity, algorithms and mathematics. Since many important algorithms and algorithmic techniques can be cast as proof search algorithms for certain proof systems, proving lower bounds on proof sizes in these systems implies run-time lower bounds on the corresponding algorithms. This connects proof complexity to more applied areas such as SAT solving.
Mathematical logic can also serve as a framework to study propositional proof sizes. First-order theories and, in particular, weak fragments of Peano arithmetic, which come under the name of bounded arithmetic, serve as uniform versions of propositional proof systems and provide further background for interpreting short propositional proofs in terms of various levels of feasible reasoning.

## Related

- [[Propositional proof system]]
- [[Automated reasoning]]
- [[Boolean circuit]]
- [[Model elimination]]
- [[Proof (truth)]]
- [[Unification (computer science)]]
- [[WalkSAT]]
- [[1-in-3-SAT]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Abstract rewriting system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Proof_complexity