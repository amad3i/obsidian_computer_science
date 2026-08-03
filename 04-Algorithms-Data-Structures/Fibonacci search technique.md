---
title: "Fibonacci search technique"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Fibonacci_search_technique"
wikipedia_categories: ["Fibonacci numbers", "Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# Fibonacci search technique

In computer science, the Fibonacci search technique is a method of searching a sorted array using a divide and conquer algorithm that narrows down possible locations with the aid of Fibonacci numbers. The technique is conceptually similar to a binary search, which repeatedly splits the search interval into two equal halves. Fibonacci search, however, splits the array into two unequal parts, with sizes that are consecutive Fibonacci numbers.
This method has a key advantage on older computer hardware where arithmetic division or bit-shifting operations were computationally expensive compared to addition and subtraction. Since the Fibonacci sequence is based on addition, this search method could be implemented more efficiently. While on modern CPUs the performance difference is often negligible, the algorithm remains of theoretical and historical interest. On average, Fibonacci search performs about 4% more comparisons than binary search, and it has an average-case complexity  and worst-case complexity of 
  
    
      
        O
        log
         
        n
      
    
    
  
 (see Big O notation).
Fibonacci search can also have an advantage in searching data stored in certain structures, such as on a magnetic tape, where seek times are heavily dependent on the distance from the current head position. It is derived from Golden section search, an algorithm by Jack Kiefer (1953) to search for the maximum or minimum of a unimodal function in an interval.

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

- Wikipedia: https://en.wikipedia.org/wiki/Fibonacci_search_technique