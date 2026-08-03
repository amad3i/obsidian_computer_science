---
title: "Lexical grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Lexical_grammar"
wikipedia_categories: ["Formal languages", "Parsing"]
related: ["[[Attribute grammar]]", "[[Definite clause grammar]]", "[[Extended affix grammar]]", "[[Left recursion]]", "[[Parser combinator]]", "[[Syntactic predicate]]", "[[Van Wijngaarden grammar]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]"]
---

# Lexical grammar

In computer science, a lexical grammar or lexical structure is a formal grammar defining the syntax of tokens. The program is written using characters that are defined by the lexical structure of the language used. The character set is equivalent to the alphabet used by any written language. The lexical grammar lays down the rules governing how a character sequence is divided up into subsequences of characters, each part of which represents an individual token. This is frequently defined in terms of regular expressions.
For instance, the lexical grammar for many programming languages specifies that a string literal starts with a " character and continues until a matching " is found (escaping makes this more complicated), that an identifier is an alphanumeric sequence (letters and digits, usually also allowing underscores, and disallowing initial digits), and that an integer literal is a sequence of digits. So in the following character sequence "abc" xyz1 23 the tokens are string, identifier and number (plus whitespace tokens) because the space character terminates the sequence of characters forming the identifier. Further, certain sequences are categorized as keywords – these generally have the same form as identifiers (usually alphabetical words), but are categorized separately; formally they have a different token type.

## Related

- [[Attribute grammar]]
- [[Definite clause grammar]]
- [[Extended affix grammar]]
- [[Left recursion]]
- [[Parser combinator]]
- [[Syntactic predicate]]
- [[Van Wijngaarden grammar]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lexical_grammar