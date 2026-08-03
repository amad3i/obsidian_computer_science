---
title: "Association (object-oriented programming)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Association_(object-oriented_programming)"
wikipedia_categories: ["Computer programming stubs", "Object-oriented programming"]
related: ["[[Convention over Code]]", "[[Indexer (programming)]]", "[[Runtime Callable Wrapper]]", "[[Singly rooted hierarchy]]", "[[Abstraction (computer science)]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Aggregate pattern]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]"]
---

# Association (object-oriented programming)

In object-oriented programming, association defines a relationship between classes of  objects that allows one object instance to cause another to perform an action on its behalf. This relationship is structural, because it specifies that objects of one kind are connected to objects of another and does not represent behaviour.

In generic terms, the causation is usually called "sending a message", "invoking a method" or "calling a member function" to the controlled object. Concrete implementation usually requires the requesting object to invoke a method or member function using a reference or pointer to the memory location of the controlled object.
The objects that are related via the association are considered to act in a role with respect to the association, if object's current state in the active situation allows the other associated objects to use the object in the manner specified by the role. A role can be used to distinguish two objects of the same class when describing its use in the context of the association. A role describes the public aspects of an object with respect to an association.
The ends of the association can have all the characteristics of a property:

They can have a multiplicity, expressed by a lower and an upper limit in the form of "lowerLimit..upperLimit".
You can have a name.
You can declare a visibility.
You can specify whether the end of the association is ordered and / or unique.

## Related

- [[Convention over Code]]
- [[Indexer (programming)]]
- [[Runtime Callable Wrapper]]
- [[Singly rooted hierarchy]]
- [[Abstraction (computer science)]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Aggregate pattern]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Association_(object-oriented_programming)