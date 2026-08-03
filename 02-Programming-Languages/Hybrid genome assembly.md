---
title: "Hybrid genome assembly"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Hybrid_genome_assembly"
wikipedia_categories: ["Bioinformatics"]
related: ["[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]", "[[Actino-ugpB RNA motif]]", "[[Adaptive sampling]]", "[[Algae DNA barcoding]]", "[[Align-m]]", "[[Alignment-free sequence analysis]]"]
---

# Hybrid genome assembly

In bioinformatics, hybrid genome assembly refers to utilizing various sequencing technologies  to achieve the task of assembling a genome from fragmented, sequenced DNA resulting from shotgun sequencing. Genome assembly presents one of the most challenging tasks in genome sequencing as most modern DNA sequencing technologies can only produce reads  that are, on average, 25–300 base pairs in length. This is orders of magnitude smaller than the average size of a genome (the genome of the octoploid plant Paris japonica is 149 billion base pairs). This assembly is computationally difficult and has some inherent challenges, one of these challenges being that genomes often contain complex tandem repeats of sequences that can be thousands of base pairs in length. These repeats can be long enough that second generation sequencing reads are not long enough to bridge the repeat, and, as such, determining the location of each repeat in the genome can be difficult. Resolving these tandem repeats can be accomplished by utilizing long third generation sequencing reads, such as those obtained using the PacBio RS DNA sequencer. These sequences are, on average, 10,000–15,000 base pairs in length and are long enough to span most repeated regions. Using a hybrid approach to this process can increase the fidelity of assembling tandem repeats by being able to accurately place them along a linear scaffold and make the process more computationally efficient.

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

- Wikipedia: https://en.wikipedia.org/wiki/Hybrid_genome_assembly