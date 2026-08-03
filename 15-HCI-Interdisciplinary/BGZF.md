---
title: "BGZF"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/BGZF"
wikipedia_categories: ["Bioinformatics", "Computer file formats", "Data compression"]
related: ["[[European Data Format]]", "[[Gene transfer format]]", "[[General Data Format for Biomedical Signals]]", "[[Multiscale Electrophysiology Format]]", "[[Predicted Aligned Error]]", "[[wps]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]"]
---

# BGZF

Blocked GNU Zip Format (BGZF) is a variant of gzip file format that uses block compression, a method that compresses data in independent blocks of content—each of which is a valid gzip file. This design is utilized widely in bioinformatics for genomic data compression. The block-based design provides efficient storage, random access with indexed queries, and parallel processing; allowing large-scale data processing.
The format was developed as part of SAM/BAM specification and SAMtools. It is a core component of the common BAM format (the binary version of the Sequence Alignment Map format) and is also used to compress and index Variant Call Format (VCF), FASTA, and BED files. Because each block is a standard gzip block, a BGZF file can be decompressed by any standard gzip-compatible tool, ensuring backward compatibility. A general purpose compression utility for producing BGZF files bgzip is distributed with HTSlib software library.

## Related

- [[European Data Format]]
- [[Gene transfer format]]
- [[General Data Format for Biomedical Signals]]
- [[Multiscale Electrophysiology Format]]
- [[Predicted Aligned Error]]
- [[wps]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/BGZF