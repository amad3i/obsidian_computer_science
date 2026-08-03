---
title: "Lexer hack"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Lexer_hack"
wikipedia_categories: ["C++", "C (programming language)", "Parsing"]
related: ["[[Opaque pointer]]", "[[Sequence point]]", "[[Abstract syntax]]", "[[Attribute grammar]]", "[[Brian Kernighan]]", "[[C (programming language)]]", "[[C++]]", "[[Camlp4]]", "[[CERT Coding Standards]]", "[[Comparative illusion]]"]
---

# Lexer hack

In computer programming, the lexer hack is a solution to parsing a context-sensitive grammar such as C, where classifying a sequence of characters as a variable name or a type name requires contextual information, by feeding contextual information backwards from the parser to the lexer.
The lexer hack is frowned upon in modern compilers as it creates tight coupling between otherwise largely independent steps in the compilation process. Instead, identifier-like tokens are tokenized as identifiers and later disambiguated by the parser, allowing cleaner separation of concerns.

## Related

- [[Opaque pointer]]
- [[Sequence point]]
- [[Abstract syntax]]
- [[Attribute grammar]]
- [[Brian Kernighan]]
- [[C (programming language)]]
- [[C++]]
- [[Camlp4]]
- [[CERT Coding Standards]]
- [[Comparative illusion]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lexer_hack