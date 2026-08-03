---
title: "Parser combinator"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Parser_combinator"
wikipedia_categories: ["Formal languages", "Functional programming", "Parsing"]
related: ["[[Attribute grammar]]", "[[Definite clause grammar]]", "[[Extended affix grammar]]", "[[Left recursion]]", "[[Lexical grammar]]", "[[Syntactic predicate]]", "[[Van Wijngaarden grammar]]", "[[A-normal form]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]"]
---

# Parser combinator

In computer programming, a parser combinator is a higher-order function that accepts several parsers as input and returns a new parser as its output. In this context, a parser is a function accepting strings as input and returning some structure as output, typically a parse tree or a set of indices representing locations in the string where parsing stopped successfully. Parser combinators enable a recursive descent parsing strategy that facilitates modular piecewise construction and testing. This parsing technique is called combinatory parsing.
Parsers using combinators have been used extensively in the prototyping of compilers and processors for domain-specific languages such as natural-language user interfaces to databases, where complex and varied semantic actions are closely integrated with syntactic processing. In 1989, Richard Frost and John Launchbury demonstrated use of parser combinators to construct natural-language interpreters. Graham Hutton also used higher-order functions for basic parsing in 1992 and monadic parsing in 1996. S. D. Swierstra also exhibited the practical aspects of parser combinators in 2001. In 2008, Frost, Hafiz and Callaghan described a set of parser combinators in the functional programming language Haskell that solve the long-standing problem of accommodating left recursion, and work as a complete top-down parsing tool in polynomial time and space.

## Related

- [[Attribute grammar]]
- [[Definite clause grammar]]
- [[Extended affix grammar]]
- [[Left recursion]]
- [[Lexical grammar]]
- [[Syntactic predicate]]
- [[Van Wijngaarden grammar]]
- [[A-normal form]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Parser_combinator