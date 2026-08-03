---
title: "Data re-identification"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_re-identification"
wikipedia_categories: ["Anonymity", "Information governance", "Internet privacy", "Privacy"]
related: ["[[Anonymous blog]]", "[[HTTP cookie]]", "[[Reputation management]]", "[[Web tracking]]", "[[2010 Duke University faux sex thesis controversy]]", "[[2014 celebrity nude photo leak]]", "[[2017 Equifax data breach]]", "[[2023 Bangladesh Government website data breach]]", "[[Ageless Linux]]", "[[Behavioral retargeting]]"]
---

# Data re-identification

Data re-identification or de-anonymization is the practice of matching anonymous data (also known as de-identified data) with publicly available information, or auxiliary data, in order to discover the person to whom the data belongs. This is a concern because companies with privacy policies, health care providers, and financial institutions may release the data they collect after the data has gone through the de-identification process.
The de-identification process involves masking, generalizing or deleting both direct and indirect identifiers; the definition of this process is not universal. Information in the public domain, even seemingly anonymized, may thus be re-identified in combination with other pieces of available data and basic computer science techniques. The Protection of Human Subjects ('Common Rule'), a collection of multiple U.S. federal agencies and departments including the U.S. Department of Health and Human Services, warn that re-identification is becoming gradually easier because of "big data"—the abundance and constant collection and analysis of information along with the evolution of technologies and the advances of algorithms. However, others have claimed that de-identification is a safe and effective data liberation tool and do not view re-identification as a concern.
More and more data are becoming publicly available over the Internet. These data are released after applying some anonymization techniques like removing personally identifiable information (PII) such as names, addresses and social security numbers to ensure the sources' privacy. This assurance of privacy allows the government to legally share limited data sets with third parties without requiring written permission. Such data has proved to be very valuable for researchers, particularly in health care.
GDPR-compliant pseudonymization seeks to reduce the risk of re-identification through the use of separately kept "additional information". The approach is based on an expert evaluation of a dataset to designate some identifiers as "direct" and some as "indirect." Proponents of this approach argue that re-identification can be avoided by limiting access to "additional information" that is kept separately by the controller. The theory is that access to separately kept "additional information" is required for re-identification, attribution of data to a specific data subject can be limited by the controller to support lawful purposes only. This approach is controversial, as it fails if there are additional datasets that can be used for re-identification. Such additional datasets may be unknown to those certifying the GDPR-compliant pseudonymization, or may not at exist at the time of the pseudonymization but may come into existence at some point in the future.

## Related

- [[Anonymous blog]]
- [[HTTP cookie]]
- [[Reputation management]]
- [[Web tracking]]
- [[2010 Duke University faux sex thesis controversy]]
- [[2014 celebrity nude photo leak]]
- [[2017 Equifax data breach]]
- [[2023 Bangladesh Government website data breach]]
- [[Ageless Linux]]
- [[Behavioral retargeting]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_re-identification