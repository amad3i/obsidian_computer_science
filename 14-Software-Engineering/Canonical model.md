---
title: "Canonical model"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Canonical_model"
wikipedia_categories: ["Enterprise application integration", "Enterprise architecture", "Enterprise modelling", "Software design patterns"]
related: ["[[ADOIT]]", "[[ArchiMate]]", "[[Enterprise Architect (software)]]", "[[Enterprise content management]]", "[[Enterprise engineering]]", "[[Enterprise information system]]", "[[Enterprise integration]]", "[[Enterprise Integration Patterns]]", "[[Service-oriented architecture]]", "[[Thoughtworks]]"]
---

# Canonical model

A canonical model is a design pattern used to communicate between different data formats.  Essentially:  create a data model which is a superset of all the others ("canonical"), and create a "translator" module or layer to/from which all existing modules exchange data with other modules. The canonical model acts as a middleman. Each model now only needs to know how to communicate with the canonical model and doesn't need to know the implementation details of the other modules.

## Related

- [[ADOIT]]
- [[ArchiMate]]
- [[Enterprise Architect (software)]]
- [[Enterprise content management]]
- [[Enterprise engineering]]
- [[Enterprise information system]]
- [[Enterprise integration]]
- [[Enterprise Integration Patterns]]
- [[Service-oriented architecture]]
- [[Thoughtworks]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Canonical_model