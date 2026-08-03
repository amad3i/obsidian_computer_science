---
title: "System U"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/System_U"
wikipedia_categories: ["Lambda calculus", "Proof theory", "Type theory"]
related: ["[[Pure type system]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Calculus of constructions]]", "[[Curry–Howard correspondence]]", "[[Hindley–Milner type system]]", "[[Implicit computational complexity]]", "[[Intersection type discipline]]", "[[Lambda cube]]", "[[Lambda-mu calculus]]", "[[Simply typed lambda calculus]]"]
---

# System U

In type theory and mathematical logic, System U and System U− are two closely related pure type systems (PTS), i.e. typed λ-calculi specified by a finite set of sorts (universes), axioms between sorts, and rules describing which kinds of dependent function spaces (Π-types) may be formed.
System U is historically important because it is strong enough to express a form of "type-in-type"/impredicativity that leads to Girard's paradox. Girard proved System U inconsistent in 1972. A later simplification due to Hurkens shows that even the restricted variant System U− suffices for a paradox; for example, the Coq/Rocq standard library explicitly presents "Hurkens's paradox … for system U−" as a derivation of false.
These inconsistency results influenced the design of later type theories and proof assistants, which typically use a hierarchy of universes rather than a single universe containing itself.

## Related

- [[Pure type system]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Calculus of constructions]]
- [[Curry–Howard correspondence]]
- [[Hindley–Milner type system]]
- [[Implicit computational complexity]]
- [[Intersection type discipline]]
- [[Lambda cube]]
- [[Lambda-mu calculus]]
- [[Simply typed lambda calculus]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/System_U