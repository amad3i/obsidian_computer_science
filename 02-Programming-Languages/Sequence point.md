---
title: "Sequence point"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Sequence_point"
wikipedia_categories: ["C++", "C (programming language)", "Programming paradigms"]
related: ["[[Lexer hack]]", "[[Opaque pointer]]", "[[Array programming]]", "[[Aspect-oriented programming]]", "[[Attribute-oriented programming]]", "[[Automata-based programming]]", "[[Automata-based programming (Shalyto's approach)]]", "[[Automatic programming]]", "[[Brian Kernighan]]", "[[C (programming language)]]"]
---

# Sequence point

In C and C++, a sequence point defines any point in a computer program’s execution at which it is guaranteed that all side effects of previous evaluations will have been performed, and no side effects from subsequent evaluations have yet been performed. They are a core concept for determining the validity of and, if valid, the possible results of expressions. Adding more sequence points is sometimes necessary to make an expression defined and to ensure a single valid order of evaluation.
Documentation for C11 and C++11 stopped using the term "sequence point" and now uses alternative terms:"ISO/IEC 14882:2024"."A finer-grained alternative to sequence points (revised) (WG21/N2239 J16/07-0099)". Retrieved 2012-07-05."Order of evaluation". Retrieved 2015-10-14.

An expression's evaluation can be "sequenced before" the evaluation of another expression. (Equivalently, the other expression's evaluation can be "sequenced after" that of the first.)
The expression's evaluation is "indeterminately sequenced", meaning that one is "sequenced before" the other, but which is unspecified.
The expression's evaluation is "unsequenced", meaning the operations in each expression may be interleaved.
The execution of unsequenced evaluations can overlap, leading to potentially catastrophic undefined behavior if they share state. This situation can arise in parallel computing, causing race conditions, but undefined behavior can also result in single-threaded situations. For example, a[i] = i++; (where a is an array and i is an integer) has undefined behavior.
In earlier C standards (such as C89 and C99), sequence points were defined to occur at specific locations in code, including at the end of a full expression (such as a statement), after the evaluation of the first operand of the logical AND (&&) and logical OR (||) operators, after the first operand of the conditional (?:) operator, and at function call boundaries after all arguments have been evaluated."Sequence point rules in C and C++". Retrieved 2026-05-02.

## Related

- [[Lexer hack]]
- [[Opaque pointer]]
- [[Array programming]]
- [[Aspect-oriented programming]]
- [[Attribute-oriented programming]]
- [[Automata-based programming]]
- [[Automata-based programming (Shalyto's approach)]]
- [[Automatic programming]]
- [[Brian Kernighan]]
- [[C (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sequence_point