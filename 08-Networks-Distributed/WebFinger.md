---
title: "WebFinger"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/WebFinger"
wikipedia_categories: ["2013 introductions", "Internet protocols"]
related: ["[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]", "[[Binkp]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]"]
---

# WebFinger

WebFinger is a protocol specified by the Internet Engineering Task Force IETF in RFC 7033 that allows for discovery of information about people and things identified by a URI. Information about a person might be discovered via an acct: URI, for example, which is a URI that looks like an email address.
WebFinger is specified as the discovery protocol for OpenID Connect, which is a protocol that allows one to more easily log in to various sites on the Internet.
The WebFinger protocol is used by federated software, such as GNU social (via its use in OStatus), Diaspora, or Mastodon, to discover users on federated nodes and pods, as well as the remoteStorage protocol. The WebFinger protocol does not specify the usage of "template" within the "links" section. That is an extension made by the former oStatus protocol that the Fediverse inherited from. The reasoning for expanding upon this later was justified by wanting to use a different key for a value that isn't an URL but a pattern to create one.
As a historical note, the name "WebFinger" is derived from the old ARPANET Finger protocol, but it is a very different protocol designed for HTTP.
The protocol payload is represented in JSON format with a MIME-Type of  application/jrd+json.

## Related

- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[BEEP]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]
- [[Bidirectional Forwarding Detection]]
- [[Binkp]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/WebFinger