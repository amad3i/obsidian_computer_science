---
title: "HiLog"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/HiLog"
wikipedia_categories: ["Declarative programming languages", "Knowledge representation", "Logic programming languages"]
related: ["[[F-logic]]", "[[QL]]", "[[Datalog]]", "[[Prova]]", "[[Transaction logic]]", "[[4E cognition]]", "[[Agent Communications Language]]", "[[Agentive logic]]", "[[AgMES]]", "[[Agricultural Information Management Standards]]"]
---

# HiLog

HiLog is a programming logic with higher-order syntax, which allows arbitrary terms to appear in predicate and function positions. However, the model theory of HiLog is first-order. Although syntactically HiLog strictly extends first order logic, HiLog can be embedded into this logic.
HiLog was first described in 1989. It was later extended in the direction of many-sorted logic.
The XSB system parses HiLog syntax, but the integration of HiLog into XSB is only partial. In particular, HiLog is not integrated with the XSB module system. A full implementation of HiLog is available in the Flora-2 system.
It has been shown that HiLog can be embedded into first-order logic through a fairly simple transformation. For instance, p(X)(Y,Z(V)(W)) gets embedded as the following first-order term: apply(p(X),Y,apply(apply(Z,V),W)).
The Framework for Logic-Based Dialects (RIF-FLD) of the Rule Interchange Format (RIF) is largely based on the ideas underlying HiLog and F-logic.

## Related

- [[F-logic]]
- [[QL]]
- [[Datalog]]
- [[Prova]]
- [[Transaction logic]]
- [[4E cognition]]
- [[Agent Communications Language]]
- [[Agentive logic]]
- [[AgMES]]
- [[Agricultural Information Management Standards]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HiLog