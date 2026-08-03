---
title: "Dynamic programming"
tags: ["cs", "foundations-math", "core"]
domain: Foundations & Math
level: core
source: "https://en.wikipedia.org/wiki/Dynamic_programming"
wikipedia_categories: ["Dynamic programming", "Equations", "Optimal control", "Optimization algorithms and methods", "Systems engineering"]
related: ["[[Bellman equation]]", "[[Recursive economics]]", "[[Alpha–beta pruning]]", "[[Ant colony optimization algorithms]]", "[[Automatic label placement]]", "[[Backtracking line search]]", "[[Backward induction]]", "[[Barzilai–Borwein method]]", "[[Behavior tree]]", "[[Bellman pseudospectral method]]"]
---

# Dynamic programming

Dynamic programming (DP) is both a mathematical optimization method and an algorithmic paradigm. The method was developed by Richard Bellman in the 1950s and has found applications in numerous fields, such as aerospace engineering and economics.
In both contexts it refers to simplifying a complicated problem by breaking it down into simpler sub-problems in a recursive manner. While some decision problems cannot be taken apart this way, decisions that span several points in time do often break apart recursively. Likewise, in computer science, if a problem can be solved optimally by breaking it into sub-problems and then recursively finding the optimal solutions to the sub-problems, then it is said to have optimal substructure.
If sub-problems can be nested recursively inside larger problems, so that dynamic programming methods are applicable, then there is a relation between the value of the larger problem and the values of the sub-problems. In the optimization literature this relationship is called the Bellman equation.

== Overview ==

=== Mathematical optimization ===
In terms of mathematical optimization, dynamic programming usually refers to simplifying a decision by breaking it down into a sequence of decision steps over time.
This is done by defining a sequence of value functions V1, V2, ..., Vn taking y as an argument representing the state of the system at times i from 1 to n.
The definition of Vn(y) is the value obtained in state y at the last time n.
The values Vi at earlier times i = n −1, n − 2, ..., 2, 1 can be found by working backwards, using a recursive relationship called the Bellman equation.
For i = 2, ..., n, Vi−1 at any state y is calculated from Vi by maximizing a simple function (usually the sum) of the gain from a decision at time i − 1 and the function Vi at the new state of the system if this decision is made.
Since Vi has already been calculated for the needed states, the above operation yields Vi−1 for those states.
Finally, V1 at the initial state of the system is the value of the optimal solution. The optimal values of the decision variables can be recovered, one by one, by tracking back the calculations already performed.

=== Control theory ===
In control theory, a typical problem is to find an admissible control 
  
    
      
        
          
            u
          
          
          
        
      
    
    
  
 which causes the system 
  
    
      
        
          
            
              
                x
              
              ˙
            
          
        
        t
        =
        
          g
        
        
          
            
              x
            
            t
            ,
            
              u
            
            t
            ,
            t
          
        
      
    
    
  
 to follow an admissible trajectory 
  
    
      
        
          
            x
          
          
          
        
      
    
    
  
 on a continuous time interval 
  
    
      
        
          t
          
            0
          
        
        ≤
        t
        ≤
        
          t
          
            1
          
        
      
    
    
  
 that minimizes a cost function

  
    
      
        J
        b
        
          
            
              x
            
            
              t
              
                1
              
            
            ,
            
              t
              
                1
              
            
          
        
        
          ∫
          
            
              t
              
                0
              
            
          
          
            
              t
              
                1
              
            
          
        
        f
        
          
            
              x
            
            t
            ,
            
              u
            
            t
            ,
            t
          
        
        
          d
        
        t
      
    
    
  

The solution to this problem is an optimal control law or policy 
  
    
      
        
          
            u
          
          
          
        
        h
        
          x
        
        t
        ,
        t
      
    
    
  
, which produces an optimal trajectory 
  
    
      
        
          
            x
          
          
          
        
      
    
    
  
 and a cost-to-go function 
  
    
      
        
          J
          
          
        
      
    
    
  
. The latter obeys the fundamental equation of dynamic programming:

  
    
      
        
          J
          
            t
          
          
          
        
        
          min
          
            
              u
            
          
        
        
          
            f
            
              
                
                  x
                
                t
                ,
                
                  u
                
                t
                ,
                t
              
            
            
              J
              
                x
              
              
                
                  
                    T
                  
                
              
            
            
              g
            
            
              
                
                  x
                
                t
                ,
                
                  u
                
                t
                ,
                t
              
            
          
        
      
    
    
  

a partial differential equation known as the Hamilton–Jacobi–Bellman equation, in which 
  
    
      
        
          J
          
            x
          
          
          
        
        
          
            
              ∂
              
                J
                
                
              
            
            
              ∂
              
                x
              
            
          
        
        
          
            
              
                
                  
                    ∂
                    
                      J
                      
                      
                    
                  
                  
                    ∂
                    
                      x
                      
                        1
                      
                    
                  
                
              
               
               
               
               
              
                
                  
                    ∂
                    
                      J
                      
                      
                    
                  
                  
                    ∂
                    
                      x
                      
                        2
                      
                    
                  
                
              
               
               
               
               
              …
               
               
               
               
              
                
                  
                    ∂
                    
                      J
                      
                      
                    
                  
                  
                    ∂

*(note truncated for size; full article at the source link below)*

## Related

- [[Bellman equation]]
- [[Recursive economics]]
- [[Alpha–beta pruning]]
- [[Ant colony optimization algorithms]]
- [[Automatic label placement]]
- [[Backtracking line search]]
- [[Backward induction]]
- [[Barzilai–Borwein method]]
- [[Behavior tree]]
- [[Bellman pseudospectral method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_programming