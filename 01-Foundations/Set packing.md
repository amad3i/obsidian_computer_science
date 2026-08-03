---
title: "Set packing"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Set_packing"
wikipedia_categories: ["Combinatorics", "NP-complete problems"]
related: ["[[3-dimensional matching]]", "[[Longest common subsequence]]", "[[Shortest common supersequence]]", "[[1-in-3-SAT]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]", "[[All-pairs testing]]"]
---

# Set packing

Set packing is a classical NP-complete problem in computational complexity theory and combinatorics, and was one of Karp's 21 NP-complete problems. Suppose one has a finite set S and a list of subsets of S. Then, the set packing problem asks if some k subsets in the list are pairwise disjoint (in other words, no two of them share an element).
More formally, given a universe 
  
    
      
        
          
            U
          
        
      
    
    
  
 and a family 
  
    
      
        
          
            S
          
        
      
    
    
  
 of subsets of 
  
    
      
        
          
            U
          
        
      
    
    
  
, a packing is a subfamily 
  
    
      
        
          
            C
          
        
        ⊆
        
          
            S
          
        
      
    
    
  
 of sets such that all sets in 
  
    
      
        
          
            C
          
        
      
    
    
  
 are pairwise disjoint. The size of the packing is 
  
    
      
        
          |
        
        
          
            C
          
        
        
          |
        
      
    
    
  
. In the set packing decision problem, the input is a pair 
  
    
      
        
          
            U
          
        
        ,
        
          
            S
          
        
      
    
    
  
 and an integer 
  
    
      
        t
      
    
    
  
; the question is whether
there is a set packing of size 
  
    
      
        t
      
    
    
  
 or more. In the set packing optimization problem, the input is a pair 
  
    
      
        
          
            U
          
        
        ,
        
          
            S
          
        
      
    
    
  
, and the task is to find a set packing that uses the most sets.
The problem is clearly in NP since, given 
  
    
      
        t
      
    
    
  
 subsets, we can easily verify that they are pairwise disjoint in polynomial time.
The optimization version of the problem, maximum set packing, asks for the maximum number of pairwise disjoint sets in the list. It is a maximization problem that can be formulated naturally as an integer linear program, belonging to the class of packing problems.

## Related

- [[3-dimensional matching]]
- [[Longest common subsequence]]
- [[Shortest common supersequence]]
- [[1-in-3-SAT]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]
- [[All-pairs testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Set_packing