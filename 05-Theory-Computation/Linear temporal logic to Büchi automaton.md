---
title: "Linear temporal logic to Büchi automaton"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Linear_temporal_logic_to_Büchi_automaton"
wikipedia_categories: ["Automata (computation)", "Model checking", "Temporal logic"]
related: ["[[Alternating timed automaton]]", "[[Clock (model checking)]]", "[[Computation tree logic]]", "[[Generalized Büchi automaton]]", "[[Kripke structure (model checking)]]", "[[Metric interval temporal logic]]", "[[Metric temporal logic]]", "[[Timed propositional temporal logic]]", "[[Abstract machine]]", "[[Abstract model checking]]"]
---

# Linear temporal logic to Büchi automaton

In formal verification (a methodology from computer science), finite state model checking needs to find a Büchi automaton (BA) equivalent to a given linear temporal logic (LTL) formula, i.e., such that the LTL formula and the BA recognize the same ω-language. There are algorithms that translate an LTL formula to a BA. This transformation is normally done in two steps. The first step produces a generalized Büchi automaton (GBA) from a LTL formula. The second step translates this GBA into a BA, which involves a relatively easy construction. Since LTL is strictly less expressive than BA, the reverse construction is not always possible.
The algorithms for transforming LTL to GBA differ in their construction strategies but they  all have a common underlying principle, i.e., each state in the constructed automaton represents a set of LTL formulas that are expected to be satisfied by the remaining input word after occurrence of the state during a run.

## Related

- [[Alternating timed automaton]]
- [[Clock (model checking)]]
- [[Computation tree logic]]
- [[Generalized Büchi automaton]]
- [[Kripke structure (model checking)]]
- [[Metric interval temporal logic]]
- [[Metric temporal logic]]
- [[Timed propositional temporal logic]]
- [[Abstract machine]]
- [[Abstract model checking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Linear_temporal_logic_to_Büchi_automaton