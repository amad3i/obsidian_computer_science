---
title: "Trace monoid"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Trace_monoid"
wikipedia_categories: ["Combinatorics", "Formal languages", "Free algebraic structures", "Semigroup theory", "Trace theory"]
related: ["[[Free monoid]]", "[[History monoid]]", "[[Chinese monoid]]", "[[Free convolution]]", "[[Local language (formal language)]]", "[[Longest increasing subsequence]]", "[[Longest repeated substring problem]]", "[[Morphic word]]", "[[Piecewise syndetic set]]", "[[Recurrent word]]"]
---

# Trace monoid

In computer science, a trace is an equivalence class of strings, wherein certain letters in the string are allowed to commute, but others are not. Traces generalize the concept of strings by relaxing the requirement for all the letters to have a definite order, instead allowing for indefinite orderings in which certain reshufflings could take place. In an opposite way, traces generalize the concept of sets with multiplicities by allowing for specifying some incomplete ordering of the letters rather than requiring complete equivalence under all reorderings. The trace monoid or free partially commutative monoid is a monoid of traces.
Traces were introduced by Pierre Cartier and Dominique Foata in 1969 to give a combinatorial proof of MacMahon's master theorem.  Traces are used in theories of concurrent computation, where commuting letters stand for portions of a job that can execute independently of one another, while non-commuting letters stand for locks, synchronization points or thread joins.
The trace monoid is constructed from the free monoid (the set of all strings of finite length) as follows. First, sets of commuting letters are given by an independency relation. These induce an equivalence relation of equivalent strings; the elements of the equivalence classes are the traces. The equivalence relation then partitions the elements of the free monoid into a set of equivalence classes; the result is still a monoid; it is a quotient monoid now called the trace monoid. The trace monoid is universal, in that all dependency-homomorphic (see below) monoids are in fact isomorphic.
Trace monoids are commonly used to model concurrent computation, forming the foundation for process calculi. They are the object of study in trace theory. The utility of trace monoids comes from the fact that they are isomorphic to the monoid of dependency graphs; thus allowing algebraic techniques to be applied to graphs, and vice versa. They are also isomorphic to history monoids, which model the history of computation of individual processes in the context of all scheduled processes on one or more computers.

## Related

- [[Free monoid]]
- [[History monoid]]
- [[Chinese monoid]]
- [[Free convolution]]
- [[Local language (formal language)]]
- [[Longest increasing subsequence]]
- [[Longest repeated substring problem]]
- [[Morphic word]]
- [[Piecewise syndetic set]]
- [[Recurrent word]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Trace_monoid