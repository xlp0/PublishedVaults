---
Aliases: DNS, Domain Name System
---

The [[Domain Name System]] ([[Domain Name System|DNS]]) is a hierarchical decentralized naming system that translates human-readable domain names into machine-readable IP addresses. It serves as a crucial component of the internet infrastructure, allowing users to access websites and other online resources by simply typing in domain names instead of having to remember complex IP addresses.

DNS works by maintaining a distributed database of domain names and their corresponding IP addresses. When a user enters a domain name in their web browser, the browser sends a DNS query to the DNS resolver (usually provided by the Internet Service Provider). The resolver then searches its cache for the corresponding IP address. If it doesn't have the information cached, it forwards the query to other DNS servers until it reaches one that can provide the requested information.

The DNS hierarchy consists of multiple levels, starting from the top-level domains (TLDs) such as .com, .org, or .net. Below TLDs are second-level domains (SLDs), which are registered by individuals or organizations for specific purposes. Further subdomains can be created under SLDs to organize websites or services.

DNS also supports various types of records that provide additional information about domains. For example, an A record maps a domain name to an IPv4 address, while an AAAA record maps it to an IPv6 address. Other record types include MX records for email servers, CNAME records for aliasing one domain name to another, and TXT records for storing arbitrary text data.

Besides translating domain names into IP addresses, DNS also plays a role in load balancing and fault tolerance. By using techniques like round-robin DNS or geographic load balancing, multiple IP addresses can be associated with one domain name to distribute traffic across multiple servers or locations.

Overall, the Domain Name System is fundamental to how we navigate and access resources on the internet. It simplifies the process of connecting with websites and other online services by providing an organized naming system that bridges the gap between human-readable domain names and machine-readable IP addresses.stem
