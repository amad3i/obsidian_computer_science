---
title: "Chomsky normal form"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Chomsky_normal_form"
wikipedia_categories: ["Formal languages", "Noam Chomsky"]
related: ["[[Chomsky hierarchy]]", "[[Chomsky–Schützenberger enumeration theorem]]", "[[Chomsky–Schützenberger representation theorem]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]"]
---

# Chomsky normal form

In formal language theory, a context-free grammar, G, is said to be in Chomsky normal form (first described by Noam Chomsky) if all of its production rules are of the form:

A → BC,   or
A → a,   or
S → ε,
where A, B, and C are nonterminal symbols, the letter a is a terminal symbol (a symbol that represents a constant value), S is the start symbol, and ε denotes the empty string.  Also, neither B nor C may be the start symbol, and the third production rule can only appear if ε is in L(G), the language produced by the context-free grammar G.
Every grammar in Chomsky normal form is context-free, and conversely, every context-free grammar can be transformed into an equivalent one which is in Chomsky normal form and has a size no larger than the square of the original grammar's size.

## Related

- [[Chomsky hierarchy]]
- [[Chomsky–Schützenberger enumeration theorem]]
- [[Chomsky–Schützenberger representation theorem]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]
- [[Action algebra]]
- [[Adaptive grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Chomsky_normal_form