---
title: "IDispatch"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/IDispatch"
wikipedia_categories: ["Microsoft application programming interfaces", "Object-oriented programming"]
related: ["[[Component Object Model]]", "[[IUnknown]]", "[[Microsoft Interface Definition Language]]", "[[OLE Automation]]", "[[Runtime Callable Wrapper]]", "[[Windows Template Library]]", "[[Abstraction (computer science)]]", "[[ADO.NET]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]"]
---

# IDispatch

IDispatch is  the interface that exposes the OLE Automation protocol. Extending IUnknown, it is one of the standard interfaces that can be exposed by COM objects. COM distinguishes between three interface types: custom that are VTABLE-based IUnknown interfaces, dispatch that are IDispatch interfaces supporting introspection, and dual interfaces supporting both types.
The Automation (IDispatch) interface allows a client application to find out what properties and methods are supported by an object at run-time, i.e. implements the concept of RTTI. It also provides the information necessary to invoke these properties and methods. Client applications do not need to be aware of the object members when they are compiled. This allows COM and ActiveX objects to be called by scripting programs platforms such as the ASP server and JavaScript on Internet Explorer, where calling conventions were not known at the time IIS or IE were built. By contrast, a simple object library is compiled and linked into a program, e.g. a DLL call needs to know a function name and parameters at compile time.
A script writer can ask the COM object for a method or property it already knows about from documentation. Then, the client can execute the function with Invoke provided by the IDispatch interface, a form of late-binding. This sort of capability was also supported by Dynamic Data Exchange (DDE), which never became popular due to being too low-level.
Dispatch interfaces are flexible, but suffer from additional introspection and invocation overhead compared to custom interfaces. It is therefore often a good idea to support both interface types with dual interfaces. That way, clients supporting VTABLE-based invocation can use the custom interface instead of the dispatch counterpart.

## Related

- [[Component Object Model]]
- [[IUnknown]]
- [[Microsoft Interface Definition Language]]
- [[OLE Automation]]
- [[Runtime Callable Wrapper]]
- [[Windows Template Library]]
- [[Abstraction (computer science)]]
- [[ADO.NET]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IDispatch