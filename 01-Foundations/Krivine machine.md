---
title: "Krivine machine"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Krivine_machine"
wikipedia_categories: ["Abstract machines", "Computability theory", "Educational abstract machines", "Lambda calculus", "Models of computation", "Operational semantics", "Programming language implementation", "Theoretical computer science"]
related: ["[[Random-access Turing machine]]", "[[Turing machine]]", "[[Lambda calculus]]", "[[Description number]]", "[[LogP machine]]", "[[Abstract machine]]", "[[Algorithm characterizations]]", "[[Applicative computing systems]]", "[[Explicit substitution]]", "[[Glossary of quantum computing]]"]
---

# Krivine machine

In theoretical computer science, the Krivine machine is an abstract machine.  As an abstract machine, it shares features with Turing machines and the SECD machine. The Krivine machine explains how to compute a recursive function.  More specifically it aims to define rigorously head normal form reduction of a lambda term using call-by-name reduction.  Thanks to its formalism, it tells in details how a kind of reduction works and sets the theoretical foundation of the operational semantics of functional programming languages.  On the other hand, Krivine machine implements call-by-name because it evaluates the body of a β-redex before it applies the body to its parameter. In other words, in an expression (λ x. t) u it evaluates first λ x. t before applying it to u. In functional programming, this would mean that in order to evaluate a function applied to a parameter, it evaluates first the function before applying it to the parameter.
The Krivine machine was designed by the French logician Jean-Louis Krivine at the beginning of the 1980s.

## Related

- [[Random-access Turing machine]]
- [[Turing machine]]
- [[Lambda calculus]]
- [[Description number]]
- [[LogP machine]]
- [[Abstract machine]]
- [[Algorithm characterizations]]
- [[Applicative computing systems]]
- [[Explicit substitution]]
- [[Glossary of quantum computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Krivine_machine