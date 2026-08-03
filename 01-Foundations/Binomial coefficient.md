---
title: "Binomial coefficient"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Binomial_coefficient"
wikipedia_categories: ["Combinatorics", "Factorial and binomial topics", "Integer sequences", "Operations on numbers", "Triangles of numbers"]
related: ["[[Singmaster's conjecture]]", "[[Bernoulli umbra]]", "[[Bhargava factorial]]", "[[Combinatorial number system]]", "[[Constant-recursive sequence]]", "[[Delannoy number]]", "[[Factorial]]", "[[Factorial number system]]", "[[Large set (combinatorics)]]", "[[Meander (mathematics)]]"]
---

# Binomial coefficient

In mathematics, the binomial coefficients are the positive integers that occur as coefficients in the binomial theorem. Commonly, a binomial coefficient is indexed by a pair of integers n ≥ k ≥ 0 and is written 
  
    
      
        
          
            
              
              
              
                n
                k
              
              
              
            
          
        
      
    
    
  
 or ⁠
  
    
      
        C
        n
        ,
        k
      
    
    
  
⁠. It is the coefficient of the xk term in the polynomial expansion of the binomial power (1 + x)n; this coefficient can be computed by the multiplicative formula

  
    
      
        
          
            
            
            
              n
              k
            
            
            
          
        
        
          
            
              n
              (
              n
              1
              ×
              ⋯
              (
              n
              k
              1
            
            
              k
              (
              k
              1
              ×
              ⋯
              1
            
          
        
        ,
      
    
    
  

which using factorial notation can be compactly expressed as

  
    
      
        
          
            
            
            
              n
              k
            
            
            
          
        
        
          
            
              n
              !
            
            
              k
              !
              n
              k
              !
            
          
        
        .
      
    
    
  

For example, the fourth power of 1 + x is

  
    
      
        
          
            
              
                1
                x
                
                  
                    4
                  
                
              
              
                
                
                  
                    
                      
                      
                      
                        4
                        0
                      
                      
                      
                    
                  
                
                
                  x
                  
                    0
                  
                
                
                  
                    
                      
                      
                      
                        4
                        1
                      
                      
                      
                    
                  
                
                
                  x
                  
                    1
                  
                
                
                  
                    
                      
                      
                      
                        4
                        2
                      
                      
                      
                    
                  
                
                
                  x
                  
                    2
                  
                
                
                  
                    
                      
                      
                      
                        4
                        3
                      
                      
                      
                    
                  
                
                
                  x
                  
                    3
                  
                
                
                  
                    
                      
                      
                      
                        4
                        4
                      
                      
                      
                    
                  
                
                
                  x
                  
                    4
                  
                
              
            
            
              
              
                
                1
                4
                x
                6
                
                  x
                  
                    2
                  
                
                4
                
                  x
                  
                    3
                  
                
                
                  x
                  
                    4
                  
                
                ,
              
            
          
        
      
    
    
  

and the binomial coefficient 
  
    
      
        
          
            
              
              
              
                4
                2
              
              
              
            
          
        
        
          
            
              
                4
                3
              
              
                2
                1
              
            
          
        
        
          
            
              
                4
                !
              
              
                2
                !
                2
                !
              
            
          
        
        6
      
    
    
  
 is the coefficient of the x2 term.
Arranging the numbers 
  
    
      
        
          
            
              
              
              
                n
                0
              
              
              
            
          
        
        ,
        
          
            
              
              
              
                n
                1
              
              
              
            
          
        
        ,
        …
        ,
        
          
            
              
              
              
                n
                n
              
              
              
            
          
        
      
    
    
  
 in successive rows for n = 0, 1, 2, ... gives a triangular array called Pascal's triangle, satisfying the recurrence relation

  
    
      
        
          
            
            
            
              n
              k
            
            
            
          
        
        
          
            
            
            
              
                n
                1
              
              
                k
                1
              
            
            
            
          
        
        
          
            
            
            
              
                n
                1
              
              k
            
            
            
          
        
        .
      
    
    
  

The binomial coefficients occur in many areas of mathematics, and especially in combinatorics. In combinatorics the symbol 
  
    
      
        
          
            
              
              
              
                n
                k
              
              
              
            
          
        
      
    
    
  
 is usually read as "n choose k" because there are 
  
    
      
        
          
            
              
              
              
                n
                k
              
              
              
            
          
        
      
    
    
  
 ways to choose an (unordered) subset of k elements from a fixed set of n elements. Said otherwise, there are 
  
    
      
        
          
            
              
              
              
                n
                k
              
              
              
            
          
        
      
    
    
  
 subsets of k elements that can be extracted from a set of n elements. For example, there are 
  
    
      
        
          
            
              
              
              
                4
                2
              
              
              
            
          
        
        6
      
    
    
  
 ways to choose 2 elements from {1, 2, 3, 4}, namely {1, 2}, {1, 3}, {1, 4}, {2, 3}, {2, 4} and {3, 4}.
The binomial coefficients can be extended to accept more general families of inputs.  When n is a nonnegative integer and k is an integer such that k < 0 or k > n, it is common to define ⁠
  
    
      
        
          
            
              
              
              
                n
                k
              
              
              
            
          
        
        0
      
    
    
  
⁠.  If k is a nonnegative integer and z is any complex number, the first multiplicative formula above can be used to define ⁠
  
    
      
        
          
            
              
              
              
                z
                k
              
              
              
            
          
        
      
    
    
  
⁠.  Many of the properties of binomial coefficients continue to hold in these more general contexts.

*(note truncated for size; full article at the source link below)*

## Related

- [[Singmaster's conjecture]]
- [[Bernoulli umbra]]
- [[Bhargava factorial]]
- [[Combinatorial number system]]
- [[Constant-recursive sequence]]
- [[Delannoy number]]
- [[Factorial]]
- [[Factorial number system]]
- [[Large set (combinatorics)]]
- [[Meander (mathematics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Binomial_coefficient