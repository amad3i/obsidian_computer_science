---
title: "RNA integrity number"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/RNA_integrity_number"
wikipedia_categories: ["Bioinformatics", "Bioinformatics software", "Gene expression", "Molecular biology", "RNA"]
related: ["[[Epitranscriptomic sequencing]]", "[[SNP array]]", "[[3D-Jury]]", "[[Actino-ugpB RNA motif]]", "[[Base calling]]", "[[Biochip]]", "[[ChIP-exo]]", "[[ChIP-on-chip]]", "[[Disease gene identification]]", "[[DNA and RNA codon tables]]"]
---

# RNA integrity number

The RNA integrity number (RIN) is an algorithm for assigning integrity values to RNA measurements.
The integrity of RNA is a major concern for gene expression studies and traditionally has been evaluated using the 28S to 18S rRNA ratio, a method that has been shown to be inconsistent. This inconsistency arises because subjective, human interpretation is necessary to compare the 28S and 18S gel images. The RIN algorithm was devised to overcome this issue. The RIN algorithm is applied to electrophoretic RNA measurements, typically obtained using capillary gel electrophoresis, and based on a combination of different features that contribute information about the RNA integrity to provide a more universal measure. RIN has been demonstrated to be robust and reproducible in studies comparing it to other RNA integrity calculation algorithms, cementing its position as a preferred method of determining the quality of RNA to be analyzed.
A major criticism to RIN is when using with plants or in studies of eukaryotic-prokaryotic cells interactions. The RIN algorithm is unable to differentiate eukaryotic/prokaryotic/chloroplastic ribosomal RNA, creating serious quality index underestimation in such situations.
Another limitation is that RIN reflects the integrity of ribosomal RNAs, which have quite different stability from mRNAs and microRNAs that are more interesting biomarkers. An alternative is to determine the stability of the target RNA or a representative mRNA directly using the differential amplicon (△△Amp) approach developed by the European project SPIDIA.

## Related

- [[Epitranscriptomic sequencing]]
- [[SNP array]]
- [[3D-Jury]]
- [[Actino-ugpB RNA motif]]
- [[Base calling]]
- [[Biochip]]
- [[ChIP-exo]]
- [[ChIP-on-chip]]
- [[Disease gene identification]]
- [[DNA and RNA codon tables]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/RNA_integrity_number