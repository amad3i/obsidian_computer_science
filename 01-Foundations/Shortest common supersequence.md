---
title: "Shortest common supersequence"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Shortest_common_supersequence"
wikipedia_categories: ["Approximation algorithms", "Combinatorics", "Dynamic programming", "Formal languages", "NP-complete problems", "Problems on strings"]
related: ["[[Longest common subsequence]]", "[[Longest increasing subsequence]]", "[[Longest alternating subsequence]]", "[[Longest repeated substring problem]]", "[[3-dimensional matching]]", "[[Hunt–Szymanski algorithm]]", "[[Knapsack problem]]", "[[Set packing]]", "[[Smallest grammar problem]]", "[[Trace monoid]]"]
---

# Shortest common supersequence

In computer science, the shortest common supersequence of two sequences X and Y is the shortest sequence which has X and Y as subsequences. This is a problem closely related to the longest common subsequence problem. Given two sequences X = < x1,...,xm > and Y = < y1,...,yn >, a sequence U = < u1,...,uk > is a common supersequence of X and Y if items can be removed from U to produce X and Y.
A shortest common supersequence (SCS) is a common supersequence of minimal length.  In the SCS problem, two sequences X and Y are given, and the task is to find a shortest possible common supersequence of these sequences.  In general, an SCS is not unique.
For two input sequences, an SCS can be formed from a longest common subsequence (LCS) easily.  For example, the longest common subsequence of X
  
    
      
        1..
        m
        =
        a
        b
        c
        b
        d
        a
        b
      
    
    
  
 and Y
  
    
      
        1..
        n
        =
        b
        d
        c
        a
        b
        a
      
    
    
  
 is Z
  
    
      
        1..
        L
        =
        b
        c
        b
        a
      
    
    
  
.  By inserting the non-LCS symbols into Z while preserving their original order, we obtain a shortest common supersequence U
  
    
      
        1..
        S
        =
        a
        b
        d
        c
        a
        b
        d
        a
        b
      
    
    
  
.  In particular, the equation 
  
    
      
        L
        S
        m
        n
      
    
    
  
 holds for any two input sequences.
There is no similar relationship between shortest common supersequences and longest common subsequences of three or more input sequences.  (In particular, LCS and SCS are not dual problems.)  However, both problems can be solved in 
  
    
      
        O
        
          n
          
            k
          
        
      
    
    
  
 time using dynamic programming, where 
  
    
      
        k
      
    
    
  
 is the number of sequences, and 
  
    
      
        n
      
    
    
  
 is their maximum length.  For the general case of an arbitrary number of input sequences, the problem is NP-hard.

## Related

- [[Longest common subsequence]]
- [[Longest increasing subsequence]]
- [[Longest alternating subsequence]]
- [[Longest repeated substring problem]]
- [[3-dimensional matching]]
- [[Hunt–Szymanski algorithm]]
- [[Knapsack problem]]
- [[Set packing]]
- [[Smallest grammar problem]]
- [[Trace monoid]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Shortest_common_supersequence