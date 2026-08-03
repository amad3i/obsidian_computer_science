---
title: "D*"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/D*"
wikipedia_categories: ["Graph algorithms", "Robot control", "Search algorithms"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[B-]]", "[[Bidirectional search]]", "[[Breadth-first search]]", "[[Contraction hierarchies]]", "[[Depth-first search]]", "[[Dijkstra's algorithm]]", "[[Fringe search]]", "[[Incremental heuristic search]]"]
---

# D*

D* (pronounced "D star") is any one of the following three related incremental search algorithms:

The original D*, by Anthony Stentz, is an informed incremental search algorithm.
Focused D* is an informed incremental heuristic search algorithm by Anthony Stentz that combines ideas of A* and the original D*. Focused D* resulted from a further development of the original D*.
D* Lite is an incremental heuristic search algorithm by Sven Koenig and Maxim Likhachev that builds on LPA*, an incremental heuristic search algorithm that combines ideas of A* and Dynamic SWSF-FP.
All three search algorithms solve the same assumption-based path planning problems, including planning with the freespace assumption, where a robot has to navigate to given goal coordinates in unknown terrain. It makes assumptions about the unknown part of the terrain (for example: that it contains no obstacles) and finds a shortest path from its current coordinates to the goal coordinates under these assumptions. The robot then follows the path. When it observes new map information (such as previously unknown obstacles), it adds the information to its map and, if necessary, replans a new shortest path from its current coordinates to the given goal coordinates. It repeats the process until it reaches the goal coordinates or determines that the goal coordinates cannot be reached. When traversing unknown terrain, new obstacles may be discovered frequently, so this replanning needs to be fast. Incremental (heuristic) search algorithms speed up searches for sequences of similar search problems by using experience with the previous problems to speed up the search for the current one. Assuming the goal coordinates do not change, all three search algorithms are more efficient than repeated A* searches.
D* and its variants have been widely used for mobile robot and autonomous vehicle navigation. Current systems are typically based on D* Lite rather than the original D* or Focused D*. In fact, even Stentz's lab uses D* Lite rather than D* in some implementations. Such navigation systems include a prototype system tested on the Mars rovers Opportunity and Spirit and the navigation system of the winning entry in the DARPA Urban Challenge, both developed at Carnegie Mellon University.
The original D* was introduced by Anthony Stentz in 1994.  The name D* comes from the term "Dynamic A*", because the algorithm behaves like A* except that the arc costs can change as the algorithm runs.

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[B-]]
- [[Bidirectional search]]
- [[Breadth-first search]]
- [[Contraction hierarchies]]
- [[Depth-first search]]
- [[Dijkstra's algorithm]]
- [[Fringe search]]
- [[Incremental heuristic search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/D*