---
title: "S-attributed grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/S-attributed_grammar"
wikipedia_categories: ["Compiler construction", "Formal languages"]
related: ["[[Affix grammar]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Compiler Description Language]]", "[[Context-free grammar]]", "[[ECLR-attributed grammar]]", "[[Extended Backus–Naur form]]", "[[L-attributed grammar]]", "[[LR-attributed grammar]]", "[[Van Wijngaarden grammar]]"]
---

# S-attributed grammar

In formal language S-attributed grammars are a class of attribute grammars characterized by having no  inherited attributes, but only  synthesized attributes. Inherited attributes, which must be passed down from parent nodes to children nodes of the abstract syntax tree during the semantic analysis of the parsing process, are a problem for bottom-up parsing because in bottom-up parsing, the parent nodes of the abstract syntax tree are created after creation of all of their children. Attribute evaluation in S-attributed grammars can be incorporated conveniently in both top-down parsing and bottom-up parsing.
Specifications for parser generators in the Yacc family can be broadly considered S-attributed grammars. However, these parser generators usually include the capacity to reference global variables and/or fields from within any given grammar rule, meaning that this is not a pure S-attributed approach.
Any S-attributed grammar is also an L-attributed grammar.

## Related

- [[Affix grammar]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Compiler Description Language]]
- [[Context-free grammar]]
- [[ECLR-attributed grammar]]
- [[Extended Backus–Naur form]]
- [[L-attributed grammar]]
- [[LR-attributed grammar]]
- [[Van Wijngaarden grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/S-attributed_grammar