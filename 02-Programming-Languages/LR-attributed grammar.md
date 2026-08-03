---
title: "LR-attributed grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/LR-attributed_grammar"
wikipedia_categories: ["Compiler construction", "Formal languages"]
related: ["[[Affix grammar]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Compiler Description Language]]", "[[Context-free grammar]]", "[[ECLR-attributed grammar]]", "[[Extended Backus–Naur form]]", "[[L-attributed grammar]]", "[[S-attributed grammar]]", "[[Van Wijngaarden grammar]]"]
---

# LR-attributed grammar

LR-attributed grammars are a special type of attribute grammars. They allow the attributes to be evaluated on LR parsing. As a result, attribute evaluation in LR-attributed grammars can be incorporated conveniently in bottom-up parsing. zyacc is based on LR-attributed grammars. They are a subset of the L-attributed grammars, where the attributes can be evaluated in one left-to-right traversal of the abstract syntax tree. They are a superset of the S-attributed grammars, which allow only synthesized attributes. In yacc, a common hack is to use global variables to simulate some kind of inherited attributes and thus LR-attribution.

## Related

- [[Affix grammar]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Compiler Description Language]]
- [[Context-free grammar]]
- [[ECLR-attributed grammar]]
- [[Extended Backus–Naur form]]
- [[L-attributed grammar]]
- [[S-attributed grammar]]
- [[Van Wijngaarden grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/LR-attributed_grammar