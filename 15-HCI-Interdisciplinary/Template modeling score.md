---
title: "Template modeling score"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Template_modeling_score"
wikipedia_categories: ["Bioinformatics", "Computational chemistry"]
related: ["[[Adaptive sampling]]", "[[CAMEO3D]]", "[[CASP]]", "[[Docking (molecular)]]", "[[Folding@home]]", "[[Global distance test]]", "[[Molecular modelling]]", "[[Phi coefficient]]", "[[Scoring functions for docking]]", "[[Sequential structure alignment program]]"]
---

# Template modeling score

In bioinformatics, the template modeling score or TM-score is a measure of similarity between two protein structures. The TM-score is intended as a more accurate measure of the global similarity of full-length protein structures than the often used RMSD measure. The TM-score indicates the similarity between two structures by a score between 
  
    
      
        0
        ,
        1
      
    
    
  
, where 1 indicates a perfect match between two structures (thus the higher the better). Generally scores below 0.20 corresponds to randomly chosen unrelated proteins whereas structures with a score higher than 0.5 assume roughly the same fold. 
A quantitative study 

shows that proteins of TM-score = 0.5 have a posterior probability of 37% in the same CATH topology family and of 13% in the same SCOP fold family. The probabilities increase rapidly when TM-score > 0.5. The TM-score is designed to be independent of protein lengths.

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
- [[Sequential structure alignment program]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Template_modeling_score