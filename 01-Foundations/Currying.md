---
title: "Currying"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Currying"
wikipedia_categories: ["Functional programming", "Higher-order functions", "Lambda calculus"]
related: ["[[Function application]]", "[[Higher-order function]]", "[[Anonymous function]]", "[[Supercombinator]]", "[[A-normal form]]", "[[Actant]]", "[[Algebraic data type]]", "[[Applicative computing systems]]", "[[Applicative functor]]", "[[Arrow (computer science)]]"]
---

# Currying

In mathematics and computer science, currying (named after Haskell Curry) is the technique of translating a function that takes multiple arguments into a sequence of families of functions, each taking a single argument.
In the prototypical example, one begins with a function 
  
    
      
        f
        :
        X
        Y
        →
        Z
      
    
    
  
 that takes two arguments, one from 
  
    
      
        X
      
    
    
  
 and one from 
  
    
      
        Y
        ,
      
    
    
  
 and produces objects in 
  
    
      
        Z
        .
      
    
    
  
 The curried form of this function treats the first argument as a parameter, so as to create a family of functions 
  
    
      
        
          f
          
            x
          
        
        :
        Y
        →
        Z
        .
      
    
    
  
 The family is arranged so that for each object 
  
    
      
        x
      
    
    
  
 in 
  
    
      
        X
        ,
      
    
    
  
 there is exactly one function 
  
    
      
        
          f
          
            x
          
        
      
    
    
  
, such that for any 
  
    
      
        y
      
    
    
  
 in 
  
    
      
        Y
      
    
    
  
, 
  
    
      
        
          f
          
            x
          
        
        y
        =
        f
        x
        ,
        y
      
    
    
  
.
In this example, 
  
    
      
        
          
            curry
          
        
      
    
    
  
 itself becomes a function that takes 
  
    
      
        f
      
    
    
  
 as an argument, and returns a function that maps each 
  
    
      
        x
      
    
    
  
 to 
  
    
      
        
          f
          
            x
          
        
        .
      
    
    
  
 The proper notation for expressing this is verbose. The function 
  
    
      
        f
      
    
    
  
 belongs to the set of functions 
  
    
      
        X
        Y
        →
        Z
        .
      
    
    
  
  Meanwhile, 
  
    
      
        
          f
          
            x
          
        
      
    
    
  
 belongs to the set of functions 
  
    
      
        Y
        →
        Z
        .
      
    
    
  
 Thus, something that maps 
  
    
      
        x
      
    
    
  
 to 
  
    
      
        
          f
          
            x
          
        
      
    
    
  
 will be of the type 
  
    
      
        X
        →
        Y
        →
        Z
        .
      
    
    
  
 With this notation, 
  
    
      
        
          
            curry
          
        
      
    
    
  
 is a function that takes objects from the first set, and returns objects in the second set, and so one writes 
  
    
      
        
          
            curry
          
        
        :
        (
        X
        Y
        →
        Z
        →
        X
        →
        Y
        →
        Z
        )
        .
      
    
    
  
 This is a somewhat informal example; more precise definitions of what is meant by "object" and "function" are given below. These definitions vary from context to context, and take different forms, depending on the theory that one is working in.
Currying is related to, but not the same as, partial application. The example above can be used to illustrate partial application; it is quite similar.  Partial application is the function 
  
    
      
        
          
            apply
          
        
      
    
    
  
 that takes the pair 
  
    
      
        f
      
    
    
  
 and 
  
    
      
        x
      
    
    
  
 together as arguments, and returns 
  
    
      
        
          f
          
            x
          
        
        .
      
    
    
  
 Using the same notation as above, partial application has the signature 
  
    
      
        
          
            apply
          
        
        :
        [
        X
        Y
        →
        Z
        ×
        X
        →
        Y
        →
        Z
        .
      
    
    
  
 Written this way, application can be seen to be adjoint to currying.
The currying of a function with more than two arguments can be defined by induction. 
Currying is useful in both practical and theoretical settings. In functional programming languages, and many others, it provides a way of automatically managing how arguments are passed to functions and exceptions. In theoretical computer science, it provides a way to study functions with multiple arguments in simpler theoretical models which provide only one argument. The most general setting for the strict notion of currying and uncurrying is in the closed monoidal categories, which underpins a vast generalization of the Curry–Howard correspondence of proofs and programs to a correspondence with many other structures, including quantum mechanics, cobordisms, and string theory.
The concept of currying was introduced by Gottlob Frege, developed by Moses Schönfinkel,
and further developed by Haskell Curry.
Uncurrying is the dual transformation to currying, and can be seen as a form of defunctionalization. It takes a function 
  
    
      
        f
      
    
    
  
 whose return value is another function 
  
    
      
        g
      
    
    
  
, and yields a new function 
  
    
      
        
          f
          ′
        
      
    
    
  
 that takes as parameters the arguments for both 
  
    
      
        f
      
    
    
  
 and 
  
    
      
        g
      
    
    
  
, and returns, as a result, the application of 
  
    
      
        f
      
    
    
  
 and subsequently, 
  
    
      
        g
      
    
    
  
, to those arguments. The process can be iterated.

## Related

- [[Function application]]
- [[Higher-order function]]
- [[Anonymous function]]
- [[Supercombinator]]
- [[A-normal form]]
- [[Actant]]
- [[Algebraic data type]]
- [[Applicative computing systems]]
- [[Applicative functor]]
- [[Arrow (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Currying