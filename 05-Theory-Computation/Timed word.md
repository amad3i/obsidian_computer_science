---
title: "Timed word"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Timed_word"
wikipedia_categories: ["Model checking"]
related: ["[[Abstract model checking]]", "[[Alternating timed automaton]]", "[[Binary decision diagram]]", "[[Büchi automaton]]", "[[Clock (model checking)]]", "[[Counterexample-guided abstraction refinement]]", "[[Generalized Büchi automaton]]", "[[Kripke structure (model checking)]]", "[[Linear temporal logic to Büchi automaton]]", "[[Linear time property]]"]
---

# Timed word

In model checking, a subfield of computer science, a timed word is an extension of the notion of words, in a formal language, in which each letter is associated with a positive time tag. The sequence of time tags must be non-decreasing, which intuitively means that letters are received. For example, a system receiving a word over a network may associate to each letter the time at which the letter is received. The non-decreasing condition here means that the letters are received in the correct order.
A timed language is a set of timed words.

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

- Wikipedia: https://en.wikipedia.org/wiki/Timed_word