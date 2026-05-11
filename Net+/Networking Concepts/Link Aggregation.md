# Overview
Adds the speed of two different [[Ethernet]] cables to get a faster connection between two devices.

# Core Ideas
- Follows a per vendor naming scheme:
	- **Link Aggregation Control Protocol** a.k.a. **LACP**
	- **EtherChannel**
	- **Port Channel**
	- **Aggregated Ethernet**
 - Can connect two devices, be it on the [[DATA LINK LAYER|layer 2]] or the [[Network Layer|layer 3]].
 - Unlike in [[Spanning Tree Protocol (STP)|STP]], both ports are being used simultaneously.