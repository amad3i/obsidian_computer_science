---
title: "Homology modeling"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Homology_modeling"
wikipedia_categories: ["Bioinformatics", "Protein methods", "Protein structure"]
related: ["[[De novo protein structure prediction]]", "[[Loop modeling]]", "[[Protein structure prediction]]", "[[3D-Jury]]", "[[Backbone-dependent rotamer library]]", "[[CAFASP]]", "[[ChIP-exo]]", "[[ChIP-on-chip]]", "[[Chou–Fasman method]]", "[[Contact order]]"]
---

# Homology modeling

Homology modeling, also known as comparative modeling of protein, refers to constructing an atomic-resolution model of the "target" protein from its amino acid sequence and an experimental three-dimensional structure of a related homologous protein (the "template"). Homology modeling relies on the identification of one or more known protein structures likely to resemble the structure of the query sequence, and on the production of a sequence alignment that maps residues in the query sequence to residues in the template sequence. It has been seen that protein structures are more conserved than protein sequences amongst homologues, but sequences falling below a 20% sequence identity can have very different structure.
Evolutionarily related proteins have similar sequences and naturally occurring homologous proteins have similar protein structure.
It has been shown that three-dimensional protein structure is evolutionarily more conserved than would be expected on the basis of sequence conservation alone. 
The sequence alignment and template structure are then used to produce a structural model of the target. Because protein structures are more conserved than DNA sequences, and detectable levels of sequence similarity usually imply significant structural similarity.
The quality of the homology model is dependent on the quality of the sequence alignment and template structure. The approach can be complicated by the presence of alignment gaps (commonly called indels) that indicate a structural region present in the target but not in the template, and by structure gaps in the template that arise from poor resolution in the experimental procedure (usually X-ray crystallography) used to solve the structure. Model quality declines with decreasing sequence identity; a typical model has ~1–2 Å root mean square deviation between the matched Cα atoms at 70% sequence identity but only 2–4 Å agreement at 25% sequence identity. However, the errors are significantly higher in the loop regions, where the amino acid sequences of the target and template proteins may be completely different.
Regions of the model that were constructed without a template, usually by loop modeling, are generally much less accurate than the rest of the model. Errors in side chain packing and position also increase with decreasing identity, and variations in these packing configurations have been suggested as a major reason for poor model quality at low identity. Taken together, these various atomic-position errors are significant and impede the use of homology models for purposes that require atomic-resolution data, such as drug design and protein–protein interaction predictions; even the quaternary structure of a protein may be difficult to predict from homology models of its subunit(s). Nevertheless, homology models can be useful in reaching qualitative conclusions about the biochemistry of the query sequence, especially in formulating hypotheses about why certain residues are conserved, which may in turn lead to experiments to test those hypotheses. For example, the spatial arrangement of conserved residues may suggest whether a particular residue is conserved to stabilize the folding, to participate in binding some small molecule, or to foster association with another protein or nucleic acid.
Homology modeling can produce high-quality structural models when the target and template are closely related, which has inspired the formation of a structural genomics consortium dedicated to the production of representative experimental structures for all classes of protein folds. The chief inaccuracies in homology modeling, which worsen with lower sequence identity, derive from errors in the initial sequence alignment and from improper template selection. Like other methods of structure prediction, current practice in homology modeling is assessed in a biennial large-scale experiment known as the Critical Assessment of Techniques for Protein Structure Prediction, or Critical Assessment of Structure Prediction (CASP).

## Related

- [[De novo protein structure prediction]]
- [[Loop modeling]]
- [[Protein structure prediction]]
- [[3D-Jury]]
- [[Backbone-dependent rotamer library]]
- [[CAFASP]]
- [[ChIP-exo]]
- [[ChIP-on-chip]]
- [[Chou–Fasman method]]
- [[Contact order]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Homology_modeling