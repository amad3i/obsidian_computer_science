---
title: "Refal"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Refal"
wikipedia_categories: ["Functional languages", "Homoiconic programming languages", "Pattern matching programming languages", "Programming languages", "Term-rewriting programming languages"]
related: ["[[APL (programming language)]]", "[[Elixir (programming language)]]", "[[Erlang (programming language)]]", "[[Gleam (programming language)]]", "[[Haxe]]", "[[Julia (programming language)]]", "[[Rebol]]", "[[Red (programming language)]]", "[[Scala (programming language)]]", "[[SNOBOL]]"]
---

# Refal

Refal ("Recursive functions algorithmic language"; Russian: РЕФАЛ) "is a functional programming language oriented toward symbolic computations", including "string processing, language translation, [and] artificial intelligence". It is one of the oldest members of this family, first conceived of in 1966 as a theoretical tool, with the first implementation appearing in 1968. Refal was intended to combine mathematical simplicity with practicality for writing large and sophisticated programs.
One of the first functional programming languages to do so, and unlike Lisp of its time, Refal is based on pattern matching. Its pattern matching works in conjunction with term rewriting.
The basic data structure of Lisp and Prolog is a linear list built by cons operation in a sequential manner, thus with O(n) access to list's nth element. Refal's lists are built and scanned from both ends, with pattern matching working for nested lists as well as the top-level one. In effect, the basic data structure of Refal is a tree rather than a list. This gives freedom and convenience in creating data structures while using only mathematically simple control mechanisms of pattern matching and substitution.
Refal also includes a feature called the freezer to support efficient partial evaluation.
Refal can be applied to the processing and transformation of tree structures, similarly to XSLT.

## Related

- [[APL (programming language)]]
- [[Elixir (programming language)]]
- [[Erlang (programming language)]]
- [[Gleam (programming language)]]
- [[Haxe]]
- [[Julia (programming language)]]
- [[Rebol]]
- [[Red (programming language)]]
- [[Scala (programming language)]]
- [[SNOBOL]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Refal