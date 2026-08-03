---
title: "Verlet list"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Verlet_list"
wikipedia_categories: ["Computational chemistry", "Computational chemistry stubs", "Molecular dynamics"]
related: ["[[OPLS]]", "[[Protein Local Optimization Program]]", "[[Accessible surface area]]", "[[Car–Parrinello molecular dynamics]]", "[[CCP4 (file format)]]", "[[Cell lists]]", "[[Centre for Theoretical and Computational Chemistry]]", "[[Combining rules]]", "[[Component detection algorithm]]", "[[Computational chemical methods in solid-state physics]]"]
---

# Verlet list

A Verlet list (named after Loup Verlet) is a data structure in molecular dynamics simulations to efficiently maintain a list of all particles within a given cut-off distance of each other.
This method may easily be applied to Monte Carlo simulations. For short-range interactions, a cut-off radius is typically used, beyond which particle interactions are considered "close enough" to zero to be safely ignored. For each particle, a Verlet list is constructed that lists all other particles within the potential cut-off distance, plus some extra distance so that the list may be used for several consecutive Monte Carlo "sweeps" (set of Monte Carlo steps or moves) before being updated. If we wish to use the same Verlet list 
  
    
      
        n
      
    
    
  
 times before updating, then the cut-off distance for inclusion in the Verlet list should be 
  
    
      
        
          R
          
            c
          
        
        2
        n
        d
      
    
    
  
, where 
  
    
      
        
          R
          
            c
          
        
      
    
    
  
 is the cut-off distance of the potential, and 
  
    
      
        d
      
    
    
  
 is the maximum Monte Carlo step (move) of a single particle. Thus, we will spend of order 
  
    
      
        
          N
          
            2
          
        
      
    
    
  
 time to compute the Verlet lists (
  
    
      
        N
      
    
    
  
 is the total number of particles), but are rewarded with 
  
    
      
        n
      
    
    
  
 Monte Carlo "sweeps" of order 
  
    
      
        N
        
          n
          
            2
          
        
      
    
    
  
 instead of 
  
    
      
        N
        N
      
    
    
  
. By optimizing our choice of 
  
    
      
        n
      
    
    
  
 it can be shown that Verlet lists allow converting the 
  
    
      
        O
        
          N
          
            2
          
        
      
    
    
  
 problem of Monte Carlo sweeps to an 
  
    
      
        O
        
          N
          
            5
            
              /
            
            3
          
        
      
    
    
  
 problem.
Using cell lists to identify the nearest neighbors in 
  
    
      
        O
        N
      
    
    
  
 further reduces the computational cost.

## Related

- [[OPLS]]
- [[Protein Local Optimization Program]]
- [[Accessible surface area]]
- [[Car–Parrinello molecular dynamics]]
- [[CCP4 (file format)]]
- [[Cell lists]]
- [[Centre for Theoretical and Computational Chemistry]]
- [[Combining rules]]
- [[Component detection algorithm]]
- [[Computational chemical methods in solid-state physics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Verlet_list