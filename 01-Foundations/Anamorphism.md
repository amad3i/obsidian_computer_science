---
title: "Anamorphism"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Anamorphism"
wikipedia_categories: ["Category theory", "Recursion schemes"]
related: ["[[Catamorphism]]", "[[Hylomorphism (computer science)]]", "[[2-Yoneda lemma]]", "[[3-category]]", "[[AB5 category]]", "[[Abstract elementary class]]", "[[Abstract nonsense]]", "[[Accessible category]]", "[[Accessible quasi-category]]", "[[Adhesive category]]"]
---

# Anamorphism

In computer programming, an anamorphism is a function that generates a sequence by repeated application of the function to its previous result. You begin with some value A and apply a function f to it to get B. Then you apply f to B to get C, and so on until some terminating condition is reached. The anamorphism is the function that generates the list of A, B, C, etc. You can think of the anamorphism as unfolding the initial value into a sequence.
The above layman's description can be stated more formally in category theory: the anamorphism of a coinductive type denotes the assignment of a coalgebra to its unique morphism to the final coalgebra of an endofunctor. These objects are used in functional programming as unfolds.
The categorical dual (the notion most naturally considered the "opposite") of the anamorphism is the catamorphism.

## Related

- [[Catamorphism]]
- [[Hylomorphism (computer science)]]
- [[2-Yoneda lemma]]
- [[3-category]]
- [[AB5 category]]
- [[Abstract elementary class]]
- [[Abstract nonsense]]
- [[Accessible category]]
- [[Accessible quasi-category]]
- [[Adhesive category]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Anamorphism