---
title: "Privilege Management Infrastructure"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Privilege_Management_Infrastructure"
wikipedia_categories: ["Communications protocols", "Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[ActivityPub]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[AT Protocol]]"]
---

# Privilege Management Infrastructure

In cryptography Privilege Management is the process of managing user authorisations based on the ITU-T Recommendation X.509. The 2001 edition of X.509  specifies most (but not all) of the components of a Privilege Management Infrastructure (PMI), based on X.509 attribute certificates (ACs). Later editions of X.509 (2005 and 2009) have added further components to the PMI, including a delegation service (in 2005 ) and interdomain authorisation (in the 2009 edition ).
Privilege management infrastructures (PMIs) are to authorisation what public key infrastructures (PKIs) are to authentication. PMIs use attribute certificates (ACs) to hold user privileges, in the form of attributes, instead of public key certificates (PKCs) to hold public keys. PMIs have Sources of Authority (SoAs) and Attribute Authorities (AAs) that issue ACs to users, instead of certification authorities (CAs) that issue PKCs to users. Usually PMIs rely on an underlying PKI, since ACs have to be digitally signed by the issuing AA, and the PKI is used to validate the AA's signature.
An X.509 AC is a generalisation of the well known X.509 public key certificate (PKC), in which the public key of the PKC has been replaced by any set of attributes of the certificate holder (or subject). Therefore, one could in theory use X.509 ACs to hold a user's public key as well as any other attribute of the user. (In a similar vein, X.509 PKCs can also be used to hold privilege attributes of the subject, by adding them to the subject directory attributes extension of an X.509 PKC). However, the life cycle of public keys and user privileges are usually very different, and therefore it isn't usually a good idea to combine both of them in the same certificate. Similarly, the  authority that assigns a privilege to someone is usually different from the authority that certifies someone's public key. Therefore, it isn't usually a good idea to combine the functions of the SoA/AA and the CA in the same trusted authority. PMIs allow privileges and authorisations to be managed separately from keys and authentication.
The first open source implementation of an X.509 PMI was built with funding under the EC PERMIS project, and the software is available from here. A description of the implementation can be found in.
X.509 ACs and PMIs are used today in Grids (see Grid computing), to assign privileges to users, and to carry the privileges around the Grid. In the most popular Grid privilege management system today, called VOMS, user privileges, in the shape of VO memberships and roles, are placed inside an X.509 AC by the VOMS server, signed by the VOMS server, and then embedded in the user's X.509 proxy certificate for carrying around the Grid.
Because of the rise in popularity of XML SOAP based services, SAML attribute assertions are now more popular than X.509 ACs for transporting user attributes. However, they both have similar functionality, which is to strongly bind a set of privilege attributes to a user.

## Related

- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[ActivityPub]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[AT Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Privilege_Management_Infrastructure