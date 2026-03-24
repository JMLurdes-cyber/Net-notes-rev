# Concept
A kind of notation made to indicate in a standard manner the [[Subnet Masks|Subnet mask]].

# Key Ideas
- Also known as Classless Inter Domain Routing
- Count the amount of bits that are found on the subnet mask.
- Add them to the end of the [[IP Addresses|IP]] to showcase their subnet.

# Example
1st. A more complex example to showcase it:
Subnet mask = 255.255.240.0

| 255      | 255      | 240      | 0        |
| -------- | -------- | -------- | -------- |
| 11111111 | 11111111 | 11111000 | 00000000 |
| 8        | 8        | 5        | 0        |
So the CIDR would end up in /21.

# Notation Tips
- **255 = 8 bits**, which means that :
	- 255.0.0.0 = /8
	- 255.255.0.0 = /16
	- 255.255.255.0 = /24
	- 255.255.255.255 = /32

 The others fall into the table

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2   | 4   | 8   | 16  | 32  | 64  | 128 | 256 |

