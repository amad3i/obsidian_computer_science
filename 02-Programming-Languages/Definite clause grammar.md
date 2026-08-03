---
title: "Definite clause grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Definite_clause_grammar"
wikipedia_categories: ["Formal languages", "Logic programming", "Parsing"]
related: ["[[Attribute grammar]]", "[[Extended affix grammar]]", "[[Left recursion]]", "[[Lexical grammar]]", "[[Parser combinator]]", "[[Syntactic predicate]]", "[[Van Wijngaarden grammar]]", "[[Abductive logic programming]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]"]
---

# Definite clause grammar

A definite clause grammar (DCG) is a way of expressing grammar, either for natural or formal languages, in a logic programming language such as Prolog. It is closely related to the concept of attribute grammars / affix grammars.
DCGs are usually associated with Prolog, but similar languages such as Mercury also include DCGs. They are called definite clause grammars because they represent a grammar as a set of definite clauses in first-order logic.
The term DCG refers to the specific type of expression in Prolog and other similar languages; not all ways of expressing grammars using definite clauses are considered DCGs. However, all of the capabilities or properties of DCGs will be the same for any grammar that is represented with definite clauses in essentially the same way as in Prolog.
The definite clauses of a DCG can be considered a set of axioms where the validity of a sentence, and the fact that it has a certain parse tree can be considered theorems that follow from these axioms. This has the advantage of making it so that recognition and parsing of expressions in a language becomes a general matter of proving statements, such as statements in a logic programming language.

## Related

- [[Attribute grammar]]
- [[Extended affix grammar]]
- [[Left recursion]]
- [[Lexical grammar]]
- [[Parser combinator]]
- [[Syntactic predicate]]
- [[Van Wijngaarden grammar]]
- [[Abductive logic programming]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Definite_clause_grammar