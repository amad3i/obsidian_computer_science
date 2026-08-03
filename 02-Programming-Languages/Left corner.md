---
title: "Left corner"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Left_corner"
wikipedia_categories: ["Computer science stubs", "Parsing"]
related: ["[[Deterministic parsing]]", "[[Inverse parser]]", "[[Abstract syntax]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[AQUA@home]]", "[[Asynchrony (computer programming)]]", "[[Attentive user interface]]", "[[Attribute grammar]]"]
---

# Left corner

In formal language theory, the left corner of a production rule in a context-free grammar is the left-most symbol on the right side of the rule.
For example, in the rule A→Xα, X is the left corner.
The left corner table associates to a symbol all possible left corners for that symbol, and the left corners of those symbols, etc.
Given the grammar

S → VP
S → NP VP
VP → V NP
NP → DET N
the left corner table is as follows.

Left corners are used to add bottom-up filtering to a top-down parser, or top-down filtering to a bottom-up parser.

## Related

- [[Deterministic parsing]]
- [[Inverse parser]]
- [[Abstract syntax]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[AQUA@home]]
- [[Asynchrony (computer programming)]]
- [[Attentive user interface]]
- [[Attribute grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Left_corner