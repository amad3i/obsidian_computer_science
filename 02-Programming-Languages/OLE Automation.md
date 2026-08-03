---
title: "OLE Automation"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/OLE_Automation"
wikipedia_categories: ["Microsoft application programming interfaces", "Object-oriented programming"]
related: ["[[Component Object Model]]", "[[IDispatch]]", "[[IUnknown]]", "[[Microsoft Interface Definition Language]]", "[[Runtime Callable Wrapper]]", "[[Windows Template Library]]", "[[Abstraction (computer science)]]", "[[ADO.NET]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]"]
---

# OLE Automation

In Microsoft Windows applications programming, OLE Automation (later renamed to simply Automation) is an inter-process communication mechanism created by Microsoft. It is based on a subset of Component Object Model (COM) that was intended for use by scripting languages – originally Visual Basic – but now is used by several languages on Windows. All automation objects are required to implement the IDispatch interface. It provides an infrastructure whereby applications called automation controllers can access and manipulate (i.e. set properties of or call methods on) shared automation objects that are exported by other applications. It supersedes Dynamic Data Exchange (DDE), an older mechanism for applications to control one another.  As with DDE, in OLE Automation the automation controller is the "client" and the application exporting the automation objects is the "server".
Contrary to its name, automation objects do not necessarily use Microsoft OLE, although some Automation objects can be used in OLE environments. The confusion has its roots in Microsoft's earlier definition of OLE, which was previously more or less a synonym of COM.

## Related

- [[Component Object Model]]
- [[IDispatch]]
- [[IUnknown]]
- [[Microsoft Interface Definition Language]]
- [[Runtime Callable Wrapper]]
- [[Windows Template Library]]
- [[Abstraction (computer science)]]
- [[ADO.NET]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/OLE_Automation