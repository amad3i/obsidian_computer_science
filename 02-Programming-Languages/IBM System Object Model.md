---
title: "IBM System Object Model"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/IBM_System_Object_Model"
wikipedia_categories: ["IBM software", "OS/2 technology", "Object-oriented programming", "Object request broker"]
related: ["[[Component Object Model]]", "[[IBM Common User Access]]", "[[Inter-Language Unification]]", "[[Abstraction (computer science)]]", "[[Address constant]]", "[[Ambiguous viewpoint]]", "[[APL (programming language)]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Attached Support Processor]]"]
---

# IBM System Object Model

The System Object Model (SOM) is an object-oriented shared library technology developed by IBM that supports defining an interface to an object so that its interface is separate from its implementation. 
DSOM, a distributed variant based on CORBA, allowed objects on different computers to communicate.
A SOM library can be updated without requiring client code to be rebuilt. If a library is changed to add new classes or methods, or to change the internal implementation of classes or methods, a consuming program can still use it without being rebuilt. In this way, SOM addresses the fragile binary interface problem that affects other library technology such as C++.
SOM allows classes to be defined in one programming language and used in another. A client can create and use objects from the exposed classes and derive subclasses from the exposed classes even if the client language does not support class typing.
SOM provides an application programming interface (API) that provides access to library metadata. Each object exposes methods that provide the class name and whether the object implements a particular method, for example.

## Related

- [[Component Object Model]]
- [[IBM Common User Access]]
- [[Inter-Language Unification]]
- [[Abstraction (computer science)]]
- [[Address constant]]
- [[Ambiguous viewpoint]]
- [[APL (programming language)]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Attached Support Processor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IBM_System_Object_Model