---
title: "Quotient type"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Quotient_type"
wikipedia_categories: ["Composite data types", "Data types", "Type theory"]
related: ["[[Algebraic data type]]", "[[Composite data type]]", "[[Generalized algebraic data type]]", "[[Intersection type]]", "[[Product type]]", "[[Abstract data type]]", "[[Any type]]", "[[Associative array]]", "[[Bottom type]]", "[[Cons]]"]
---

# Quotient type

In the field of type theory in computer science, a quotient type is a data type that respects a user-defined equality relation. A quotient type defines an equivalence relation 
  
    
      
        ≡
      
    
    
  
 on elements of the type — for example, we might say that two values of the type Point are equivalent if they have the same respective x- and y-coordinates; formally p1 == p2 if p1.x == p2.x && p1.y == p2.y. In type theories that allow quotient types, an additional requirement is made that all operations must respect the equivalence between elements. For example, if f is a function on values of type Point, it must be the case that for two Points p1 and p2, if p1 == p2 then f(p1) == f(p2).
Quotient types are part of a general class of types known as algebraic data types. In the early 1980s, quotient types were defined and implemented as part of the Nuprl proof assistant, in work led by Robert L. Constable and others. Quotient types have been studied in the context of Martin-Löf type theory, dependent type theory, higher-order logic, and homotopy type theory.

## Related

- [[Algebraic data type]]
- [[Composite data type]]
- [[Generalized algebraic data type]]
- [[Intersection type]]
- [[Product type]]
- [[Abstract data type]]
- [[Any type]]
- [[Associative array]]
- [[Bottom type]]
- [[Cons]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quotient_type