---
title: "Graph cut optimization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Graph_cut_optimization"
wikipedia_categories: ["Combinatorial optimization", "Computational problems in graph theory", "Computer vision"]
related: ["[[Graph cuts in computer vision and artificial intelligence]]", "[[Travelling salesman problem]]", "[[3D body scanning]]", "[[3D Morphable Model]]", "[[3D pose estimation]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D selfie]]", "[[A- search algorithm]]", "[[Active appearance model]]"]
---

# Graph cut optimization

Graph cut optimization is a combinatorial optimization method applicable to a family of functions of discrete variables, named after the concept of cut in the theory of flow networks. Thanks to the max-flow min-cut theorem, determining the minimum cut over a graph representing a flow network is equivalent to computing the maximum flow over the network. Given a pseudo-Boolean function 
  
    
      
        f
      
    
    
  
, if it is possible to construct a flow network with positive weights such that

each cut 
  
    
      
        C
      
    
    
  
 of the network can be mapped to an assignment of variables 
  
    
      
        
          x
        
      
    
    
  
 to 
  
    
      
        f
      
    
    
  
 (and vice versa), and
the cost of 
  
    
      
        C
      
    
    
  
 equals 
  
    
      
        f
        
          x
        
      
    
    
  
 (up to an additive constant)
then it is possible to find the global optimum of 
  
    
      
        f
      
    
    
  
 in polynomial time by computing a minimum cut of the graph. The mapping between cuts and variable assignments is done by representing each variable with one node in the graph and, given a cut, each variable will have a value of 0 if the corresponding node belongs to the component connected to the source, or 1 if it belong to the component connected to the sink.
Not all pseudo-Boolean functions can be represented by a flow network, and in the general case the global optimization problem is NP-hard. There exist sufficient conditions to characterise families of functions that can be optimised through graph cuts, such as submodular quadratic functions. Graph cut optimization can be extended to functions of discrete variables with a finite number of values, that can be approached with iterative algorithms with strong optimality properties, computing one graph cut at each iteration.
Graph cut optimization is an important tool for inference over graphical models such as Markov random fields or conditional random fields, and it has applications in computer vision problems such as image segmentation, denoising, registration and stereo matching.

## Related

- [[Graph cuts in computer vision and artificial intelligence]]
- [[Travelling salesman problem]]
- [[3D body scanning]]
- [[3D Morphable Model]]
- [[3D pose estimation]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D selfie]]
- [[A- search algorithm]]
- [[Active appearance model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graph_cut_optimization