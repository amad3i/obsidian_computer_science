---
title: "Church encoding"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Church_encoding"
wikipedia_categories: ["Lambda calculus"]
related: ["[[Anonymous function]]", "[[Applicative computing systems]]", "[[B, C, K, W system]]", "[[Beta normal form]]", "[[Böhm tree]]", "[[Calculus of constructions]]", "[[Call-by-push-value]]", "[[Cartesian closed category]]", "[[Church–Rosser theorem]]", "[[Combinatory logic]]"]
---

# Church encoding

In mathematics, Church encoding is a way of representing various types of data in the lambda calculus.
In the untyped lambda calculus the only primitive data type are functions, represented by lambda abstraction terms. Types that are usually considered primitive in other notations (such as integers, Booleans, pairs, lists, and tagged unions) are not natively present.
Hence the need arises to have ways to represent the data of these varying types by lambda terms, that is, by functions that are taking functions as their arguments and are returning functions as their results.
The Church numerals are a representation of the natural numbers using lambda notation. The method is named for Alonzo Church, who first encoded data in the lambda calculus this way. It can also be extended to represent other data types in the similar spirit.
This article makes occasional use of the alternative syntax for lambda abstraction terms, where λx.λy.λz.N is abbreviated as λxyz.N, as well as the two standard combinators, 
  
    
      
        I
        ≡
        λ
        x
        .
        x
      
    
    
  
 and 
  
    
      
        K
        ≡
        λ
        x
        y
        .
        x
      
    
    
  
, as needed.

## Related

- [[Anonymous function]]
- [[Applicative computing systems]]
- [[B, C, K, W system]]
- [[Beta normal form]]
- [[Böhm tree]]
- [[Calculus of constructions]]
- [[Call-by-push-value]]
- [[Cartesian closed category]]
- [[Church–Rosser theorem]]
- [[Combinatory logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Church_encoding