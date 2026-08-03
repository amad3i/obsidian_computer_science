---
title: "Unparser"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Unparser"
wikipedia_categories: ["Algorithms and data structures stubs", "Compiler construction", "Syntax"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[Aliasing (computing)]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Bach's algorithm]]", "[[Backus–Naur form]]"]
---

# Unparser

In computing, an unparser is a system that constructs a set of characters or image components from a given parse tree.
An unparser is in effect the reverse of a traditional parser that takes a set of strings of characters and produces a parse tree. Unparsing generally involves the application of a specific set of rules to the parse tree as a "tree walk" takes place.
Given that the tree may involve both textual and graphic elements, the unparser may have two separate modules, each of which handles the relevant components. In such cases the "master unparser" looks up the "master unparse table" to determine if a given nested structure should be handled by one module, or the other.

## Related

- [[Abstract syntax]]
- [[Affix grammar]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[Aliasing (computing)]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Array-access analysis]]
- [[Aspect weaver]]
- [[Attribute grammar]]
- [[Bach's algorithm]]
- [[Backus–Naur form]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unparser