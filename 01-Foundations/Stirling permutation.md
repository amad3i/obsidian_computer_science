---
title: "Stirling permutation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Stirling_permutation"
wikipedia_categories: ["Combinatorics", "Permutations"]
related: ["[[Inversion (discrete mathematics)]]", "[[Josephus problem]]", "[[Langford pairing]]", "[[Lehmer code]]", "[[Longest alternating subsequence]]", "[[Twelvefold way]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algorithmic Lovász local lemma]]"]
---

# Stirling permutation

In combinatorial mathematics, a Stirling permutation of order k is a permutation of the multiset 1, 1, 2, 2, ..., k, k (with two copies of each value from 1 to k) with the additional property that, for each value i appearing in the permutation, any values between the two copies of i are larger than i. For instance, the 15 Stirling permutations of order three are

1,1,2,2,3,3;   1,2,2,1,3,3;   2,2,1,1,3,3;
1,1,2,3,3,2;   1,2,2,3,3,1;   2,2,1,3,3,1;
1,1,3,3,2,2;   1,2,3,3,2,1;   2,2,3,3,1,1;
1,3,3,1,2,2;   1,3,3,2,2,1;   2,3,3,2,1,1;
3,3,1,1,2,2;   3,3,1,2,2,1;   3,3,2,2,1,1.
The number of Stirling permutations of order k is given by the double factorial (2k − 1)!!. 
Stirling permutations were introduced by Gessel and Stanley in order to show that certain numbers appearing as coefficients in rational expressions involving Stirling numbers are non-negative. Specifically, letting the numbers 
  
    
      
        
          ⟨
          
            
            
              ⟨
              
                
                  n
                  k
                
              
              ⟩
            
            
          
          ⟩
        
      
    
    {\textstyle \left\langle \!\left\langle {n \atop k}\right\rangle \!\right\rangle }
  
 be defined by

  
    
      
        
          ∑
          
            m
            0
          
          
            ∞
          
        
        
          
            
              
                n
                m
              
              m
            
          
        
        
          x
          
            m
          
        
        
          
            
              
                ∑
                
                  k
                  0
                
                
                  n
                
              
              
                ⟨
                
                  
                  
                    ⟨
                    
                      
                        n
                        k
                      
                    
                    ⟩
                  
                  
                
                ⟩
              
              
                x
                
                  k
                  1
                
              
            
            
              1
              x
              
                
                  2
                  n
                  1
                
              
            
          
        
      
    
    
  

where the 
  
    
      
        
          
            
              n
              k
            
          
        
      
    
    
  
 denote the Stirling numbers of the second kind, Gessel and Stanley proved that 
  
    
      
        
          ⟨
          
            
            
              ⟨
              
                
                  n
                  k
                
              
              ⟩
            
            
          
          ⟩
        
      
    
    {\textstyle \left\langle \!\left\langle {n \atop k}\right\rangle \!\right\rangle }
  
 counts the number of Stirling permutations of order 
  
    
      
        n
      
    
    
  
 with exactly 
  
    
      
        k
      
    
    
  
 ascents. It is this connection to Stirling numbers which explains the name "Stirling permutations." Meanwhile, the numbers 
  
    
      
        
          ⟨
          
            
            
              ⟨
              
                
                  n
                  k
                
              
              ⟩
            
            
          
          ⟩
        
      
    
    {\textstyle \left\langle \!\left\langle {n \atop k}\right\rangle \!\right\rangle }
  
 are called Eulerian numbers of the second order.

Stirling permutations may be used to describe the sequences by which it is possible to construct a rooted plane tree with k edges by adding leaves one by one to the tree. For, if the edges are numbered by the order in which they were inserted, then the sequence of numbers in an Euler tour of the tree (formed by doubling the edges of the tree and traversing the children of each node in left to right order) is a Stirling permutation. Conversely every Stirling permutation describes a tree construction sequence, in which the next edge closer to the root from an edge labeled i is the one whose pair of values most closely surrounds the pair of i values in the permutation.
Stirling permutations have been generalized to the permutations of a multiset with more than two copies of each value. Researchers have also studied the number of Stirling permutations that avoid certain patterns.

## Related

- [[Inversion (discrete mathematics)]]
- [[Josephus problem]]
- [[Langford pairing]]
- [[Lehmer code]]
- [[Longest alternating subsequence]]
- [[Twelvefold way]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algorithmic Lovász local lemma]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stirling_permutation