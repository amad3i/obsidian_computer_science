---
title: "Best-first search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Best-first_search"
wikipedia_categories: ["Greedy algorithms", "Search algorithms"]
related: ["[[A- search algorithm]]", "[[Dijkstra's algorithm]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]"]
---

# Best-first search

In computer science, best-first search is a class of search algorithms which explores a graph by expanding the most promising node chosen according to a specified rule.
Judea Pearl described best-first search as estimating the promise of node n by a "heuristic evaluation function 
  
    
      
        f
        n
      
    
    
  
 which, in general, may depend on the description of n, the description of the goal, the information gathered by the search up to that point, and most importantly, on any extra knowledge about the problem domain."
Some authors have used "best-first search" to refer specifically to a search with a heuristic that attempts to predict how close the end of a path is to a solution (or, goal), so that paths which are judged to be closer to a solution (or, goal) are expanded first. This specific type of search is called greedy best-first search or pure heuristic search.
Efficient selection of the current best candidate for extension is typically implemented using a priority queue.
The A* search algorithm is an example of a best-first search algorithm, as is B*. Best-first algorithms are often used for path finding in combinatorial search. Neither A* nor B* is a greedy best-first search, as they incorporate the distance from the start in addition to estimated distances to the goal.

## Related

- [[A- search algorithm]]
- [[Dijkstra's algorithm]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]
- [[B-]]
- [[Backjumping]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Best-first_search