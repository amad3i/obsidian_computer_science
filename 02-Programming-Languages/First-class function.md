---
title: "First-class function"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/First-class_function"
wikipedia_categories: ["Compiler construction", "Data types", "Functional programming", "Primitive types", "Programming language theory", "Subroutines"]
related: ["[[Anonymous function]]", "[[Abstract syntax]]", "[[Address constant]]", "[[Algebraic data type]]", "[[Cons]]", "[[Function type]]", "[[Generalized algebraic data type]]", "[[Higher-order function]]", "[[Option type]]", "[[Polymorphism (computer science)]]"]
---

# First-class function

In computer science, a programming language is said to have first-class functions if it treats functions as first-class citizens. This means the language supports passing functions as arguments to other functions, returning them as the values from other functions, and assigning them to variables or storing them in data structures. Some programming language theorists require support for anonymous functions (function literals) as well. In languages with first-class functions, the names of functions do not have any special status; they are treated like ordinary variables with a function type. The term was coined by Christopher Strachey in the context of "functions as first-class citizens" in the mid-1960s.
First-class functions are a necessity for the functional programming style, in which the use of higher-order functions is a standard practice. A simple example of a higher-ordered function is the map function, which takes, as its arguments, a function and a list, and returns the list formed by applying the function to each member of the list. For a language to support map, it must support passing a function as an argument.
There are certain implementation difficulties in passing functions as arguments or returning them as results, especially in the presence of non-local variables introduced in nested and anonymous functions. Historically, these were termed the funarg problems, the name coming from function argument. In early imperative languages these problems were avoided by either not supporting functions as result types (e.g. ALGOL 60, Pascal) or omitting nested functions and thus non-local variables (e.g. C). The early functional language Lisp took the approach of dynamic scoping, where non-local variables refer to the closest definition of that variable at the point where the function is executed, instead of where it was defined. Proper support for lexically scoped first-class functions was introduced in Scheme and requires handling references to functions as closures instead of bare function pointers, which in turn makes garbage collection a necessity.

## Related

- [[Anonymous function]]
- [[Abstract syntax]]
- [[Address constant]]
- [[Algebraic data type]]
- [[Cons]]
- [[Function type]]
- [[Generalized algebraic data type]]
- [[Higher-order function]]
- [[Option type]]
- [[Polymorphism (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/First-class_function