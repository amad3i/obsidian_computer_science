---
title: "Aspect-oriented programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Aspect-oriented_programming"
wikipedia_categories: ["Aspect-oriented programming", "Aspect-oriented software development", "Programming paradigms"]
related: ["[[Aspect weaver]]", "[[AspectJ]]", "[[Subject-oriented programming]]", "[[Array programming]]", "[[Attribute-oriented programming]]", "[[Automata-based programming]]", "[[Automata-based programming (Shalyto's approach)]]", "[[Automatic programming]]", "[[Choreographic programming]]", "[[Comparison of multi-paradigm programming languages]]"]
---

# Aspect-oriented programming

In computing, aspect-oriented programming (AOP) is a programming paradigm that aims to increase modularity by allowing the separation of cross-cutting concerns. It does so by adding behavior to existing code (an advice) without modifying the code, instead separately specifying which code is modified via a "pointcut" specification, such as "log all function calls when the function's name begins with 'set'". This allows behaviors that are not central to the business logic (such as logging) to be added to a program without cluttering the code of core functions.
AOP includes programming methods and tools that support the modularization of concerns at the level of the source code, while aspect-oriented software development refers to a whole engineering discipline.
Aspect-oriented programming entails breaking down program logic into cohesive areas of functionality (so-called concerns). Nearly all programming paradigms support some level of grouping and encapsulation of concerns into separate, independent entities by providing abstractions (e.g., functions, procedures, modules, classes, methods) that can be used for implementing, abstracting, and composing these concerns. Some concerns "cut across" multiple abstractions in a program, and defy these forms of implementation. These concerns are called cross-cutting concerns or horizontal concerns.
Logging exemplifies a cross-cutting concern because a logging strategy must affect every logged part of the system. Logging thereby crosscuts all logged classes and methods.
All AOP implementations have some cross-cutting expressions that encapsulate each concern in one place. The difference between implementations lies in the power, safety, and usability of the constructs provided. For example, interceptors that specify the methods to express a limited form of cross-cutting, without much support for type-safety or debugging. AspectJ has a number of such expressions and encapsulates them in a special class, called an aspect. For example, an aspect can alter the behavior of the base code (the non-aspect part of a program) by applying advice (additional behavior) at various join points (points in a program) specified in a quantification or query called a pointcut (that detects whether a given join point matches). An aspect can also make binary-compatible structural changes to other classes, such as adding members or parents.

## Related

- [[Aspect weaver]]
- [[AspectJ]]
- [[Subject-oriented programming]]
- [[Array programming]]
- [[Attribute-oriented programming]]
- [[Automata-based programming]]
- [[Automata-based programming (Shalyto's approach)]]
- [[Automatic programming]]
- [[Choreographic programming]]
- [[Comparison of multi-paradigm programming languages]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Aspect-oriented_programming