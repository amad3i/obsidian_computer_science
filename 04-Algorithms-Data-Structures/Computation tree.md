---
title: "Computation tree"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Computation_tree"
wikipedia_categories: ["Computational complexity theory"]
related: ["[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]", "[[Boolean circuit]]", "[[Certificate (complexity)]]"]
---

# Computation tree

A computation tree is a representation for the computation steps of a non-deterministic Turing machine on a specified input. A computation tree is a rooted tree of nodes and edges. Each node in the tree represents a single computational state, while each edge represents a transition to the next possible computation. The number of nodes of the tree is the size of the tree and the length of the path from the root to a given node is the depth of the node. The largest depth of an output node is the depth of the tree. The leaves of the tree are called output nodes. 
In a computation tree for a decision problem, each output node is labeled Yes or No. If a tree, T, with an input space X, if 
  
    
      
        x
        ∈
        X
      
    
    
  
 and the path for x ends in node labeled yes, then the input x is accepted. Else it is rejected.
The depth of the computation tree for a given input is the computation time for the Turing machine on that input.
Computation trees have also been used to study the computational complexity of problems in computational geometry and  real number calculations.

## Related

- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Averaging argument]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]
- [[Boolean circuit]]
- [[Certificate (complexity)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Computation_tree