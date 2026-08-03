---
title: "Observer pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Observer_pattern"
wikipedia_categories: ["Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]", "[[Behavioral pattern]]"]
---

# Observer pattern

In software design and software engineering, the observer pattern is a software design pattern in which an object, called the subject (also known as event source or event stream), maintains a list of its dependents, called observers (also known as event sinks), and automatically notifies them of any state changes, typically by calling one of their methods. The subject knows its observers through a standardized interface and manages the subscription list directly.
This pattern creates a one-to-many dependency where multiple observers can listen to a single subject, but the coupling is typically synchronous and direct—the subject calls observer methods when changes occur, though asynchronous implementations using event queues are possible. Unlike the publish-subscribe pattern, there is no intermediary broker; the subject and observers have direct references to each other.
It is commonly used to implement event handling systems in event-driven programming, particularly in-process systems like GUI toolkits or MVC frameworks. This makes the pattern well-suited to processing data that arrives unpredictably—such as user input, HTTP requests, GPIO signals, updates from distributed databases, or changes in a GUI model.

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

- Wikipedia: https://en.wikipedia.org/wiki/Observer_pattern