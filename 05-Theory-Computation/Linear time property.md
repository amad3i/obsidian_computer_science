---
title: "Linear time property"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Linear_time_property"
wikipedia_categories: ["Model checking"]
related: ["[[Abstract model checking]]", "[[Alternating timed automaton]]", "[[Binary decision diagram]]", "[[Büchi automaton]]", "[[Clock (model checking)]]", "[[Counterexample-guided abstraction refinement]]", "[[Generalized Büchi automaton]]", "[[Kripke structure (model checking)]]", "[[Linear temporal logic to Büchi automaton]]", "[[Metric interval temporal logic]]"]
---

# Linear time property

In model checking, a branch of computer science, linear time properties are used to describe requirements of a model of a computer system. Example properties include "the vending machine does not dispense a drink until money has been entered" (a safety property) or "the computer program eventually terminates" (a liveness property). Fairness properties can be used to rule out unrealistic paths of a model. For instance, in a model of two traffic lights, the liveness property "both traffic lights are green infinitely often" may only be true under the unconditional fairness constraint "each traffic light changes colour infinitely often" (to exclude the case where one traffic light is "infinitely faster" than the other).
Formally, a linear time property is an ω-language over the power set of "atomic propositions". That is, the property contains sequences of sets of propositions, each sequence known as a "word". Every property can be rewritten as "P and Q both occur" for some safety property P and liveness property Q. An invariant for a system is something that is true or false for a particular state. Invariant properties describe an invariant that every reachable state of a model must satisfy, while persistence properties are of the form "eventually forever some invariant holds".
Temporal logics such as linear temporal logic describe types of linear time properties using formulae.
This article is about propositional linear-time properties and cannot handle predicates about program states, so it cannot define a property like: the current value of y determines the number of times that x toggles between 0 and 1 before termination. The more general formalism used in Safety and liveness properties can handle this.

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
- [[Metric interval temporal logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Linear_time_property