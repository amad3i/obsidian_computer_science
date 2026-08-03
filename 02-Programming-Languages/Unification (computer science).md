---
title: "Unification (computer science)"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Unification_(computer_science)"
wikipedia_categories: ["Automated theorem proving", "Logic in computer science", "Logic programming", "Rewriting systems", "Type theory", "Unification (computer science)"]
related: ["[[Occurs check]]", "[[Abstract rewriting system]]", "[[Automated reasoning]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Curry–Howard correspondence]]", "[[Dershowitz–Manna ordering]]", "[[Dis-unification]]", "[[Event calculus]]", "[[Higher-order abstract syntax]]", "[[Intuitionistic type theory]]"]
---

# Unification (computer science)

In logic and computer science, specifically automated reasoning, unification is an algorithmic process of solving equations between symbolic expressions, each of the form Left-hand side = Right-hand side. For example, using x,y,z as variables, and taking f to be an uninterpreted function, the singleton equation set { f(1,y) = f(x,2) } is a syntactic first-order unification problem that has the substitution { x ↦ 1, y ↦ 2 } as its only solution.
Conventions differ on what values variables may assume and which expressions are considered equivalent. In first-order syntactic unification, variables range over first-order terms and equivalence is syntactic. This version of unification has a unique "best" answer and is used in logic programming and programming language type system implementation, especially in Hindley–Milner based type inference algorithms. In higher-order unification, possibly restricted to higher-order pattern unification, terms may include lambda expressions, and equivalence is up to beta-reduction. This version is used in proof assistants and higher-order logic programming, for example Isabelle, Twelf, and lambdaProlog. Finally, in semantic unification or E-unification, equality is subject to background knowledge and variables range over a variety of domains. This version is used in SMT solvers, term rewriting algorithms, and cryptographic protocol analysis.

## Related

- [[Occurs check]]
- [[Abstract rewriting system]]
- [[Automated reasoning]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Curry–Howard correspondence]]
- [[Dershowitz–Manna ordering]]
- [[Dis-unification]]
- [[Event calculus]]
- [[Higher-order abstract syntax]]
- [[Intuitionistic type theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unification_(computer_science)