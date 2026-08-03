---
title: "Loop modeling"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Loop_modeling"
wikipedia_categories: ["Bioinformatics", "Protein methods", "Protein structure"]
related: ["[[De novo protein structure prediction]]", "[[Homology modeling]]", "[[Protein structure prediction]]", "[[3D-Jury]]", "[[Backbone-dependent rotamer library]]", "[[CAFASP]]", "[[ChIP-exo]]", "[[ChIP-on-chip]]", "[[Chou–Fasman method]]", "[[Contact order]]"]
---

# Loop modeling

Loop modeling is a problem in protein structure prediction requiring the prediction of the conformations of loop regions in proteins with or without the use of a structural template. Computer programs that solve these problems have been used to research a broad range of scientific topics from ADP to breast cancer. Because protein function is determined by its shape and the physiochemical properties of its exposed surface, it is important to create an accurate model for protein/ligand interaction studies. The problem arises often in homology modeling, where the tertiary structure of an amino acid sequence is predicted based on a sequence alignment to a template, or a second sequence whose structure is known. Because loops have highly variable sequences even within a given structural motif or protein fold, they often correspond to unaligned regions in sequence alignments; they also tend to be located at the solvent-exposed surface of globular proteins and thus are more conformationally flexible. Consequently, they often cannot be modeled using standard homology modeling techniques. More constrained versions of loop modeling are also used in the data fitting stages of solving a protein structure by X-ray crystallography, because loops can correspond to regions of low electron density and are therefore difficult to resolve.
Regions of a structural model that are predicted by non-template-based loop modeling tend to be much less accurate than regions that are predicted using template-based techniques. The extent of the inaccuracy increases with the number of amino acids in the loop. The loop amino acids' side chains dihedral angles are often approximated from a rotamer library, but can worsen the inaccuracy of side chain packing in the overall model. Andrej Sali's homology modeling suite MODELLER includes a facility explicitly designed for loop modeling by a satisfaction of spatial restraints method. All methods require an upload of the PDB file and some require the specification of the loop location.

## Related

- [[De novo protein structure prediction]]
- [[Homology modeling]]
- [[Protein structure prediction]]
- [[3D-Jury]]
- [[Backbone-dependent rotamer library]]
- [[CAFASP]]
- [[ChIP-exo]]
- [[ChIP-on-chip]]
- [[Chou–Fasman method]]
- [[Contact order]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Loop_modeling