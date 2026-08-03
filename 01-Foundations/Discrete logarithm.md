---
title: "Discrete logarithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Discrete_logarithm"
wikipedia_categories: ["Computational hardness assumptions", "Cryptography", "Finite fields", "Group theory", "Logarithms", "Modular arithmetic", "Unsolved problems in computer science"]
related: ["[[Schoof's algorithm]]", "[[Schoof–Elkies–Atkin algorithm]]", "[[Security level]]", "[[Unique games conjecture]]", "[[123 Reg]]", "[[3SUM]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Absolutely convex set]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]"]
---

# Discrete logarithm

In mathematics, for given real numbers 
  
    
      
        a
      
    
    
  
 and 
  
    
      
        b
      
    
    
  
, the logarithm 
  
    
      
        
          
            b
          
        
         
        a
      
    
    
  
 is a number 
  
    
      
        x
      
    
    
  
 such that 
  
    
      
        
          b
          
            x
          
        
        a
      
    
    
  
. The discrete logarithm is an analogous concept in group theory. In any group 
  
    
      
        G
      
    
    
  
, powers 
  
    
      
        
          b
          
            k
          
        
      
    
    
  
 can be defined for all integers 
  
    
      
        k
      
    
    
  
, and the discrete logarithm 
  
    
      
        
          
            b
          
        
         
        a
      
    
    
  
 is an integer 
  
    
      
        k
      
    
    
  
 such that 
  
    
      
        
          b
          
            k
          
        
        a
      
    
    
  
. In the special case of arithmetic modulo an integer 
  
    
      
        m
      
    
    
  
, the more commonly used term is index: One can write 
  
    
      
        k
        
          
            i
            n
            d
          
          
            b
          
        
        a
        
        
        
        
        
          
          mod
          
          m
        
      
    
    
  
 when 
  
    
      
        
          b
          
            k
          
        
        ≡
        a
        
        
        
        
        
          
          mod
          
          m
        
      
    
    
  
.
Discrete logarithms are quickly computable in a few special cases, but no efficient method is known for computing them in general. Several cryptographic systems, including Diffie–Hellman and ElGamal, base their security on the hardness assumption that the discrete logarithm problem over carefully chosen groups has no efficient solution. In general, there is no subexponential time solution for black box groups.

## Related

- [[Schoof's algorithm]]
- [[Schoof–Elkies–Atkin algorithm]]
- [[Security level]]
- [[Unique games conjecture]]
- [[123 Reg]]
- [[3SUM]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Absolutely convex set]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Discrete_logarithm