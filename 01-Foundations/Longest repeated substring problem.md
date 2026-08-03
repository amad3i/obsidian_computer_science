---
title: "Longest repeated substring problem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Longest_repeated_substring_problem"
wikipedia_categories: ["Algorithms and data structures stubs", "Combinatorics", "Combinatorics stubs", "Formal languages", "Problems on strings"]
related: ["[[Longest increasing subsequence]]", "[[Shortest common supersequence]]", "[[Cameron–Erdős conjecture]]", "[[Chinese monoid]]", "[[Combinatorial biology]]", "[[Combinatorial data analysis]]", "[[Combinatorics and dynamical systems]]", "[[Dittert conjecture]]", "[[Erdős sumset conjecture]]", "[[Extremal combinatorics]]"]
---

# Longest repeated substring problem

In computer science, the longest repeated substring problem is the problem of finding the longest substring of a string that occurs at least twice. 
This problem can be solved in linear time and space 
  
    
      
        Θ
        n
      
    
    
  
 by building a suffix tree for the string (with a special end-of-string symbol like '$' appended), and finding the deepest internal node in the tree with more than one child.  Depth is measured by the number of characters traversed from the root.  The string spelled by the edges from the root to such a node is a longest repeated substring. The problem of finding the longest substring with at least 
  
    
      
        k
      
    
    
  
 occurrences can be solved by first preprocessing the tree to count the number of leaf descendants for each internal node, and then finding the deepest node with at least 
  
    
      
        k
      
    
    
  
 leaf descendants. To avoid overlapping repeats, you can check that the list of suffix lengths has no consecutive elements with less than prefix-length difference.
In the figure with the string "ATCGATCGA$", the longest substring that repeats at least twice is "ATCGA".

## Related

- [[Longest increasing subsequence]]
- [[Shortest common supersequence]]
- [[Cameron–Erdős conjecture]]
- [[Chinese monoid]]
- [[Combinatorial biology]]
- [[Combinatorial data analysis]]
- [[Combinatorics and dynamical systems]]
- [[Dittert conjecture]]
- [[Erdős sumset conjecture]]
- [[Extremal combinatorics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Longest_repeated_substring_problem