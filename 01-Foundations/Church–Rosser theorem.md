---
title: "Church–Rosser theorem"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Church–Rosser_theorem"
wikipedia_categories: ["Lambda calculus", "Rewriting systems", "Theorems in the foundations of mathematics"]
related: ["[[Director string]]", "[[Divergence (computer science)]]", "[[Explicit substitution]]", "[[Normal form (abstract rewriting)]]", "[[Reduction strategy]]", "[[Scott–Curry theorem]]", "[[Abstract rewriting system]]", "[[Anonymous function]]", "[[Applicative computing systems]]", "[[B, C, K, W system]]"]
---

# Church–Rosser theorem

In lambda calculus, the Church–Rosser theorem states that, when applying reduction rules to terms,  the ordering in which the reductions are chosen does not make a difference to the eventual result.
More precisely, if there are two distinct reductions or sequences of reductions that can be applied to the same term, then there exists a term that is reachable from both results, by applying (possibly empty) sequences of additional reductions. The theorem was proved in 1936 by Alonzo Church and J. Barkley Rosser, after whom it is named.
The theorem is symbolized by the adjacent diagram: If term a can be reduced to both b and c, then there must be a further term d (possibly equal to either b or c) to which both b and c can be reduced.
Viewing the lambda calculus as an abstract rewriting system, the Church–Rosser theorem states that the reduction rules of the lambda calculus are confluent.  As a consequence of the theorem, a term in the lambda calculus has at most one normal form, justifying reference to "the normal form" of a given normalizable term.

## Related

- [[Director string]]
- [[Divergence (computer science)]]
- [[Explicit substitution]]
- [[Normal form (abstract rewriting)]]
- [[Reduction strategy]]
- [[Scott–Curry theorem]]
- [[Abstract rewriting system]]
- [[Anonymous function]]
- [[Applicative computing systems]]
- [[B, C, K, W system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Church–Rosser_theorem