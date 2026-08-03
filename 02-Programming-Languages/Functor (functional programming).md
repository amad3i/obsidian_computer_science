---
title: "Functor (functional programming)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Functor_(functional_programming)"
wikipedia_categories: []
related: []
---

# Functor (functional programming)

In functional programming, a functor is a design pattern inspired by the definition from category theory that allows one to apply a function to values inside a generic type without changing the structure of the generic type. In Haskell this idea can be captured in a type class:

This declaration says that any instance of Functor must support a method fmap, which maps a function over the elements of the instance.
Functors in Haskell should also obey the so-called functor laws, which state that the mapping operation preserves the identity function and composition of functions:

where . stands for function composition.
In Scala a trait can instead be used:

Functors form a base for more complex abstractions like applicative functors, monads, and comonads, all of which build atop a canonical functor structure. Functors are useful in modeling functional effects by values of parameterized data types. Modifiable computations are modeled by allowing a pure function to be applied to values of the "inner" type, thus creating the new overall value which represents the modified computation (which may have yet to run).

## Related

*(no automatic links — see MOC)*

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Functor_(functional_programming)