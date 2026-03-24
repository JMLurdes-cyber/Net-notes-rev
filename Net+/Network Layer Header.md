# Overview
- Overview of how [[BASICS OF ENCAPSULATION|encapsulation]] works in the [[Network Layer]]. 

# Core Ideas
- This header is added after the [[Transport Layer Header]] is added to the data, before it begins routing through the [[LAN]] by using [[Data Link Frames|Frames]]
- Contains:
	- **Source [[IP Addresses|IP Address]]:** Where the packet comes from
	- **Destination [[IP Addresses|IP Address]]**: Where the packet is going
	- **[[TTL|Time To live]]**: The amount of time/router hops the packet can go before being dropped
	- **[[INTRODUCTION TO PORTS|Protocol]]**: Whether the computer will use [[TCP]] or [[UDP]]
	- **Header Checksum**: Error-checking to make sure the header wasn't corrupted during travel.
- When the device is making a connection to a device that it never connected before, it will need to send first an [[ARP|ARP request]] to learn the destination device's [[MAC Addresses|MAC Address]].