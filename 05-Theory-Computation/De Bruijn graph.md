---
title: "De Bruijn graph"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/De_Bruijn_graph"
wikipedia_categories: ["Automata (computation)", "Directed graphs", "Dynamical systems", "Parametric families of graphs"]
related: ["[[Abstract machine]]", "[[Alternating timed automaton]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Augmented transition network]]", "[[Automata theory]]", "[[Automatic sequence]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[Behavioral modeling]]", "[[Black box model of power converter]]"]
---

# De Bruijn graph

In graph theory, an n-dimensional De Bruijn graph of m symbols is a directed graph representing overlaps between sequences of symbols. It has mn vertices, consisting of all possible length-n sequences of the given symbols; the same symbol may appear multiple times in a sequence. For a set of m symbols S = {s1, …, sm}, the set of vertices is:

  
    
      
        V
        
          S
          
            n
          
        
        {
        
          s
          
            1
          
        
        ,
        …
        ,
        
          s
          
            1
          
        
        ,
        
          s
          
            1
          
        
        ,
        
          s
          
            1
          
        
        ,
        …
        ,
        
          s
          
            1
          
        
        ,
        
          s
          
            2
          
        
        ,
        …
        ,
        
          s
          
            1
          
        
        ,
        …
        ,
        
          s
          
            1
          
        
        ,
        
          s
          
            m
          
        
        ,
        
          s
          
            1
          
        
        ,
        …
        ,
        
          s
          
            2
          
        
        ,
        
          s
          
            1
          
        
        ,
        …
        ,
        
          s
          
            m
          
        
        ,
        …
        ,
        
          s
          
            m
          
        
        ,
        
          s
          
            m
          
        
        }
        .
      
    
    
  

If one of the vertices can be expressed as another vertex by shifting all its symbols by one place to the left and adding a new symbol at the end of this vertex, then the latter has a directed edge to the former vertex. Thus the set of arcs (that is, directed edges) is

  
    
      
        E
        {
        (
        
          t
          
            1
          
        
        ,
        
          t
          
            2
          
        
        ,
        …
        ,
        
          t
          
            n
          
        
        ,
        
          t
          
            2
          
        
        ,
        …
        ,
        
          t
          
            n
          
        
        ,
        
          s
          
            j
          
        
        )
        :
        
          t
          
            i
          
        
        ∈
        S
        ,
        1
        ≤
        i
        ≤
        n
        ,
        1
        ≤
        j
        ≤
        m
        .
      
    
    
  

Although De Bruijn graphs are named after Nicolaas Govert de Bruijn, they were invented independently by both de Bruijn and I. J. Good. Much earlier, Camille Flye Sainte-Marie implicitly used their properties.

## Related

- [[Abstract machine]]
- [[Alternating timed automaton]]
- [[Alternating tree automata]]
- [[Asynchronous circuit]]
- [[Augmented transition network]]
- [[Automata theory]]
- [[Automatic sequence]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[Behavioral modeling]]
- [[Black box model of power converter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/De_Bruijn_graph