---
title: "Semigroupoid"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Semigroupoid"
wikipedia_categories: ["Algebraic structures", "Category theory", "Category theory stubs"]
related: ["[[3-category]]", "[[AB5 category]]", "[[Accessible quasi-category]]", "[[Adhesive category]]", "[[Applied category theory]]", "[[Associativity isomorphism]]", "[[Balanced category]]", "[[Categorical probability]]", "[[Categorical set theory]]", "[[Category (mathematics)]]"]
---

# Semigroupoid

In mathematics, a semigroupoid (also called semicategory, naked category or precategory) is a partial algebra that satisfies the axioms for a small category, except possibly for the requirement that there be an identity at each object. While this definition is due to Tilson, Exel has introduced a different definition, one in which there is no underlying graph. The term semicategory usually refers to a Tilson's graphed semigroupoid. Semigroupoids generalise semigroups in the same way that small categories generalise monoids and groupoids generalise groups. Semigroupoids have applications in the structural theory of semigroups.
Formally, a semigroupoid consists of:

a set of things called objects.
for every two objects A and B a set Mor(A,B) of things called morphisms from A to B. If f is in Mor(A,B), we write f : A → B.
for every three objects A, B and C a binary operation Mor(A,B) × Mor(B,C) → Mor(A,C) called composition of morphisms. The composition of f : A → B and g : B → C is written as g ∘ f or gf. (Some authors write it as fg.)
such that the following axiom holds:

(associativity) if f : A → B, g : B → C and h : C → D then h ∘ (g ∘ f) = (h ∘ g) ∘ f.

## Related

- [[3-category]]
- [[AB5 category]]
- [[Accessible quasi-category]]
- [[Adhesive category]]
- [[Applied category theory]]
- [[Associativity isomorphism]]
- [[Balanced category]]
- [[Categorical probability]]
- [[Categorical set theory]]
- [[Category (mathematics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Semigroupoid