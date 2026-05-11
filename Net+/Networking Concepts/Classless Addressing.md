
# Concept
- A subnetting model that uses [[Subnet Masks|a subnet mask]] as a basis to operate.

# Key Ideas
- The [[Subnet Masks|subnet mask]] delimits the separation of the [[IP Host portion|host]] and [[IP Network portion|network]] of the [[IPv4 Addresses|IP address]].
- The classless addressing is based on separating the 1s from the 0, making a model in which the 1s are hosts and the 0s are networks.

# Example
### 10.0.0.10

| 10       | 0        | 0        | 10       |
| -------- | -------- | -------- | -------- |
| 00001010 | 00000000 | 00000000 | 00001010 |
| 11111111 | 11111111 | 11110000 | 00000000 |

That example showcases the general idea, in which the [[Subnet Masks|subnet mask]] separates 1s and 0s, and then it would be noted with [[CIDR]].