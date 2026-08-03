---
title: "Language-Theoretic Security"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Language-Theoretic_Security"
wikipedia_categories: ["Computer programming", "Computer security", "Formal languages", "Theoretical computer science"]
related: ["[[Formal language]]", "[[Grammar systems theory]]", "[[Pattern language (formal languages)]]", "[[Profinite word]]", "[[Random-access Turing machine]]", "[[Ranked alphabet]]", "[[Regular numerical predicate]]", "[[Tree (automata theory)]]", "[[Tree automaton]]", "[[Tree transducer]]"]
---

# Language-Theoretic Security

Language-theoretic security, or LangSec, is an approach to software security that focuses on input handling, complexity, and program design as strategies to improve the verifiability of computer programs.  It was introduced in 2005 by Robert J. Hansen and Meredith L. Patterson at BlackHat and in 2011 by Len Sassaman and Patterson.  It aims to create a formal description of which software is likely to have security vulnerabilities of particular classes, and why.  It considers programs to have an inherent parser component, whether or not explicit, composed of that part of the program which operates on external input before that input is fully parsed.  A central hypothesis of language-theoretic security is that vulnerabilities in software increase according to the computational power of the notional input-accepting automaton equivalent to this parser, using the definitions of automata theory.  The lower bound on this computational power is the input language complexity of the program.  The extent to which reducing this complexity is possible is a function of the specification of the communication protocol or file format the program takes as input.

## Related

- [[Formal language]]
- [[Grammar systems theory]]
- [[Pattern language (formal languages)]]
- [[Profinite word]]
- [[Random-access Turing machine]]
- [[Ranked alphabet]]
- [[Regular numerical predicate]]
- [[Tree (automata theory)]]
- [[Tree automaton]]
- [[Tree transducer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Language-Theoretic_Security