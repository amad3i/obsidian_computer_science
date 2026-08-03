---
title: "Cyclomatic complexity"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Cyclomatic_complexity"
wikipedia_categories: ["Software metrics"]
related: ["[[ABC Software Metric]]", "[[Bauhaus Project (computing)]]", "[[Cockburn Scale]]", "[[Code coverage]]", "[[Cohesion (computer science)]]", "[[COSMIC functional size measurement]]", "[[Coupling (computer programming)]]", "[[Cppdepend]]", "[[Design predicates]]", "[[Domain-to-range ratio]]"]
---

# Cyclomatic complexity

Cyclomatic complexity is a software metric used to indicate the complexity of a program. It is a quantitative measure of the number of linearly independent paths through a program's source code. It was developed by Thomas J. McCabe, Sr. in 1976.
Cyclomatic complexity is computed using the control-flow graph of the program. The nodes of the graph correspond to indivisible groups of commands of a program, and a directed edge connects two nodes if the second command might be executed immediately after the first command. Cyclomatic complexity may also be applied to individual functions, modules, methods, or classes within a program.
One testing strategy, called basis path testing by McCabe who first proposed it, is to test each linearly independent path through the program. In this case, the number of test cases will equal the cyclomatic complexity of the program.

## Related

- [[ABC Software Metric]]
- [[Bauhaus Project (computing)]]
- [[Cockburn Scale]]
- [[Code coverage]]
- [[Cohesion (computer science)]]
- [[COSMIC functional size measurement]]
- [[Coupling (computer programming)]]
- [[Cppdepend]]
- [[Design predicates]]
- [[Domain-to-range ratio]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cyclomatic_complexity