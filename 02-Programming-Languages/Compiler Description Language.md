---
title: "Compiler Description Language"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Compiler_Description_Language"
wikipedia_categories: ["Compiler construction", "Compiler theory", "Formal languages", "Parser generators"]
related: ["[[Compiler-compiler]]", "[[Affix grammar]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Bootstrapping (compilers)]]", "[[Compilers- Principles, Techniques, and Tools]]", "[[Context-free grammar]]", "[[ECLR-attributed grammar]]", "[[Extended Backus–Naur form]]", "[[L-attributed grammar]]"]
---

# Compiler Description Language

Compiler Description Language (CDL) is a programming language based on affix grammars. It is very similar to Backus–Naur form (BNF) notation. It was designed for the development of compilers. It is very limited in its capabilities and control flow, and intentionally so. The benefits of these limitations are twofold.
On the one hand, they  make possible the sophisticated data and control flow analysis used by the CDL2 optimizers resulting in extremely efficient code. The other benefit is that they foster a highly verbose naming convention. This, in turn, leads to programs that are, to a great extent, self-documenting.
The language looks a bit like Prolog (this is not surprising since both languages arose at about the same time out of work on affix grammars). However, as opposed to Prolog, control flow in CDL is deterministically based on success/failure, i.e., no other alternatives are tried when the current one succeeds.  This idea is also used in parsing expression grammars.
CDL3 is the third version of the CDL language, significantly different from the previous two versions.

## Related

- [[Compiler-compiler]]
- [[Affix grammar]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Bootstrapping (compilers)]]
- [[Compilers- Principles, Techniques, and Tools]]
- [[Context-free grammar]]
- [[ECLR-attributed grammar]]
- [[Extended Backus–Naur form]]
- [[L-attributed grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Compiler_Description_Language