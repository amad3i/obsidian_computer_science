---
title: "Common Gateway Interface"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Common_Gateway_Interface"
wikipedia_categories: ["Network protocols", "Servers (computing)", "Web 1.0", "Web technology"]
related: ["[[Server Side Includes]]", "[[Stateless protocol]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[AiScaler]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[Application server]]"]
---

# Common Gateway Interface

In computing, Common Gateway Interface (CGI) is an interface specification that enables web servers to execute an external program to process HTTP or HTTPS user requests.
Such programs are often written in a scripting language and are commonly referred to as CGI scripts, but they may include compiled programs.
A typical use case occurs when a web user submits a web form on a web page that uses CGI. The form's data is sent to the web server within an HTTP request with a URL denoting a CGI script. The web server then launches the CGI script in a new computer process, passing the form data to it. The CGI script passes its output, usually in the form of HTML, to the Web server, and the server relays it back to the browser as its response to the browser's request.
Developed in the early 1990s, CGI was the earliest common method available that allowed a web page to be interactive. Due to a necessity to run CGI scripts in a separate process every time the request comes in from a client, various alternatives were developed.

## Related

- [[Server Side Includes]]
- [[Stateless protocol]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[AiScaler]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[Application server]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Common_Gateway_Interface