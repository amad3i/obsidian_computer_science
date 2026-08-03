---
title: "Vala (programming language)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Vala_(programming_language)"
wikipedia_categories: ["2006 software", "Cross-platform free software", "Object-oriented programming languages", "Programming languages", "Programming languages created in 2006", "Software using the GNU Lesser General Public License", "Source-to-source compilers", "Statically typed programming languages"]
related: ["[[Scala (programming language)]]", "[[Crystal (programming language)]]", "[[Gosu (programming language)]]", "[[Processing]]", "[[Swift (programming language)]]", "[[V (programming language)]]", "[[ABAP]]", "[[Apache Groovy]]", "[[Boo (programming language)]]", "[[Carbon (programming language)]]"]
---

# Vala (programming language)

Vala is an object-oriented programming language with a self-hosting compiler that generates an intermediate representation in C source code and uses the GObject system. It is free and open-source software released with a GNU Lesser General Public License (LGPL) version 2.1+. 
Vala is syntactically similar to C# and includes notable features such as anonymous functions, signals, properties, generics, assisted memory management, exception handling, type inference, and foreach statements. Its developers, Jürg Billeter and Raffaele Sandrini, wanted to bring these features to the plain C runtime with little overhead and no special runtime support by targeting the GObject object system. Rather than compiling directly to machine code or assembly language, it compiles to a lower-level intermediate language. It transpiles to C, which is then compiled with a C compiler for a given platform, such as GNU Compiler Collection (GCC) or Clang.
Using functions from native code libraries requires writing vapi files, defining the library interfaces. Writing these interface definitions is well-documented for C libraries. Bindings are already available for many libraries, including some not based on GObject such as the multimedia library Simple DirectMedia Layer (SDL) and OpenGL.

## Related

- [[Scala (programming language)]]
- [[Crystal (programming language)]]
- [[Gosu (programming language)]]
- [[Processing]]
- [[Swift (programming language)]]
- [[V (programming language)]]
- [[ABAP]]
- [[Apache Groovy]]
- [[Boo (programming language)]]
- [[Carbon (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vala_(programming_language)