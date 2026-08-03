---
title: "Scope (computer programming)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Scope_(computer_programming)"
wikipedia_categories: ["Programming language comparisons", "Programming language concepts"]
related: ["[[Boxing (computer programming)]]", "[[Polymorphism (computer science)]]", "[[Assignment (computer science)]]", "[[Binding time]]", "[[Bridging (programming)]]", "[[Carbon (programming language)]]", "[[Comparison of multi-paradigm programming languages]]", "[[Comparison of programming languages (object-oriented programming)]]", "[[Constructor (object-oriented programming)]]", "[[Context-free language reachability]]"]
---

# Scope (computer programming)

In computer programming, the scope of a name binding (an association of a name to an entity, such as a variable) is the part of a program in which the name binding is valid. In other words, a scope is where a name can be used to refer to an entity. In other parts of the program, the name may refer to a different entity (it may have a different binding), or to nothing at all (it may be unbound). Scope helps prevent name collisions by allowing the same name to refer to different objects – as long as the names have separate scopes. The scope of a name binding is also known as the visibility of an entity, particularly in older or more technical literature—this is in relation to the referenced entity, not the referencing name.
The term "scope" is also used to refer to the set of all name bindings that are valid within a part of a program or at a given point in a program, which is more correctly referred to as context or environment.
Strictly speaking and in practice for most programming languages, "part of a program" refers to a portion of source code (area of text), and is known as lexical scope. In some languages, however, "part of a program" refers to a portion of run time (period during execution), and is known as dynamic scope. Both of these terms are somewhat misleading—they misuse technical terms, as discussed in the definition—but the distinction itself is accurate and precise, and these are the standard respective terms. Lexical scope is the main focus of this article, with dynamic scope understood by contrast with lexical scope.
In most cases, name resolution based on lexical scope is relatively straightforward to use and to implement, as in use one can read backwards in the source code to determine to which entity a name refers, and in implementation one can maintain a list of names and contexts when compiling or interpreting a program. Difficulties arise in name masking, forward declarations, and hoisting, while considerably subtler ones arise with non-local variables, particularly in closures.

## Related

- [[Boxing (computer programming)]]
- [[Polymorphism (computer science)]]
- [[Assignment (computer science)]]
- [[Binding time]]
- [[Bridging (programming)]]
- [[Carbon (programming language)]]
- [[Comparison of multi-paradigm programming languages]]
- [[Comparison of programming languages (object-oriented programming)]]
- [[Constructor (object-oriented programming)]]
- [[Context-free language reachability]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Scope_(computer_programming)