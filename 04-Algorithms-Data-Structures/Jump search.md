---
title: "Jump search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Jump_search"
wikipedia_categories: ["Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# Jump search

In computer science, a jump search or block search refers to a search algorithm for ordered lists. It works by first checking all items Lkm, where 
  
    
      
        k
        ∈
        
          N
        
      
    
    
  
 and m is the block size, until an item is found that is larger than the search key. To find the exact position of the search key in the list a linear search is performed on the sublist L[(k-1)m, km].
The optimal value of m is √n, where n is the length of the list L. Because both steps of the algorithm look at, at most, √n items the algorithm runs in O(√n) time. This is better than a linear search, but worse than a binary search. The advantage over the latter is that a jump search only needs to jump backwards once, while a binary can jump backwards up to log n times. This can be important if jumping backwards takes significantly more time than jumping forward.
The algorithm can be modified by performing multiple levels of jump search on the sublists, before finally performing the linear search. For a k-level jump search the optimum block size ml for the l th level (counting from 1) is n(k-l)/k. The modified algorithm will perform k backward jumps and runs in O(kn1/(k+1)) time.

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

- Wikipedia: https://en.wikipedia.org/wiki/Jump_search