---
title: "Exponential search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Exponential_search"
wikipedia_categories: ["Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# Exponential search

In computer science, an exponential search (also called doubling search or galloping search or Struzik search) is an algorithm, created by Jon Bentley and Andrew Chi-Chih Yao in 1976, for searching sorted, unbounded/infinite lists. There are numerous ways to implement this, with the most common being to determine a range that the search key resides in and performing a binary search within that range. This takes 
  
    
      
        O
        log
         
        i
      
    
    
  
 time, where 
  
    
      
        i
      
    
    
  
 is the position of the search key in the list, if the search key is in the list, or the position where the search key should be, if the search key is not in the list.
Exponential search can also be used to search in bounded lists. Exponential search can even out-perform more traditional searches for bounded lists, such as binary search, when the element being searched for is near the beginning of the array. This is because exponential search will run in 
  
    
      
        O
        log
         
        i
      
    
    
  
 time, where 
  
    
      
        i
      
    
    
  
 is the index of the element being searched for in the list, whereas binary search would run in 
  
    
      
        O
        log
         
        n
      
    
    
  
 time, where 
  
    
      
        n
      
    
    
  
 is the number of elements in the list.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]
- [[B-]]
- [[Backjumping]]
- [[Backtracking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Exponential_search