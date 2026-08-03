---
title: "IUnknown"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/IUnknown"
wikipedia_categories: ["Microsoft application programming interfaces", "Object-oriented programming"]
related: ["[[Component Object Model]]", "[[IDispatch]]", "[[Microsoft Interface Definition Language]]", "[[OLE Automation]]", "[[Runtime Callable Wrapper]]", "[[Windows Template Library]]", "[[Abstraction (computer science)]]", "[[ADO.NET]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]"]
---

# IUnknown

In the computer programming of applications on Microsoft Windows through the Windows API, the IUnknown interface is the fundamental interface of Component Object Model (COM). The COM specification mandates that COM objects must implement this interface. Furthermore, every other COM interface must be derived from IUnknown. IUnknown resides in the global namespace. IUnknown exposes two essential features of all COM objects: object lifetime management through reference counting, and access to object functionality through other interfaces.
As well as being a foundational part of Microsoft's COM and DCOM models of objects, there are implementations of the same interface on other platforms -either because the other platforms implement some form of COM-compatibility, or because the design was considered effective.
An IUnknown (or IUnknown-derived) interface generally consists of a pointer to a virtual method table that contains a list of pointers to the functions that implement the functions declared in the interface, in the order that they are declared in the interface. The in-process invocation call overhead is therefore identical to virtual method calls in C++.

## Related

- [[Component Object Model]]
- [[IDispatch]]
- [[Microsoft Interface Definition Language]]
- [[OLE Automation]]
- [[Runtime Callable Wrapper]]
- [[Windows Template Library]]
- [[Abstraction (computer science)]]
- [[ADO.NET]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IUnknown