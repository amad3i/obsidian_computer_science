---
title: "Symbolic execution"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Symbolic_execution"
wikipedia_categories: ["Abstract interpretation", "Program analysis"]
related: ["[[Abstract interpretation]]", "[[Aliasing (computing)]]", "[[Compiler-compiler]]", "[[Context-free language reachability]]", "[[Dynamic program analysis]]", "[[Effect system]]", "[[Flow-sensitive typing]]", "[[KPI-driven code analysis]]", "[[Path explosion]]", "[[Perl--Critic]]"]
---

# Symbolic execution

In computer science, symbolic execution (also symbolic evaluation or symbex) is a means of analyzing a program to determine what inputs cause each part of a program to execute.  An interpreter follows the program, assuming symbolic values for inputs rather than obtaining actual inputs as normal execution of the program would.  It thus arrives at expressions in terms of those symbols for expressions and variables in the program, and constraints in terms of those symbols for the possible outcomes of each conditional branch. Finally, the possible inputs that trigger a branch can be determined by solving the constraints.
The field of symbolic simulation applies the same concept to hardware. Symbolic computation applies the concept to the analysis of mathematical expressions.

## Related

- [[Abstract interpretation]]
- [[Aliasing (computing)]]
- [[Compiler-compiler]]
- [[Context-free language reachability]]
- [[Dynamic program analysis]]
- [[Effect system]]
- [[Flow-sensitive typing]]
- [[KPI-driven code analysis]]
- [[Path explosion]]
- [[Perl--Critic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Symbolic_execution