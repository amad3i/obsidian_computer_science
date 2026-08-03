---
title: "3SUM"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/3SUM"
wikipedia_categories: ["Computational geometry", "Polynomial-time problems", "Unsolved problems in computer science"]
related: ["[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Artificial general intelligence]]", "[[Artificial intelligence content detection]]", "[[Artificial wisdom]]", "[[Badouel intersection algorithm]]"]
---

# 3SUM

In computational complexity theory, the 3SUM problem asks if a given set of 
  
    
      
        n
      
    
    
  
 real numbers contains three elements that sum to zero.  A generalized version, 
  
    
      
        k
      
    
    
  
-SUM, asks the same question on 
  
    
      
        k
      
    
    
  
 elements, rather than simply 3. 3SUM can be easily solved in 
  
    
      
        O
        
          n
          
            2
          
        
      
    
    
  
 time, and matching 
  
    
      
        Ω
        
          n
          
            ⌈
            k
            
              /
            
            2
            ⌉
          
        
      
    
    
  
 lower bounds are known in some specialized models of computation (Erickson 1999).
It was conjectured that any deterministic algorithm for the 3SUM requires 
  
    
      
        Ω
        
          n
          
            2
          
        
      
    
    
  
 time.
In 2014, the original 3SUM conjecture was refuted by Allan Grønlund and Seth Pettie who gave a deterministic algorithm that solves 3SUM in 
  
    
      
        O
        
          n
          
            2
          
        
        
          /
        
        
           
          n
        
        
          /
        
        
           
           
          n
        
        
          
            2
            
              /
            
            3
          
        
      
    
    
  
 time.
Additionally, Grønlund and Pettie showed that the 4-linear decision tree complexity of 3SUM is 
  
    
      
        O
        
          n
          
            3
            
              /
            
            2
          
        
        
          
             
            n
          
        
      
    
    
  
.
These bounds were subsequently improved.
The current best known algorithm for 3SUM runs in 
  
    
      
        O
        
          n
          
            2
          
        
        log
         
         
        n
        
          
            O
            1
          
        
        
          /
        
        
          
            
              2
            
          
           
          n
        
      
    
    
  
 time.
Kane, Lovett, and Moran showed that the 6-linear decision tree complexity of 3SUM is 
  
    
      
        O
        n
        
          
            
              2
            
          
           
          n
        
      
    
    
  
. The latter bound is tight (up to a logarithmic factor).  
It is still conjectured that 3SUM is unsolvable in 
  
    
      
        O
        
          n
          
            2
            Ω
            1
          
        
      
    
    
  
 expected time.
When the elements are integers in the range 
  
    
      
        −
        N
        ,
        …
        ,
        N
      
    
    
  
, 3SUM can be solved in 
  
    
      
        O
        n
        N
         
        N
      
    
    
  
 time by representing the input set 
  
    
      
        S
      
    
    
  
 as a bit vector, computing the set 
  
    
      
        S
        S
      
    
    
  
 of all pairwise sums as a discrete convolution using the fast Fourier transform, and finally comparing this set to 
  
    
      
        S
      
    
    
  
.

## Related

- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Artificial general intelligence]]
- [[Artificial intelligence content detection]]
- [[Artificial wisdom]]
- [[Badouel intersection algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/3SUM