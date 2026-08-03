---
title: "MINLOG"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/MINLOG"
wikipedia_categories: ["Formal methods stubs", "Proof assistants"]
related: ["[[Automath]]", "[[ACL2]]", "[[ALF (proof assistant)]]", "[[Attempto Controlled English]]", "[[Axiomatic semantics]]", "[[Boolean grammar]]", "[[Dafny]]", "[[Epigram (programming language)]]", "[[F- (programming language)]]", "[[HOL (proof assistant)]]"]
---

# MINLOG

MINLOG is a proof assistant developed at LMU Munich by the team of Helmut Schwichtenberg.
MINLOG is based on first order natural deduction calculus. It is intended to reason about computable functionals, using minimal rather than classical or intuitionistic logic. The primary motivation behind MINLOG is to exploit the proofs-as-programs paradigm for program development and program verification. Proofs are, in fact, treated as first-class objects, which can be normalized. If a formula is existential, then its proof can be used for reading off an instance of it or changed appropriately for program development by proof transformation. To this end, MINLOG is equipped with tools to extract functional programs directly from proof terms. This also applies to non-constructive proofs, using a refined A-translation. The system is supported by automatic proof search and normalization by evaluation as an efficient term rewriting device.

## Related

- [[Automath]]
- [[ACL2]]
- [[ALF (proof assistant)]]
- [[Attempto Controlled English]]
- [[Axiomatic semantics]]
- [[Boolean grammar]]
- [[Dafny]]
- [[Epigram (programming language)]]
- [[F- (programming language)]]
- [[HOL (proof assistant)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MINLOG