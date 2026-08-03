---
title: "Red (programming language)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Red_(programming_language)"
wikipedia_categories: ["2011 software", "Cross-platform free software", "Cross-platform software", "Domain-specific programming languages", "Extensible syntax programming languages", "Free and open source compilers", "Free and open source interpreters", "Functional languages"]
related: ["[[Agda (programming language)]]", "[[Ciao (programming language)]]", "[[Clojure]]", "[[Julia (programming language)]]", "[[V (programming language)]]", "[[Atom (programming language)]]", "[[AWK]]", "[[Concurrent Haskell]]", "[[Crystal (programming language)]]", "[[F- (programming language)]]"]
---

# Red (programming language)

Red is a programming language designed to overcome the limits of the programming language Rebol. Red was introduced in 2011 by Nenad Rakočević, and is both an imperative and functional programming language. Its syntax and general usage overlaps that of the interpreted Rebol language.
The implementation choices of Red intend to create a full stack programming language: Red can be used for extremely high-level programming (domain-specific languages (DSLs) and graphical user interfaces (GUIs) and low-level programming (operating systems and device drivers). Key to the approach is that the language has two parts: Red/System and Red.

Red/System is similar to C, but packaged into a Rebol lexical structure –  for example, one would write if x > y [print "Hello"] instead of if (x > y) {printf("Hello\n");}.
Red is a homoiconic language, which is capable of metaprogramming with Rebol-like semantics. Red's runtime library is written in Red/System, and uses a hybrid approach: it compiles what it can deduce statically and uses an embedded interpreter otherwise. The project roadmap includes a just-in-time compiler for cases in between, but this has not yet been implemented.
Red seeks to remain independent of any other toolchain; it does its own code generation. It is therefore possible to cross-compile Red programs from any platform it supports to any other, via a command-line switch. Both Red and Red/System are distributed as open-source software under the BSD 3-clause (modified) license. The runtime library is distributed under the more permissive Boost Software License.
As of version 0.6.4 Red includes a garbage collector "the Simple GC".

## Related

- [[Agda (programming language)]]
- [[Ciao (programming language)]]
- [[Clojure]]
- [[Julia (programming language)]]
- [[V (programming language)]]
- [[Atom (programming language)]]
- [[AWK]]
- [[Concurrent Haskell]]
- [[Crystal (programming language)]]
- [[F- (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Red_(programming_language)