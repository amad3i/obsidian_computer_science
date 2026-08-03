---
title: "Shifted force method"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Shifted_force_method"
wikipedia_categories: ["Computational chemistry", "Molecular dynamics", "Molecular modelling"]
related: ["[[Accessible surface area]]", "[[Combining rules]]", "[[Implicit solvation]]", "[[Molecular dynamics]]", "[[Molecular modeling on GPUs]]", "[[Adaptive sampling]]", "[[Car–Parrinello molecular dynamics]]", "[[Cell lists]]", "[[Constraint (computational chemistry)]]", "[[Docking (molecular)]]"]
---

# Shifted force method

The net electrostatic force acting on a charged particle with index 
  
    
      
        i
      
    
    
  
 contained within a collection of particles is given as:

  
    
      
        
          F
        
        
          r
        
        =
        
          ∑
          
            j
            ≠
            i
          
        
        F
        r
        
          
            
              r
              ^
            
          
        
        
        
        
        ;
        
        
        F
        r
        =
        
          
            
              
                q
                
                  i
                
              
              
                q
                
                  j
                
              
            
            
              4
              π
              
                ε
                
                  0
                
              
              
                r
                
                  2
                
              
            
          
        
      
    
    
  

where 
  
    
      
        
          r
        
      
    
    
  
 is the spatial coordinate, 
  
    
      
        j
      
    
    
  
 is a particle index, 
  
    
      
        r
      
    
    
  
 is the separation distance between particles 
  
    
      
        i
      
    
    
  
 and 
  
    
      
        j
      
    
    
  
, 
  
    
      
        
          
            
              r
              ^
            
          
        
      
    
    
  
 is the unit vector from particle 
  
    
      
        j
      
    
    
  
 to particle 
  
    
      
        i
      
    
    
  
, 
  
    
      
        F
        r
      
    
    
  
 is the force magnitude, and 
  
    
      
        
          q
          
            i
          
        
      
    
    
  
 and 
  
    
      
        
          q
          
            j
          
        
      
    
    
  
 are the charges of particles 
  
    
      
        i
      
    
    
  
 and 
  
    
      
        j
      
    
    
  
, respectively. With the electrostatic force being proportional to 
  
    
      
        
          r
          
            2
          
        
      
    
    
  
, individual particle-particle interactions are long-range in nature, presenting a challenging computational problem in the simulation of particulate systems. To determine the net forces acting on particles, the Ewald or Lekner summation methods are generally employed. One alternative and usually computationally faster technique based on the notion that interactions over large distances (e.g. > 1 nm) are insignificant to the net forces acting in certain systems is the method of spherical truncation. The equations for basic truncation are:

  
    
      
        
          
            F
            
              C
              U
              T
            
          
          r
          =
          
            
              
                
                  
                    
                      
                        
                          
                            q
                            
                              i
                            
                          
                          
                            q
                            
                              j
                            
                          
                        
                        
                          4
                          π
                          
                            ε
                            
                              0
                            
                          
                          
                            r
                            
                              2
                            
                          
                        
                      
                    
                  
                  
                    
                      for 
                    
                    r
                    ≤
                    
                      r
                      
                        c
                      
                    
                  
                
                
                  
                    0
                  
                  
                    
                      for 
                    
                    r
                    
                      r
                      
                        c
                      
                    
                    .
                  
                
              
              
            
          
        
      
    
    
  

where 
  
    
      
        
          r
          
            c
          
        
      
    
    
  
 is the cutoff distance. Simply applying this cutoff method introduces a discontinuity in the force at 
  
    
      
        
          r
          
            c
          
        
      
    
    
  
 that results in particles experiencing sudden impulses when other particles cross the boundary of their respective interaction spheres. In the particular case of electrostatic forces, as the force magnitude is large at the boundary, this unphysical feature can compromise simulation accuracy. A way to correct this problem is to shift the force to zero at 
  
    
      
        
          r
          
            c
          
        
      
    
    
  
, thus removing the discontinuity. This can be accomplished with a variety of functions, but the most simple/computationally efficient approach is to simply subtract the value of the electrostatic force magnitude at the cutoff distance as such:

  
    
      
        
          
            F
            
              S
              F
            
          
          r
          =
          
            
              
                
                  
                    
                      
                        
                          
                            q
                            
                              i
                            
                          
                          
                            q
                            
                              j
                            
                          
                        
                        
                          4
                          π
                          
                            ε
                            
                              0
                            
                          
                          
                            r
                            
                              2
                            
                          
                        
                      
                    
                    
                      
                        
                          
                            q
                            
                              i
                            
                          
                          
                            q
                            
                              j
                            
                          
                        
                        
                          4
                          π
                          
                            ε
                            
                              0
                            
                          
                          
                            r
                            
                              c
                            
                            
                              2
                            
                          
                        
                      
                    
                  
                  
                    
                      for 
                    
                    r
                    ≤
                    
                      r
                      
                        c
                      
                    
                  
                
                
                  
                    0
                  
                  
                    
                      for 
                    
                    r
                    
                      r
                      
                        c
                      
                    
                    .
                  
                
              
              
            
          
        
      
    
    
  

As mentioned before, the shifted force (SF) method is generally suited for systems that do not have net electrostatic interactions that are long-range in nature. This is the case for condensed systems that show electric-field screening effects. Note that anisotropic systems (e.g. interfaces) may not be accurately simulated with the SF method, although an adaption of the SF method for interfaces has been recently suggested. Additionally, note that certain system properties (e.g. energy-dependent observables) will be more greatly influenced by the use of the SF method than others. It is not safe to assume, without reasonable argument, that the SF method can be used to accurately determine a certain property for a given system. If the accuracy of the SF method need be tested, this may be done by testing for convergence (i.e. showing that simulation results do not significantly change with increasing cutoff) or by comparing with results obtained through other electrostatics techniques (such as Ewald) that are known to perform well. As a rough rule of thumb, results obtained with the SF method tend to be sufficiently accurate when the cutoff is at least five times larger than the distance of the near neighbor interactions.
With the SF method, a discontinuity is still present in the derivative of the force, and it may be preferable for ionic liquids to further alter the force equation as to remove that discontinuity.

*(note truncated for size; full article at the source link below)*

## Related

- [[Accessible surface area]]
- [[Combining rules]]
- [[Implicit solvation]]
- [[Molecular dynamics]]
- [[Molecular modeling on GPUs]]
- [[Adaptive sampling]]
- [[Car–Parrinello molecular dynamics]]
- [[Cell lists]]
- [[Constraint (computational chemistry)]]
- [[Docking (molecular)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Shifted_force_method