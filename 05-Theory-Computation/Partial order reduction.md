---
title: "Partial order reduction"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Partial_order_reduction"
wikipedia_categories: ["Model checking"]
related: ["[[Abstract model checking]]", "[[Alternating timed automaton]]", "[[Binary decision diagram]]", "[[Büchi automaton]]", "[[Clock (model checking)]]", "[[Counterexample-guided abstraction refinement]]", "[[Generalized Büchi automaton]]", "[[Kripke structure (model checking)]]", "[[Linear temporal logic to Büchi automaton]]", "[[Linear time property]]"]
---

# Partial order reduction

In computer science, partial order reduction is a technique for reducing the size of the state-space to be searched by a model checking or automated planning and scheduling algorithm. It exploits the commutativity of concurrently executed transitions that result in the same state when executed in different orders.
In explicit state space exploration, partial order reduction usually refers to the specific technique of expanding a representative subset of all enabled transitions. This technique has also been described as model checking with representatives. There are various versions of the method, the so-called stubborn set method, ample set method, and persistent set method.

## Related

- [[Abstract model checking]]
- [[Alternating timed automaton]]
- [[Binary decision diagram]]
- [[Büchi automaton]]
- [[Clock (model checking)]]
- [[Counterexample-guided abstraction refinement]]
- [[Generalized Büchi automaton]]
- [[Kripke structure (model checking)]]
- [[Linear temporal logic to Büchi automaton]]
- [[Linear time property]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Partial_order_reduction