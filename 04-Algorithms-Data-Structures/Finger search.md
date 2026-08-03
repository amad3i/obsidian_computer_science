---
title: "Finger search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Finger_search"
wikipedia_categories: ["Search algorithms", "Trees (data structures)"]
related: ["[[Expectiminimax]]", "[[Finger search tree]]", "[[Ternary search tree]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[Abstract syntax tree]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[And–or tree]]"]
---

# Finger search

In computer science, a finger search on a data structure is an extension of any search operation that structure supports, where a reference (finger) to an element in the data structure is given along with the query. While the search time for an element is most frequently expressed as a function of the number of elements in a data structure, finger search times are a function of the distance between the element and the finger.
In a set of n elements, the distance d(x,y) (or simply d when unambiguous) between two elements x and y is their difference in rank. If x and y are the ith and jth largest elements in the structure, then the difference in rank is |i - j|. If a normal search in some structure would normally take ⁠
  
    
      
        O
        f
        n
        )
      
    
    
  
⁠ time, then a finger search for x with finger y should ideally take ⁠
  
    
      
        O
        f
        d
        )
      
    
    
  
⁠ time. Remark that since d ≤ n, it follows that in the worst case, finger search is only as bad as normal search. However, in practice these degenerate finger searches do more work than normal searches. For instance, if f(n) is log(n), and finger search does twice as many comparisons as normal search in the worst case, it follows that finger search is slower when d > √n. Therefore, finger search should only be used when one can reasonably expect the target to actually be close to the finger.

## Related

- [[Expectiminimax]]
- [[Finger search tree]]
- [[Ternary search tree]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[Abstract syntax tree]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[And–or tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Finger_search