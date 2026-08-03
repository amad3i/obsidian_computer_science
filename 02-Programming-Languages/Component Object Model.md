---
title: "Component Object Model"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Component_Object_Model"
wikipedia_categories: ["Component-based software engineering", "Inter-process communication", "Microsoft application programming interfaces", "Object-oriented programming", "Object models", "Object request broker"]
related: ["[[Inter-Language Unification]]", "[[Runtime Callable Wrapper]]", "[[Franca IDL]]", "[[Microsoft Interface Definition Language]]", "[[Common Object Request Broker Architecture]]", "[[Component-based software engineering]]", "[[IBM System Object Model]]", "[[IDispatch]]", "[[IUnknown]]", "[[OLE Automation]]"]
---

# Component Object Model

Component Object Model (COM) is a binary-interface technology for software components from Microsoft that enables using objects in a language-neutral way between different programming languages, programming contexts, processes and machines.
COM is the basis for other Microsoft domain-specific component technologies including OLE, OLE Automation, ActiveX, COM+, and DCOM as well as implementations such as DirectX, Windows shell, UMDF, Windows Runtime, and Browser Helper Object.
COM enables object use when only the object's interface is known, not its internal implementation. The component implementer defines interfaces that are separate from the implementation. 
Support for multiple programming contexts is handled by relying on the object for aspects that would be challenging to implement as a facility. Supporting multiple uses of an object is handled by requiring each object to destroy itself via reference-counting. Access to an object's interfaces (similar to Type conversion) is provided by each object as well.
COM is available only in Microsoft Windows and Apple's Core Foundation 1.3 and later plug-in application programming interface (API). The latter only implements a subset of the whole COM interface. 
Over time, COM is being replaced with other technologies such as Microsoft .NET and web services (i.e. via WCF). However, COM objects can be used in a .NET language via COM Interop. 
COM is similar to other component technologies such as SOM, CORBA and Enterprise JavaBeans, although each has its strengths and weaknesses. 
Unlike C++, COM provides a stable application binary interface (ABI) that is unaffected by compiler differences. This makes using COM advantageous for object-oriented C++ libraries that are to be used by clients compiled via different compilers.

## Related

- [[Inter-Language Unification]]
- [[Runtime Callable Wrapper]]
- [[Franca IDL]]
- [[Microsoft Interface Definition Language]]
- [[Common Object Request Broker Architecture]]
- [[Component-based software engineering]]
- [[IBM System Object Model]]
- [[IDispatch]]
- [[IUnknown]]
- [[OLE Automation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Component_Object_Model