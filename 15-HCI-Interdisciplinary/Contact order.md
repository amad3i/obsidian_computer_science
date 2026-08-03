---
title: "Contact order"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Contact_order"
wikipedia_categories: ["Bioinformatics", "Protein structure"]
related: ["[[3D-Jury]]", "[[Backbone-dependent rotamer library]]", "[[De novo protein structure prediction]]", "[[Docking (molecular)]]", "[[Folding@home]]", "[[Homology modeling]]", "[[Loop modeling]]", "[[Macromolecular docking]]", "[[Protein Data Bank]]", "[[Protein fragment library]]"]
---

# Contact order

The contact order of a protein is a measure of the locality of the inter-amino acid contacts in the protein's native state tertiary structure. It is calculated as the average sequence distance between residues that form native contacts in the folded protein divided by the total length of the protein. Higher contact orders indicate longer folding times, and low contact order has been suggested as a predictor of potential downhill folding, or protein folding that occurs without a free energy barrier. This effect is thought to be due to the lower loss of conformational entropy associated with the formation of local as opposed to nonlocal contacts.
Relative contact order (CO) is formally defined as:

  
    
      
        C
        O
        
          
            1
            
              L
              ⋅
              N
            
          
        
        
          ∑
          
            N
          
        
        Δ
        
          S
          
            i
            ,
            j
          
        
      
    
    
  

where N is the total number of contacts, ΔSi,j is the sequence separation, in residues, between contacting residues i and j, and L is the total number of residues in the protein. The value of contact order typically ranges from 5% to 25% for single-domain proteins, with lower contact order belonging to mainly helical proteins, and higher contact order belonging to proteins with a high beta-sheet content.
Protein structure prediction methods are more accurate in predicting the structures of proteins with low contact orders. This may be partly because low contact order proteins tend to be small, but is likely to be explained by the smaller number of possible long-range residue-residue interactions to be considered during global optimization procedures that minimize an energy function. Even successful structure prediction methods such as the Rosetta method overproduce low-contact-order structure predictions compared to the distributions observed in experimentally determined protein structures.
The percentage of the natively folded contact order can also be used as a measure of the "nativeness" of folding transition states. Phi value analysis in concert with molecular dynamics has produced transition-state models whose contact order is close to that of the folded state in proteins that are small and fast-folding. Further, contact orders in transition states as well as those in native states are highly correlated with overall folding time.
In addition to their role in structure prediction, contact orders can themselves be predicted based on a sequence alignment, which can be useful in classifying the fold of a novel sequence with some degree of homology to known sequences.

## Related

- [[3D-Jury]]
- [[Backbone-dependent rotamer library]]
- [[De novo protein structure prediction]]
- [[Docking (molecular)]]
- [[Folding@home]]
- [[Homology modeling]]
- [[Loop modeling]]
- [[Macromolecular docking]]
- [[Protein Data Bank]]
- [[Protein fragment library]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Contact_order