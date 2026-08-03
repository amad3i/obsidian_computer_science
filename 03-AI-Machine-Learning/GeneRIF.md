---
title: "GeneRIF"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/GeneRIF"
wikipedia_categories: ["Bioinformatics", "Genomics", "Molecular biology", "Natural language processing"]
related: ["[[Biochip]]", "[[ChIP-exo]]", "[[Disease gene identification]]", "[[Duplex sequencing]]", "[[SNP annotation]]", "[[Whole genome sequencing]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[Base calling]]", "[[Chip description file]]"]
---

# GeneRIF

A GeneRIF or Gene Reference Into Function is a short (255 characters or fewer) statement about the function of a gene.  GeneRIFs provide a simple mechanism for allowing scientists to add to the functional annotation of genes described in the Entrez Gene database. In practice, function is constructed quite broadly.  For example, there are GeneRIFs that discuss the role of a gene in a disease, GeneRIFs that point the viewer towards a review article about the gene, and GeneRIFs that discuss the structure of a gene.  However, the stated intent is for GeneRIFs to be about gene function. Currently over half a million geneRIFs have been created for genes from almost 1000 different species.
GeneRIFs are always associated with specific entries in the Entrez Gene database.  Each GeneRIF has a pointer to the PubMed ID (a type of document identifier) of a scientific publication that provides evidence for the statement made by the GeneRIF.  GeneRIFs are often extracted directly from the document that is identified by the PubMed ID, very frequently from its title or from its final sentence.
GeneRIFs are usually produced by NCBI indexers, but anyone may submit a GeneRIF.
To be processed, a valid Gene ID must exist for the specific gene, or the Gene staff must have assigned an overall Gene ID to the species. The latter case is implemented via records in Gene with the symbol NEWENTRY. Once the Gene ID is identified, only three types of information are required to complete a submission:

a concise phrase describing a function or functions (less than 255 characters in length, preferably more than a restatement of the title of the paper);
a published paper describing that function, implemented by supplying the PubMed ID of a citation in PubMed;
a valid e-mail address (which will remain confidential).

## Related

- [[Biochip]]
- [[ChIP-exo]]
- [[Disease gene identification]]
- [[Duplex sequencing]]
- [[SNP annotation]]
- [[Whole genome sequencing]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[Base calling]]
- [[Chip description file]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/GeneRIF