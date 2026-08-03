---
title: "COSMO solvation model"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/COSMO_solvation_model"
wikipedia_categories: ["Computational chemistry"]
related: ["[[1s Slater-type function]]", "[[Ab initio quantum chemistry methods]]", "[[Accessible surface area]]", "[[Activation strain model]]", "[[Adaptive sampling]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Alexander Boldyrev]]", "[[Basis set (chemistry)]]", "[[Bette Korber]]", "[[Bond order potential]]"]
---

# COSMO solvation model

COSMO (COnductor-like Screening MOdel) is a calculation method for determining the electrostatic interaction of a molecule with a solvent. COSMO is a dielectric continuum model (a.k.a. continuum solvation model). These models can be used in computational chemistry to model solvation effects. COSMO has become a popular method of these solvation models in recent years. The COSMO formalism is similar to the method proposed earlier by Hoshi et al. The COSMO approach is based – as many other dielectric continuum models – on the surface segmentation of a molecule surface (usually referred to as 'solvent accessible surface' SAS approach). 
Continuum solvation models – such as COSMO – treat each solvent as a continuum with a permittivity 
  
    
      
        ε
      
    
    
  
. Continuum solvation models approximate the solvent by a dielectric continuum, surrounding the solute molecules outside of a molecular cavity. In most cases it is constructed as an assembly of atom-centered spheres with radii approximately 20% larger than the Van der Waals radius. For the actual calculation the cavity surface is approximated by segments, e.g., hexagons, pentagons, or triangles.
Unlike other continuum solvation models, COSMO derives the polarization charges of the continuum, caused by the polarity of the solute, from a scaled-conductor approximation. If the solvent were an ideal conductor the electric potential on the cavity surface must disappear. If the distribution of the electric charge in the molecule is known, e.g. from quantum chemistry, then it is possible to calculate the charge 
  
    
      
        
          q
          
          
        
      
    
    
  
 on the surface segments. For solvents with finite dielectric constant this charge 
  
    
      
        q
      
    
    
  
 is lower by approximately a factor 
  
    
      
        f
        ε
      
    
    
  
:

  
    
      
        q
        f
        ε
        
          q
          
          
        
        .
      
    
    
  

The factor 
  
    
      
        f
        ε
      
    
    
  
 is approximately

  
    
      
        f
        ε
        =
        
          
            
              ε
              1
            
            
              ε
              x
            
          
        
        ,
      
    
    
  

where the value of 
  
    
      
        x
      
    
    
  
 should be set to 0.5 for neutral molecules and to 0.0 for ions, see original derivation. The value of 
  
    
      
        x
      
    
    
  
 is erroneously set to 0 in the popular C-PCM reimplementation of COSMO in Gaussian.
From the thus determined solvent charges 
  
    
      
        q
      
    
    
  
 and the known charge distribution of the molecule, the energy of the interaction between the solvent and the solute molecule can be calculated.
The COSMO method can be used for all methods in theoretical chemistry where the charge distribution of a molecule can be determined, for example semiempirical calculations, Hartree–Fock-method calculations or density functional theory (quantum physics) calculations.

## Related

- [[1s Slater-type function]]
- [[Ab initio quantum chemistry methods]]
- [[Accessible surface area]]
- [[Activation strain model]]
- [[Adaptive sampling]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Alexander Boldyrev]]
- [[Basis set (chemistry)]]
- [[Bette Korber]]
- [[Bond order potential]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/COSMO_solvation_model