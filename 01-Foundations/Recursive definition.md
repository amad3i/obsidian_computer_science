---
title: "Recursive definition"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Recursive_definition"
wikipedia_categories: ["Definition", "Mathematical logic", "Recursion", "Theoretical computer science"]
related: ["[[Algorithm]]", "[[Algorithmic technique]]", "[[Corecursion]]", "[[Hub labels]]", "[[Impredicativity]]", "[[Institutional model theory]]", "[[Knuth's Simpath algorithm]]", "[[Regular numerical predicate]]", "[[Absoluteness (logic)]]", "[[Abstract logic]]"]
---

# Recursive definition

In mathematics and computer science, a recursive definition, or inductive definition, is used to define the elements in a set in terms of other elements in the set (Aczel 1977:740ff). Some examples of recursively definable objects include factorials, natural numbers, Fibonacci numbers, and the Cantor ternary set.
A recursive definition of a function defines values of the function for some inputs in terms of the values of the same function for other (usually smaller) inputs. For example, the factorial function n! is defined by the rules

  
    
      
        
          
            
              
              
                0
                !
                1.
              
            
            
              
              
                
                n
                1
                !
                (
                n
                1
                ⋅
                n
                !
                .
              
            
          
        
      
    
    
  

This definition is valid for each natural number n, because the recursion eventually reaches the base case of 0. The definition may also be thought of as giving a procedure for computing the value of the function n!, starting from n = 0 and proceeding onwards with n = 1, 2, 3 etc.
The recursion theorem states that such a definition indeed defines a function that is unique. The proof uses mathematical induction.
An inductive definition of a set describes the elements in a set in terms of other elements in the set. For example, one definition of the set ⁠
  
    
      
        
          N
        
      
    
    
  
⁠ of natural numbers is:

0 is in ⁠
  
    
      
        
          N
        
        .
      
    
    
  
⁠
If an element n is in ⁠
  
    
      
        
          N
        
      
    
    
  
⁠ then n + 1 is in ⁠
  
    
      
        
          N
        
        .
      
    
    
  
⁠
⁠
  
    
      
        
          N
        
      
    
    
  
⁠ is the smallest set satisfying (1) and (2).
There are many sets that satisfy (1) and (2) – for example, the set {0, 1, 1.649, 2, 2.649, 3, 3.649, …}  satisfies the definition. However, condition (3) specifies the set of natural numbers by removing the sets with extraneous members. 
Properties of recursively defined functions and sets can often be proved by an induction principle that follows the recursive definition. For example, the definition of the natural numbers presented here directly implies the principle of mathematical induction for natural numbers: if a property holds of the natural number 0 (or 1), and the property holds of n + 1 whenever it holds of n, then the property holds of all natural numbers (Aczel 1977:742).

## Related

- [[Algorithm]]
- [[Algorithmic technique]]
- [[Corecursion]]
- [[Hub labels]]
- [[Impredicativity]]
- [[Institutional model theory]]
- [[Knuth's Simpath algorithm]]
- [[Regular numerical predicate]]
- [[Absoluteness (logic)]]
- [[Abstract logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Recursive_definition