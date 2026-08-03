---
title: "Service-oriented programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Service-oriented_programming"
wikipedia_categories: ["Programming paradigms", "Service-oriented (business computing)"]
related: ["[[Architecture of Interoperable Information Systems]]", "[[Array programming]]", "[[Aspect-oriented programming]]", "[[Attribute-oriented programming]]", "[[Automata-based programming]]", "[[Automata-based programming (Shalyto's approach)]]", "[[Automatic programming]]", "[[Choreographic programming]]", "[[Cloud-native computing]]", "[[Comparison of multi-paradigm programming languages]]"]
---

# Service-oriented programming

Service-oriented programming (SOP) is a programming paradigm that uses "services" as the unit of computer work, to design and implement integrated business applications and mission critical software programs. Services can represent steps of business processes and thus one of the main applications of this paradigm is the cost-effective delivery of standalone or composite business applications that can "integrate from the inside-out". It inherently promotes service-oriented architecture (SOA), however, it is not the same as SOA. While SOA focuses on communication between systems using "services", SOP provides a new technique to build agile application modules using in-memory services as the unit of work.
An in-memory service in SOP can be transparently externalized as a web service operation. Due to language and platform independent Web Service standards, SOP embraces all existing programming paradigms, languages and platforms.  In SOP, the design of the programs pivot around the semantics of service calls, logical routing and data flow description across well-defined service interfaces.  All SOP program modules are encapsulated as services and a service can be composed of other nested services in a hierarchical manner with virtually limitless depth to this service stack hierarchy. A composite service can also contain programming constructs some of which are specific and unique to SOP. A service can be an externalized system component that is accessed via any proprietary API or web service standards utilizing an in-memory plug-in technique.
While SOP supports the basic programming constructs for sequencing, selection and iteration, it is differentiated with a slew of new programming constructs that provide built-in native ability geared towards data list manipulation, data integration, automated multithreading of service modules, declarative context management and synchronization of services.  SOP design enables programmers to semantically synchronize the execution of services in order to guarantee that it is correct, or to declare a service module as a transaction boundary with automated commit/rollback behavior.
Semantic design tools and runtime automation platforms can be built to support the fundamental concepts of SOP.  For example, a service virtual machine (SVM) that automatically creates service objects as units of work and manages their context can be designed to run based on the SOP program metadata stored in XML and created by a design-time automation tool. In SOA terms, the SVM is both a service producer and a service consumer.

## Related

- [[Architecture of Interoperable Information Systems]]
- [[Array programming]]
- [[Aspect-oriented programming]]
- [[Attribute-oriented programming]]
- [[Automata-based programming]]
- [[Automata-based programming (Shalyto's approach)]]
- [[Automatic programming]]
- [[Choreographic programming]]
- [[Cloud-native computing]]
- [[Comparison of multi-paradigm programming languages]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Service-oriented_programming