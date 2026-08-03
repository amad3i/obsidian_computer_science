---
title: "Horizontal correlation"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Horizontal_correlation"
wikipedia_categories: ["Bioinformatics"]
related: ["[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]", "[[Actino-ugpB RNA motif]]", "[[Adaptive sampling]]", "[[Algae DNA barcoding]]", "[[Align-m]]", "[[Alignment-free sequence analysis]]"]
---

# Horizontal correlation

Horizontal correlation is a methodology for gene sequence analysis. Rather than referring to one specific technique, horizontal correlation instead encompasses a variety of approaches to sequence analysis that are unified by two specific themes:

Sequence analysis is performed by making comparisons horizontally, along the length of a single genetic sequence; this is in contrast to vertical methods that make comparisons across several different genetic sequences.
The comparisons made generally measure information theoretic quantities such as value of the mutual information function between two regions of the sequence.
The core ideas of the horizontal correlation approach were first presented in a year 2000 paper by Grosse, Herzel, Buldyrev, and Stanley (Grosse, et al. 2000). In this first formulation, Grosse and colleagues sought to characterize a large genetic sequence by dividing the sequence into coding and non-coding regions. Whereas traditional approaches to the coding-vs.-non-coding problem generally relied on sophisticated pattern recognition systems that were first trained on small inputs and then run over the entire sequence (Ohler, et al. 1999), the horizontal correlation approach of Grosse and colleagues worked instead by breaking the sequence into many relatively short sequence fragments, each only 500 base pairs in length. They then sought to characterize each of these fragments as either coding or non-coding. This was accomplished by comparing each size 3 window along the length of a fragment with the first size 3 window in that fragment, then measuring the value of the mutual information function between the two windows. Coding sequences were found to display a stylized pattern of 3-periodicity that non-coding sequences did not. Such a pattern was easy to recognize, and enabled significantly more rapid, more species-independent identification of coding regions (Grosse, et al. 2000).
Since 2000, horizontal correlation methodologies emphasizing the measurement of information theoretic quantities along the length of a gene sequence have been put to widespread use, and have even found application in shotgun sequencing fragment assembly (Otu & Sayood, 2004).

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

- Wikipedia: https://en.wikipedia.org/wiki/Horizontal_correlation