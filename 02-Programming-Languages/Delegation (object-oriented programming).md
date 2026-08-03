---
title: "Delegation (object-oriented programming)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Delegation_(object-oriented_programming)"
wikipedia_categories: ["Object-oriented programming", "Prototype-based programming"]
related: ["[[Prototype-based programming]]", "[[Schizophrenia (object-oriented programming)]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[Call super]]", "[[Circle–ellipse problem]]"]
---

# Delegation (object-oriented programming)

In object-oriented programming, delegation refers to evaluating a member (property or method) of one object (the receiver) in the context of another original object (the sender). Delegation can be done explicitly, by passing the responsibilities of the sending object to the receiving object, which can be done in any object-oriented language; or implicitly, by the member lookup rules of the language, which requires language support for the feature. Implicit delegation is the fundamental method for behavior reuse in prototype-based programming, corresponding to inheritance in class-based programming. The best-known languages that support delegation at the language level are Self, which incorporates the notion of delegation through its notion of mutable parent slots that are used upon method lookup on self calls, and JavaScript; see JavaScript delegation.
The term delegation is also used loosely for various other relationships between objects; see delegation (programming) for more. Frequently confused concepts are simply using another object, more precisely referred to as consultation or aggregation; and evaluating a member on one object by evaluating the corresponding member on another object, notably in the context of the receiving object, which is more precisely referred to as forwarding (when a wrapper object doesn't pass itself to the wrapped object). The delegation pattern is a software design pattern for implementing delegation, though this term is also used loosely for consultation or forwarding.

## Related

- [[Prototype-based programming]]
- [[Schizophrenia (object-oriented programming)]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[Call super]]
- [[Circle–ellipse problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Delegation_(object-oriented_programming)