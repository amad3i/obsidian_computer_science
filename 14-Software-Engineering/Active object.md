---
title: "Active object"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Active_object"
wikipedia_categories: ["Computer programming stubs", "Concurrency (computer science)", "Software design patterns"]
related: ["[[Balking pattern]]", "[[Action–domain–responder]]", "[[Aggregate pattern]]", "[[Broker pattern]]", "[[Concurrency pattern]]", "[[Data transfer object]]", "[[Guarded suspension]]", "[[Head–body pattern]]", "[[Lazy loading]]", "[[UI data binding]]"]
---

# Active object

The active object design pattern decouples method execution from method invocation for objects that each reside in their own thread of control. The goal is to introduce concurrency, by using asynchronous method invocation and a scheduler for handling requests.
The pattern consists of six elements:

A proxy, which provides an interface towards clients with publicly accessible methods.
An interface which defines the method request on an active object.
A list of pending requests from clients.
A scheduler, which decides which request to execute next.
The implementation of the active object method.
A callback or variable for the client to receive the result.

## Related

- [[Balking pattern]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Active_object