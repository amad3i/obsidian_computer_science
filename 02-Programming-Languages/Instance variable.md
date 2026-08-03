---
title: "Instance variable"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Instance_variable"
wikipedia_categories: ["Object-oriented programming", "Variable (computer science)"]
related: ["[[Class variable]]", "[[Member variable]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[Call super]]", "[[Circle–ellipse problem]]"]
---

# Instance variable

In class-based, object-oriented programming, an instance variable is a variable defined in a class (i.e., a member variable), for which each instantiated object of the class has a separate copy, or instance. An instance variable has similarities with a class variable, but is non-static. In C++ or Java language, an instance variable is a variable which is declared in a class but outside of constructors, methods, or blocks. Instance variables are created when an object is instantiated, and are accessible to all the constructors, methods, or blocks in the class. Access modifiers can be given to the instance variable.
An instance variable is not a class variable, although there are similarities. Both are a type of class attribute (or class property, field, or data member). While an instance variable's value may differ between instances of a class, a class variable can only have one value at any one time, shared between all instances. The same dichotomy between instance and class members applies to methods ("member functions") as well.
Each instance variable lives in memory for the lifetime of the object it is owned by.
Instance variables are properties of that object. All instances of a class have their own copies of instance variables, even if the value is the same from one object to another. One class instance can change values of its instance variables without affecting all other instances. A class may have both instance variables and class variables.
Instance variables can be used by all instance methods of an object, but may not be used by class methods. An instance variable may also be changed directly, provided access restrictions are set.

## Related

- [[Class variable]]
- [[Member variable]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[Call super]]
- [[Circle–ellipse problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Instance_variable