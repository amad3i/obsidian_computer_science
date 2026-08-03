---
title: "DIMPL"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/DIMPL"
wikipedia_categories: ["Bioinformatics", "Computational biology"]
related: ["[[Adaptive sampling]]", "[[Alignment-free sequence analysis]]", "[[CERNO test]]", "[[Computational biology]]", "[[Computer Atlas of Surface Topography of Proteins]]", "[[Darwin Core]]", "[[De novo transcriptome assembly]]", "[[Ensembl genome database project]]", "[[European Conference on Computational Biology]]", "[[Flux balance analysis]]"]
---

# DIMPL

DIMPL (Discovery of Intergenic Motifs PipeLine) is a bioinformatic pipeline that enables the extraction and selection of bacterial GC-rich intergenic regions (IGRs) that are enriched for structured non-coding RNAs (ncRNAs). The method of enriching bacterial IGRs for ncRNA motif discovery was first reported for a study in "Genome-wide discovery of structured noncoding RNAs in bacteria".
DIMPL pipeline automates the process of total genome analysis by extracting IGRs, filtering them by length and nucleic acid composition, and collecting the data necessary to identify candidate motifs and assign their possible functions. DIMPL pipeline provides reproducible techniques for identifying genomic regions enriched for ncRNA through support vector machine (SVM) classifiers. It can be used to look for nucleic acid and protein motifs, including riboswitch-like elements, upstream open reading frames (uORFs), short open reading frames (sORFs), ribosomal protein leader sequences, selfish genetic elements and other structured RNA motifs of unknown function.
DIMPL uses various sequence analysis resources, including:

Rfam database, as a reference of known RNA families
BLASTX search tool, to eliminate unannotated protein coding regions
INFERNAL package, to search the IGSs sequences
CMfinder, to look for possible RNA secondary structure features
R-scape software and R2R drawing algorithm, to generate the consensus model
RNAcode, to look for the presence of coding regions
GenomeView, to visualize the genetic context of the RNA motif
RNA motifs discovered using DIMPL include HMP-PP riboswitch, icd-II ncRNA motif, carA ncRNA motif, ldh2 ncRNA motif, among others.

## Related

- [[Adaptive sampling]]
- [[Alignment-free sequence analysis]]
- [[CERNO test]]
- [[Computational biology]]
- [[Computer Atlas of Surface Topography of Proteins]]
- [[Darwin Core]]
- [[De novo transcriptome assembly]]
- [[Ensembl genome database project]]
- [[European Conference on Computational Biology]]
- [[Flux balance analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/DIMPL