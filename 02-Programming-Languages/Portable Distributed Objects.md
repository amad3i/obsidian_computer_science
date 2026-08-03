---
title: "Portable Distributed Objects"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Portable_Distributed_Objects"
wikipedia_categories: ["MacOS APIs", "NeXT", "Object-oriented programming", "Parallel computing"]
related: ["[[Core Data]]", "[[ABIT BP6]]", "[[Abstraction (computer science)]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[Ambiguous viewpoint]]"]
---

# Portable Distributed Objects

Portable Distributed Objects (PDO) is an application programming interface (API) for creating object-oriented code that can be executed remotely on a network of computers. It was created by NeXT Computer, Inc. using their OpenStep system, whose use of Objective-C made the package very easy to write. It was characterized by its very light weight and high speed in comparison to similar systems such as CORBA.
Versions of PDO were available for Solaris, HP-UX and all versions of the OPENSTEP system, although an agreement was also announced for a version to be made for Digital Unix, then still known as OSF/1, with delivery anticipated after versions for SunOS and Solaris had been released. Product licence pricing for these platforms varied from $2,500 for use on a "small server" up to $10,000 for use on a "large server". A version that worked with Microsoft OLE was also available called D'OLE, allowing distributed code written using PDO on any platform to be presented on Microsoft systems as if they were local OLE objects.
PDO, on the other hand, relied on a small number of features in the Objective-C runtime to handle both portability as well as distribution. The key feature was the language's support for a "second chance" method in all classes; if a method call on an object failed because the object didn't support it (normally not allowed in most languages due to strong typing), the runtime would then bundle the message into a compact format and pass it back into the object's forwardInvocation method.
The normal behavior for forwardInvocation was to return an error, including details taken from the message (the "invocation").  PDO instead supplied a number of new objects with forwardInvocation methods that passed the invocation object to another machine on the network, with various versions to support different networks and platforms. Calling methods on remote objects was almost invisible; after some network setup (a few lines typically) PDO objects were instantiated locally and called the same way as any other object on the system. The PDO object then forwarded the invocation to the remote computer for processing and unbundled the results when they were returned.
In comparison with CORBA, PDO programs were typically 1/10 or less in size; it was common for NeXT staffers to write into magazines showing how to re-implement a multi-page CORBA article in perhaps 15 lines of code. From a programming standpoint, there was nearly nothing as easy to use as PDO.
However, PDO was also reliant entirely on Objective-C to function. This was a price most were unwilling to pay, as at the time C++ was more widely used and the effort to shift codebases to an entirely new language and paradigm was considered too onerous. PDO never saw much use, and NeXT's emphasis shifted to its new WebObjects framework in 1995.
The ability to instantiate any object known to the local process from any other process is a known security vulnerability, and Apple strongly discourages use of PDO for that reason.
In addition to the OS X platform, there is GNUstep, which has its own implementation of Distributed Objects.

## Related

- [[Core Data]]
- [[ABIT BP6]]
- [[Abstraction (computer science)]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[Ambiguous viewpoint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Portable_Distributed_Objects