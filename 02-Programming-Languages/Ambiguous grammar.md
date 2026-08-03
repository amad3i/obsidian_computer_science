---
title: "Ambiguous grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Ambiguous_grammar"
wikipedia_categories: ["Ambiguity", "Formal languages"]
related: ["[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agent Communications Language]]", "[[Algorithmic learning theory]]"]
---

# Ambiguous grammar

In computer science, an ambiguous grammar is a context-free grammar for which there exists a string that can have more than one leftmost derivation or parse tree. Every non-empty context-free language admits an ambiguous grammar by introducing e.g. a duplicate rule. A language that only admits ambiguous grammars is called an inherently ambiguous language. Deterministic context-free grammars are always unambiguous, and are an important subclass of unambiguous grammars; there are non-deterministic unambiguous grammars, however.
For computer programming languages, the reference grammar is often ambiguous, due to issues such as the dangling else problem. If present, these ambiguities are generally resolved by adding precedence rules or other context-sensitive parsing rules, so the overall phrase grammar is unambiguous. Some parsing algorithms (such as Earley or GLR parsers) can generate sets of parse trees (or "parse forests") from strings that are syntactically ambiguous.

## Related

- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]
- [[Action algebra]]
- [[Adaptive grammar]]
- [[Affix grammar]]
- [[Agent Communications Language]]
- [[Algorithmic learning theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ambiguous_grammar