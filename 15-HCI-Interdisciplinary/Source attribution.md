---
title: "Source attribution"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Source_attribution"
wikipedia_categories: ["Computational biology", "Epidemiology"]
related: ["[[Adaptive sampling]]", "[[African Society for Bioinformatics and Computational Biology]]", "[[AIDA interactive educational freeware diabetes simulator]]", "[[Alignment-free sequence analysis]]", "[[Alternative Splicing Annotation Project]]", "[[Asian Young Researchers Conference on Computational and Omics Biology]]", "[[Attack rate]]", "[[Base rate]]", "[[Bette Korber]]", "[[Biocomplexity Institute of Virginia Tech]]"]
---

# Source attribution

In the field of epidemiology, source attribution refers to a category of methods with the objective of reconstructing the transmission of an infectious disease from a specific source, such as a population, individual, or location.  For example, source attribution methods may be used to trace the origin of a new pathogen that recently crossed from another host species into humans, or from one geographic region to another.  It may be used to determine the common source of an outbreak of a foodborne infectious disease, such as a contaminated water supply.  Finally, source attribution may be used to estimate the probability that an infection was transmitted from one specific individual to another, i.e., "who infected whom".
Source attribution can play an important role in public health surveillance and  management of infectious disease outbreaks.  In practice, it tends to be a problem of statistical inference, because transmission events are seldom observed directly and may have occurred in the distant past.  Thus, there is an unavoidable level of uncertainty when reconstructing transmission events from residual evidence, such as the spatial distribution of the disease.  As a result, source attribution models often employ Bayesian methods that can accommodate substantial uncertainty in model parameters.
Molecular source attribution is a subfield of source attribution that uses the molecular characteristics of the pathogen — most often its nucleic acid genome — to reconstruct transmission events.  Many infectious diseases are routinely detected or characterized through genetic sequencing, which can be faster than culturing isolates in a reference laboratory and can identify specific strains of the pathogen at substantially higher precision than laboratory assays, such as antibody-based assays or drug susceptibility tests.  On the other hand, analyzing the genetic (or whole genome) sequence data requires specialized computational methods to fit models of transmission.  Consequently, molecular source attribution is a highly interdisciplinary area of molecular epidemiology that incorporates concepts and skills from mathematical statistics and modeling, microbiology, public health and computational biology.
There are generally two ways that molecular data are used for source attribution.  First, infections can be categorized into different "subtypes" that each corresponds to a unique molecular variety, or a cluster of similar varieties.  Source attribution can then be inferred from the similarity of subtypes.  Individual infections that belong to the same subtype are more likely to be related epidemiologically, including direct source-recipient transmission, because they have not substantially evolved away from their common ancestor.  Similarly, we assume the true source population will have frequencies of subtypes that are more similar to the recipient population, relative to other potential sources.  Second, molecular (genetic) sequences from different infections can be directly compared to reconstruct a phylogenetic tree, which represents how they are related by common ancestors.  The resulting phylogeny can approximate the transmission history, and a variety of methods have been developed to adjust for confounding factors.
Due to the associated stigma and the criminalization of transmission for specific infectious diseases, molecular source attribution at the level of individuals can be a controversial use of data that was originally collected in a healthcare setting, with potentially severe legal consequences for individuals who become identified as putative sources.  In these contexts, the development and application of molecular source attribution techniques may involve trade-offs between public health responsibilities and individual rights to data privacy.

## Related

- [[Adaptive sampling]]
- [[African Society for Bioinformatics and Computational Biology]]
- [[AIDA interactive educational freeware diabetes simulator]]
- [[Alignment-free sequence analysis]]
- [[Alternative Splicing Annotation Project]]
- [[Asian Young Researchers Conference on Computational and Omics Biology]]
- [[Attack rate]]
- [[Base rate]]
- [[Bette Korber]]
- [[Biocomplexity Institute of Virginia Tech]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Source_attribution