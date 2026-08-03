---
title: "Threading (protein sequence)"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Threading_(protein_sequence)"
wikipedia_categories: ["Bioinformatics", "NP-complete problems", "Protein methods"]
related: ["[[Biclustering]]", "[[CAFASP]]", "[[ChIP-exo]]", "[[ChIP-on-chip]]", "[[Chou–Fasman method]]", "[[De novo protein structure prediction]]", "[[EVA (benchmark)]]", "[[GOR method]]", "[[Homology modeling]]", "[[LiveBench]]"]
---

# Threading (protein sequence)

In molecular biology, protein threading, also known as fold recognition, is a method of protein modeling which is used to model those proteins which have the same fold as proteins of known structures, but do not have homologous proteins with known structure.
It differs from the homology modeling method of structure prediction as it (protein threading) is used for proteins which do not have their homologous protein structures deposited in the Protein Data Bank (PDB), whereas homology modeling is used for those proteins which do. Threading works by using statistical knowledge of the relationship between the structures deposited in the PDB and the sequence of the protein which one wishes to model.
The prediction is made by "threading" (i.e. placing, aligning) each amino acid in the target sequence to a position in the template structure, and evaluating how well the target fits the template. After the best-fit template is selected, the structural model of the sequence is built based on the alignment with the chosen template. Protein threading is based on two basic observations: that the number of different folds in nature is fairly small (approximately 1300); and that 90% of the new structures submitted to the PDB in the past three years have similar structural folds to ones already in the PDB.

## Related

- [[Biclustering]]
- [[CAFASP]]
- [[ChIP-exo]]
- [[ChIP-on-chip]]
- [[Chou–Fasman method]]
- [[De novo protein structure prediction]]
- [[EVA (benchmark)]]
- [[GOR method]]
- [[Homology modeling]]
- [[LiveBench]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Threading_(protein_sequence)