---
title: "Voronoi deformation density"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Voronoi_deformation_density"
wikipedia_categories: ["Computational chemistry", "Computational chemistry stubs"]
related: ["[[CCP4 (file format)]]", "[[Centre for Theoretical and Computational Chemistry]]", "[[Component detection algorithm]]", "[[Computational chemical methods in solid-state physics]]", "[[Computer-assisted structure elucidation]]", "[[Density matrix embedding theory]]", "[[Dynamic Monte Carlo method]]", "[[Embedded atom model]]", "[[Fenske–Hall method]]", "[[International Journal of Quantum Chemistry]]"]
---

# Voronoi deformation density

Voronoi deformation density (VDD) is a method employed in computational chemistry to compute the atomic charge distribution of a molecule in order to provide information about its chemical properties. The method is based on the partitioning of space into non-overlapping atomic areas modelled as Voronoi cells and then computing the deformation density within those cells (i.e. the extent to which electron density differs from that of an unbonded atom).
The VDD charge QA of atom A is computed as the (numerical) integral of the deformation density ∆ρ(r) = ρ(r) – ΣBρB(r) associated with the formation of the molecule from its atoms over the volume of the Voronoi cell of atom A:

  
    
      
        
          Q
          
            A
          
        
        −
        
          ∫
          
            
              Voronoi cell 
            
            A
          
        
        
          
          
        
        ρ
        
          r
        
        −
        
          ∑
          
            B
          
        
        
          ρ
          
            B
          
        
        
          r
        
        
          
          
        
        d
        
          r
        
      
    
    
  

The Voronoi cell of atom A is defined as the compartment of space bounded by the bond midplanes on and perpendicular to all bond axes between nucleus A and its neighboring nuclei (cf. the Wigner–Seitz cells in crystals). The Voronoi cell of atom A is therefore the region of space closer to nucleus A than to any other nucleus. Furthermore, ρ(r) is the electron density of the molecule and ΣBρB(r) the superposition of atomic densities ρB of a fictitious promolecule without chemical interactions that is associated with the situation in which all atoms are neutral.
Note that an atomic charge is not a physical observable. Nevertheless, it has been proven a useful means to compactly describe and analyze the electron density distribution in a molecule, which is important for understanding the behavior of the latter. In this connection, it is an asset of VDD atomic charges QA that they have a rather straightforward and transparent interpretation. Instead of measuring the amount of charge associated with a particular atom A, QA directly monitors how much charge flows, due to chemical interactions, out of (QA > 0) or into (QA < 0) the Voronoi cell of atom A, that is, the region of space that is closer to nucleus A than to any other nucleus.

## Related

- [[CCP4 (file format)]]
- [[Centre for Theoretical and Computational Chemistry]]
- [[Component detection algorithm]]
- [[Computational chemical methods in solid-state physics]]
- [[Computer-assisted structure elucidation]]
- [[Density matrix embedding theory]]
- [[Dynamic Monte Carlo method]]
- [[Embedded atom model]]
- [[Fenske–Hall method]]
- [[International Journal of Quantum Chemistry]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Voronoi_deformation_density