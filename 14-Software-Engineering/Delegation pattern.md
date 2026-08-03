---
title: "Delegation pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Delegation_pattern"
wikipedia_categories: ["Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]", "[[Behavioral pattern]]"]
---

# Delegation pattern

In software engineering, the delegation pattern is an object-oriented design pattern that allows object composition to achieve the same code reuse as inheritance.
In delegation, an object handles a request by delegating to a second object (the delegate).  The delegate is a helper object, but with the original context. With language-level support for delegation, this is done implicitly by having self in the delegate refer to the original (sending) object, not the delegate (receiving object). In the delegate pattern, this is instead accomplished by explicitly passing the original object to the delegate, as an argument to a method. "Delegation" is often used loosely to refer to the distinct concept of forwarding, where the sending object simply uses the corresponding member on the receiving object, evaluated in the context of the receiving object, not the original object.
This article uses "sending object/receiving object" for the two objects, rather than "receiving object/delegate", emphasizing which objects send and receive the delegation call, not the original call.

## Related

- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]
- [[Asynchronous method invocation]]
- [[Balking pattern]]
- [[Behavioral pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Delegation_pattern