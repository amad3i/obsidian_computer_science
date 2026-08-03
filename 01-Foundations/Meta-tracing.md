---
title: "Meta-tracing"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Meta-tracing"
wikipedia_categories: ["Compiler construction", "Computer science stubs", "Software optimization"]
related: ["[[Semantic dictionary encoding]]", "[[Tracing just-in-time compilation]]", "[[Abstract syntax]]", "[[Affix grammar]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Aliasing (computing)]]", "[[Analog image processing]]", "[[Analytical Performance Modeling]]", "[[Approximate computing]]"]
---

# Meta-tracing

Meta-tracing is a mostly automatic transformation that takes an interpreter as input and produces a tracing just-in-time compiler as output. Since interpreters are usually easier to write than compilers, but run slower, this technique can make it easier to produce efficient implementations of programming languages.
The essence of the approach is based on the use of two levels of interpretation, in which a tracing interpreter is used to execute a second interpreter that interprets the target language for which a compiler is to be generated; the tracing interpreter then watches the second interpreter as it executes sequences of instructions generated from the input program.  
This approach is used by the PyPy project to create their Python compiler, by meta-tracing a Python interpreter written in RPython, a restricted version of the Python programming language. In the special case of RPython, the RPython language is itself interpreted by an interpreter written in the full Python language, symbolized by the PyPy project's logo of an ouroboros.
RPython has also been used to create an interpreter for the Scheme programming language.
Meta-tracing can be compared to the AST-guided partial evaluation approach for generating compilers, such as the Truffle/JS compiler for the JavaScript programming language. Both meta-tracing and AST-guided partial evaluation can be viewed as examples of Futamura projection.

## Related

- [[Semantic dictionary encoding]]
- [[Tracing just-in-time compilation]]
- [[Abstract syntax]]
- [[Affix grammar]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Aliasing (computing)]]
- [[Analog image processing]]
- [[Analytical Performance Modeling]]
- [[Approximate computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Meta-tracing