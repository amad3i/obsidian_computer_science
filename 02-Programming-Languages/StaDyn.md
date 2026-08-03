---
title: "StaDyn"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/StaDyn"
wikipedia_categories: [".NET programming languages", "2007 software", "Class-based programming languages", "Dynamically typed programming languages", "Free and open source compilers", "Object-oriented programming languages", "Programming languages", "Programming languages created in 2007"]
related: ["[[Boo (programming language)]]", "[[Smalltalk]]", "[[D (programming language)]]", "[[J (programming language)]]", "[[Julia (programming language)]]", "[[PHP]]", "[[Python (programming language)]]", "[[Self (programming language)]]", "[[ABAP]]", "[[Apache Groovy]]"]
---

# StaDyn

StaDyn is an object-oriented general-purpose programming language for the .NET platform that supports both static and dynamic typing in the same programming language.
The StaDyn compiler gathers type information for the dynamically typed code. That type information is used to detect type errors at compilation time and to perform significant optimizations. For that purpose, it provides type reconstruction (inference), flow-sensitive types, union and intersection types, constraint-based typing,  alias analysis and method specialization.
Its first prototype appeared in 2007, as a modification of C# 3.0. Type inference was supported by including var as a new type, unlike C#, which only offers var to define initialized local variables. Flow-sensitive types of var references are inferred by the compiler, providing type-safe duck typing. When a more lenient approach is required by the programmer, the dynamictype could be used instead of var. Although type inference is still performed, dynamic references behave closer to those in dynamic languages.
StaDyn is designed by Francisco Ortin from the University of Oviedo. The language has been implemented by different members of the Computational Reflection research group, including Miguel Garcia, Jose Baltasar García Perez-Schofield and Jose Quiroga, besides Francisco Ortin.
The name StaDyn is a portmanteau of static and dynamic, denoting its aim to provide the benefits of both static and dynamic typing.

## Related

- [[Boo (programming language)]]
- [[Smalltalk]]
- [[D (programming language)]]
- [[J (programming language)]]
- [[Julia (programming language)]]
- [[PHP]]
- [[Python (programming language)]]
- [[Self (programming language)]]
- [[ABAP]]
- [[Apache Groovy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/StaDyn