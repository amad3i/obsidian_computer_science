---
title: "Deterministic pushdown automaton"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Deterministic_pushdown_automaton"
wikipedia_categories: ["Automata (computation)", "Formal languages", "Models of computation"]
related: ["[[Random-access Turing machine]]", "[[Turing machine]]", "[[Abstract machine]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[CIP-Tool]]", "[[Conference on Implementation and Application of Automata]]", "[[Discrete system]]", "[[Embedded pushdown automaton]]", "[[Formal grammar]]", "[[Generalized star-height problem]]"]
---

# Deterministic pushdown automaton

In automata theory, a deterministic pushdown automaton (DPDA or DPA) is a variation of the pushdown automaton. The class of deterministic pushdown automata accepts the deterministic context-free languages, a proper subset of context-free languages.
Machine transitions are based on the current state and input symbol, and also the current topmost symbol of the stack.  Symbols lower in the stack are not visible and have no immediate effect. Machine actions include pushing, popping, or replacing the stack top.  A deterministic pushdown automaton has at most one legal transition for the same combination of input symbol, state, and top stack symbol. This is where it differs from the nondeterministic pushdown automaton.

## Related

- [[Random-access Turing machine]]
- [[Turing machine]]
- [[Abstract machine]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[CIP-Tool]]
- [[Conference on Implementation and Application of Automata]]
- [[Discrete system]]
- [[Embedded pushdown automaton]]
- [[Formal grammar]]
- [[Generalized star-height problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Deterministic_pushdown_automaton