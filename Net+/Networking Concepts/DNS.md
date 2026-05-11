# Overview
- **DNS** a.k.a. **Domain Name System** translates [[Uniform Resource Locater|URLs]]  into [[IP Addresses|IP's]] for the computer, and vice-versa.

# Core Ideas
- Allows us to use "google.com" instead of making us remember it's IP address.
- Can be acceded as a:
	- [[Reverse DNS Lookup]]
	- [[Forward DNS Lookup]]
- Separated into:
	- [[Autoritative DNS server]]
	- [[Non-authoritative DNS server]]
- Follows a set [[DNS Priority|priority]]



# Security
- [[DNS Security Extensions (DNSSEC)]]
	- Digitally signs DNS data to ensure authenticity and integrity
	- Prevents [[DNS Spoofing]] or [[cache poisoning]]
- [[DNS over HTTPS (DoH)]]
	- Hides the "DNS request" nature of the DNS query traffic
	- Prevents eavesdropping and manipulation of data
- [[DNS over TLS (DoL)]]
	- Encrypts the entire DNS query
	- [[TCP]] 853


# Records
- "A": Domain Name to [[IPv4 Addressing|IPv4]]
- "AAAA": Domain Name to [[IPv6 addressing|IPv6]]
- "CNAME": Domain Name to another Domain name (useful when moving a website to a new location)
- "MX": Directs email to mail server
- "NS": Identifies an [[Autoritative DNS server]]
- "PTR": IPv4 into a Domain Name
- "TXT": Adds notes to other records

# Use cases
- Can be used during [[ping]] lookups  to connect to "google.com".
- Can be used during [[traceroute|tracert]] command lookups to search from "google.com".
- Can be used during [[nslookups]] to get the Ip address of a domain.

## Attacks
- [[DNS Spoofing]]: masking a malicious site as a common link to redirect to the site
- [[DNS Poisoning]]: 

## Ports
- Uses [[UDP]] 53 as default, for smaller queries
- Uses [[TCP]] 53 for bigger queries

---
[[Common Ports]]
#ports-and-protocols 