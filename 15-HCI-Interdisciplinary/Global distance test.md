---
title: "Global distance test"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Global_distance_test"
wikipedia_categories: ["Bioinformatics", "Computational chemistry"]
related: ["[[Adaptive sampling]]", "[[CAMEO3D]]", "[[CASP]]", "[[Docking (molecular)]]", "[[Folding@home]]", "[[Molecular modelling]]", "[[Phi coefficient]]", "[[Scoring functions for docking]]", "[[Sequential structure alignment program]]", "[[Template modeling score]]"]
---

# Global distance test

The global distance test (GDT), also written as GDT_TS to represent "total score",  is a measure of similarity between two protein structures with known amino acid correspondences (e.g. identical amino acid sequences) but different tertiary structures. It is most commonly used to compare the results of protein structure prediction to the experimentally determined structure as measured by X-ray crystallography, protein NMR, or, increasingly, cryoelectron microscopy. 
The GDT metric was developed by Adam Zemla at Lawrence Livermore National Laboratory and originally implemented in the Local-Global Alignment (LGA) program. It is intended as a more accurate measurement than the common root-mean-square deviation (RMSD) metric - which is sensitive to outlier regions created, for example, by poor modeling of individual loop regions in a structure that is otherwise reasonably accurate. The conventional GDT_TS score is computed over the alpha carbon atoms and is reported as a percentage, ranging from 0 to 100. In general, the higher the GDT_TS score, the more closely a model approximates a given reference structure.
GDT_TS measurements are used as major assessment criteria in the production of results from the Critical Assessment of Structure Prediction (CASP), a large-scale experiment in the structure prediction community dedicated to assessing current modeling techniques. The metric was first introduced as an evaluation standard in the third iteration of the biannual experiment (CASP3) in 1998. Various extensions to the original method have been developed; variations that accounts for the positions of the side chains are known as global distance calculations (GDC).

## Related

- [[Adaptive sampling]]
- [[CAMEO3D]]
- [[CASP]]
- [[Docking (molecular)]]
- [[Folding@home]]
- [[Molecular modelling]]
- [[Phi coefficient]]
- [[Scoring functions for docking]]
- [[Sequential structure alignment program]]
- [[Template modeling score]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Global_distance_test