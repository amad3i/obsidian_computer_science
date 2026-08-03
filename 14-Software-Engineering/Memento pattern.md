---
title: "Memento pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Memento_pattern"
wikipedia_categories: ["Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]", "[[Behavioral pattern]]"]
---

# Memento pattern

The memento pattern is a software design pattern in the field of object-oriented programming that allows reverting the state of an object.
Uses of this design pattern include undo, version control, and serialization.
The memento pattern is implemented with three objects: the originator, a caretaker and a memento. The originator is some object that has an internal state. The caretaker is going to do something to the originator, but wants to be able to easily bring back the prior state. The caretaker first asks the originator for a memento object. Then it does whatever operation (or sequence of operations) it was going to do. To roll back to the state before the operations, it returns the memento object to the originator. The memento object itself is immutable. When using this pattern, care should be taken if the originator may change other objects or resources—the memento pattern operates on a single object.
One classic example of this pattern is the pseudorandom number generator (PRNG). In this case, each consumer of the PRNG serves as a caretaker who can initialize the PRNG (the originator) with a particular seed (the memento) to produce an identical sequence of pseudorandom numbers.

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

- Wikipedia: https://en.wikipedia.org/wiki/Memento_pattern