---
title: "Littlewood–Offord problem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Littlewood–Offord_problem"
wikipedia_categories: ["Combinatorics", "Combinatorics stubs", "Lemmas", "Mathematical problems", "Probability problems"]
related: ["[[Zero-sum problem]]", "[[Algorithmic Lovász local lemma]]", "[[Cameron–Erdős conjecture]]", "[[Chinese monoid]]", "[[Combinatorial biology]]", "[[Combinatorial data analysis]]", "[[Combinatorics and dynamical systems]]", "[[Counting lemma]]", "[[Dickson's lemma]]", "[[Dittert conjecture]]"]
---

# Littlewood–Offord problem

In mathematical field of combinatorial geometry, the Littlewood–Offord problem is the problem of determining the number of subsums of a set of vectors that fall in a given convex set. More formally, if V is a vector space of dimension d, the problem is to determine, given a finite subset of vectors S and a convex subset A, the number of subsets of S whose summation is in A.
The first upper bound for this problem was proven (for d = 1 and d = 2) in 1938 by John Edensor Littlewood and A. Cyril Offord. This Littlewood–Offord lemma states that if S is a set of n real or complex numbers of absolute value at least one and A is any disc of diameter r, then not more than 
  
    
      
        c
        r
        
          2
          
            n
          
        
        log
         
        n
        
          n
          
            1
            
              /
            
            2
          
        
      
    
    
  
 of the 2n possible subsums of S fall into the disc.
In 1945 Paul Erdős improved the upper bound for d = 1 and r = 1 to

  
    
      
        
          
            
            
            
              n
              
                ⌊
                
                  n
                  
                    /
                  
                  2
                
                ⌋
              
            
            
            
          
        
        ≈
        
          2
          
            n
          
        
        
        
          
            1
            
              n
            
          
        
      
    
    
  

using  Sperner's theorem. This bound is sharp; equality is attained when all vectors in S are equal. In 1966, Kleitman showed that the same bound held for complex numbers. In 1970, he extended this to the setting when V is a normed space.
Suppose S = {v1, …, vn}. By subtracting

  
    
      
        
          
            1
            2
          
        
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          v
          
            i
          
        
      
    
    
  

from each possible subsum (that is, by changing the origin and then scaling by a factor of 2), the Littlewood–Offord problem is equivalent to the problem of determining the number of sums of the form

  
    
      
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          ε
          
            i
          
        
        
          v
          
            i
          
        
      
    
    
  

that fall in the target set A, where 
  
    
      
        
          ε
          
            i
          
        
      
    
    
  
 takes the value 
  
    
      
        
          
            1
            2
          
        
      
    
    
  
 or 
  
    
      
        
          
            1
            2
          
        
      
    
    
  
. This makes the problem into a probabilistic one, in which the question is of the distribution of these random vectors, and what can be said knowing nothing more about the vi.
If the 
  
    
      
        
          ε
          
            i
          
        
      
    
    
  
's take values from 1 or -1, instead of 
  
    
      
        
          
            1
            2
          
        
      
    
    
  
 or 
  
    
      
        
          
            1
            2
          
        
      
    
    
  
, the target set A for the Littlewood-Offord lemma can be changed from a disk of diameter one to a disk of radius one to account for the doubling of the coefficients.

## Related

- [[Zero-sum problem]]
- [[Algorithmic Lovász local lemma]]
- [[Cameron–Erdős conjecture]]
- [[Chinese monoid]]
- [[Combinatorial biology]]
- [[Combinatorial data analysis]]
- [[Combinatorics and dynamical systems]]
- [[Counting lemma]]
- [[Dickson's lemma]]
- [[Dittert conjecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Littlewood–Offord_problem