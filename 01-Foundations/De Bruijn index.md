---
title: "De Bruijn index"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/De_Bruijn_index"
wikipedia_categories: ["Lambda calculus"]
related: ["[[Anonymous function]]", "[[Applicative computing systems]]", "[[B, C, K, W system]]", "[[Beta normal form]]", "[[Böhm tree]]", "[[Calculus of constructions]]", "[[Call-by-push-value]]", "[[Cartesian closed category]]", "[[Church encoding]]", "[[Church–Rosser theorem]]"]
---

# De Bruijn index

In mathematical logic, the de Bruijn index is a tool invented by the Dutch mathematician Nicolaas Govert de Bruijn for representing terms of lambda calculus without naming the bound variables. Terms written using these indices are invariant with respect to α-conversion, so the check for α-equivalence is the same as that for syntactic equality. Each de Bruijn index is a natural number that represents an occurrence of a variable in a λ-term, and denotes the number of binders that are in scope between that occurrence and its corresponding binder. The following are some examples:

The term λx. λy. x, sometimes called the K combinator, is written as λ λ 2 with de Bruijn indices. The binder for the occurrence x is the second λ in scope.
The term λx. λy. λz. x z (y z) (the S combinator), with de Bruijn indices, is λ λ λ 3 1 (2 1).
The term λz. (λy. y (λx. x)) (λx. z x) is λ (λ 1 (λ 1)) (λ 2 1). See the following illustration, where the binders are colored and the references are shown with arrows.

De Bruijn indices are commonly used in higher-order reasoning systems such as automated theorem provers and logic programming systems.

## Related

- [[Anonymous function]]
- [[Applicative computing systems]]
- [[B, C, K, W system]]
- [[Beta normal form]]
- [[Böhm tree]]
- [[Calculus of constructions]]
- [[Call-by-push-value]]
- [[Cartesian closed category]]
- [[Church encoding]]
- [[Church–Rosser theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/De_Bruijn_index