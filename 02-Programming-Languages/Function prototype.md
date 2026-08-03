---
title: "Function prototype"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Function_prototype"
wikipedia_categories: ["C programming language family", "Computer programming", "Subroutines"]
related: ["[[Event (computing)]]", "[[Alef (programming language)]]", "[[Algorave]]", "[[Anonymous function]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[C (programming language)]]"]
---

# Function prototype

In computer programming, a function prototype  is a declaration of a function that specifies the function's name and type signature (arity, data types of parameters, and return type), but omits the function body. While a function definition specifies how the function does what it does (the "implementation"), a function prototype merely specifies its interface, i.e. what data types go in and come out of it. The term "function prototype" is particularly used in the context of the programming languages C and C++ where placing forward declarations of functions in header files allows for splitting a program into translation units, i.e. into parts that a compiler can separately translate into object files, to be combined by a linker into an executable or a library. The function declaration precedes the function definition, giving details of name, return type, and storage class along with other relevant attributes.
Function prototypes can be used when either:

Defining an external type
Creating an interface part
In a prototype, parameter names are optional (and in C/C++ have function prototype scope, meaning their scope ends at the end of the prototype), however, the type is necessary along with all modifiers (e.g. if it is a pointer or a reference to const parameter) except const alone.
In object-oriented programming, interfaces and abstract methods serve much the same purpose.

## Related

- [[Event (computing)]]
- [[Alef (programming language)]]
- [[Algorave]]
- [[Anonymous function]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[C (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Function_prototype