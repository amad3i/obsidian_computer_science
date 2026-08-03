---
title: "Bisection bandwidth"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bisection_bandwidth"
wikipedia_categories: ["Computer network stubs", "Information theory", "Network management"]
related: ["[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Algorithmic information theory]]", "[[Application-layer framing]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]"]
---

# Bisection bandwidth

In computer networking, a network may be bisected into two equal-sized partitions. The bisection bandwidth of a network topology is the minimum bandwidth available between any two such partitions. Given a graph 
  
    
      
        G
      
    
    
  
 with vertices 
  
    
      
        V
      
    
    
  
, edges 
  
    
      
        E
      
    
    
  
, and edge weights 
  
    
      
        w
      
    
    
  
, the bisection bandwidth of 
  
    
      
        G
      
    
    
  
 is

  
    
      
        B
        B
        G
        =
        
          min
          
            S
            ⊂
            V
            :
            
              |
            
            S
            
              |
            
            
              
                1
                2
              
            
            
              |
            
            V
            
              |
            
          
        
        
        
          ∑
          
            u
            ∈
            S
            ,
            v
            ∉
            S
          
        
        w
        u
        ,
        v
      
    
    
  
.
In other words, the network is bisected s in such a way that the bandwidth between the two partitions is minimum. A network is considered to have full bisection bandwidth if 
  
    
      
        B
        B
        G
        ≥
        
          
            1
            2
          
        
        
          |
        
        V
        
          |
        
      
    
    
  
. Intuitively, full bisection bandwidth means that if all vertices in the network are matched as source-destination pairs, then if all pairs send flow at rate 1 simultaneously, there are no bisection bottlenecks. Therefore, bisection bandwidth accounts for the bottleneck bandwidth of the bisected network as a whole.

## Related

- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Algorithmic information theory]]
- [[Application-layer framing]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bisection_bandwidth