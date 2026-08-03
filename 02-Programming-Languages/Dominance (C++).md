---
title: "Dominance (C++)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Dominance_(C++)"
wikipedia_categories: ["C++", "Object-oriented programming"]
related: ["[[Object slicing]]", "[[Resource acquisition is initialization]]", "[[Virtual function]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[C++]]"]
---

# Dominance (C++)

In the C++ programming language, dominance refers to a particular aspect of C++ name lookup in the presence of Inheritance. When the compiler computes the set of declarations to which a particular name might refer, declarations in very-ancestral classes which are "dominated" by declarations in less-ancestral classes are hidden for the purposes of name lookup. In other languages or contexts, the same principle may be referred to as "name masking" or "shadowing".
The algorithm for computing name lookup is described in section 10.2 [class.member.lookup] of the C++11 Standard. The Standard's description does not use the word "dominance", preferring to describe things in terms of declaration sets and hiding. However, the Index contains an entry for "dominance, virtual base class" referring to section 10.2.

## Related

- [[Object slicing]]
- [[Resource acquisition is initialization]]
- [[Virtual function]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[C++]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dominance_(C++)