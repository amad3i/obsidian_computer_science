---
title: "Behavioral subtyping"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Behavioral_subtyping"
wikipedia_categories: ["Object-oriented programming"]
related: ["[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Bounded quantification]]", "[[Call super]]", "[[Circle–ellipse problem]]", "[[Class variable]]", "[[Climate Data Exchange]]", "[[Cloning (programming)]]"]
---

# Behavioral subtyping

In object-oriented programming, behavioral subtyping is the principle that subclasses should satisfy the expectations of clients accessing subclass objects through references of superclass type, not just as regards syntactic safety (such as the absence of "method-not-found" errors) but also as regards behavioral correctness. Specifically, properties that clients can prove using the specification of an object's presumed type should hold even though the object is actually a member of a subtype of that type.
For example, consider a type Stack and a type Queue, which both have a put method to add an element and a get method to remove one. Suppose the documentation associated with these types specifies that type Stack's methods shall behave as expected for stacks (i.e. they shall exhibit LIFO behavior), and that type Queue's methods shall behave as expected for queues (i.e. they shall exhibit FIFO behavior). Suppose, now, that type Stack was declared as a subclass of type Queue. Most programming language compilers ignore documentation and perform only the checks that are necessary to preserve type safety. Since, for each method of type Queue, type Stack provides a method with a matching name and signature, this check would succeed. However, clients accessing a Stack object through a reference of type Queue would, based on Queue's documentation, expect FIFO behavior but observe LIFO behavior, invalidating these clients' correctness proofs and potentially leading to incorrect behavior of the program as a whole.
This example violates behavioral subtyping because type Stack is not a behavioral subtype of type Queue: it is not the case that the behavior described by the documentation of type Stack (i.e. LIFO behavior) complies with the documentation of type Queue (which requires FIFO behavior).
In contrast, a program where both Stack and Queue are subclasses of a type Bag, whose specification for get is merely that it removes some element, does satisfy behavioral subtyping and allows clients to safely reason about correctness based on the presumed types of the objects they interact with. Indeed, any object that satisfies the Stack or Queue specification also satisfies the Bag specification.
It is important to stress that whether a type S is a behavioral subtype of a type T depends only on the specification (i.e. the documentation) of type T; the implementation of type T, if it has any, is completely irrelevant to this question. Indeed, type T need not even have an implementation; it might be a purely abstract class. As another case in point, type Stack above is a behavioral subtype of type Bag even if type Bag's implementation exhibits FIFO behavior: what matters is that type Bag's specification does not specify which element is removed by method get. This also means that behavioral subtyping can be discussed only with respect to a particular (behavioral) specification for each type involved and that if the types involved have no well-defined behavioral specification, behavioral subtyping cannot be discussed meaningfully.

## Related

- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Bounded quantification]]
- [[Call super]]
- [[Circle–ellipse problem]]
- [[Class variable]]
- [[Climate Data Exchange]]
- [[Cloning (programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Behavioral_subtyping