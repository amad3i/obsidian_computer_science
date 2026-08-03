---
title: "Debugging pattern"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Debugging_pattern"
wikipedia_categories: ["Software architecture", "Software design patterns"]
related: ["[[Bulkhead pattern]]", "[[Data, context and interaction]]", "[[Dependency injection]]", "[[Inversion of control]]", "[[JSP model 1 architecture]]", "[[JSP model 2 architecture]]", "[[Multitier architecture]]", "[[MVC4WPF]]", "[[Naked objects]]", "[[Presentation–abstraction–control]]"]
---

# Debugging pattern

A debugging pattern describes a generic set of steps to rectify or correct a bug within a software system.  It is a solution to a recurring problem that is related to a particular bug or type of bug in a specific context.
A bug pattern is a particular type of pattern.  The original concept of a pattern was introduced by the architect Christopher Alexander as a design pattern.
Some examples of debugging patterns include:

Eliminate noise bug pattern – Isolate and expose a particular bug by eliminating all other noise in the system.  This enables you to concentrate on finding the real issue.
Recurring bug pattern – Expose a bug via a unit test.  Run that unit test as part of a standard build from that moment on.  This ensure that the bug will not recur.
Time-specific bug pattern – Expose the bug by writing a continuous test that runs continuously and fails when an expected error occurs.  This is useful for transient bugs.

## Related

- [[Bulkhead pattern]]
- [[Data, context and interaction]]
- [[Dependency injection]]
- [[Inversion of control]]
- [[JSP model 1 architecture]]
- [[JSP model 2 architecture]]
- [[Multitier architecture]]
- [[MVC4WPF]]
- [[Naked objects]]
- [[Presentation–abstraction–control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Debugging_pattern