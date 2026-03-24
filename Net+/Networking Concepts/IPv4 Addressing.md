[[Network Layer|Layer 3]] protocol that takes care of the routing performed between two networks.
## Bases of IPv4 Addresses
IP Addressing refers to the practice of using IP addresses to be able to identify and work with devices within a network. There are several components that are related to this method:
###### [[IP Addresses]]
	- Unique identifiers for each device within the network
###### [[Subnet Masks]]
	 - Numbers that identify the subnet to which an IP is part of
###### [[Default Gateway]] 
	- The router that allows communications outside of the local subnet.

### Special IPv4 Addresses
This refers to some of the more specific IP addresses that I should remember, since they are useful in several scenarios:

###### [[Loopback Addresses]]
	- An Address that is directed to the user himself.

###### [[Reserved Addresses]]
	- Addresses set aside for future use, or testing.

###### [[Virtual IP  Addresses (VIP)]]
	- IP addresses found within Virtual Machines.

## Internet Protocol version 4 (IPv4)
 To truly understand IPv4, we need to talk about the main subject of the theme:
- The [[Internet Protocol version 4 (IPv4)]].

## IPv4 configuration
Nowadays, we mostly use the **[[DHCP|Domain Host Configuration Protocol]]** to automatically assign addresses and IP configure all devices within a network. This process used to be manual before the apparition of this protocol

However, not all networks have a DHCP server. Those that do not have it use instead [[APIPA]] 

## Range Issue
In the current times, there are more devices connected to the internet than the amount that IPv4 can maintain.  There were several solutions that engineers came up over time to deal with this issue:
- [[Classless Addressing]]
- [[Private IP Addresses]] which are not routed through the Internet, and only locally (which allows them to be repeated in different locations without conflicts)
- [[NAT]]

The ranges of private networks are decided by [[RFC]].

---
[[COMPTIA NETWORKING +]]