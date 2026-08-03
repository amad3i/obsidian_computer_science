---
title: "Finalizer"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Finalizer"
wikipedia_categories: ["Memory management", "Method (computer programming)", "Object-oriented programming"]
related: ["[[Constructor (object-oriented programming)]]", "[[Dispose pattern]]", "[[Virtual function]]", "[[bss]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]"]
---

# Finalizer

In computer science, a finalizer or finalize method is a special method that performs finalization, generally some form of cleanup. A finalizer is executed during object destruction, prior to the object being deallocated, and is complementary to an initializer, which is executed during object creation, following allocation. Finalizers are strongly discouraged by some, due to difficulty in proper use and the complexity they add, and alternatives are suggested instead, mainly the dispose pattern (see problems with finalizers).
The term finalizer is mostly used with programming languages that use garbage collection, such as object-oriented, archetypically Smalltalk, and functional, archetypically ML. This is contrasted with a destructor, which is a method called for finalization in languages with deterministic object lifetimes, archetypically C++. These are generally exclusive: a language will have either finalizers (if automatically garbage collected) or destructors (if manually memory managed), but in rare cases a language may have both, as in C++/CLI and D, and in case of reference counting (instead of tracing garbage collection), terminology varies. In technical use, finalizer may also be used to refer to destructors, as these also perform finalization, and some subtler distinctions are drawn – see terminology. The term final also indicates a class that cannot be inherited; this is unrelated.

## Related

- [[Constructor (object-oriented programming)]]
- [[Dispose pattern]]
- [[Virtual function]]
- [[bss]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Finalizer