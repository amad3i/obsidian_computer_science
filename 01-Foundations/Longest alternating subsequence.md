---
title: "Longest alternating subsequence"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Longest_alternating_subsequence"
wikipedia_categories: ["Combinatorics", "Dynamic programming", "Permutations", "Problems on strings"]
related: ["[[Longest common subsequence]]", "[[Longest increasing subsequence]]", "[[Shortest common supersequence]]", "[[Hunt–Szymanski algorithm]]", "[[Inversion (discrete mathematics)]]", "[[Josephus problem]]", "[[Langford pairing]]", "[[Lehmer code]]", "[[Longest repeated substring problem]]", "[[Stirling permutation]]"]
---

# Longest alternating subsequence

In combinatorial mathematics, probability, and computer science, in the longest alternating subsequence problem, one wants to find a subsequence of a given sequence in which the elements are in alternating order, and in which the sequence is as long as possible.
Formally, if 
  
    
      
        
          x
        
        {
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
      
    
    
  
 is a sequence of distinct real numbers, then the subsequence 
  
    
      
        
          x
          
            
              i
              
                1
              
            
          
        
        ,
        
          x
          
            
              i
              
                2
              
            
          
        
        ,
        …
        ,
        
          x
          
            
              i
              
                k
              
            
          
        
      
    
    
  
 is alternating (or zigzag or down-up) if

  
    
      
        
          x
          
            
              i
              
                1
              
            
          
        
        
          x
          
            
              i
              
                2
              
            
          
        
        
          x
          
            
              i
              
                3
              
            
          
        
        ⋯
        
          x
          
            
              i
              
                k
              
            
          
        
        
        
          and
        
        
        1
        ≤
        
          i
          
            1
          
        
        
          i
          
            2
          
        
        ⋯
        
          i
          
            k
          
        
        ≤
        n
        .
      
    
    
  

Similarly, 
  
    
      
        
          x
        
      
    
    
  
 is reverse alternating (or up-down) if 

  
    
      
        
          x
          
            
              i
              
                1
              
            
          
        
        
          x
          
            
              i
              
                2
              
            
          
        
        
          x
          
            
              i
              
                3
              
            
          
        
        ⋯
        
          x
          
            
              i
              
                k
              
            
          
        
        
        
          and
        
        
        1
        ≤
        
          i
          
            1
          
        
        
          i
          
            2
          
        
        ⋯
        
          i
          
            k
          
        
        ≤
        n
        .
      
    
    
  

Note that every sequence of length 1 is both alternating and reverse alternating.
Let 
  
    
      
        
          
            
              a
              s
            
          
          
            n
          
        
        
          x
        
      
    
    
  
 denote the length (number of terms) of the longest alternating subsequence of 
  
    
      
        
          x
        
      
    
    
  
. For example, if we consider some of the permutations of the integers 1,2,3,4,5, we have that

  
    
      
        
          
            
              a
              s
            
          
          
            5
          
        
        5
        ,
        4
        ,
        3
        ,
        2
        ,
        1
        =
        2
      
    
    
  
, because there are alternating subsequences of length 2, (for example 5,4 or 5,2 or 3,1), but all subsequences of length 3 are not alternating;

  
    
      
        
          
            
              a
              s
            
          
          
            5
          
        
        1
        ,
        2
        ,
        3
        ,
        4
        ,
        5
        =
        1
      
    
    
  
, because all subsequences of length 2 are not alternating. (actually, they are reverse alternating);

  
    
      
        
          
            
              a
              s
            
          
          
            5
          
        
        5
        ,
        1
        ,
        3
        ,
        4
        ,
        2
        =
        4
        ,
      
    
    
  
 because 5,1,3,2 and 5,1,4,2 and 5,3,4,2 are all alternating, and there is no alternating subsequence with more elements;

  
    
      
        
          
            
              a
              s
            
          
          
            5
          
        
        4
        ,
        3
        ,
        5
        ,
        1
        ,
        2
        =
        5
        ,
      
    
    
  
 because 4,3,5,1,2 is itself alternating.

## Related

- [[Longest common subsequence]]
- [[Longest increasing subsequence]]
- [[Shortest common supersequence]]
- [[Hunt–Szymanski algorithm]]
- [[Inversion (discrete mathematics)]]
- [[Josephus problem]]
- [[Langford pairing]]
- [[Lehmer code]]
- [[Longest repeated substring problem]]
- [[Stirling permutation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Longest_alternating_subsequence