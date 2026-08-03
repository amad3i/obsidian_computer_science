---
title: "Mie potential"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Mie_potential"
wikipedia_categories: ["Computational chemistry", "Intermolecular forces", "Quantum mechanical potentials", "Thermodynamics"]
related: ["[[Buckingham potential]]", "[[Lennard-Jones potential]]", "[[Morse-Long-range potential]]", "[[Pair potential]]", "[[Combining rules]]", "[[Molecular mechanics]]", "[[1s Slater-type function]]", "[[Ab initio quantum chemistry methods]]", "[[Accessible surface area]]", "[[Activation strain model]]"]
---

# Mie potential

The Mie potential is an interaction potential describing the interactions between particles on the atomic level. It is mostly used for describing intermolecular interactions, but at times also for modeling intramolecular interaction, i.e. bonds.
The Mie potential is named after the German physicist Gustav Mie; yet the history of intermolecular potentials is more complicated. The Mie potential is the generalized case of the Lennard-Jones (LJ) potential, which is perhaps the most widely used pair potential.
The Mie potential 
  
    
      
        V
        r
      
    
    
  
 is a function of 
  
    
      
        r
      
    
    
  
, the distance between two particles, and is written as

  
    
      
        V
        r
        =
        C
        
        ε
        
          
            
              
                
                  
                    σ
                    r
                  
                
              
              
                n
              
            
            
              
                
                  
                    σ
                    r
                  
                
              
              
                m
              
            
          
        
        ,
         
         
         
         
         
         
        1
      
    
    
  

with

  
    
      
        C
        
          
            n
            
              n
              m
            
          
        
        
          
            
              
                n
                m
              
            
          
          
            
              m
              
                n
                m
              
            
          
        
      
    
    
  
 
such that the potential minimum is 
  
    
      
        
          V
          
            m
            i
            n
          
        
        −
        ε
      
    
    
  
.
The Lennard-Jones potential corresponds to the special case where 
  
    
      
        n
        12
      
    
    {\textstyle n=12}
  
 and 
  
    
      
        m
        6
      
    
    {\textstyle m=6}
  
 in Eq. (1). 
In Eq. (1), 
  
    
      
        ε
      
    
    
  
 is the dispersion energy, and 
  
    
      
        σ
      
    
    
  
 indicates the distance at which 
  
    
      
        V
        0
      
    
    
  
, which is sometimes called the "collision radius." The parameter 
  
    
      
        σ
      
    
    {\textstyle \sigma }
  
 is generally indicative of the size of the particles involved in the collision. The parameters 
  
    
      
        n
      
    
    {\textstyle n}
  
 and 
  
    
      
        m
      
    
    {\textstyle m}
  
 characterize the shape of the potential: 
  
    
      
        n
      
    
    {\textstyle n}
  
 describes the character of the repulsion and 
  
    
      
        m
      
    
    {\textstyle m}
  
 describes the character of the attraction.
The attractive exponent 
  
    
      
        m
        6
      
    
    {\textstyle m=6}
  
 is physically justified by the London dispersion force, whereas no justification for a certain value for the repulsive exponent is known. The repulsive steepness parameter 
  
    
      
        n
      
    
    {\textstyle n}
  
 has a significant influence on the modeling of thermodynamic derivative properties, e.g. the compressibility and the speed of sound. Therefore, the Mie potential is a more flexible intermolecular potential than the simpler Lennard-Jones potential.
The Mie potential is used today in many force fields in molecular modeling. Typically, the attractive exponent is chosen to be 
  
    
      
        m
        6
      
    
    {\textstyle m=6}
  
, whereas the repulsive exponent is used as an adjustable parameter during the model fitting.

## Related

- [[Buckingham potential]]
- [[Lennard-Jones potential]]
- [[Morse-Long-range potential]]
- [[Pair potential]]
- [[Combining rules]]
- [[Molecular mechanics]]
- [[1s Slater-type function]]
- [[Ab initio quantum chemistry methods]]
- [[Accessible surface area]]
- [[Activation strain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mie_potential