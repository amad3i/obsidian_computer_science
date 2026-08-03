---
title: "Generation gap (pattern)"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Generation_gap_(pattern)"
wikipedia_categories: ["Computer science stubs", "Software design patterns"]
related: ["[[Concurrency pattern]]", "[[Distributed design patterns]]", "[[Identity map pattern]]", "[[Strangler fig pattern]]", "[[Table data gateway]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]"]
---

# Generation gap (pattern)

Generation gap is a software design pattern documented by John Vlissides that treats automatically generated code differently than code that was written by a developer. Modifications should not be made to generated code, as they would be overwritten if the code generation process was ever re-run, such as during recompilation.  Vlissides proposed creating a subclass of the generated code which contains the desired modification. This might be considered an example of the template method pattern.

## Related

- [[Concurrency pattern]]
- [[Distributed design patterns]]
- [[Identity map pattern]]
- [[Strangler fig pattern]]
- [[Table data gateway]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Generation_gap_(pattern)