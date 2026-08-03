---
title: "Abstract syntax tree"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Abstract_syntax_tree"
wikipedia_categories: ["Formal languages", "Trees (data structures)"]
related: ["[[Ranked alphabet]]", "[[Tree (automata theory)]]", "[[Tree automaton]]", "[[Tree transducer]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Action algebra]]", "[[Adaptive grammar]]"]
---

# Abstract syntax tree

An abstract syntax tree (AST) is a data structure used in computer science to represent the structure of a program or code snippet. It is a tree representation of the abstract syntactic structure of text (often source code) written in a formal language. Each node of the tree denotes a construct occurring in the text. It is sometimes called just a syntax tree.
The syntax is "abstract" in the sense that it does not represent every detail appearing in the real syntax, but rather just the structural or content-related details. For instance, grouping parentheses are implicit in the tree structure, so these do not have to be represented as separate nodes. Likewise, a syntactic construct like an if-condition-then statement may be denoted by means of a single node with three branches.
This distinguishes abstract syntax trees from concrete syntax trees, traditionally designated parse trees. Parse trees are typically built by a parser during the source code translation and compiling process. Once built, additional information is added to the AST by means of subsequent processing, e.g., contextual analysis.
Abstract syntax trees are also used in program analysis and program transformation systems.

## Related

- [[Ranked alphabet]]
- [[Tree (automata theory)]]
- [[Tree automaton]]
- [[Tree transducer]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Action algebra]]
- [[Adaptive grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Abstract_syntax_tree