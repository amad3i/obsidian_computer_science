---
title: "Bond order potential"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Bond_order_potential"
wikipedia_categories: ["Computational chemistry", "Computational physics"]
related: ["[[Car–Parrinello molecular dynamics]]", "[[CCPForge]]", "[[Cell lists]]", "[[Computational chemical methods in solid-state physics]]", "[[Computational chemistry]]", "[[Constraint (computational chemistry)]]", "[[Density matrix embedding theory]]", "[[Hartree–Fock method]]", "[[Intracule]]", "[[Linearized augmented-plane-wave method]]"]
---

# Bond order potential

Bond order potential is a class of empirical (analytical) interatomic potentials which is used in molecular dynamics and molecular statics simulations. Examples include the Tersoff potential, the EDIP potential, the Brenner potential, the Finnis–Sinclair potentials, ReaxFF, and the second-moment tight-binding potentials.
They have the advantage over conventional molecular mechanics force fields in that they can, with the same parameters, describe several different bonding states of an atom, and thus to some extent may be able to describe chemical reactions correctly. The potentials were developed partly independently of each other, but share the common idea that the strength of a chemical bond depends on the bonding environment, including the number of bonds and possibly also angles and bond lengths. It is based on the Linus Pauling bond order concept and can be written in the form

  
    
      
        
          V
          
            i
            j
          
        
        
          r
          
            i
            j
          
        
        =
        
          V
          
            
              r
              e
              p
              u
              l
              s
              i
              v
              e
            
          
        
        
          r
          
            i
            j
          
        
        +
        
          b
          
            i
            j
            k
          
        
        
          V
          
            
              a
              t
              t
              r
              a
              c
              t
              i
              v
              e
            
          
        
        
          r
          
            i
            j
          
        
      
    
    
  

This means that the potential is written as a simple pair potential depending on the distance between two atoms 
  
    
      
        
          r
          
            i
            j
          
        
      
    
    
  
, but the strength of this bond is modified by the environment of the atom 
  
    
      
        i
      
    
    
  
 via the bond order 
  
    
      
        
          b
          
            i
            j
            k
          
        
      
    
    
  
. 
  
    
      
        
          b
          
            i
            j
            k
          
        
      
    
    
  
 is a function that in Tersoff-type potentials depends inversely on the number of bonds to the atom 
  
    
      
        i
      
    
    
  
, the bond angles  between sets of three atoms 
  
    
      
        i
        j
        k
      
    
    
  
, and optionally on the relative bond lengths 
  
    
      
        
          r
          
            i
            j
          
        
      
    
    
  
, 
  
    
      
        
          r
          
            i
            k
          
        
      
    
    
  
. In case of only one atomic bond (like in a diatomic molecule), 
  
    
      
        
          b
          
            i
            j
            k
          
        
        1
      
    
    
  
 which corresponds to the strongest and shortest possible bond. The other limiting case, for increasingly many number of bonds within some interaction range, 
  
    
      
        
          b
          
            i
            j
            k
          
        
        →
        0
      
    
    
  
 and the potential turns completely repulsive (as illustrated in the figure to the right).
Alternatively, the potential energy can be written in the embedded atom model form

  
    
      
        
          V
          
            i
            j
          
        
        
          r
          
            i
            j
          
        
        =
        
          V
          
            
              p
              a
              i
              r
            
          
        
        
          r
          
            i
            j
          
        
        −
        D
        
          
            
              ρ
              
                i
              
            
          
        
      
    
    
  

where 
  
    
      
        
          ρ
          
            i
          
        
      
    
    
  
 is the electron density at the location of atom 
  
    
      
        i
      
    
    
  
. These two forms for the energy can be shown to be equivalent (in the special case that the bond-order function 
  
    
      
        
          b
          
            i
            j
            k
          
        
      
    
    
  
 contains no angular dependence).
A more detailed summary of how the bond order concept can be motivated by the second-moment approximation of tight binding and both of these functional forms derived from it can be found in.
The original bond order potential concept has been developed further to include distinct bond orders for sigma bonds and pi bonds in the so-called BOP potentials.
Extending the analytical expression for the bond order of the sigma bonds to include fourth moments of the exact tight binding bond order reveals contributions from both sigma- and pi- bond integrals between neighboring atoms. These pi-bond contributions to the sigma bond order are responsible to stabilize the asymmetric before the symmetric (2x1) dimerized reconstruction of the Si(100) surface.
Also the ReaxFF potential can be considered a bond order potential, although the motivation of its bond order terms is different from that described here.

## Related

- [[Car–Parrinello molecular dynamics]]
- [[CCPForge]]
- [[Cell lists]]
- [[Computational chemical methods in solid-state physics]]
- [[Computational chemistry]]
- [[Constraint (computational chemistry)]]
- [[Density matrix embedding theory]]
- [[Hartree–Fock method]]
- [[Intracule]]
- [[Linearized augmented-plane-wave method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bond_order_potential