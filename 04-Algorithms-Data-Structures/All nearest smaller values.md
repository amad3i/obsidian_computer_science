---
title: "All nearest smaller values"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/All_nearest_smaller_values"
wikipedia_categories: ["Parallel computing", "Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All-to-all (parallel pattern)]]", "[[Alpha–beta pruning]]", "[[AMD Instinct]]"]
---

# All nearest smaller values

In computer science, the all nearest smaller values (ANSV) problem is: given an array 
  
    
      
        A
        1..
        n
      
    
    
  
, compute for each position 
  
    
      
        i
      
    
    
  
 the index

  
    
      
        P
        i
        =
        max
        
        j
        i
        ∣
        A
        j
        <
        A
        i
        
      
    
    
  
, using a sentinel value (e.g. 
  
    
      
        0
      
    
    
  
) when no such 
  
    
      
        j
      
    
    
  
 exists.  The corresponding nearest-smaller value is 
  
    
      
        A
        P
        i
        ]
      
    
    
  
.  Some presentations report 
  
    
      
        A
        P
        i
        ]
      
    
    
  
, but many applications require the indices 
  
    
      
        P
        i
      
    
    
  
.
This problem can be solved efficiently both by parallel and non-parallel algorithms: Berkman, Schieber & Vishkin (1993),  who first identified the procedure as a useful subroutine for other parallel programs, developed efficient algorithms to solve it in the Parallel Random Access Machine model; it may also be solved in linear time on a non-parallel computer using a stack-based algorithm. Later researchers have studied algorithms to solve it in other models of parallel computation.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All-to-all (parallel pattern)]]
- [[Alpha–beta pruning]]
- [[AMD Instinct]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/All_nearest_smaller_values