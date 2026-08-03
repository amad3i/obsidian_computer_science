---
title: "Multilinear principal component analysis"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Multilinear_principal_component_analysis"
wikipedia_categories: ["Dimension reduction"]
related: ["[[Canonical correspondence analysis]]", "[[Correspondence analysis]]", "[[Detrended correspondence analysis]]", "[[Feature selection]]", "[[Generalized canonical correlation]]", "[[Generalized multidimensional scaling]]", "[[Independent component analysis]]", "[[Kernel principal component analysis]]", "[[Local tangent space alignment]]", "[[Locality-sensitive hashing]]"]
---

# Multilinear principal component analysis

Multilinear principal component analysis (MPCA)  is a multilinear extension of principal component analysis (PCA) that is used to analyze M-way arrays, also informally referred to as "data tensors". M-way arrays may be modeled by 

linear tensor models, such as CANDECOMP/Parafac, or by
multilinear tensor models, such as multilinear  principal component analysis (MPCA) or multilinear (tensor) independent component analysis (MICA).
In 2005, Vasilescu and Terzopoulos introduced the Multilinear PCA terminology as a way to better differentiate between multilinear data models that employed 2nd order statistics  versus higher order statistics to compute a  set of independent components for each mode, such as Multilinear ICA 
Multilinear PCA may be applied to compute the causal factors of data formation, or as signal processing tool on data tensors whose individual observation have either been vectorized, or whose observations are treated as a collection of column/row observations, an "observation as a matrix", and concatenated into a data tensor.  The latter approach is suitable for compression and reducing redundancy in the rows, columns and fibers that are unrelated to the causal factors of data formation. 

Vasilescu and Terzopoulos in their paper "TensorFaces" introduced the  M-mode SVD algorithm which are algorithms misidentified in the literature as the HOSVD
or the Tucker which employ the power method or gradient descent, respectively.  
Vasilescu and Terzopoulos framed the data analysis, recognition and synthesis problems as multilinear tensor problems. Data is viewed as the compositional consequence of several causal factors, that are well suited for multi-modal tensor factor analysis.  The power of the tensor framework was showcased by analyzing human motion joint angles, facial images or textures in the following papers: Human Motion Signatures
(CVPR 2001, ICPR 2002), face recognition – TensorFaces,
(ECCV 2002, CVPR 2003, etc.) and computer graphics – TensorTextures (Siggraph 2004).

## Related

- [[Canonical correspondence analysis]]
- [[Correspondence analysis]]
- [[Detrended correspondence analysis]]
- [[Feature selection]]
- [[Generalized canonical correlation]]
- [[Generalized multidimensional scaling]]
- [[Independent component analysis]]
- [[Kernel principal component analysis]]
- [[Local tangent space alignment]]
- [[Locality-sensitive hashing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multilinear_principal_component_analysis