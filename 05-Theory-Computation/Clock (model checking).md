---
title: "Clock (model checking)"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Clock_(model_checking)"
wikipedia_categories: ["Automata (computation)", "Model checking"]
related: ["[[Alternating timed automaton]]", "[[Generalized Büchi automaton]]", "[[Linear temporal logic to Büchi automaton]]", "[[Abstract machine]]", "[[Abstract model checking]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Augmented transition network]]", "[[Automata theory]]", "[[Automatic sequence]]"]
---

# Clock (model checking)

In model checking, a subfield of computer science, a clock is a mathematical object used to model time. More precisely, a clock measures how much time passed since a particular event occurs, in this sense, a clock is more precisely an abstraction of a stopwatch. In a model of some particular program, the value of the clock may either be the time since the program was started, or the time since a particular event occurred in the program. Those clocks are used in the definition of timed automaton, signal automaton, timed propositional temporal logic and clock temporal logic. They are also used in programs such as UPPAAL which implement timed automata.
Generally, the model of a system uses many clocks. Those multiple clocks are required in order to track a bounded number of events. All of those clocks are synchronized. That means that the difference in value between two fixed clocks is constant until one of them is restarted. In the language of electronics, it means that clock's jitter is null.

## Related

- [[Alternating timed automaton]]
- [[Generalized Büchi automaton]]
- [[Linear temporal logic to Büchi automaton]]
- [[Abstract machine]]
- [[Abstract model checking]]
- [[Alternating tree automata]]
- [[Asynchronous circuit]]
- [[Augmented transition network]]
- [[Automata theory]]
- [[Automatic sequence]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Clock_(model_checking)