---
title: "Referential transparency"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Referential_transparency"
wikipedia_categories: ["Programming language theory"]
related: ["[[Abstract syntax]]", "[[Divergence (computer science)]]", "[[First-class function]]", "[[Function-level programming]]", "[[Higher-order abstract syntax]]", "[[Implicit computational complexity]]", "[[Logic error]]", "[[Logic of Computable Functions]]", "[[Non-local variable]]", "[[POPLmark challenge]]"]
---

# Referential transparency

In analytic philosophy and computer science, referential transparency and referential opacity are properties of linguistic constructions, and by extension of languages. A linguistic construction is called referentially transparent when for any expression built from it, replacing a subexpression with another one that denotes the same value does not change the value of the expression. Otherwise, it is called referentially opaque. Each expression built from a referentially opaque linguistic construction states something about a subexpression, whereas each expression built from a referentially transparent linguistic construction states something not about a subexpression, meaning that the subexpressions are ‘transparent’ to the expression, acting merely as ‘references’ to something else. For example, the linguistic construction ‘_ was wise’ is referentially transparent (e.g., Socrates was wise is equivalent to The founder of Western philosophy was wise) but ‘_ said _’ is referentially opaque (e.g., Xenophon said ‘Socrates was wise’ is not equivalent to Xenophon said ‘The founder of Western philosophy was wise’).
Referential transparency, in programming languages, depends on semantic equivalences among denotations of expressions, or on contextual equivalence of expressions themselves. That is, referential transparency depends on the semantics of the language. So, both declarative languages and imperative languages can have referentially transparent positions, referentially opaque positions, or (usually) both, according to the semantics they are given.
The importance of referentially transparent positions is that they allow the programmer and the compiler to reason about program behavior as a rewrite system at those positions. This can help in proving correctness, simplifying an algorithm, assisting in modifying code without breaking it, or optimizing code by means of memoization, common subexpression elimination, lazy evaluation, constant folding, or parallelization.

## Related

- [[Abstract syntax]]
- [[Divergence (computer science)]]
- [[First-class function]]
- [[Function-level programming]]
- [[Higher-order abstract syntax]]
- [[Implicit computational complexity]]
- [[Logic error]]
- [[Logic of Computable Functions]]
- [[Non-local variable]]
- [[POPLmark challenge]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Referential_transparency