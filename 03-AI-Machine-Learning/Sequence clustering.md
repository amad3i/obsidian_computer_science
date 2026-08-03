---
title: "Sequence clustering"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Sequence_clustering"
wikipedia_categories: ["Bioinformatics"]
related: ["[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]", "[[Actino-ugpB RNA motif]]", "[[Adaptive sampling]]", "[[Algae DNA barcoding]]", "[[Align-m]]", "[[Alignment-free sequence analysis]]"]
---

# Sequence clustering

In bioinformatics, sequence clustering algorithms attempt to group biological sequences that are somehow related.  The sequences can be either of genomic, "transcriptomic" (ESTs) or protein origin.
For proteins, homologous sequences are typically grouped into families.  For EST data, clustering is important to group sequences originating from the same gene before the ESTs are assembled to reconstruct the original mRNA.
Some clustering algorithms use single-linkage clustering, constructing a transitive closure of sequences with a similarity over a particular threshold. UCLUST and CD-HIT use a greedy algorithm that identifies a representative sequence for each cluster and assigns a new sequence to that cluster if it is sufficiently similar to the representative; if a sequence is not matched then it becomes the representative sequence for a new cluster. The similarity score is often based on sequence alignment. Sequence clustering is often used to make a non-redundant set of representative sequences.
Sequence clusters are often synonymous with (but not identical to) protein families. Determining a representative tertiary structure for each sequence cluster is the aim of many structural genomics initiatives.

## Related

- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]
- [[Accession number (bioinformatics)]]
- [[Actino-ugpB RNA motif]]
- [[Adaptive sampling]]
- [[Algae DNA barcoding]]
- [[Align-m]]
- [[Alignment-free sequence analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sequence_clustering