---
title: "Non-virtual interface pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Non-virtual_interface_pattern"
wikipedia_categories: ["Method (computer programming)", "Software design patterns"]
related: ["[[Double dispatch]]", "[[Factory method pattern]]", "[[Template method pattern]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]"]
---

# Non-virtual interface pattern

The non-virtual interface pattern (NVI) controls how methods in a base class are overridden. Such methods may be called by clients and overridable methods with core functionality. It is a pattern that is strongly related to the template method pattern. The NVI pattern recognizes the benefits of a non-abstract method invoking the subordinate abstract methods. This level of indirection allows for pre and post operations relative to the abstract operations both immediately and with future unforeseen changes. The NVI pattern can be deployed with very little software production and runtime cost. Many commercial software frameworks employ the NVI pattern.

## Related

- [[Double dispatch]]
- [[Factory method pattern]]
- [[Template method pattern]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Non-virtual_interface_pattern