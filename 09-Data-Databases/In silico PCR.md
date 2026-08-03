---
title: "In silico PCR"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/In_silico_PCR"
wikipedia_categories: ["Bioinformatics", "Nucleic acids"]
related: ["[[K-mer]]", "[[Linguistic sequence complexity]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]", "[[Actino-ugpB RNA motif]]", "[[Adaptive sampling]]", "[[Algae DNA barcoding]]"]
---

# In silico PCR

In silico PCR refers to computational tools used to calculate theoretical polymerase chain reaction (PCR) results using a given set of primers (probes) to amplify DNA sequences from a sequenced genome or transcriptome.
These tools are used to optimize the design of primers for target DNA or cDNA sequences. Primer optimization has two goals: efficiency and selectivity. Efficiency involves taking into account such factors as GC-content, efficiency of binding, complementarity, secondary structure, and annealing and melting point (Tm). Primer selectivity requires that the primer pairs not fortuitously bind to random sites other than the target of interest, nor should the primer pairs bind to conserved regions of a gene family. If the selectivity is poor, a set of primers will amplify multiple products besides the target of interest.

The design of appropriate short or long primer pairs is only one goal of PCR product prediction. Other information provided by in silico PCR tools may include determining primer location, orientation, length of each amplicon, simulation of electrophoretic mobility, identification of open reading frames, and links to other web resources.
Many software packages are available offering differing balances of feature set, ease of use, efficiency, and cost. Primer-BLAST is widely used, and freely accessible from the National Center for Biotechnology Information (NCBI) website. On the other hand, FastPCR, a commercial application, allows simultaneous testing of a single primer or a set of primers designed for multiplex target sequences. It performs a fast, gapless alignment to test the complementarity of the primers to the target sequences. Probable PCR products can be found for linear and circular templates using standard or inverse PCR as well as for multiplex PCR. Dicey is free software that outputs in-silico PCR products from primer sets provided in a FASTA file. It is fast (through use of a genome's FM-index) and can account for primer melting temperature and tolerated edit distances between primers and hit locations on the genome. VPCR runs a dynamic simulation of multiplex PCR, allowing for an estimate of quantitative competition effects between multiple amplicons in one reaction.  The UCSC Genome Browser offers isPCR, which provides graphical as well text-file output to view PCR products on more than 100 sequenced genomes.
A primer may bind to many predicted sequences, but only sequences with no or few mismatches (1 or 2, depending on location and nucleotide) at the 3' end of the primer can be used for polymerase extension. The last 10-12 bases at the 3' end of a primer are sensitive to initiation of polymerase extension and general primer stability on the template binding site. The effect of a single mismatch at these last 10 bases at the 3' end of the primer depends on its position and local structure, reducing the primer binding, selectivity, and PCR efficiency.

## Related

- [[K-mer]]
- [[Linguistic sequence complexity]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]
- [[Accession number (bioinformatics)]]
- [[Actino-ugpB RNA motif]]
- [[Adaptive sampling]]
- [[Algae DNA barcoding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/In_silico_PCR