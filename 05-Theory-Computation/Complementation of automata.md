---
title: "Complementation of automata"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Complementation_of_automata"
wikipedia_categories: ["Automata (computation)"]
related: ["[[Abstract machine]]", "[[Alternating timed automaton]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Augmented transition network]]", "[[Automata theory]]", "[[Automatic sequence]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[Boolean differential calculus]]", "[[CIP-Tool]]"]
---

# Complementation of automata

In theoretical computer science and formal language theory, complementation is a computational problem that applies to automata. An automaton is an abstract machine that verifies a property on its inputs, and either accepts it (if the property is verified) or rejects it (if the property is not verified). The complement of an automaton is another automaton that accepts precisely what the other one rejects, and vice-versa. More precisely, an automaton A defines a formal language L formed of the inputs that A accepts, and complementation is the problem of computing a "complement" automaton that precisely recognizes the words that are not in L, i.e., the complement of L.
Several questions on the complementation operation are studied in automata theory research, such as:

Expressiveness: Do complement automata always exist? The answer depends on the automaton formalism used to represent the input automaton A and the complement automaton. For instance, if A is a finite automaton, then a complement automaton for A as a finite automaton always exists, because the regular languages are closed under complementation. In contrast, there are pushdown automata that do not have a complement pushdown automaton.
Decidability: Is there an algorithm that takes as input an automaton A and performs automaton complementation (i.e., builds the complement automaton), or can the task be undecidable? Again, the answer to this question depends on the automaton class used to represent the input and output of the complementation problem.
Computational complexity: If complement automata exist, and if computing them is decidable, then we can ask what is the computational complexity of the complementation operation: given an automaton, how efficiently can we compute a complement automaton, e.g., in time complexity?
State complexity: When complement automata exist, what is the smallest number of states that they require, as a function of the number of states of the input automaton?

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

- Wikipedia: https://en.wikipedia.org/wiki/Complementation_of_automata