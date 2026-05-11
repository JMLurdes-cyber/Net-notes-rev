Whenever [[DNS]] makes a query, it will check if the Domain is in the step going downwards in this list. If that doesn't check, it will go to the next one:
1. **Host**: File found in any OS that has a list of [[Uniform Resource Locater|Domains]] and their [[IP Addresses|IP Counterparts]]
2. **DNS cache**: Memory that saves the Domains until the [[TTL]] expires
3. **Local DNS resolver**: DNS server found in an internal server (at home devices usually found on the [[Routers|router]]).
4. If the Local DNS resolver cannot find it, it will instead connect with each other of these servers to check if they have it. Whether they have it or not, they will send an answer to the resolver, be it to search elsewhere or to give the answer back to the client
	1. **Root Server**: Another DNS server that has all the DNS queries made over time.
	2. **TLD Server**: Manages the final extension of a domain name, such as .com.
	3. **[[Authoritative Server]]**: the final, trusted source of truth for domain name information, holding the records.