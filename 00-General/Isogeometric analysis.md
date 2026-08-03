---
title: "Isogeometric analysis"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Isogeometric_analysis"
wikipedia_categories: ["Computer-aided design", "Finite element method"]
related: ["[[Surface triangulation]]", "[[2D geometric model]]", "[[3D Content Retrieval]]", "[[3D floor plan]]", "[[3D Systems]]", "[[AgcXML]]", "[[Algorithms-Aided Design]]", "[[Arc-length method]]", "[[Architectural animation]]", "[[Architectural geometry]]"]
---

# Isogeometric analysis

Isogeometric analysis is a computational approach that offers the possibility of integrating finite element analysis (FEA) into conventional NURBS-based CAD design tools. Currently, it is necessary to convert data between CAD and FEA packages to analyse new designs during development, a difficult task since the two computational geometric approaches are different. Isogeometric analysis employs complex NURBS geometry (the basis of most CAD packages) in the FEA application directly. This allows models to be designed, tested and adjusted in one go, using a common data set.
The pioneers of this technique are Tom Hughes and his group at The University of Texas at Austin. A reference free software implementation of some isogeometric analysis methods is GeoPDEs.  Likewise, other implementations can be found online. For instance, PetIGA is an open framework for high performance isogeometric analysis heavily based on PETSc. In addition, MIGFEM is another IGA code which is implemented in Matlab and supports Partition of Unity enrichment IGA for 2D and 3D fracture. Furthermore, G+Smo is an open C++ library for isogeometric analysis. In particular, FEAP is a finite element analysis program which includes an Isogeometric analysis library FEAP IsoGeometric (Version FEAP84 & Version FEAP85).

## Related

- [[Surface triangulation]]
- [[2D geometric model]]
- [[3D Content Retrieval]]
- [[3D floor plan]]
- [[3D Systems]]
- [[AgcXML]]
- [[Algorithms-Aided Design]]
- [[Arc-length method]]
- [[Architectural animation]]
- [[Architectural geometry]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Isogeometric_analysis