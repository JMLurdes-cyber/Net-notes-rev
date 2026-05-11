# Overview
- The **Domain Host Configuration Protocol**  is a protocol that automatically assigns [[IP Addresses|IP's]] to a device that connects to a network. 

# Core Ideas
- Uses two [[Common Ports|port]] to be able to efficiently separate between client and [[Servers|server]].
- Follows a series of steps known as **DORA**:
	- **Discover** : The connected device sends a broadcast trying to find the DHCP server
	- **Offer**: The DHCP server sends an answer to the client device, with an offer of a desired IP 
	- **Request**: The client device answers back accepting/denying the inquiry
	- **Acknowledge**: The DHCP servers sends an answer accepting the answer from the client.
- The DHCP server doesn't need to be in the same [[Subnets|subnet]] as the requesting device, but a router (or any gateway) needs to be set as a relay device that forwards DHCP requests to the server.
- IP ranges can be excluded to ensure free space in case of need
- Devices can be set to specific addresses to ensure control/security over the system
- DHCP leases are time-bound with the sole exception of reservations, of course.
- Can give also [[DNS]] Servers and Time servers
## Port 
- [[UDP]] 67 for *server-side connections*
- [[UDP]] 68 for *client-side connections*

### Attacks
- [[DHCP Spoofing]]
- [[DHCP Starvation]]
---
[[Common Ports]]
#ports-and-protocols 