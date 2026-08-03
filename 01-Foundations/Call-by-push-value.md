---
title: "Call-by-push-value"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Call-by-push-value"
wikipedia_categories: ["Lambda calculus", "Programming language semantics"]
related: ["[[Normalisation by evaluation]]", "[[Algebraic semantics (computer science)]]", "[[Anonymous function]]", "[[Applicative computing systems]]", "[[Axiomatic semantics]]", "[[B, C, K, W system]]", "[[Beta normal form]]", "[[Böhm tree]]", "[[Calculus of constructions]]", "[[Cartesian closed category]]"]
---

# Call-by-push-value

In programming language theory, call-by-push-value (CBPV) is an intermediate language that embeds the call-by-value (CBV) and call-by-name (CBN) evaluation strategies. CBPV is structured as a polarized λ-calculus with two main types, "values" (+) and "computations" (-). Restrictions on interactions between the two types enforce a controlled order of evaluation, similar to monads or CPS. The calculus can embed computational effects, such as nontermination, mutable state, or nondeterminism. There are natural semantics-preserving translations from CBV and CBN into CBPV. This means that giving a CBPV semantics and proving its properties implicitly establishes CBV and CBN semantics and properties as well. Paul Blain Levy formulated and developed CBPV in several papers and his doctoral thesis.

## Related

- [[Normalisation by evaluation]]
- [[Algebraic semantics (computer science)]]
- [[Anonymous function]]
- [[Applicative computing systems]]
- [[Axiomatic semantics]]
- [[B, C, K, W system]]
- [[Beta normal form]]
- [[Böhm tree]]
- [[Calculus of constructions]]
- [[Cartesian closed category]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Call-by-push-value