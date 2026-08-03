---
title: "Noncontracting grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Noncontracting_grammar"
wikipedia_categories: ["Formal languages"]
related: ["[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agent Communications Language]]", "[[Algorithmic learning theory]]"]
---

# Noncontracting grammar

In formal language theory, a noncontracting grammar (also called monotonic grammar) is a type of formal grammar whose production rules never decrease the total length of a string during derivation. This means that when applying any rule to transform one string into another, the resulting string must have at least as many symbols as the original.
Noncontracting grammars are significant because they are equivalent in expressive power to context-sensitive grammars and define the same class of languages (the context-sensitive languages) in the Chomsky hierarchy. This equivalence makes them important for understanding the computational limits of natural language processing and compiler design, as they can model complex linguistic phenomena while maintaining certain desirable mathematical properties. Some authors use the term context-sensitive grammar to refer to noncontracting grammars in general, though this usage varies in the literature.
A closely related concept is the essentially noncontracting grammar, which allows one special exception: a rule that produces the empty string from the start symbol, provided that the start symbol never appears elsewhere in the grammar.

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

- Wikipedia: https://en.wikipedia.org/wiki/Noncontracting_grammar