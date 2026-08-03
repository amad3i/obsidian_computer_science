---
title: "Tabled logic programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Tabled_logic_programming"
wikipedia_categories: ["Dynamic programming", "Logic programming", "Programming language topic stubs"]
related: ["[[BNR Prolog]]", "[[Functional logic programming]]", "[[A-normal form]]", "[[Abductive logic programming]]", "[[Access query language]]", "[[Advice taker]]", "[[Alef (programming language)]]", "[[Alpha (programming language)]]", "[[Answer set programming]]", "[[Array-access analysis]]"]
---

# Tabled logic programming

Tabling is a technique first developed for natural language processing, where it was called Earley parsing. It consists of storing in a table (a.k.a. chart in the context of parsing) partial successful analyses that might come in handy for future reuse.
Tabling consists of maintaining a table of goals that are called during execution, along with their answers, and then using the answers directly when the same goal is subsequently called. Tabling gives a guarantee of total correctness for any (pure) Prolog program without function symbols.
Tabling can be extended in various directions. It can support recursive predicates through SLG resolution or linear tabling. In a multi-threaded Prolog system tabling results could be kept private to a thread or shared among all threads. And in incremental tabling, tabling might react to changes.

## Related

- [[BNR Prolog]]
- [[Functional logic programming]]
- [[A-normal form]]
- [[Abductive logic programming]]
- [[Access query language]]
- [[Advice taker]]
- [[Alef (programming language)]]
- [[Alpha (programming language)]]
- [[Answer set programming]]
- [[Array-access analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tabled_logic_programming