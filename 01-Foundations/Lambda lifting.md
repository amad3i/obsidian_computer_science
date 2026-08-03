---
title: "Lambda lifting"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Lambda_lifting"
wikipedia_categories: ["Compiler construction", "Implementation of functional programming languages", "Lambda calculus", "Programming language comparisons"]
related: ["[[Fixed-point combinator]]", "[[Higher-order function]]", "[[Lambda calculus]]", "[[Supercombinator]]", "[[A-normal form]]", "[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Anonymous function]]", "[[Applicative computing systems]]"]
---

# Lambda lifting

Lambda lifting is a meta-process that restructures a computer program so that functions are defined independently of each other in a global scope. An individual lift transforms a local function (subroutine) into a global function. It is a two step process, consisting of:

Eliminating free variables in the function by adding parameters.
Moving functions from a restricted scope to broader or global scope.
The term "lambda lifting" was first introduced by Thomas Johnsson around 1982 and was historically considered as a mechanism for implementing programming languages based on functional programming. It is used in conjunction with other techniques in some modern compilers.
Lambda lifting is not the same as closure conversion. It requires all call sites to be adjusted (adding extra arguments (parameters) to calls) and does not introduce a closure for the lifted lambda expression. In contrast, closure conversion does not require call sites to be adjusted but does introduce a closure for the lambda expression mapping free variables to values.
The technique may be used on individual functions, in code refactoring, to make a function usable outside the scope in which it was written. Lambda lifts may also be repeated, to transform the program. Repeated lifts may be used to convert a program written in lambda calculus into a set of recursive functions, without lambdas. This demonstrates the equivalence of programs written in lambda calculus and programs written as functions.  However it does not demonstrate the soundness of lambda calculus for deduction, as the eta reduction used in lambda lifting is the step that introduces cardinality problems into the lambda calculus, because it removes the value from the variable, without first checking that there is only one value that satisfies the conditions on the variable (see Curry's paradox).
Lambda lifting can be performed with time complexity linear in the size of the lifted program, which is at most 
  
    
      
        O
        
          n
          
            2
          
        
      
    
    
  
.
In the untyped lambda calculus, where the basic types are functions, lifting may change the result of beta reduction of a lambda expression. The resulting functions will have the same meaning, in a mathematical sense, but are not regarded as the same function in the untyped lambda calculus. See also intensional versus extensional equality.
The reverse operation to lambda lifting is lambda dropping.
Lambda dropping may make the compilation of programs quicker for the compiler, and may also increase the efficiency of the resulting program, by reducing the number of parameters, and reducing the size of stack frames.
However it makes a function harder to re-use. A dropped function is tied to its context, and can only be used in a different context if it is first lifted.

## Related

- [[Fixed-point combinator]]
- [[Higher-order function]]
- [[Lambda calculus]]
- [[Supercombinator]]
- [[A-normal form]]
- [[Abstract syntax]]
- [[Affix grammar]]
- [[Aliasing (computing)]]
- [[Anonymous function]]
- [[Applicative computing systems]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lambda_lifting