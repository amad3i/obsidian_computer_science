---
title: "CRAM (file format)"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/CRAM_(file_format)"
wikipedia_categories: ["Bioinformatics", "Biological sequence format", "Science and technology in Cambridgeshire", "South Cambridgeshire District"]
related: ["[[Ensembl genome database project]]", "[[Identifiers.org]]", "[[MIRIAM Registry]]", "[[Pfam]]", "[[UniProt]]", "[[BED (file format)]]", "[[FASTA format]]", "[[FASTQ format]]", "[[Gene transfer format]]", "[[General feature format]]"]
---

# CRAM (file format)

Compressed Reference-oriented Alignment Map (CRAM) is a compressed columnar file format for storing biological sequences aligned to a reference sequence, initially devised by Markus Hsi-Yang Fritz et al.
CRAM was designed to be an efficient reference-based alternative to the Sequence Alignment Map (SAM) and Binary Alignment Map (BAM) file formats.  It optionally uses a genomic reference to describe differences between the aligned sequence fragments and the reference sequence, reducing storage costs.  Additionally each column in the SAM format is separated into its own blocks, improving compression ratio.  CRAM files typically vary from 30 to 60% smaller than BAM, depending on the data held within them.
Implementations of CRAM exist in htsjdk, htslib, JBrowse, and Scramble.
The file format specification is maintained by the Global Alliance for Genomics and Health (GA4GH) with the specification document available from the EBI cram toolkit page.

## Related

- [[Ensembl genome database project]]
- [[Identifiers.org]]
- [[MIRIAM Registry]]
- [[Pfam]]
- [[UniProt]]
- [[BED (file format)]]
- [[FASTA format]]
- [[FASTQ format]]
- [[Gene transfer format]]
- [[General feature format]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CRAM_(file_format)