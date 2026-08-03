---
title: "Tree (automata theory)"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Tree_(automata_theory)"
wikipedia_categories: ["Automata (computation)", "Formal languages", "Theoretical computer science", "Trees (data structures)"]
related: ["[[Ranked alphabet]]", "[[Tree automaton]]", "[[Tree transducer]]", "[[Random-access Turing machine]]", "[[Regular numerical predicate]]", "[[Turing machine]]", "[[Abstract syntax tree]]", "[[Conference on Implementation and Application of Automata]]", "[[Deterministic pushdown automaton]]", "[[Formal grammar]]"]
---

# Tree (automata theory)

In automata theory, a tree is a particular way of representing a tree structure as sequences of natural numbers. 

For example, each node of the tree is a word over set of natural numbers (
  
    
      
        
          N
        
      
    
    
  
), which helps this definition to be used in automata theory.
A tree is a set T ⊆ 
  
    
      
        
          N
        
      
    
    
  
* such that if t.c ∈ T, with t ∈ 
  
    
      
        
          N
        
      
    
    
  
* and c ∈ 
  
    
      
        
          N
        
      
    
    
  
, then t ∈ T and t.c1 ∈ T for all 0 ≤ c1 < c. The elements of T are known as nodes, and the empty word ε is the (single) root of T. For every t ∈ T, the element t.c ∈ T is a successor of t in direction c. The number of successors of t is called its degree or arity, and represented as d(t). A node is a leaf if it has no successors. If every node of a tree has finitely many successors, then it is called a finitely, otherwise an infinitely branching tree. A path π is a subset of T such that ε ∈ π and for every t ∈ T, either t is a leaf or there exists a unique c ∈ 
  
    
      
        
          N
        
      
    
    
  
 such that t.c ∈ π. A path may be a finite or infinite set. If all paths of a tree are finite then the tree is called finite, otherwise infinite. A tree is called fully infinite if all its paths are infinite. Given an alphabet Σ, a Σ-labeled tree is a pair (T,V), where T is a tree and V: T → Σ maps each node of T to a symbol in Σ. A labeled tree formally defines a commonly used term tree structure. A set of labeled trees is called a tree language.
A tree is called ordered if there is an order among the successors of each of its nodes. The above definition of tree naturally suggests an order among the successors, which can be used to make the tree ranked. 
In the case of ranked alphabets, an extra function Ar: Σ → 
  
    
      
        
          N
        
      
    
    
  
 is defined. This function associates a fixed arity to each symbol of the alphabet. In this case, each t ∈ T has to satisfy Ar(V(t)) = d(t). The trees that satisfy this property are called ranked trees. The trees that do not (necessarily) satisfy that property are called unranked.
For example, the above definition is used in the definition of an infinite tree automaton.

## Related

- [[Ranked alphabet]]
- [[Tree automaton]]
- [[Tree transducer]]
- [[Random-access Turing machine]]
- [[Regular numerical predicate]]
- [[Turing machine]]
- [[Abstract syntax tree]]
- [[Conference on Implementation and Application of Automata]]
- [[Deterministic pushdown automaton]]
- [[Formal grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tree_(automata_theory)