---
title: "Predicted Aligned Error"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Predicted_Aligned_Error"
wikipedia_categories: ["Bioinformatics", "Computer file formats"]
related: ["[[BGZF]]", "[[European Data Format]]", "[[Gene transfer format]]", "[[General Data Format for Biomedical Signals]]", "[[Multiscale Electrophysiology Format]]", "[[wps]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]"]
---

# Predicted Aligned Error

The Predicted Aligned Error (PAE) is a quantitative output produced by AlphaFold, a protein structure prediction system developed by DeepMind, and other similar programs. During training, the aligned error between two residues, i and j is calculated by aligning the predicted N, Cα, and C atoms of residue i onto the same atoms in the experimental structure in the training data, and measuring the resulting distance between the predicted position of the Cα atom of residue j and the experimental position of that atom. The network is trained to calculate a probability distribution over the aligned error for each pair of residues from which the PAE for each pair can be calculated. Thus, the PAE estimates the expected positional error for each residue in a predicted protein structure given the alignment of the predicted structure onto the experimental structure on a different residue. This measurement helps scientists assess the confidence in the relative positions and orientations of different parts of the predicted protein model.

## Related

- [[BGZF]]
- [[European Data Format]]
- [[Gene transfer format]]
- [[General Data Format for Biomedical Signals]]
- [[Multiscale Electrophysiology Format]]
- [[wps]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Predicted_Aligned_Error