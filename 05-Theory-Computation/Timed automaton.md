---
title: "Timed automaton"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Timed_automaton"
wikipedia_categories: ["Automata (computation)"]
related: ["[[Abstract machine]]", "[[Alternating timed automaton]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Augmented transition network]]", "[[Automata theory]]", "[[Automatic sequence]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[Boolean differential calculus]]", "[[CIP-Tool]]"]
---

# Timed automaton

A timed automaton is a mathematical model in automata theory that extends finite automata with a finite set of real-valued clocks. This formalism, introduced by Rajeev Alur and David Dill in 1994, enables the modeling of systems where timing constraints are crucial.
In a timed automaton, all clock values increase uniformly with passing time. Transitions between states can be constrained by guards—conditions that compare clock values to integers—enabling or disabling transitions based on timing conditions. Clocks can also be reset during transitions. Timed automata are a decidable subclass of hybrid automata, making them theoretically tractable while maintaining significant modeling power.
Timed automata have become fundamental tools for analyzing time-dependent systems, including real-time systems, communication protocols, and embedded systems. Over the past three decades, researchers have developed methods for verifying both safety properties (ensuring bad states are never reached) and liveness properties (ensuring good states are eventually reached).
The proof that the state reachability problem for timed automata is decidable was a breakthrough result that spurred extensive research into various extensions, including stopwatches, real-time tasks, cost functions, and timed games. Several software tools have been developed to specify and analyze timed automata, with UPPAAL, Kronos, and the TIMES schedulability analyzer being notable examples. While these tools continue to mature, they remain primarily academic research instruments.

## Related

- [[Abstract machine]]
- [[Alternating timed automaton]]
- [[Alternating tree automata]]
- [[Asynchronous circuit]]
- [[Augmented transition network]]
- [[Automata theory]]
- [[Automatic sequence]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[Boolean differential calculus]]
- [[CIP-Tool]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Timed_automaton