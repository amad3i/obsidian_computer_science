---
title: "Path explosion"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Path_explosion"
wikipedia_categories: ["Program analysis"]
related: ["[[Abstract interpretation]]", "[[Aliasing (computing)]]", "[[Compiler-compiler]]", "[[Context-free language reachability]]", "[[Dynamic program analysis]]", "[[Effect system]]", "[[Flow-sensitive typing]]", "[[KPI-driven code analysis]]", "[[Perl--Critic]]", "[[Polyvariance]]"]
---

# Path explosion

In computer science, path explosion is a fundamental problem that limits the scalability and/or completeness of certain kinds of program analyses, including fuzzing, symbolic execution, and path-sensitive static analysis. Path explosion refers to the fact that the number of control-flow paths in a program grows exponentially ("explodes") with an increase in program size and can even be infinite in the case of programs with unbounded loop iterations. Therefore, any program analysis that attempts to explore control-flow paths through a program will either have exponential runtime in the length of the program (or potentially even failure to terminate on certain inputs), or will have to choose to analyze only a subset of all possible paths. When an analysis only explores a subset of all paths, the decision of which paths to analyze is often made heuristically.

## Related

- [[Abstract interpretation]]
- [[Aliasing (computing)]]
- [[Compiler-compiler]]
- [[Context-free language reachability]]
- [[Dynamic program analysis]]
- [[Effect system]]
- [[Flow-sensitive typing]]
- [[KPI-driven code analysis]]
- [[Perl--Critic]]
- [[Polyvariance]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Path_explosion