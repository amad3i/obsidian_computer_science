---
title: "Compiler-compiler"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Compiler-compiler"
wikipedia_categories: ["Compiler construction", "Compiler theory", "Domain-specific programming languages", "Extensible syntax programming languages", "Metaprogramming", "Parser generators", "Parsing", "Pattern matching programming languages"]
related: ["[[Compiler Description Language]]", "[[Abstract syntax]]", "[[Attribute grammar]]", "[[AWK]]", "[[Bootstrapping (compilers)]]", "[[Compilers- Principles, Techniques, and Tools]]", "[[Elm (programming language)]]", "[[Lexical analysis]]", "[[Optimizing compiler]]", "[[Red (programming language)]]"]
---

# Compiler-compiler

In computer science, a compiler-compiler or compiler generator is a programming tool that creates a parser, interpreter, or compiler from some form of formal description of a programming language and machine.
The most common type of compiler-compiler is called a parser generator. It handles only syntactic analysis.
A formal description of a language is usually a grammar used as an input to a parser generator. It often resembles Backus–Naur form (BNF), extended Backus–Naur form (EBNF), or has its own syntax. Grammar files describe a syntax of a generated compiler's target programming language and actions that should be taken against its specific constructs.
Source code for a parser of the programming language is returned as the parser generator's output. This source code can then be compiled into a parser, which may be either standalone or embedded. The compiled parser then accepts the source code of the target programming language as an input and performs an action or outputs an abstract syntax tree (AST).
Parser generators do not handle the semantics of the AST, or the generation of machine code for the target machine.
A metacompiler is a software development tool used mainly in the construction of compilers, translators, and interpreters for other programming languages. The input to a metacompiler is a computer program written in a specialized programming metalanguage designed mainly for the purpose of constructing compilers. The language of the compiler produced is called the object language. The minimal input producing a compiler is a metaprogram specifying the object language grammar and semantic transformations into an object program.

## Related

- [[Compiler Description Language]]
- [[Abstract syntax]]
- [[Attribute grammar]]
- [[AWK]]
- [[Bootstrapping (compilers)]]
- [[Compilers- Principles, Techniques, and Tools]]
- [[Elm (programming language)]]
- [[Lexical analysis]]
- [[Optimizing compiler]]
- [[Red (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Compiler-compiler