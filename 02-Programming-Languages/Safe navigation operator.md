---
title: "Safe navigation operator"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Safe_navigation_operator"
wikipedia_categories: ["Conditional constructs", "Object-oriented programming", "Operators (programming)"]
related: ["[[Indexer (programming)]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Assertion (software development)]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bitwise ternary logic instruction]]", "[[Boolean flag]]", "[[Bounded quantification]]"]
---

# Safe navigation operator

In object-oriented programming, the safe navigation operator (also known as optional chaining operator, safe call operator, null-conditional operator, null-propagation operator) is a binary operator that returns null if its first argument is null; otherwise it performs a dereferencing operation as specified by the second argument (typically an object member access, array index, or lambda invocation).
It is used to avoid sequential explicit null checks and assignments and replace them with method/property chaining.  In programming languages where the navigation operator (e.g. ".") leads to an error if applied to a null object, the safe navigation operator stops the evaluation of a method/field chain and returns null as the value of the chain expression. It was first used by Groovy 1.0 in 2007 and is currently supported in languages such as
C#, Swift, TypeScript, Ruby, Kotlin, Rust,  JavaScript,
and others. There is currently no common naming convention for this operator, but safe navigation operator is the most widely used term.
The main advantage of using this operator is that it avoids the pyramid of doom. Instead of writing multiple nested ifs, programmers can just use usual chaining, but add question mark symbols before dots (or other characters used for chaining).
While the safe navigation operator and null coalescing operator are both null-aware operators, they are operationally different.

## Related

- [[Indexer (programming)]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Assertion (software development)]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bitwise ternary logic instruction]]
- [[Boolean flag]]
- [[Bounded quantification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Safe_navigation_operator