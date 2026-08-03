---
title: "Effect system"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Effect_system"
wikipedia_categories: ["Program analysis", "Type theory"]
related: ["[[Flow-sensitive typing]]", "[[Type system]]", "[[Typing environment]]", "[[Typing rule]]", "[[Abstract data type]]", "[[Abstract interpretation]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Aliasing (computing)]]"]
---

# Effect system

In computing, an effect system is a formal system that describes the computational effects of computer programs, such as side effects. An effect system can be used to provide a compile-time check of the possible effects of the program.
The effect system extends the notion of type to have an "effect" component, which comprises an effect kind and a region. The effect kind describes what is being done, and the region describes with what (parameters) it is being done.
An effect system is typically an extension of a type system. The term "type and effect system" is sometimes used in this case. Often, a type of a value is denoted together with its effect as type ! effect, where both the type component and the effect component mention certain regions (for example, a type of a mutable memory cell is parameterized by the label of the memory region in which the cell resides). The term "algebraic effect" follows from the type system.
Effect systems may be used to prove the external purity of certain internally impure definitions: for example, if a function internally allocates and modifies a region of memory, but the function's type does not mention the region, then the corresponding effect may be erased from the function's effect.

## Related

- [[Flow-sensitive typing]]
- [[Type system]]
- [[Typing environment]]
- [[Typing rule]]
- [[Abstract data type]]
- [[Abstract interpretation]]
- [[Abstract type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]
- [[Aliasing (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Effect_system