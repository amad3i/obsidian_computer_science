---
title: "Intersection type"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Intersection_type"
wikipedia_categories: ["Composite data types", "Data types", "Polymorphism (computer science)", "TypeScript", "Type systems", "Type theory"]
related: ["[[Algebraic data type]]", "[[Composite data type]]", "[[Flow-sensitive typing]]", "[[Generalized algebraic data type]]", "[[Intersection type discipline]]", "[[Polymorphism (computer science)]]", "[[Product type]]", "[[Quotient type]]", "[[Subtyping]]", "[[Type system]]"]
---

# Intersection type

In type theory, an intersection type can be allocated to values that can be assigned both the type 
  
    
      
        σ
      
    
    
  
 and the type 
  
    
      
        τ
      
    
    
  
. This value can be given the intersection type 
  
    
      
        σ
        ∩
        τ
      
    
    
  
 in an intersection type system.
Generally, if the ranges of values of two types overlap, then a value belonging to the intersection of the two ranges can be assigned the intersection type of these two types. Such a value can be safely passed as argument to functions expecting either of the two types.
For example, in Java the class Boolean implements both the Serializable and the Comparable interfaces. Therefore, an object of type Boolean can be safely passed to functions expecting an argument of type Serializable and to functions expecting an argument of type Comparable.
Intersection types are composite data types. Similar to product types, they are used to assign several types to an object.
However, product types are assigned to tuples, so that each tuple element is assigned a particular product type component. 
In comparison, underlying objects of intersection types are not necessarily composite. A restricted form of intersection types are refinement types.
Intersection types are useful for describing overloaded functions. For example, if number => number is the type of function taking a number as an argument and returning a number, and string => string is the type of function taking a string as an argument and returning a string, then the intersection of these two types can be used to describe (overloaded) functions that do one or the other, based on what type of input they are given.
Contemporary programming languages, including Ceylon, Flow, Java, Scala, TypeScript, and Whiley (see comparison of languages with intersection types), use intersection types to combine interface specifications and to express ad hoc polymorphism.
Complementing parametric polymorphism, intersection types may be used to avoid class hierarchy pollution from cross-cutting concerns and reduce boilerplate code, as shown in the TypeScript example below.
The type theoretic study of intersection types is referred to as the intersection type discipline.
Remarkably, program termination can be precisely characterized using intersection types. Consequently, type inference for infinite-intersection types is undecidable, but it is decidable for all finite rank intersection types.

## Related

- [[Algebraic data type]]
- [[Composite data type]]
- [[Flow-sensitive typing]]
- [[Generalized algebraic data type]]
- [[Intersection type discipline]]
- [[Polymorphism (computer science)]]
- [[Product type]]
- [[Quotient type]]
- [[Subtyping]]
- [[Type system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Intersection_type