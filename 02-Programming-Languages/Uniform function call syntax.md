---
title: "Uniform function call syntax"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Uniform_function_call_syntax"
wikipedia_categories: ["Object-oriented programming", "Subroutines"]
related: ["[[First-class message]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[Anonymous function]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[Call super]]", "[[Circle–ellipse problem]]"]
---

# Uniform function call syntax

Uniform function call syntax (UFCS) or uniform call syntax (UCS) is a programming language feature in D, Nim, Koka, Effekt,, Lean, and other programming languages, that allows any function to be called using the syntax for method calls (as in object-oriented programming), by using the receiver as the first parameter and the given arguments as the remaining parameters. The same technique is used in the AviSynth scripting language under the name "OOP notation".
UFCS is particularly useful when function calls are chained (behaving similar to pipes, or the various dedicated operators available in functional languages for passing values through a series of expressions). It allows free functions to fill a role similar to extension methods in some other languages. Another benefit of the syntax is related to completion systems in IDEs, which use type information to show a list of available functions, dependent on the context. When the programmer starts with an argument, the set of potentially applicable functions is greatly narrowed down, aiding discoverability.

## Related

- [[First-class message]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[Anonymous function]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[Call super]]
- [[Circle–ellipse problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Uniform_function_call_syntax