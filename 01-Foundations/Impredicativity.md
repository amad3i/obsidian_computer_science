---
title: "Impredicativity"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Impredicativity"
wikipedia_categories: ["Concepts in logic", "Mathematical logic", "Philosophy of mathematics", "Recursion", "Self-reference"]
related: ["[[Absoluteness (logic)]]", "[[Corecursion]]", "[[Foundations of mathematics]]", "[[Grossone]]", "[[Hume's principle]]", "[[Mathematical logic]]", "[[Recursion]]", "[[Recursive definition]]", "[[Strength (mathematical logic)]]", "[[Structuralism (philosophy of mathematics)]]"]
---

# Impredicativity

In mathematics, logic and philosophy of mathematics, something that is impredicative is a self-referencing definition. Roughly speaking, a definition is impredicative if it invokes (mentions or quantifies over) the set being defined, or (more commonly) another set that contains the thing being defined. There is no generally accepted precise definition of what it means to be predicative or impredicative. Authors have given different but related definitions.
The opposite of impredicativity is predicativity, which essentially entails building stratified (or ramified) theories where quantification over a type at one 'level' results in types at a new, higher, level. A prototypical example is intuitionistic type theory, which retains ramification (without the explicit levels) so as to discard impredicativity. The 'levels' here correspond to the number of layers of dependency in a term definition. 
Russell's paradox is a famous example of an impredicative construction—namely the set of all sets that do not contain themselves. The paradox is that such a set cannot exist: If it were to exist, the question could be asked whether it contains itself or not—if it does then by definition it should not, and if it does not then by definition it should.
The greatest lower bound of a set X, glb(X), also has an impredicative definition: y = glb(X) if and only if for all elements x of X, y is less than or equal to x, and any z less than or equal to all elements of X is less than or equal to y. This definition quantifies over the set (potentially infinite, depending on the order in question) whose members are the lower bounds of X, one of which being the glb itself. Hence predicativism would reject this definition.

## Related

- [[Absoluteness (logic)]]
- [[Corecursion]]
- [[Foundations of mathematics]]
- [[Grossone]]
- [[Hume's principle]]
- [[Mathematical logic]]
- [[Recursion]]
- [[Recursive definition]]
- [[Strength (mathematical logic)]]
- [[Structuralism (philosophy of mathematics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Impredicativity