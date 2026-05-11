# Overview
- **VN**s or **Virtual Networks** describes a single or a group of networks found on the cloud, taking up the function of a physical server farm.

# Core Ideas
- Usually replaces a physical network through [[Network Function Virtualization|virtualization]].
	- An example would be running a whole virtual network within a beefy server, instead of having a weaker server that runs a physical network.
- Helps with:
	- **Optimization**: physical networks are limited by the space, and can be either underused or hard to enlarge, unlike virtual
	- **Simplification**: No need to find the space for the physical servers/separating the servers by function, both the layout and use can be specified virtually that runs virtual application server.
	- **Load Balancing**: synchronization between virtual servers is easier to implement than physical ones, which simplifies the seamless use of [[Failover|failovers]].
	
- Can be paired to a [[SAN]] to make backups/use as storage.

# Types of Virtual Clouds
- There are three main kind of virtual networks:
	- **[[Private Clouds]]**: run on premises by the client themselves
	- **[[Public Clouds]]**: service hired from a provider
	- **[[Hybrid Clouds]]**: a cloud that has a private section and a public one.



---
[[CLOUD COMPONENTS]]
#cloud-computing 