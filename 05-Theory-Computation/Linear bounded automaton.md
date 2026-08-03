---
title: "Linear bounded automaton"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Linear_bounded_automaton"
wikipedia_categories: ["Automata (computation)", "Models of computation"]
related: ["[[Abstract machine]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[CIP-Tool]]", "[[Deterministic pushdown automaton]]", "[[Discrete system]]", "[[Embedded pushdown automaton]]", "[[Lazy linear hybrid automaton]]", "[[Nested stack automaton]]", "[[Pushdown automaton]]", "[[Queue automaton]]"]
---

# Linear bounded automaton

In computer science, a linear bounded automaton (abbreviated LBA) is a restricted form of Turing machine that functions as a more accurate model of a real-world computer, as its definition does not assume an unlimited tape.
Formally, it satisfies the following three conditions:

Its input alphabet includes two special symbols, serving as left and right endmarkers.
Its transitions may not print other symbols over the endmarkers.
Its transitions may neither move to the left of the left endmarker nor to the right of the right endmarker.
In other words: 
instead of having potentially infinite tape on which to compute, computation is restricted to the portion of the tape containing the input plus the two tape squares holding the endmarkers. 
An alternative, less restrictive definition is as follows:

Like a Turing machine, an LBA possesses a tape made up of cells that can contain symbols from a finite alphabet, a head that can read from or write to one cell on the tape at a time and can be moved, and a finite number of states.
An LBA differs from a Turing machine in that while the tape is initially considered to have unbounded length, only a finite contiguous portion of the tape, whose length is a linear function of the length of the initial input, can be accessed by the read/write head; hence the name linear bounded automaton.
The strong and the weaker definition lead to the same computational abilities of the respective automaton classes, by the same argument used to prove the linear speedup theorem.

## Related

- [[Abstract machine]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[CIP-Tool]]
- [[Deterministic pushdown automaton]]
- [[Discrete system]]
- [[Embedded pushdown automaton]]
- [[Lazy linear hybrid automaton]]
- [[Nested stack automaton]]
- [[Pushdown automaton]]
- [[Queue automaton]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Linear_bounded_automaton