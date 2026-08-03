---
title: "Typestate analysis"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Typestate_analysis"
wikipedia_categories: ["Program analysis"]
related: ["[[Abstract interpretation]]", "[[Aliasing (computing)]]", "[[Compiler-compiler]]", "[[Context-free language reachability]]", "[[Dynamic program analysis]]", "[[Effect system]]", "[[Flow-sensitive typing]]", "[[KPI-driven code analysis]]", "[[Path explosion]]", "[[Perl--Critic]]"]
---

# Typestate analysis

Typestate analysis, sometimes called protocol analysis, is a form of program analysis employed in programming languages. It is most commonly applied to object-oriented languages. Typestates define valid sequences of operations that can be performed upon an instance of a given type. Typestates, as the name suggests, associate state information with variables of that type. This state information is used to determine at compile-time which operations are valid to be invoked upon an instance of the type. Operations performed on an object that would usually only be executed at run-time are performed upon the type state information which is modified to be compatible with the new state of the object.
Typestates are capable of representing behavioral type refinements such as "method A must be invoked before method B is invoked, and method C may not be invoked in between". Typestates are well-suited to representing resources that use open/close semantics by enforcing semantically valid sequences such as "open then close" as opposed to invalid sequences such as leaving a file in an open state. Such resources include filesystem elements, transactions, connections and protocols. For instance, developers may want to specify that files or sockets must be opened before they are read or written, and that they can no longer be read or written if they have been closed. The name "typestate" stems from the fact that this kind of analysis often models each type of object as a finite-state machine. In this state machine, each state has a well-defined set of permitted methods/messages, and method invocations may cause state transitions. Petri nets have also been proposed as a possible behavioral model for use with refinement types.
In recent years, various studies have developed ways of applying the typestate concept to object-oriented languages.

## Related

- [[Abstract interpretation]]
- [[Aliasing (computing)]]
- [[Compiler-compiler]]
- [[Context-free language reachability]]
- [[Dynamic program analysis]]
- [[Effect system]]
- [[Flow-sensitive typing]]
- [[KPI-driven code analysis]]
- [[Path explosion]]
- [[Perl--Critic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Typestate_analysis