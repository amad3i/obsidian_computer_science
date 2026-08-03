---
title: "TransferJet"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/TransferJet"
wikipedia_categories: ["Computer-related introductions in 2008", "Electrical connectors", "Interfaces", "Network protocols", "Sony hardware"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# TransferJet

TransferJet is a close proximity wireless transfer technology initially proposed by Sony and demonstrated publicly in early 2008. By touching (or bringing very close together) two electronic devices, TransferJet allows high speed exchange of data. The concept of TransferJet consists of a touch-activated interface which can be applied for applications requiring high-speed data transfer between two devices in a peer-to-peer mode without the need for external physical connectors.
TransferJet's maximum physical layer transmission rate is 560 Mbit/s. After allowing for error correction and other protocol overhead, the effective maximum throughput is 375 Mbit/s. TransferJet will adjust the data rate downward according to the wireless environment, thereby maintaining a robust link even when the surrounding wireless condition fluctuates.
TransferJet has the capability of identifying the unique MAC addresses of individual devices, enabling users to choose which devices can establish a connection. By allowing only devices inside the household, for example, one can prevent data theft from strangers while riding a crowded train. If, on the other hand, one wishes to connect the device with any other device at a party, this can be done by simply disabling the filtering function.
TransferJet uses the same frequency spectrum as UWB, but occupies only a section of this band available as a common worldwide channel. Since the RF power is kept under -70 dBm/MHz, it can operate in the same manner as that of UWB devices equipped with DAA functionality. In addition, this low power level also ensures that there will be no interference to other wireless systems, including other TransferJet systems, operating nearby.
By reducing the RF power and spatial reach down to a few centimeters (about an inch or less), a TransferJet connection in its most basic mode does not require any initial setup procedure by the user for either device, and the action of spontaneously touching one device with another will automatically trigger the data transfer. More complex usage scenarios will require various means to select the specific data to send as well as the location to store (or method to process) the received data.
TransferJet utilizes a newly developed TransferJet Coupler based on the principle of electric induction field as opposed to radiation field for conventional antennas. The functional elements of a generic TransferJet Coupler consist of a coupling electrode or plate, a resonant stub and ground. Compared to conventional radiating antennas, the TransferJet Coupler achieves higher transmission gain and more efficient coupling in the near-field while providing sharp attenuation at longer distances. Because the Coupler generates longitudinal electric fields, there is no polarization and the devices can be aligned at any angle.
TransferJet Specifications

Although sometimes confused with Near Field Communication, TransferJet depends on an entirely different technology and is also generally targeted for different usage scenarios focusing on high-speed data transfer. Thus these two systems will not interfere with each other and can even co-exist in the same location, as already implemented in certain products.
Other recent products combine TransferJet with wireless power to allow both data transfer and wireless charging capability simultaneously in the same location. TransferJet, NFC and wireless power are the three major near-field (contact-less) technologies that are expected to eliminate the physical connections and cables currently required to interface devices with each other.
Comparison with NFC

The TransferJet Consortium was established in July 2008 to advance and promote the TransferJet Format, by developing the technical specifications and compliance testing procedures as well as creating a market for TransferJet-compliant, interoperable products. In September 2011, the consortium was registered as an independent non-profit industry association. As of June 2015, the Consortium is led by five Promoter companies, consisting of: JRC, NTT, Olympus, Sony (consortium administrator), and Toshiba. The Consortium currently also has around thirty Adopter companies. The TransferJet regular typeface and TransferJet logos are trademarks managed and licensed by the TransferJet Consortium.
Commercial products have been introduced since January 2010 and the initial product categories include digital cameras, laptop PCs, USB cradle accessories, USB dongle accessories and office/business equipment. Compliance testing equipment is provided by Agilent technologies and certification services are offered by Allion Test Labs. The first commercially available TransferJet development platform for embedded systems was launched by Icoteq Ltd in February 2015. Smartphones with integrated TransferJet functionality were launched in June 2015 from Fujitsu, and Bkav. Other product vendors include Buffalo and E-Globaledge.
TransferJet X is a new second-generation TransferJet specification capable of data transfer speeds of 13.1 Gbit/sec and above, or about 20 times the speed of current TransferJet. This specification uses the 60 GHz band and requires only 2 msec or less to establish a connection prior to the actual data transfer, thereby enabling the exchange of large content files even in the short amount of time it takes, for example, for a person to walk through a wicket gate. The TransferJet Consortium is currently defining the details of the TransferJet X ecosystem, based on the IEEE 802.15.3e standard completed and published in June 2017. The HRCP Research and Development Partnership, established in 2016, is developing an SoC solution for implementing TransferJet X in a variety of products and services to be released starting around 2020.

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/TransferJet