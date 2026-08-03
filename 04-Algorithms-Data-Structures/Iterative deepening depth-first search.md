---
title: "Iterative deepening depth-first search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Iterative_deepening_depth-first_search"
wikipedia_categories: ["Graph algorithms", "Search algorithms"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[B-]]", "[[Bidirectional search]]", "[[Breadth-first search]]", "[[Contraction hierarchies]]", "[[D-]]", "[[Depth-first search]]", "[[Dijkstra's algorithm]]", "[[Fringe search]]"]
---

# Iterative deepening depth-first search

In computer science, iterative deepening search or more specifically iterative deepening depth-first search (IDS or IDDFS) is a state space/graph search strategy in which a depth-limited version of depth-first search is run repeatedly with increasing depth limits until the goal is found. IDDFS is optimal, meaning that it finds the shallowest goal. Since it visits all the nodes in the search tree down to depth 
  
    
      
        d
      
    
    
  
 before visiting any nodes at depth 
  
    
      
        d
        1
      
    
    
  
, the cumulative order in which nodes are first visited is effectively the same as in breadth-first search. However, IDDFS uses much less memory.

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[B-]]
- [[Bidirectional search]]
- [[Breadth-first search]]
- [[Contraction hierarchies]]
- [[D-]]
- [[Depth-first search]]
- [[Dijkstra's algorithm]]
- [[Fringe search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Iterative_deepening_depth-first_search