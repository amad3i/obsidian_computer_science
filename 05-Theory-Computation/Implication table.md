---
title: "Implication table"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Implication_table"
wikipedia_categories: ["Automata (computation)", "Formal methods stubs"]
related: ["[[Abstract machine]]", "[[Alternating timed automaton]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Augmented transition network]]", "[[Automata theory]]", "[[Automath]]", "[[Automatic sequence]]", "[[Axiomatic semantics]]", "[[Behavior tree (artificial intelligence, robotics and control)]]"]
---

# Implication table

An implication table is a tool used to facilitate the minimization of states in a state machine. The concept is to start assuming that every state may be able to combine with every other state, then eliminate combinations that are not possible. When all the impossible combinations have been eliminated, the remaining state combinations are valid, and thus can be combined.
The procedure is as follows:

List state-combination possibilities in an implication table,
Eliminate combinations that are impossible because the states produce different outputs,
Eliminate combinations that are impossible because the combination depends on the equivalence of a previously eliminated possibility,
Repeat the above step until no more eliminations are possible.

## Related

- [[Abstract machine]]
- [[Alternating timed automaton]]
- [[Alternating tree automata]]
- [[Asynchronous circuit]]
- [[Augmented transition network]]
- [[Automata theory]]
- [[Automath]]
- [[Automatic sequence]]
- [[Axiomatic semantics]]
- [[Behavior tree (artificial intelligence, robotics and control)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Implication_table