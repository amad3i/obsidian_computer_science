---
title: "Iterative deepening A*"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Iterative_deepening_A*"
wikipedia_categories: ["Game artificial intelligence", "Graph algorithms", "Routing algorithms", "Search algorithms"]
related: ["[[A- search algorithm]]", "[[B-]]", "[[SMA-]]", "[[Alpha–beta pruning]]", "[[Contraction hierarchies]]", "[[Dijkstra's algorithm]]", "[[Minimax]]", "[[Proof-number search]]", "[[Theta-]]", "[[Bidirectional search]]"]
---

# Iterative deepening A*

Iterative deepening A* (IDA*) is a graph traversal and path search algorithm that can find the shortest path between a designated start node and any member of a set of goal nodes in a weighted graph. It is a variant of iterative deepening depth-first search that borrows the idea to use a heuristic function to conservatively estimate the remaining cost to get to the goal from the A* search algorithm. Since it is a depth-first search algorithm, its memory usage is lower than in A*, but unlike ordinary iterative deepening search, it concentrates on exploring the most promising nodes and thus does not go to the same depth everywhere in the search tree. Unlike A*, IDA* does not utilize dynamic programming and therefore often ends up exploring the same nodes many times.
While the standard iterative deepening depth-first search uses search depth as the cutoff for each iteration, the IDA* uses the more informative 
  
    
      
        f
        n
        =
        g
        n
        +
        h
        n
      
    
    
  
, where 
  
    
      
        g
        n
      
    
    
  
 is the cost to travel from the root to node 
  
    
      
        n
      
    
    
  
 and 
  
    
      
        h
        n
      
    
    
  
 is a problem-specific heuristic estimate of the cost to travel from 
  
    
      
        n
      
    
    
  
 to the goal.
The algorithm was first described by Richard E. Korf in 1985.

## Related

- [[A- search algorithm]]
- [[B-]]
- [[SMA-]]
- [[Alpha–beta pruning]]
- [[Contraction hierarchies]]
- [[Dijkstra's algorithm]]
- [[Minimax]]
- [[Proof-number search]]
- [[Theta-]]
- [[Bidirectional search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Iterative_deepening_A*