---
title: "N50, L50, and related statistics"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics"
wikipedia_categories: ["Bioinformatics", "Genomics"]
related: ["[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[Biochip]]", "[[Chip description file]]", "[[ChIP-exo]]", "[[Computational genomics]]", "[[Computational immunology]]", "[[Disease gene identification]]", "[[Duplex sequencing]]", "[[Eimear Kenny]]"]
---

# N50, L50, and related statistics

In computational biology, N50 and L50 are statistics of a set of contig or scaffold lengths.  The N50 is similar to a mean or median of lengths, but has greater weight given to the longer contigs.  It is used widely in genome assembly, especially in reference to contig lengths within a draft assembly.  There are also the related U50, UL50, UG50, UG50%, N90, NG50, and D50 statistics.
To provide a better assessment of assembly output for viral and microbial datasets, a new metric called U50 should be used. The U50 identifies unique, target-specific contigs by using a reference genome as baseline, aiming at circumventing some limitations that are inherent to the N50 metric. The use of the U50 metric allows for a more accurate measure of assembly performance by analyzing only the unique, non-overlapping contigs. Most viral and microbial sequencing have high background noise (i.e., host and other non-targets), which contributes to having a skewed, misrepresented N50 value - this is corrected by U50.

## Related

- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[Biochip]]
- [[Chip description file]]
- [[ChIP-exo]]
- [[Computational genomics]]
- [[Computational immunology]]
- [[Disease gene identification]]
- [[Duplex sequencing]]
- [[Eimear Kenny]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics