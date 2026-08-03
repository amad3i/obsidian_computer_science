---
title: "Client Hints"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Client_Hints"
wikipedia_categories: ["Hypertext Transfer Protocol headers", "Internet privacy"]
related: ["[[Do Not Track]]", "[[Global Privacy Control]]", "[[HTTP cookie]]", "[[HTTP ETag]]", "[[Third-party cookies]]", "[[2010 Duke University faux sex thesis controversy]]", "[[2014 celebrity nude photo leak]]", "[[2017 Equifax data breach]]", "[[2023 Bangladesh Government website data breach]]", "[[Anonymous blog]]"]
---

# Client Hints

Client Hints is an extension to the HTTP protocol that allows servers to ask the client (usually a web browser)  for information about its configuration. This helps the server tailor its responses to the client; for example, a server can choose to send a smaller image if a client advertises that they have a very small screen. The client can choose to respond to this request by advertising the requested information about itself by sending the data using a specific part of the HTTP protocol called HTTP header fields or by exposing the same information to the JavaScript code being executed on a web page.
Proposed by Google engineers in 2013, Client Hints was designed as a privacy-focused alternative to user-agent headers. This was done as part of an initiative by Google called Privacy Sandbox. User-agent headers are code snippets sent by a client to identify itself to a server. While initially intended for statistical purposes, these headers had increasingly become a tool for tracking users across websites. Client Hints aimed to address this issue by providing a more controlled way to share the same information. Despite the focus on privacy, the initial design of Client Hints faced criticism from other browsers. One of the primary concerns that was brought up was that the protocol could enable new forms of tracking by third-party domains. Third-party domains are web servers not owned by the website that load resources like images and script files. Despite these concerns, Chrome implemented support for Client Hints in August 2020. By 2024, over 75% of web users had browsers that supported Client Hints.
Privacy researchers have since raised concerns that Client Hints is primarily being used by JavaScript code which tracks users. In 2023, a study from KU Leuven and Radboud University found that when examining the top 100,000 websites on the internet, most accesses of Client Hints came from JavaScript code used for tracking and advertising purposes.

## Related

- [[Do Not Track]]
- [[Global Privacy Control]]
- [[HTTP cookie]]
- [[HTTP ETag]]
- [[Third-party cookies]]
- [[2010 Duke University faux sex thesis controversy]]
- [[2014 celebrity nude photo leak]]
- [[2017 Equifax data breach]]
- [[2023 Bangladesh Government website data breach]]
- [[Anonymous blog]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Client_Hints