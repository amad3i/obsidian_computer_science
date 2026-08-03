---
title: "Sequential structure alignment program"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Sequential_structure_alignment_program"
wikipedia_categories: ["Bioinformatics", "Computational chemistry"]
related: ["[[Adaptive sampling]]", "[[CAMEO3D]]", "[[CASP]]", "[[Docking (molecular)]]", "[[Folding@home]]", "[[Global distance test]]", "[[Molecular modelling]]", "[[Phi coefficient]]", "[[Scoring functions for docking]]", "[[Template modeling score]]"]
---

# Sequential structure alignment program

The sequential structure alignment program (SSAP) in chemistry, physics, and biology is a method that uses double dynamic programming to produce a structural alignment based on atom-to-atom vectors in structure space. Instead of the alpha carbons typically used in structural alignment, SSAP constructs its vectors from the beta carbons  for all residues except glycine, a method which thus takes into account the rotameric state of each residue as well as its location along the backbone. SSAP works by first constructing a series of inter-residue distance vectors between each residue and its nearest non-contiguous neighbors on each protein. A series of matrices are then constructed containing the vector differences between neighbors for each pair of residues for which vectors were constructed. Dynamic programming applied to each resulting matrix determines a series of optimal local alignments which are then summed into a "summary" matrix to which dynamic programming is applied again to determine the overall structural alignment.
SSAP originally produced only pairwise alignments but has since been extended to multiple alignments as well. It has been applied in an all-to-all fashion to produce a hierarchical fold classification scheme known as CATH (Class, Architecture, Topology, Homology),. which has been used to construct the CATH Protein Structure Classification database.
Generally, SSAP scores above 80 are associated with highly similar structures. Scores between 70 and 80 indicate a similar fold with minor variations. Structures yielding a score between 60 and 70 do not generally contain the same fold, but usually belong to the same protein class with common structural motifs.

## Related

- [[Adaptive sampling]]
- [[CAMEO3D]]
- [[CASP]]
- [[Docking (molecular)]]
- [[Folding@home]]
- [[Global distance test]]
- [[Molecular modelling]]
- [[Phi coefficient]]
- [[Scoring functions for docking]]
- [[Template modeling score]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sequential_structure_alignment_program