---
title: "Pure type system"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Pure_type_system"
wikipedia_categories: ["Lambda calculus", "Proof theory", "Type theory"]
related: ["[[System U]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Calculus of constructions]]", "[[Curry–Howard correspondence]]", "[[Hindley–Milner type system]]", "[[Implicit computational complexity]]", "[[Intersection type discipline]]", "[[Lambda cube]]", "[[Lambda-mu calculus]]", "[[Simply typed lambda calculus]]"]
---

# Pure type system

In the branches of mathematical logic known as proof theory and type theory, a pure type system (PTS), previously known as a generalized type system (GTS), is a form of typed lambda calculus that allows an arbitrary number of sorts and dependencies between any of these. The framework can be seen as a generalisation of Barendregt's lambda cube, in the sense that all corners of the cube can be represented as instances of a PTS with just two sorts. In fact, Barendregt (1991) framed his cube in this setting. Pure type systems may obscure the distinction between types and terms and collapse the type hierarchy, as is the case with the calculus of constructions, but this is not generally the case, e.g. the simply typed lambda calculus allows only terms to depend on terms.
Pure type systems were independently introduced by Stefano Berardi (1988) and Jan Terlouw (1989). Barendregt discussed them at length in his subsequent papers. In his PhD thesis, Berardi defined a cube of constructive logics akin to the lambda cube (these specifications are non-dependent). A modification of this cube was later called the L-cube by Herman Geuvers, who in his PhD thesis extended the Curry–Howard correspondence to this setting. Based on these ideas, G. Barthe and others defined classical pure type systems (CPTS) by adding a double negation operator.    	
Similarly, in 1998, Tijn Borghuis introduced modal pure type systems (MPTS). Roorda has discussed the application of pure type systems to functional programming; and Roorda and Jeuring have proposed a programming language based on pure type systems.
The systems from the lambda cube are all known to be strongly normalizing. Pure type systems in general need not be, for example System U from Girard's paradox is not. (Roughly speaking, Girard found pure systems in which one can express the sentence "the types form a type".) Furthermore, all known examples of pure type systems that are not strongly normalizing are not even (weakly) normalizing: they contain expressions that do not have normal forms, just like the untyped lambda calculus. It is a major open problem in the field whether this is always the case, i.e. whether a (weakly) normalizing PTS always has the strong normalization property. This is known as the Barendregt–Geuvers–Klop conjecture (named after Henk Barendregt, Herman Geuvers, and Jan Willem Klop).

## Related

- [[System U]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Pure_type_system