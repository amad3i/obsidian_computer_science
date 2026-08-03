---
title: "Exception chaining"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Exception_chaining"
wikipedia_categories: ["Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]", "[[Behavioral pattern]]"]
---

# Exception chaining

Exception chaining, or exception wrapping, is an object-oriented programming technique of handling exceptions by re-throwing a caught exception after wrapping it inside a new exception. The original exception is saved as a property (such as cause) of the new exception. The idea is that a method should throw exceptions defined at the same abstraction level as the method itself, but without discarding information from the lower levels. 
For example, a method to play a movie file might handle exceptions in reading the file by re-throwing them inside an exception of movie playing. The user interface doesn't need to know whether the error occurred during reading chunk of bytes or calling eof(). It needs only the exception message extracted from cause. The user interface layer will have its own set of exceptions. The one interested in cause can see its stack trace during debugging or in proper log.
Throwing the right kind of exceptions is particularly enforced by checked exceptions in the Java programming language, and starting with language version 1.4 almost all exceptions support chaining.
In runtime engine environments such as Java or .NET there exist tools that attach to the runtime engine and every time that an exception of interest occurs they record debugging information that existed in memory at the time the exception was thrown (stack and heap values). These tools are called Exception Interception and they provide "root-cause" information for exceptions in Java programs that run in production, testing, or development environments.

## Related

- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]
- [[Asynchronous method invocation]]
- [[Balking pattern]]
- [[Behavioral pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Exception_chaining