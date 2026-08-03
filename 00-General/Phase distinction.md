---
title: "Phase distinction"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Phase_distinction"
wikipedia_categories: ["Computer programming"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]", "[[Codecademy]]"]
---

# Phase distinction

Phase Distinction is a property of programming languages that observe a strict division between types and terms. A concise rule for determining whether phase distinction is preserved in a language or not has been proposed by Luca Cardelli - If A is a compile-time term and B is a subterm of A, then B must also be a compile-time term.
Most statically typed languages conform to the principle of phase distinction. However, some languages with especially flexible and expressive type systems (notably dependently typed programming languages) allow types to be manipulated in the same ways as regular terms. They may be passed to functions or returned as results.
A language with phase distinction may have separate namespaces for types and run-time variables. In an optimizing compiler, phase distinction marks the boundary between expressions which are safe to erase.

## Related

- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[Cheat sheet]]
- [[Code Club]]
- [[Code Words]]
- [[Codecademy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Phase_distinction