---
title: "Call super"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Call_super"
wikipedia_categories: ["Anti-patterns", "Object-oriented programming"]
related: ["[[List of software anti-patterns]]", "[[Yo-yo problem]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[Anemic domain model]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[Circle–ellipse problem]]"]
---

# Call super

Call super is a code smell or anti-pattern of some object-oriented programming languages. Call super is a design pattern in which a particular class stipulates that in a derived subclass, the user is required to override a method and call back the overridden function itself at a particular point. The overridden method may be intentionally incomplete, and reliant on the overriding method to augment its functionality in a prescribed manner. However, the fact that the language itself may not be able to enforce all conditions prescribed on this call is what makes this an anti-pattern.

## Related

- [[List of software anti-patterns]]
- [[Yo-yo problem]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[Anemic domain model]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[Circle–ellipse problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Call_super