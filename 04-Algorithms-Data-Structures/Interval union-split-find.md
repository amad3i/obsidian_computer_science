---
title: "Interval union-split-find"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Interval_union-split-find"
wikipedia_categories: ["Data structures"]
related: ["[[Active data structure]]", "[[Block availability map]]", "[[Comparison of data structures]]", "[[Compressed data structure]]", "[[Control block]]", "[[Directed acyclic graph]]", "[[Dynamization]]", "[[Implicit data structure]]", "[[List of data structures]]", "[[Oblivious data structure]]"]
---

# Interval union-split-find

In computer science, an interval union-split-find data structure is a data structure that stores a partition of the integer
interval 
  
    
      
        1
        ,
        n
      
    
    
  
 into intervals. Equivalently, it stores a set of elements from 
  
    
      
        1
        ,
        n
      
    
    
  
 ("splitters"), which define the endpoints
of the intervals; for example, if n=10 and the set of endpoints is 
  
    
      
        1
        ,
        4
        ,
        8
      
    
    
  
 then the intervals are 
  
    
      
        1
        ,
        3
        ,
        4
        ,
        7
      
    
    
  
 and 
  
    
      
        8
        ,
        10
      
    
    
  
. The data structure provides the following operations:

split(x) adds x as a splitter, thus splitting the interval containing it (if x has not already been a splitter)
union(x) for merging two intervals by removing the splitter x
find(x) for finding which interval x belongs to (returning the interval's endpoint).
The problem is an instance of the dynamic predecessor problem, with a universe of size n.
Using Van Emde Boas trees, the data structure can be implemented with 
  
    
      
        O
        log
         
         
        n
      
    
    
  
 time per operation, in 
  
    
      
        O
        n
      
    
    
  
 space. A matching lower bound has been proved by Mehlhorn, Näher and Alt under the assumption of a pointer algorithm. Under the assumptions of the cell-probe model, Beame and Fich proved that a data structure that uses word size 
  
    
      
        
          2
          
            log
             
            n
            
              
                1
                Ω
                1
              
            
          
        
      
    
    
  
 must cost 
  
    
      
        Ω
        log
         
         
        k
        
          /
        
         
         
         
        k
      
    
    
  
 per operation, where k is the number of intervals.
The Union-Split-Find problem is important for a number of applications, e.g. dynamic fractional cascading 
and computing shortest paths.

## Related

- [[Active data structure]]
- [[Block availability map]]
- [[Comparison of data structures]]
- [[Compressed data structure]]
- [[Control block]]
- [[Directed acyclic graph]]
- [[Dynamization]]
- [[Implicit data structure]]
- [[List of data structures]]
- [[Oblivious data structure]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interval_union-split-find