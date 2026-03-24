# Overview
An explanation about the bases of IPv6 Addresses, how they operate and how do they differ from [[IPv4 Addressing|IPv4 Addresses]].

# Key Ideas
- IPv6 addresses are written in [[Hexadecimal Math|hexadecimal (base-16)]].
	- An IPv6 address would look like : *2001:0DB8:0002:008D:0000:0000:00A5:52F5*
- An IPv6 address is composed of [[Binary Math|128 bits]] = [[Binary Math|32 nibbles (1 nibble = 4 bits)]] = [[Binary Math|8 hextets (1 hextet = 8 bits)]].
	- Out of which, the value of each segment is written in nibbles(4 bits).
		- F.ex.: 0xA8C5 = 1010 + 1000 + 1100 + 0101 

- Similar to IPv4, there are [[IP Network portion|Network portions]], however, the equivalent to the [[IP Host portion|Host portion]] is called **Interface Identifier**
	- Each of the portions is **64 bits**.
	- Unlike with Ipv4, the [[Subnet Masks|subnet mask]] of IPv6 is almost always /64.

- Requires [[Link-local addresses]] to fully operate

# [[Simplification of IPv6 Addresses]]
- Writing the full address can be a cumbersome task, so over time, several rules got standardized to be able to shorten the IPs.

# Address Types
###### [[UNICAST|Global Unicast]]
- 2000::/3
###### [[Link-local addresses|Link Local]]
- FE80::/10
###### [[Loopback Addresses|Loopback]]
- ::1
###### [[MULTICAST|Multicast]]
- FF00::/8


# [[IPv6 Implementation]]

---
#Layer3 #Ip-addressing #IPv6 

