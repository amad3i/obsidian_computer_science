---
title: "Combinatorial number system"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Combinatorial_number_system"
wikipedia_categories: ["Combinatorics", "Factorial and binomial topics"]
related: ["[[Bernoulli umbra]]", "[[Bhargava factorial]]", "[[Binomial coefficient]]", "[[Factorial]]", "[[Factorial number system]]", "[[Multinomial theorem]]", "[[Singmaster's conjecture]]", "[[Star of David theorem]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]"]
---

# Combinatorial number system

In mathematics, and in particular in combinatorics, the combinatorial number system of degree k (for some positive integer k), also referred to as combinadics, or the Macaulay representation of an integer, is a correspondence between natural numbers (taken to include 0) N and k-combinations. The combinations are represented as strictly decreasing sequences ck > ... > c2 > c1 ≥ 0 where each ci corresponds to the index of a chosen element in a given k-combination. Distinct numbers correspond to distinct k-combinations, and produce them in lexicographic order. The numbers less than 
  
    
      
        
          
            
              
              
              
                n
                k
              
              
              
            
          
        
      
    
    
  
 correspond to all k-combinations of {0, 1, ..., n − 1}. The correspondence does not depend on the size n of the set that the k-combinations are taken from, so it can be interpreted as a map from N to the k-combinations taken from N; in this view the correspondence is a bijection.
The number N corresponding to (ck, ..., c2, c1) is given by

  
    
      
        N
        
          
            
            
            
              
                c
                
                  k
                
              
              k
            
            
            
          
        
        ⋯
        
          
            
            
            
              
                c
                
                  2
                
              
              2
            
            
            
          
        
        
          
            
            
            
              
                c
                
                  1
                
              
              1
            
            
            
          
        
      
    
    
  
.
The fact that a combination corresponds to a non-negative integer was observed by Lehmer (1964). Indeed, a greedy algorithm finds the k-combination corresponding to N: take ck maximal with 
  
    
      
        
          
            
              
              
              
                
                  c
                  
                    k
                  
                
                k
              
              
              
            
          
        
        ≤
        N
      
    
    
  
, then take ck−1 maximal with 
  
    
      
        
          
            
              
              
              
                
                  c
                  
                    k
                    1
                  
                
                
                  k
                  1
                
              
              
              
            
          
        
        ≤
        N
        
          
            
              
              
              
                
                  c
                  
                    k
                  
                
                k
              
              
              
            
          
        
      
    
    
  
, and so forth. Finding the number N, using the formula above, from the k-combination (ck, ..., c2, c1) is also known as "ranking", and the opposite operation (given by the greedy algorithm) as "unranking"; the operations are known by these names in most computer algebra systems, and in computational mathematics.
The term "combinatorial representation of integers" was shortened to "combinatorial number system" by Knuth (2011).
He also references Ernesto Pascal (1887).
The term "combinadic" is introduced by James McCaffrey.
Unlike the factorial number system, the combinatorial number system of degree k is not a mixed radix system: the part 
  
    
      
        
          
            
              
              
              
                
                  c
                  
                    i
                  
                
                i
              
              
              
            
          
        
      
    
    
  
 of the number N represented by a "digit" ci is not obtained from it by simply multiplying by a place value.
The main application of the combinatorial number system is that it allows rapid computation of the k-combination that is at a given position in the lexicographic ordering, without having to explicitly list the k-combinations preceding it; this allows for instance random generation of k-combinations of a given set. Enumeration of k-combinations has many applications, among which are software testing, sampling, quality control, and the analysis of lottery games.

## Related

- [[Bernoulli umbra]]
- [[Bhargava factorial]]
- [[Binomial coefficient]]
- [[Factorial]]
- [[Factorial number system]]
- [[Multinomial theorem]]
- [[Singmaster's conjecture]]
- [[Star of David theorem]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Combinatorial_number_system