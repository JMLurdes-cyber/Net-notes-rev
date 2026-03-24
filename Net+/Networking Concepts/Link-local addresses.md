# Overview
- A Non routable [[IP Addresses|IP Address]] that only works on the same local segment.

# Core Ideas
- It never reaches outside the local network, if the packet hits a router the IP dies there.
- It helps devices communicate when there are no:
	- [[Routers]]
	- [[DHCP]]
	- No Internet
	- No manual configs
	
- It is commonly used for:
	- Finding neighbours
	- Basic communications
	- Automatic configuration

# [[IPv4 Addressing| Link local addresses in IPv4]]
- Also known as [[APIPA]]
- Mostly sees use in modern networking whenever the [[DHCP]] server is down, or in Zeroconf / automatic local networking.
- Non routable
- Optional
- IP in the 169.254.0.0/16 range

# [[IPV6 addressing|Link-local addresses in IPv6]]
- Every interface gets one automatically
- Allows for the communication between IPv6 based devices.
- Non routable
- Required for IPv6
- Ip in the FE80::/10



# Bullet Idea
[[IPv4 Addressing|IPv4]] link-local = [[APIPA]] -> 169.254.0.0/16
[[DHCP]] fail -> optional

[[IPv6 addressing|IPv6]] link-local = FE80::/10
automatic -> required

Link-local addresses aren´t routable.