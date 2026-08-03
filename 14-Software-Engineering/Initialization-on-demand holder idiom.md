---
title: "Initialization-on-demand holder idiom"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Initialization-on-demand_holder_idiom"
wikipedia_categories: ["Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]", "[[Behavioral pattern]]"]
---

# Initialization-on-demand holder idiom

In software engineering, the initialization-on-demand holder (design pattern) idiom is a lazy-loaded singleton. In all versions of Java, the idiom enables a safe, highly concurrent lazy initialization of static fields with good performance.

The implementation of the idiom relies on the initialization phase of execution within the Java Virtual Machine (JVM) as specified by the Java Language Specification (JLS). When the class Singleton is loaded by the JVM, the class goes through initialization. Since the class does not have any static variables to initialize, the initialization completes trivially. The static class definition Holder within it is not initialized until the JVM determines that Holder must be executed. The static class Holder is only executed when the static method instance() is invoked on the class Singleton, and the first time this happens the JVM will load and initialize the Holder class. The initialization of the Holder class results in static variable INSTANCE being initialized by executing the (private) constructor for the outer class Singleton. Since the class initialization phase is guaranteed by the JLS to be sequential, i.e., non-concurrent, no further synchronization is required in the static instance() method during loading and initialization. And since the initialization phase writes the static variable INSTANCE in a sequential operation, all subsequent concurrent invocations of the instance() will return the same correctly initialized INSTANCE without incurring any additional synchronization overhead.

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

- Wikipedia: https://en.wikipedia.org/wiki/Initialization-on-demand_holder_idiom