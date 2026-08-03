---
title: "Balking pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Balking_pattern"
wikipedia_categories: ["Computer programming stubs", "Concurrency (computer science)", "Software design patterns"]
related: ["[[Active object]]", "[[Action–domain–responder]]", "[[Aggregate pattern]]", "[[Broker pattern]]", "[[Concurrency pattern]]", "[[Data transfer object]]", "[[Guarded suspension]]", "[[Head–body pattern]]", "[[Lazy loading]]", "[[UI data binding]]"]
---

# Balking pattern

The balking pattern is a software design pattern that only executes an action on an object when the object is in a particular  state. For example, if an object reads ZIP files and a calling method invokes a get method on the object when the ZIP file is not open, the object would "balk" at the request.  In the Java programming language, for example, an IllegalStateException might be thrown under these circumstances. In C# it would be InvalidOperationException.
There are some specialists in this field who consider balking more of an anti-pattern than a design pattern.  If an object cannot support its API, it should either limit the API so that the offending call is not available, or so that the call can be made without limitation. It should:

Be created in a "sane state";
not make itself available until it is in a sane state;
become a facade and answer back an object that is in a sane state.

## Related

- [[Active object]]
- [[Action–domain–responder]]
- [[Aggregate pattern]]
- [[Broker pattern]]
- [[Concurrency pattern]]
- [[Data transfer object]]
- [[Guarded suspension]]
- [[Head–body pattern]]
- [[Lazy loading]]
- [[UI data binding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Balking_pattern