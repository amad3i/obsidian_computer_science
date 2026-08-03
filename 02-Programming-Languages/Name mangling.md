---
title: "Name mangling"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Name_mangling"
wikipedia_categories: ["C++", "Compiler construction", "Computer libraries", "Java (programming language)"]
related: ["[[Binary recompiler]]", "[[Edison Design Group]]", "[[Name resolution (programming languages)]]", "[[Object file]]", "[[Static build]]", "[[Abstract syntax]]", "[[Accord.NET]]", "[[Affix grammar]]", "[[AgentSheets]]", "[[Aliasing (computing)]]"]
---

# Name mangling

In compiler construction, name mangling (also called name decoration) is a technique used to solve various problems caused by the need to resolve unique names for programming entities in many modern programming languages.
It provides means to encode added information in the name of a function, structure, class or another data type, to pass more semantic information from the compiler to the linker.
The need for name mangling arises where a language allows different entities to be named with the same identifier as long as they occupy a different namespace (typically defined by a module, class, or explicit namespace directive) or have different type signatures (such as in function overloading). It is required in these uses because each signature might require different, specialized calling convention in the machine code.
Any object code produced by compilers is usually linked with other pieces of object code (produced by the same or another compiler) by a type of program called a linker. The linker needs a great deal of information on each program entity. For example, to correctly link a function it needs its name, the number of arguments and their types, and so on.
The simple programming languages of the 1970s, like C, only distinguished subroutines by their name, ignoring other information including parameter and return types.
Later languages, like C++, defined stricter requirements for routines to be considered "equal", such as the parameter types, return type, and calling convention of a function. These requirements enable method overloading and detection of some bugs (such as using different definitions of a function when compiling different source code files).
These stricter requirements needed to work with extant programming tools and conventions. Thus, added requirements were encoded in the name of the symbol, since that was the only information a traditional linker had about a symbol.

## Related

- [[Binary recompiler]]
- [[Edison Design Group]]
- [[Name resolution (programming languages)]]
- [[Object file]]
- [[Static build]]
- [[Abstract syntax]]
- [[Accord.NET]]
- [[Affix grammar]]
- [[AgentSheets]]
- [[Aliasing (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Name_mangling