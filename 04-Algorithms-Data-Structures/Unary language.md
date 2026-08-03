---
title: "Unary language"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Unary_language"
wikipedia_categories: ["Computational complexity theory", "Formal languages"]
related: ["[[Proof (truth)]]", "[[Sparse language]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]"]
---

# Unary language

In computational complexity theory, a unary language or tally language is a formal language (a set of strings) where all strings have the form 1k, where "1" can be any fixed symbol. For example, the language {1, 111, 1111} is unary, as is the language {1k | k is prime}. The complexity class of all such languages is sometimes called TALLY.
The name "unary" comes from the fact that a unary language is the encoding of a set of natural numbers in the unary numeral system. Since the universe of strings over any finite alphabet is a countable set, every language can be mapped to a unique set A of natural numbers; thus, every language has a unary version {1k | k in A}. Conversely, every unary language has a more compact binary version, the set of binary encodings of natural numbers k such that 1k is in the language.
Since complexity is usually measured in terms of the length of the input string, the unary version of a language can be "easier" than the original language. For example, if a language can be recognized in O(2n) time, its unary version can be recognized in O(n) time, because n has become exponentially larger. More generally, if a language can be recognized in O(f(n)) time and O(g(n)) space, its unary version can be recognized in O(n + f(log n)) time and O(g(log n)) space (we require O(n) time just to read the input string). However, if membership in a language is undecidable, then membership in its unary version is also undecidable.

## Related

- [[Proof (truth)]]
- [[Sparse language]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]
- [[Action algebra]]
- [[Adaptive grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unary_language