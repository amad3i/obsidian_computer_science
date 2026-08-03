---
title: "Automata-based programming"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Automata-based_programming"
wikipedia_categories: ["Programming paradigms"]
related: ["[[Array programming]]", "[[Aspect-oriented programming]]", "[[Attribute-oriented programming]]", "[[Automata-based programming (Shalyto's approach)]]", "[[Automatic programming]]", "[[Choreographic programming]]", "[[Comparison of multi-paradigm programming languages]]", "[[Concurrent constraint logic programming]]", "[[Concurrent logic programming]]", "[[Concurrent object-oriented programming]]"]
---

# Automata-based programming

Automata-based programming is a programming paradigm in which the program or part of it is thought of as a model of a finite-state machine (FSM) or any other (often more complicated) formal automaton (see automata theory). Sometimes a potentially infinite set of possible states is introduced, and such a set can have a complicated structure, not just an enumeration.
Finite-state machine-based programming is generally the same, but, formally speaking, does not cover all possible variants, as FSM stands for finite-state machine, and automata-based programming does not necessarily employ FSMs in the strict sense.
The following properties are key indicators for automata-based programming:

The time period of the program's execution is clearly separated down to the automaton steps. Each step is effectively an execution of a code section (same for all the steps) which has a single entry point. That section might be divided down to subsections to be executed depending on different states, although this is not necessary.
Any communication between the automaton steps is only possible via the explicitly noted set of variables named the automaton state. Between any two steps, the program cannot have implicit components of its state, such as local variables' values, return addresses, the current instruction pointer, etc. That is, the state of the whole program, taken at any two moments of entering an automaton step, can only differ in the values of the variables being considered as the automaton state.
The whole execution of the automata-based code is a cycle of the automaton steps.
Another reason for using the notion of automata-based programming is that the programmer's style of thinking about the program in this technique is very similar to the style of thinking used to solve mathematical tasks using Turing machines, Markov algorithms, etc.

## Related

- [[Array programming]]
- [[Aspect-oriented programming]]
- [[Attribute-oriented programming]]
- [[Automata-based programming (Shalyto's approach)]]
- [[Automatic programming]]
- [[Choreographic programming]]
- [[Comparison of multi-paradigm programming languages]]
- [[Concurrent constraint logic programming]]
- [[Concurrent logic programming]]
- [[Concurrent object-oriented programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Automata-based_programming