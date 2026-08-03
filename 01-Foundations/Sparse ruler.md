---
title: "Sparse ruler"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sparse_ruler"
wikipedia_categories: ["Combinatorics", "Length, distance, or range measuring devices", "Number theory"]
related: ["[[Golomb ruler]]", "[[Multipartition]]", "[[Natural density]]", "[[Sidon sequence]]", "[[3-dimensional matching]]", "[[3x + 1 semigroup]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Abc conjecture]]", "[[Abel's summation formula]]", "[[Addition principle]]"]
---

# Sparse ruler

A sparse ruler is a ruler in which some of the distance marks may be missing.  More abstractly, a sparse ruler of length 
  
    
      
        L
      
    
    
  
 with 
  
    
      
        m
      
    
    
  
 marks is a sequence of integers 
  
    
      
        
          a
          
            1
          
        
        ,
        
          a
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          a
          
            m
          
        
      
    
    
  
 where 
  
    
      
        0
        
          a
          
            1
          
        
        
          a
          
            2
          
        
        .
        .
        .
        
          a
          
            m
          
        
        L
      
    
    
  
.  The marks 
  
    
      
        
          a
          
            1
          
        
      
    
    
  
 and 
  
    
      
        
          a
          
            m
          
        
      
    
    
  
 correspond to the ends of the ruler.  In order to measure the distance 
  
    
      
        K
      
    
    
  
, with 
  
    
      
        0
        ≤
        K
        ≤
        L
      
    
    
  
 there must be marks 
  
    
      
        
          a
          
            i
          
        
      
    
    
  
 and 
  
    
      
        
          a
          
            j
          
        
      
    
    
  
 such that 
  
    
      
        
          a
          
            j
          
        
        
          a
          
            i
          
        
        K
      
    
    
  
.
A complete sparse ruler allows one to measure any integer distance up to its full length.  A complete sparse ruler is called minimal if there is no complete sparse ruler of length 
  
    
      
        L
      
    
    
  
 with 
  
    
      
        m
        1
      
    
    
  
 marks.  In other words, if any of the marks is removed one can no longer measure all of the distances, even if the marks could be rearranged.  A complete sparse ruler is called maximal if there is no complete sparse ruler of greater length with 
  
    
      
        m
      
    
    
  
 marks. Complete minimal rulers of length 135 and 136 require one more mark than those of lengths 124-134, 137 and 138.  A sparse ruler is called optimal if it is both minimal and maximal.
Since the number of distinct pairs of marks is 
  
    
      
        m
        m
        1
        
          /
        
        2
      
    
    
  
, this is an upper bound on the length 
  
    
      
        L
      
    
    
  
 of any maximal sparse ruler with 
  
    
      
        m
      
    
    
  
 marks.  This upper bound can be achieved only for 2, 3 or 4 marks.  For larger numbers of marks, the difference between the optimal length and the bound grows gradually, and unevenly.
For example, for 6 marks the upper bound is 15, but the maximal length is 13.  There are 3 different configurations of sparse rulers of length 13 with 6 marks.  One is {0, 1, 2, 6, 10, 13}.  To measure a length of 7, say, with this ruler one would take the distance between the marks at 6 and 13.
A Golomb ruler is a sparse ruler that requires all of the differences 
  
    
      
        
          a
          
            j
          
        
        
          a
          
            i
          
        
      
    
    
  
 be distinct.  In general, a Golomb ruler with 
  
    
      
        m
      
    
    
  
 marks will be considerably longer than an optimal sparse ruler with 
  
    
      
        m
      
    
    
  
 marks, since 
  
    
      
        m
        m
        1
        
          /
        
        2
      
    
    
  
 is a lower bound for the length of a Golomb ruler.  A long Golomb ruler will have gaps, that is, it will have distances which it cannot measure.  For example, the optimal Golomb ruler {0, 1, 4, 10, 12, 17} has length 17, but cannot measure lengths of 14 or 15.

## Related

- [[Golomb ruler]]
- [[Multipartition]]
- [[Natural density]]
- [[Sidon sequence]]
- [[3-dimensional matching]]
- [[3x + 1 semigroup]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Abc conjecture]]
- [[Abel's summation formula]]
- [[Addition principle]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sparse_ruler