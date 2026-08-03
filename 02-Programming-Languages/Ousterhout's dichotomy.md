---
title: "Ousterhout's dichotomy"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Ousterhout's_dichotomy"
wikipedia_categories: ["1988 in computing", "Dichotomies", "Programming language folklore", "Programming paradigms", "Software engineering folklore"]
related: ["[[Programming in the large and programming in the small]]", "[[Array programming]]", "[[Aspect-oriented programming]]", "[[Attribute-oriented programming]]", "[[Automata-based programming]]", "[[Automata-based programming (Shalyto's approach)]]", "[[Automatic programming]]", "[[Choreographic programming]]", "[[Comparison of multi-paradigm programming languages]]", "[[Concurrent constraint logic programming]]"]
---

# Ousterhout's dichotomy

Ousterhout's dichotomy is computer scientist John Ousterhout's categorization that high-level programming languages tend to fall into two groups, each with distinct properties and uses: system programming languages and scripting languages – compare programming in the large and programming in the small.
System programming languages (or applications languages) usually have the following properties:

They are typed statically
They support creating complex data structures
Programs in them are compiled into machine code
Programs in them are meant to operate largely independently of other programs
System programming languages tend to be used for components and applications with large amounts of internal functionality such as operating systems, database servers, and Web browsers.  These applications typically employ complex algorithms and data structures and require high performance. Prototypical examples of system programming languages include C, OCaml and Modula-2.
By contrast, scripting languages (or glue languages) tend to have the following properties:

They are typed dynamically
They have little or no provision for complex data structures
Programs in them (scripts) are interpreted
Scripting languages tend to be used for applications where most of the functionality comes from other programs (often implemented in system programming languages); the scripts are used to glue together other programs or add additional layers of functionality on top of existing programs.  Ousterhout claims that scripts tend to be short and are often written by less sophisticated programmers. Hence, execution efficiency is less important than simplicity and ease of interaction with other programs.  Common applications for scripting include Web page generation, report generation, graphical user interfaces, and system administration. Prototypical examples of scripting languages include Python, AppleScript, C shell, and Tcl.
Ousterhout's dichotomy underlies the design of his language Tcl.

## Related

- [[Programming in the large and programming in the small]]
- [[Array programming]]
- [[Aspect-oriented programming]]
- [[Attribute-oriented programming]]
- [[Automata-based programming]]
- [[Automata-based programming (Shalyto's approach)]]
- [[Automatic programming]]
- [[Choreographic programming]]
- [[Comparison of multi-paradigm programming languages]]
- [[Concurrent constraint logic programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ousterhout's_dichotomy