---
title: "Ahead-of-time compilation"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Ahead-of-time_compilation"
wikipedia_categories: ["Compilers"]
related: ["[[Absoft]]", "[[Accelerated Linear Algebra]]", "[[Apple Dylan]]", "[[Arden2ByteCode]]", "[[Ark Compiler]]", "[[Banerjee test]]", "[[Binary optimizer]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]", "[[C--]]"]
---

# Ahead-of-time compilation

In computer science, ahead-of-time compilation (AOT compilation) is the act of compiling an (often) higher-level programming language into an (often) lower-level language before execution of a program, usually at build-time, to reduce the amount of work needed to be performed at run time.
It is most commonly associated with the act of compiling a higher-level programming language such as C or C++, or an intermediate representation such as Java bytecode or Common Intermediate Language (CIL) code, into native machine code so that the resulting binary file can execute natively, just like a standard native compiler. When being used in this context, it is often seen as an opposite of just-in-time (JIT) compiling.
Speaking more generally, the target languages of an AOT compilation are not necessarily specific to native machine code but are defined rather arbitrarily. Some academic papers use this word to mean the act of compiling the Java bytecode to C or the timing when optimization pipeline are performed. An academic project uses this word to mean the act of pre-compiling JavaScript to a machine-dependent optimized IR for V8 (JavaScript engine) and to a machine independent bytecode for JavaScriptCore. Some industrial language implementations (e.g. Clojure and Hermes JavaScript engine) use this word to mean the act of pre-compiling the source language to VM specific bytecode. Angular (web framework) uses this word to mean converting its HTML template and TypeScript to JavaScript.  
In fact, since all static compilation is technically performed ahead of time, this particular wording is often used to emphasize examples where there are significant performance advantages over the act of such pre-compiling. The act of compiling Java to Java bytecode is hence rarely referred to as AOT since it is usually a requirement, not an optimization.

## Related

- [[Absoft]]
- [[Accelerated Linear Algebra]]
- [[Apple Dylan]]
- [[Arden2ByteCode]]
- [[Ark Compiler]]
- [[Banerjee test]]
- [[Binary optimizer]]
- [[Binary recompiler]]
- [[Bootstrapping (compilers)]]
- [[C--]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ahead-of-time_compilation