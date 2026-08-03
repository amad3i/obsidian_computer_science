---
title: "Constructed product result analysis"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Constructed_product_result_analysis"
wikipedia_categories: ["Computer programming stubs", "Functional programming", "Programming language implementation"]
related: ["[[bss]]", "[[A-normal form]]", "[[Actant]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Aggregate pattern]]", "[[Algebraic data type]]", "[[Anonymous function]]", "[[Applicative functor]]", "[[Arrow (computer science)]]"]
---

# Constructed product result analysis

In the field of compiler implementation in computer science, constructed product result analysis (or CPR analysis) is a static analysis that determines which functions in a given program can return multiple results in an efficient manner. Typically, this means returning multiple results in a register (as opposed to returning a pointer to a tuple allocated on the heap whose components are the function's multiple return values.)
CPR analysis was introduced in the context of compiling Haskell (a lazy functional language) and is implemented in the Glasgow Haskell Compiler. It may be applicable to other programming languages as well.

## Related

- [[bss]]
- [[A-normal form]]
- [[Actant]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Aggregate pattern]]
- [[Algebraic data type]]
- [[Anonymous function]]
- [[Applicative functor]]
- [[Arrow (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Constructed_product_result_analysis