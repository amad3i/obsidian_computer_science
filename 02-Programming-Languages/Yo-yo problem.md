---
title: "Yo-yo problem"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Yo-yo_problem"
wikipedia_categories: ["Anti-patterns", "Object-oriented programming"]
related: ["[[Call super]]", "[[List of software anti-patterns]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[Anemic domain model]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[Circle–ellipse problem]]"]
---

# Yo-yo problem

In software development, the yo-yo problem is an anti-pattern that occurs when a programmer has to read and understand a program whose inheritance graph is so long and complicated that the programmer has to keep flipping between many different class definitions in order to follow the control flow of the program.  It is most often seen in the context of object-oriented programming. The term comes from comparing the bouncing attention of the programmer to the up-down movement of a toy yo-yo. Taenzer, Ganti, and Podar described the problem by name, explaining: "Often we get the feeling of riding a yoyo when we try to understand one of these message trees." 
Most practices of object-oriented programming recommend keeping the inheritance graph as shallow as possible, in part to avoid this problem. The use of composition instead of inheritance is also strongly preferred, although this still requires that a programmer keep multiple class definitions in mind at once.
Deep hierarchies are a code smell and a symptom of sub-classification for code reuse.
More generally, the yo-yo problem can also refer to any situation where a person must keep flipping between different sources of information in order to understand a concept.
There are several code refactor techniques to flatten these hierarchies without compromising the overall behavior.
Object-oriented design techniques such as documenting layers of the inheritance hierarchy can reduce the effect of this problem, as they collect in one place the information that the programmer is required to understand.

## Related

- [[Call super]]
- [[List of software anti-patterns]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[Anemic domain model]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[Circle–ellipse problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Yo-yo_problem