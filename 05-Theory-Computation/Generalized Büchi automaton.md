---
title: "Generalized Büchi automaton"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Generalized_Büchi_automaton"
wikipedia_categories: ["Automata (computation)", "Model checking"]
related: ["[[Alternating timed automaton]]", "[[Clock (model checking)]]", "[[Linear temporal logic to Büchi automaton]]", "[[Abstract machine]]", "[[Abstract model checking]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Augmented transition network]]", "[[Automata theory]]", "[[Automatic sequence]]"]
---

# Generalized Büchi automaton

In automata theory, a generalized Büchi automaton is a variant of a Büchi automaton. The difference with the Büchi automaton is the accepting condition, which is determined by a set of sets of states.  A run is accepted by the automaton if it visits at least one state of every set of the accepting condition infinitely often. Generalized Büchi automata are equivalent in expressive power to Büchi automata; a transformation is given here.
In formal verification, the model checking method needs to obtain an automaton from a LTL formula that specifies the desired program property. There are algorithms that translate a LTL formula
into a generalized Büchi automaton.
for this purpose. The notion of generalized Büchi automaton was introduced specifically for this translation.

## Related

- [[Alternating timed automaton]]
- [[Clock (model checking)]]
- [[Linear temporal logic to Büchi automaton]]
- [[Abstract machine]]
- [[Abstract model checking]]
- [[Alternating tree automata]]
- [[Asynchronous circuit]]
- [[Augmented transition network]]
- [[Automata theory]]
- [[Automatic sequence]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Generalized_Büchi_automaton