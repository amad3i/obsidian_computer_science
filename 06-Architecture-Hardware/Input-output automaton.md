---
title: "Input/output automaton"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Input/output_automaton"
wikipedia_categories: ["Distributed computing"]
related: ["[[ActivityPub]]", "[[AT Protocol]]", "[[Availability zone]]", "[[Botnet]]", "[[CAP theorem]]", "[[CockroachDB]]", "[[Collective operation]]", "[[Comparison of synchronous and asynchronous signalling]]", "[[Confidential Consortium Framework]]", "[[Consensus dynamics]]"]
---

# Input/output automaton

Input/output automata provide a formal model, applicable in describing most types of an asynchronous concurrent system. On its own, the I/O automaton model contains a very basic structure that enables it to model various types of
distributed systems. To describe specific types of asynchronous systems, additional structure must be added to this basic model. The model presents an explicit method for describing and reasoning about system components such as processes and message channels that interact with one another, operating at arbitrary relative speeds. The I/O automata were first introduced by Nancy A. Lynch and Mark R. Tuttle in "Hierarchical correctness proofs for distributed algorithms", 1987.
"An I/O automaton models a distributed system component that can interact with other system components. It is a simple type of state machine in which the transitions are associated with named actions."
There are three types of actions: input, output, and internal actions. The automaton uses its input and output actions to communicate with its environment, whereas the internal actions are only visible to the automaton itself. Unlike internal and output actions that are selected and carried out by the automaton, the input actions – which simply arrive from the environment - are not under automaton's control.

## Related

- [[ActivityPub]]
- [[AT Protocol]]
- [[Availability zone]]
- [[Botnet]]
- [[CAP theorem]]
- [[CockroachDB]]
- [[Collective operation]]
- [[Comparison of synchronous and asynchronous signalling]]
- [[Confidential Consortium Framework]]
- [[Consensus dynamics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Input/output_automaton