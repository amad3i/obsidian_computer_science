---
title: "Optimal apportionment"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Optimal_apportionment"
wikipedia_categories: ["Apportionment (politics)", "Apportionment method criteria", "Fairness criteria", "Mathematical optimization", "Social choice theory"]
related: ["[[Proportional-fair rule]]", "[[Nash welfare rule]]", "[[Utilitarian rule]]", "[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]"]
---

# Optimal apportionment

Optimal apportionment is an approach to apportionment that is based on mathematical optimization.
In a problem of apportionment, there is a resource to allocate, denoted by 
  
    
      
        h
      
    
    
  
. For example, it can be an integer representing the number of seats in a house of representatives. The resource should be allocated between some 
  
    
      
        n
      
    
    
  
 agents. For example, these can be federal states or political parties. The agents have different entitlements, denoted by a vector of fractions 
  
    
      
        
          t
          
            1
          
        
        ,
        …
        ,
        
          t
          
            n
          
        
      
    
    
  
 with a sum of 1. For example, ti can be the fraction of votes won by party i. The goal is to find an allocation - a vector 
  
    
      
        
          a
          
            1
          
        
        ,
        …
        ,
        
          a
          
            n
          
        
      
    
    
  
 with 
  
    
      
        
          ∑
          
            i
            1
          
          
            n
          
        
        
          a
          
            i
          
        
        h
      
    
    
  
.
The ideal share for agent i is his/her quota, defined as 
  
    
      
        
          q
          
            i
          
        
        :=
        
          t
          
            i
          
        
        ⋅
        h
      
    
    
  
. If it is possible to give each agent his/her quota, then the allocation is maximally fair. However, exact fairness is usually unattainable, since the quotas are not integers and the allocations must be integers. There are various approaches to cope with this difficulty  (see mathematics of apportionment).  The optimization-based approach aims to attain, for eacn instance, an allocation that is "as fair as possible" for this instance. An allocation is "fair" if  
  
    
      
        
          a
          
            i
          
        
        
          q
          
            i
          
        
      
    
    
  
 for all agents i, that is, each agent's allocation is exactly proportional to his/her entitlement. in this case, we say that the "unfairness" of the allocation is 0. If this equality must be violated, one can define a measure of "total unfairness", and try to minimize it.

## Related

- [[Proportional-fair rule]]
- [[Nash welfare rule]]
- [[Utilitarian rule]]
- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]
- [[Bauer maximum principle]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Optimal_apportionment