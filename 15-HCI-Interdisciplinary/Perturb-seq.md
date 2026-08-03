---
title: "Perturb-seq"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Perturb-seq"
wikipedia_categories: ["Bioinformatics", "Genomics", "Molecular biology techniques", "RNA sequencing"]
related: ["[[ChIP-exo]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[Biochip]]", "[[Chip description file]]", "[[ChIP-on-chip]]", "[[Computational genomics]]", "[[Computational immunology]]", "[[Disease gene identification]]", "[[DNA microarray]]"]
---

# Perturb-seq

Perturb-seq (also known as CRISP-seq and CROP-seq) refers to a high-throughput method of performing single cell RNA sequencing (scRNA-seq) on pooled genetic perturbation screens. Perturb-seq combines multiplexed CRISPR mediated gene inactivations with single cell RNA sequencing to assess comprehensive gene expression phenotypes for each perturbation. Inferring a gene’s function by applying genetic perturbations to knock down or knock out a gene and studying the resulting phenotype is known as reverse genetics. Perturb-seq is a reverse genetics approach that allows for the investigation of phenotypes at the level of the transcriptome, to elucidate gene functions in many cells, in a massively parallel fashion.
The Perturb-seq protocol uses CRISPR technology to inactivate specific genes and DNA barcoding of each guide RNA to allow for all perturbations to be pooled together and later deconvoluted, with assignment of each phenotype to a specific guide RNA. Droplet-based microfluidics platforms (or other cell sorting and separating techniques) are used to isolate individual cells, and then scRNA-seq is performed to generate gene expression profiles for each cell. Upon completion of the protocol, bioinformatics analyses are conducted to associate each specific cell and perturbation with a transcriptomic profile that characterizes the consequences of inactivating each gene.

## Related

- [[ChIP-exo]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[Biochip]]
- [[Chip description file]]
- [[ChIP-on-chip]]
- [[Computational genomics]]
- [[Computational immunology]]
- [[Disease gene identification]]
- [[DNA microarray]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Perturb-seq