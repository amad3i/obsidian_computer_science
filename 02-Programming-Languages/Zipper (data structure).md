---
title: "Zipper (data structure)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Zipper_(data_structure)"
wikipedia_categories: ["Functional data structures", "Functional programming"]
related: ["[[Immutable object]]", "[[Purely functional data structure]]", "[[Stream (abstract data type)]]", "[[A-normal form]]", "[[Actant]]", "[[Algebraic data type]]", "[[Anonymous function]]", "[[Applicative functor]]", "[[Arrow (computer science)]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]"]
---

# Zipper (data structure)

A zipper is a technique of representing an aggregate data structure so that it is convenient for writing programs that traverse the structure arbitrarily and update its contents, especially in purely functional programming languages. The zipper was described by Gérard Huet in 1997. It includes and generalizes the gap buffer technique sometimes used with arrays.
The zipper technique is general in the sense that it can be adapted to lists, trees, and other recursively defined data structures.
Such modified data structures are usually referred to as "a tree with zipper" or "a list with zipper" to emphasize that the structure is conceptually a tree or list, while the zipper is a detail of the implementation.
A layperson's explanation for a tree with zipper would be an ordinary computer file system with operations to go to parent (often cd ..), and to go downwards (cd subdirectory). The zipper is the pointer to the current path. Behind the scenes, zippers are efficient when making (functional) changes to a data structure, where a new, slightly changed, data structure is returned from an edit operation (instead of making a change in the current data structure).

## Related

- [[Immutable object]]
- [[Purely functional data structure]]
- [[Stream (abstract data type)]]
- [[A-normal form]]
- [[Actant]]
- [[Algebraic data type]]
- [[Anonymous function]]
- [[Applicative functor]]
- [[Arrow (computer science)]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Zipper_(data_structure)