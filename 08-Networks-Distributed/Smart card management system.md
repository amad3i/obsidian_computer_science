---
title: "Smart card management system"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Smart_card_management_system"
wikipedia_categories: ["Computer network security", "Public-key cryptography", "Smart cards"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# Smart card management system

A Smart Card Management System (SCMS) is a system for managing smart cards through the life cycle of the smart cards. Thus, the system can issue the smart cards, maintain the smart cards while in use and finally take the smart cards out of use (EOL). Chip/smart cards provide the foundation for secure electronic identity, and can be used to control access to facilities, networks or computers. As the smart cards are security credentials for authenticating the smart card holder (for example using two-factor authentication) the security requirements for a smart card management system are often high and therefore the vendors of these systems are found in the computer security industry.
Smart card management systems are generally implemented as software applications. If the system needs to be accessible by more than one operator or user simultaneously (this is normally the case) the software application is often provided in the form of a server application accessible from several different client systems. An alternative approach is to have multiple synchronized systems.
Smart card management systems connect smart cards to other systems. Which systems the smart card management system must connect to depends on the use case for the smart cards. Typical systems to connect to include:

Connected smart card reader
Unconnected (RFID) smart card reader
Card printer
User directory
Certificate authority
Identity provider
Hardware security module
Physical access control systems
To make a smart card a valid authenticator, it needs to be holding a credential that identifies the smart card holder. There are many different types of credentials, with different features and authenticator assurance levels. It is the smart card management system that typically generates and maintains the credentials. Examples of credentials that are suitable for use with smart cards:

Asymmetric keys, for example PKI (Public Key Infrastructure) or FIDO2 (specified by FIDO Alliance) keys
Symmetric keys, for example EMV keys
OTP (One-time password) generators
Password managers
During the smart card lifecycle, the smart card is changing state (examples of such states include issued, blocked and revoked), the process of taking a smart card from one state to another, is the main responsibility of a smart card management system. Different smart card management systems call these processes by different names. Below a list of the most widely used names of the processes are listed and briefly explained:

Register – adding a smart card to the smart card management system
Issue – issuing or personalizing the smart card for a smart card holder
Initiate – activating the smart card for first use by the smart card holder
Deactivate – putting the smart card on hold in the backend system
Activate – reactivating the smart card from a deactivated state
Lock – also called block; smart card holder access to the smart card is not possible
Unlock – also called unblock; smart card holder access to the smart card is re-enabled
Revoke – credentials on the smart card are made invalid
Retire – the smart card is disconnected from the smart card holder
Delete – the smart card is permanently removed from the system
Unregister – the smart card is removed from the system (but could potentially be reused)
Backup - Backup smart card certificates and selected keys
Restore - Restore smart card certificates and selected keys

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]
- [[Banner grabbing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Smart_card_management_system