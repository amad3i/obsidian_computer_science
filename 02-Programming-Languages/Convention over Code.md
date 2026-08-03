---
title: "Convention over Code"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Convention_over_Code"
wikipedia_categories: ["Computer programming stubs", "Object-oriented programming"]
related: ["[[Association (object-oriented programming)]]", "[[Indexer (programming)]]", "[[Runtime Callable Wrapper]]", "[[Singly rooted hierarchy]]", "[[Abstraction (computer science)]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Aggregate pattern]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]"]
---

# Convention over Code

Convention over Code is a design approach for programming languages where the conventional use of a feature is taken into consideration when defining the default semantics of the feature.
Similar to Convention over Configuration, if a keyword can be implied by its absence due to convention, it becomes less a part of the idea the coder is expressing and a part of the hidden implementation.
A common, notorious example is found in Java and C#. We find the keyword public infused throughout a typical Java code excerpt, and in the case of methods this access modifier implies public scope access. In practice, more methods use public scope access than the other three: private, protected and package protected (which happens to be the actual Java default). While a matter of opinion and much debate by programmers that love to be explicit about everything, it is clear that leaving out scope access keywords altogether takes very little away from the actual expression of an idea in code, because it has nothing to do with the idea at all, it is an attribute of the implementation of an idea.
Convention over Code means we would make public the default for methods, and make better use of keyword Huffman coding in language design.

## Related

- [[Association (object-oriented programming)]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Convention_over_Code