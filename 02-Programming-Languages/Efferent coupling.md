---
title: "Efferent coupling"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Efferent_coupling"
wikipedia_categories: ["Programming language theory stubs", "Software metrics"]
related: ["[[ABC Software Metric]]", "[[Bauhaus Project (computing)]]", "[[Cockburn Scale]]", "[[Code coverage]]", "[[Cohesion (computer science)]]", "[[Container (type theory)]]", "[[COSMIC functional size measurement]]", "[[Coupling (computer programming)]]", "[[Cppdepend]]", "[[Cyclomatic complexity]]"]
---

# Efferent coupling

Efferent coupling is a coupling metric in software development. It measures the number of data types a class knows about.
This includes inheritance, interface implementation, parameter types, variable types, and exceptions.
This has also been referred to by Robert C. Martin as the Fan-out stability metric which in his book Clean Architecture he describes as Outgoing dependencies. This metric identifies the number of classes inside this component that depend on classes outside the component.
This metric is often used to calculate instability of a component in software architecture as I = Fan-out / (Fan-in + Fan-out). This metric has a range [0,1]. I = 0 is maximally stable while I = 1 is maximally unstable.

## Related

- [[ABC Software Metric]]
- [[Bauhaus Project (computing)]]
- [[Cockburn Scale]]
- [[Code coverage]]
- [[Cohesion (computer science)]]
- [[Container (type theory)]]
- [[COSMIC functional size measurement]]
- [[Coupling (computer programming)]]
- [[Cppdepend]]
- [[Cyclomatic complexity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Efferent_coupling