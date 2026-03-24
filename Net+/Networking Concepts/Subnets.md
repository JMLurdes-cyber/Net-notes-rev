# Concepts
Networking practice that consists in separating a single network/IP Address range into several smaller networks, each with their respective responsibilities/tasks.

# Key Ideas
- Managing networks as-they-are can be a daunting task due, among other issues:
	- Management issues, since there would be no way of differentiating between segments.
	- Security issues, such as a single infected machine infecting the whole system
	- Scale issues, such as the fact that a single network can contain over 16000000 IPs.
- So they are **usually broken down into smaller segments**.
- Segments of the subnet **DO NOT NEED TO BE EXACTLY EQUAL** due to [[VLSM|Variable Length Subnet Masking]], but they cannot overlap (which is to say, there can not be two or more equal IPs in a single network), since that would cause issues.

- Every subnet will have a:
	- [[IP Network portion|Network Id]] which identifies to which network it is a part of
	- [[IP Host portion|Host portion]] which refers to all usable IP addresses of the network.
	- [[IP Broadcast portion|Broadcast portion]] which identifies every single address on the subnet.
	- [[Subnet Masks|Subnet mask]], which identifies the range of the subnet.


# Example
### 10.0.10.0/8

| Part        | Bits     |          |          |          |
| ----------- | -------- | -------- | -------- | -------- |
| Subnet      | 10       | 0        | 10       | 0        |
| Host        | 00001010 | 00000000 | 00001010 | 00000000 |
| Subnet Mask | 11111111 | 00000000 | 00000000 | 00000000 |
| Broadcast   | 00001010 | 11111111 | 11111111 | 11111111 |

