---
title: "Implicit computational complexity"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Implicit_computational_complexity"
wikipedia_categories: ["Computational complexity theory", "Programming language theory", "Proof theory", "Type theory"]
related: ["[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Curry–Howard correspondence]]", "[[Higher-order abstract syntax]]", "[[Proof (truth)]]", "[[Pure type system]]", "[[System U]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Abstract data type]]", "[[Abstract syntax]]", "[[Abstract type]]"]
---

# Implicit computational complexity

Implicit computational complexity (ICC) is a subfield of computational complexity theory that characterizes programs by constraints on the way in which they are constructed, without reference to a specific underlying machine model or to explicit bounds on computational resources unlike conventional complexity theory. The central goal of ICC is to identify programming formalisms — such as restricted formal languages, type systems, or recursion schemes — whose expressive power coincides exactly with a given complexity class, so that membership in the class becomes a consequence of syntactic well-formedness rather than a separate computational argument. ICC was developed in the 1990s and employs the techniques of proof theory, substructural logic, linear logic, model theory and recursion theory to prove bounds on the expressive power of high-level formal languages. Among its founding contributions are Girard, Scedrov, and Scott’s bounded linear logic (1992), Bellantoni and Cook’s function algebra based on predicative recursion (1992), and Jones’s cons-free programming language characterisation of polynomial time (1999). ICC is also concerned with the practical realization of functional programming languages, language tools and type theory that can control the resource usage of programs in a formally verifiable sense.
Two leading approaches to resource certification have been Static Analysis (SA) and Implicit Computational Complexity (ICC). SA is algorithmic in nature: it focuses on a broad programming language of choice, and seeks to determine by syntactic means whether given programs in that language are feasible. In contrast, ICC attempts to create from the outset specialized programming languages or methods that delineate a complexity class. Thus, SA's focus is on compile time, making no demand on the programmer; whereas ICC is a language-design discipline.

## Related

- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Curry–Howard correspondence]]
- [[Higher-order abstract syntax]]
- [[Proof (truth)]]
- [[Pure type system]]
- [[System U]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Abstract data type]]
- [[Abstract syntax]]
- [[Abstract type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Implicit_computational_complexity