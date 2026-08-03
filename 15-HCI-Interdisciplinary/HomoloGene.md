---
title: "HomoloGene"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/HomoloGene"
wikipedia_categories: ["Bioinformatics", "Genetics software"]
related: ["[[Gene Designer]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]", "[[Actino-ugpB RNA motif]]", "[[Adaptive sampling]]", "[[Algae DNA barcoding]]", "[[Align-m]]"]
---

# HomoloGene

HomoloGene, a tool of the United States National Center for Biotechnology Information (NCBI), is a system for automated detection of homologs (similarity attributable to descent from a common ancestor) among the annotated genes of several completely sequenced eukaryotic genomes.
The HomoloGene processing consists of the protein analysis from the input organisms. Sequences are compared using blastp, then matched up and put into groups, using a taxonomic tree built from sequence similarity, where closer related organisms are matched up first, and then further organisms are added to the tree. The protein alignments are mapped back to their corresponding DNA sequences, and then distance metrics as molecular distances Jukes and Cantor (1969), Ka/Ks ratio can be calculated.
The sequences are matched up by using a heuristic algorithm for maximizing the score globally, rather than locally, in a bipartite matching (see complete bipartite graph). And then it calculates the statistical significance of each match. Cutoffs are made per position and Ks values are set to prevent false "orthologs" from being grouped together. “Paralogs” are identified by finding sequences that are closer within species than other species.
This resource ceased making updates in 2014.

## Related

- [[Gene Designer]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]
- [[Accession number (bioinformatics)]]
- [[Actino-ugpB RNA motif]]
- [[Adaptive sampling]]
- [[Algae DNA barcoding]]
- [[Align-m]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HomoloGene