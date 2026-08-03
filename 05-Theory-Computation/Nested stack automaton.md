---
title: "Nested stack automaton"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Nested_stack_automaton"
wikipedia_categories: ["Automata (computation)", "Models of computation"]
related: ["[[Abstract machine]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[CIP-Tool]]", "[[Deterministic pushdown automaton]]", "[[Discrete system]]", "[[Embedded pushdown automaton]]", "[[Lazy linear hybrid automaton]]", "[[Linear bounded automaton]]", "[[Pushdown automaton]]", "[[Queue automaton]]"]
---

# Nested stack automaton

In automata theory, a nested stack automaton is a finite automaton that can make use of a stack containing data that can be additional stacks.  
Like a stack automaton, a nested stack automaton may step up or down in the stack, and read the current symbol; in addition, it may at any place create a new stack, operate on that one, eventually destroy it, and continue operating on the old stack. This way, stacks can be nested recursively to an arbitrary depth; however, the automaton always operates on the innermost stack only.
A nested stack automaton is capable of recognizing an indexed language, and in fact the class of indexed languages is exactly the class of languages accepted by one-way nondeterministic nested stack automata.
Nested stack automata should not be confused with embedded pushdown automata, which have less computational power.

## Related

- [[Abstract machine]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[CIP-Tool]]
- [[Deterministic pushdown automaton]]
- [[Discrete system]]
- [[Embedded pushdown automaton]]
- [[Lazy linear hybrid automaton]]
- [[Linear bounded automaton]]
- [[Pushdown automaton]]
- [[Queue automaton]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nested_stack_automaton