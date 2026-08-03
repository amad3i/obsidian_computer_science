---
title: "Attribute grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Attribute_grammar"
wikipedia_categories: ["Compiler construction", "Formal languages", "Parsing"]
related: ["[[Van Wijngaarden grammar]]", "[[Abstract syntax]]", "[[Affix grammar]]", "[[Backus–Naur form]]", "[[Compiler Description Language]]", "[[Compiler-compiler]]", "[[Context-free grammar]]", "[[Definite clause grammar]]", "[[ECLR-attributed grammar]]", "[[Extended affix grammar]]"]
---

# Attribute grammar

An attribute grammar is a formal way to supplement a formal grammar with semantic information processing. Semantic information is stored in attributes associated with terminal and nonterminal symbols of the grammar. The values of attributes are the result of attribute evaluation rules associated with productions of the grammar. Attributes allow the transfer of information from anywhere in the abstract syntax tree to anywhere else, in a controlled and formal way.
Each semantic function deals with attributes of symbols occurring only in one production rule: both semantic function parameters and its result are attributes of symbols from one particular rule. When a semantic function defines the value of an attribute of the symbol on the left hand side of the rule, the attribute is called synthesized; otherwise it is called inherited. Thus, synthesized attributes serve to pass semantic information up the parse tree, while inherited attributes allow values to be passed from the parent nodes down and across the syntax tree.
In simple applications, such as evaluation of arithmetic expressions, attribute grammar may be used to describe the entire task to be performed besides parsing in straightforward way; in complicated systems, for instance, when constructing a language translation tool, such as a compiler, it may be used to validate semantic checks associated with a grammar, representing the rules of a language not explicitly imparted by the syntax definition. It may be also used by parsers or compilers to translate the syntax tree directly into code for some specific machine, or into some intermediate language.

## Related

- [[Van Wijngaarden grammar]]
- [[Abstract syntax]]
- [[Affix grammar]]
- [[Backus–Naur form]]
- [[Compiler Description Language]]
- [[Compiler-compiler]]
- [[Context-free grammar]]
- [[Definite clause grammar]]
- [[ECLR-attributed grammar]]
- [[Extended affix grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Attribute_grammar