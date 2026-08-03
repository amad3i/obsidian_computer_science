---
title: "Implicit invocation"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Implicit_invocation"
wikipedia_categories: ["Computer science stubs", "Software architecture"]
related: ["[[Service-oriented development of applications]]", "[[4+1 architectural view model]]", "[[Active reviews for intermediate designs]]", "[[Agent architecture]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[Anemic domain model]]", "[[Application domain]]", "[[Application server]]"]
---

# Implicit invocation

Implicit invocation is a term used by some authors for a style of software architecture in which a system is structured around event handling, using a form of callback. It is closely related to inversion of control and what is known informally as the Hollywood principle.

The idea behind implicit invocation is that instead of invoking a procedure directly, a component can announce (or broadcast) one or more events. Other components in the system can register an interest in an event by associating a procedure with the event. When the event is announced the system itself invokes all of the procedures that have been registered for the event. Thus an event announcement implicitly causes the invocation of procedures in other modules.
Implicit invocation is the core technique behind the observer pattern.

## Related

- [[Service-oriented development of applications]]
- [[4+1 architectural view model]]
- [[Active reviews for intermediate designs]]
- [[Agent architecture]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[Anemic domain model]]
- [[Application domain]]
- [[Application server]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Implicit_invocation