---
title: "Buckingham potential"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Buckingham_potential"
wikipedia_categories: ["Chemical bonding", "Computational chemistry", "Intermolecular forces", "Quantum mechanical potentials", "Theoretical chemistry", "Thermodynamics"]
related: ["[[Lennard-Jones potential]]", "[[Morse-Long-range potential]]", "[[Mie potential]]", "[[Pair potential]]", "[[Combining rules]]", "[[Molecular orbital]]", "[[Ab initio quantum chemistry methods]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Basis set (chemistry)]]", "[[Car–Parrinello molecular dynamics]]"]
---

# Buckingham potential

In theoretical chemistry, the Buckingham potential is a model of intermolecular interactions based on pair potentials developed by Richard Buckingham. The model describes repulsion by the Pauli exclusion principle and attraction by van der Waals forces between all atom pairs that are not directly bonded as a function of the interatomic distance 
  
    
      
        r
      
    
    
  
.
The interatomic potential,

  
    
      
        
          Φ
          
            12
          
        
        r
        =
        A
        exp
         
        
          
            B
            r
          
        
        
          
            C
            
              r
              
                6
              
            
          
        
      
    
    
  

is given by two terms that represent the attraction and the repulsion, respectively. The constants, 
  
    
      
        A
      
    
    
  
, 
  
    
      
        B
      
    
    
  
, and 
  
    
      
        C
      
    
    
  
 are parametrizations of the model tuned to the specific type of each atom pair.
Buckingham proposed this as a simplification of the Lennard-Jones potential, in a theoretical study of the equation of state for gaseous helium, neon and argon.
As explained in Buckingham's original paper and, e.g., in section 2.2.5 of Jensen's text, the repulsion is due to the interpenetration of the closed electron shells. "There is therefore some justification for choosing the repulsive part (of the potential) as an exponential function". The Buckingham potential has been used extensively in simulations of molecular dynamics.
Because the exponential term converges to a constant with decreasing distance, while the 
  
    
      
        
          r
          
            6
          
        
      
    
    
  
 term diverges, the Buckingham potential becomes attractive as 
  
    
      
        r
      
    
    
  
 becomes small. This may be problematic when dealing with a structure with very short interatomic distances, as any nuclei that cross a certain threshold will become strongly (and unphysically) bound to one another at a distance of zero.

## Related

- [[Lennard-Jones potential]]
- [[Morse-Long-range potential]]
- [[Mie potential]]
- [[Pair potential]]
- [[Combining rules]]
- [[Molecular orbital]]
- [[Ab initio quantum chemistry methods]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Basis set (chemistry)]]
- [[Car–Parrinello molecular dynamics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Buckingham_potential