---
title: "Büchi automaton"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Büchi_automaton"
wikipedia_categories: ["Finite-state machines", "Infinite words", "Model checking"]
related: ["[[Muller automaton]]", "[[Abstract model checking]]", "[[Alternating timed automaton]]", "[[Binary decision diagram]]", "[[Clock (model checking)]]", "[[Cobham's theorem]]", "[[Counterexample-guided abstraction refinement]]", "[[Finite-state machine]]", "[[Generalized Büchi automaton]]", "[[Kleene's algorithm]]"]
---

# Büchi automaton

In computer science and automata theory, a deterministic Büchi automaton is a theoretical machine which either accepts or rejects infinite inputs. Such a machine has a set of states and a transition function, which determines which state the machine should move to from its current state when it reads the next input character. Some states are accepting states and one state is the start state. The machine accepts an input if and only if it will pass through an accepting state infinitely many times as it reads the input.
A non-deterministic Büchi automaton, later referred to just as a Büchi automaton, has a transition function which may have multiple outputs, leading to many possible paths for the same input; it accepts an infinite input if and only if some possible path is accepting. Deterministic and non-deterministic Büchi automata generalize deterministic finite automata and nondeterministic finite automata to infinite inputs. Each are types of ω-automata. Büchi automata recognize the ω-regular languages, the infinite word version of regular languages. They are named after the Swiss mathematician Julius Richard Büchi, who invented them in 1962.
Büchi automata are often used in model checking as an automata-theoretic version of a formula in linear temporal logic.

## Related

- [[Muller automaton]]
- [[Abstract model checking]]
- [[Alternating timed automaton]]
- [[Binary decision diagram]]
- [[Clock (model checking)]]
- [[Cobham's theorem]]
- [[Counterexample-guided abstraction refinement]]
- [[Finite-state machine]]
- [[Generalized Büchi automaton]]
- [[Kleene's algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Büchi_automaton