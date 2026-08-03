---
title: "Strictness analysis"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Strictness_analysis"
wikipedia_categories: ["Implementation of functional programming languages", "Static program analysis"]
related: ["[[A-normal form]]", "[[Alias analysis]]", "[[Array-access analysis]]", "[[Call graph]]", "[[Code motion]]", "[[Continuation-passing style]]", "[[Dependence analysis]]", "[[Escape analysis]]", "[[Extended static checking]]", "[[Graph reduction]]"]
---

# Strictness analysis

In computer science, strictness analysis refers to any algorithm used to prove that a function in a non-strict functional programming language is strict in one or more of its arguments. This information is useful to compilers because strict functions can be compiled more efficiently. Thus, if a function is proven to be strict (using strictness analysis) at compile time, it can be compiled to use a more efficient calling convention without changing the meaning of the enclosing program.
Note that a function f is said to diverge if it returns 
  
    
      
        ⊥
      
    
    
  
: operationally, that would mean that f either causes abnormal termination of the enclosing program (e.g., failure with an error message) or that it loops infinitely. The notion of "divergence" is significant because a strict function is one that always diverges when given an argument that diverges, whereas a lazy (or non-strict) function is one that may or may not diverge when given such an argument. Strictness analysis attempts to determine the "divergence properties" of functions, which thus identifies some functions that are strict.

## Related

- [[A-normal form]]
- [[Alias analysis]]
- [[Array-access analysis]]
- [[Call graph]]
- [[Code motion]]
- [[Continuation-passing style]]
- [[Dependence analysis]]
- [[Escape analysis]]
- [[Extended static checking]]
- [[Graph reduction]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Strictness_analysis