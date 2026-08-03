---
title: "Remote procedure call"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Remote_procedure_call"
wikipedia_categories: ["Distributed computing", "Inter-process communication", "Middleware", "Remote procedure call"]
related: ["[[Web Application Messaging Protocol]]", "[[Advanced Message Queuing Protocol]]", "[[Asynchrony (computer programming)]]", "[[Distributed Computing Environment]]", "[[Entera]]", "[[Franca IDL]]", "[[RCUDA]]", "[[ActiveVOS]]", "[[ActivityPub]]", "[[Advanced Resource Connector]]"]
---

# Remote procedure call

In distributed computing, a remote procedure call (RPC) is an action in which a computer program causes a procedure (subroutine) to execute in a different address space of the current process (commonly on another computer on a shared computer network), which is written as if it were a normal (local) procedure call, without the programmer explicitly writing the details for the remote interaction. That is, the programmer writes essentially the same code whether the subroutine is local to the executing program, or remote. This is a form of server interaction (caller is client, executor is server), typically implemented via a request–response message passing system. In the object-oriented programming paradigm, RPCs are represented by remote method invocation (RMI). The RPC model implies a level of location transparency, namely that calling procedures are largely the same whether they are local or remote, but usually, they are not identical, so local calls can be distinguished from remote calls. Remote calls are usually orders of magnitude slower and less reliable than local calls, so distinguishing them is important.
RPCs are a form of inter-process communication (IPC), in that different processes have different address spaces: if on the same host machine, they have distinct virtual address spaces, even though the physical address space is the same; while if they are on different hosts, the physical address space is also different. Many different (often incompatible) technologies have been used to implement the concept. Modern RPC frameworks, such as gRPC and Apache Thrift, enhance the basic RPC model by using efficient binary serialization (e.g., Protocol Buffers), HTTP/2 multiplexing, and built-in support for features such as authentication, load balancing, streaming, and error handling, making them well-suited for building scalable microservices and enabling language interoperability.

## Related

- [[Web Application Messaging Protocol]]
- [[Advanced Message Queuing Protocol]]
- [[Asynchrony (computer programming)]]
- [[Distributed Computing Environment]]
- [[Entera]]
- [[Franca IDL]]
- [[RCUDA]]
- [[ActiveVOS]]
- [[ActivityPub]]
- [[Advanced Resource Connector]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Remote_procedure_call