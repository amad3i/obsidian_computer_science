---
title: "Computation history"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Computation_history"
wikipedia_categories: ["Theory of computation"]
related: ["[[Ackermann function]]", "[[Admissible numbering]]", "[[Andreas Brandstädt]]", "[[Blockhead (thought experiment)]]", "[[Bremermann's limit]]", "[[Brooks–Iyengar algorithm]]", "[[Busy beaver]]", "[[Byzantine fault]]", "[[Chain rule for Kolmogorov complexity]]", "[[Chaitin's constant]]"]
---

# Computation history

In computer science, a computation history is a sequence of steps taken by an abstract machine in the process of computing its result.  Computation histories are frequently used in proofs about the capabilities of certain machines, and particularly about the undecidability of various formal languages.
Formally, a computation history is a (normally finite) sequence of configurations of a formal automaton.  Each configuration fully describes the status of the machine at a particular point.  To be valid, certain conditions must hold:

the first configuration must be a valid initial configuration of the automaton and
each transition between adjacent configurations must be valid according to the transition rules of the automaton.
In addition, to be complete, a computation history must be finite and

the final configuration must be a valid terminal configuration of the automaton.
The definitions of "valid initial configuration", "valid transition", and "valid terminal configuration" vary for different kinds of formal machines.
A deterministic automaton has exactly one computation history for a given initial configuration, though the history may be infinite and therefore incomplete.

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

- Wikipedia: https://en.wikipedia.org/wiki/Computation_history