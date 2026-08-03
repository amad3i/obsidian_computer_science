---
title: "Circle–ellipse problem"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Circle–ellipse_problem"
wikipedia_categories: ["Object-oriented programming"]
related: ["[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[Call super]]", "[[Class variable]]", "[[Climate Data Exchange]]", "[[Cloning (programming)]]"]
---

# Circle–ellipse problem

The circle–ellipse problem in software development (sometimes called the square–rectangle problem) illustrates several pitfalls which can arise when using subtype polymorphism in object modelling.  The issues are most commonly encountered when using object-oriented programming (OOP). By definition, this problem is a violation of the Liskov substitution principle, one of the SOLID principles.
The problem concerns which subtyping or inheritance relationship should exist between classes which represent circles and ellipses (or, similarly, squares and rectangles).  More generally, the problem illustrates the difficulties which can occur when a base class contains methods which mutate an object in a manner which may invalidate a (stronger) invariant found in a derived class, causing the Liskov substitution principle to be violated.
The existence of the circle–ellipse problem is sometimes used to criticize object-oriented programming. It may also imply that hierarchical taxonomies are difficult to make universal, implying that situational classification systems may be more practical.

## Related

- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[Call super]]
- [[Class variable]]
- [[Climate Data Exchange]]
- [[Cloning (programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Circle–ellipse_problem