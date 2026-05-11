# Overview
Understanding the basics of [[Comptia Network Implementation]] through understanding of how switches can organize and manage [[LAN|LANs]] through the use of VLANs.


# Core Ideas
- **Virtual LANS**, a.k.a. **VLANS**
- Getting a switch for every single section of a network would be expensive and messy:
	- To solve that, we can separate them logically.
- We can divide a single [[Switches|switch]] among several VLANs to avoid [[Packet collisions|collisions]] and incidents within the network; in fact, every port of a switch can be set to a VLAN.
- The ports that are set to the default port (not set to any VLAN) will be known to the others as 1.
- VLANs will always have a moniker: VLAN 10, VLAN 20.
- The [[MAC Addressing Table]] will also get the information about which VLAN they connect to.
- We can use [[Trunk Links]] to share/communicate devices on the same VLAN placed in different devices.
- Similar to [[subnets]], numbers from different VLANs cannot communicate directly with each other.
	- That rule doesn't apply if the VLAN is connected to a router through the use of Trunk Links. Routers allow the VLANs to communicate with each other. 