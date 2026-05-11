# Overview
- Summary of the full travel from a packet to another, from device to device.


# Core Ideas
- The [[APPLICATION LAYER|application]] used by the source device chooses [[TCP]] or [[UDP]] to make a transmission.
	- It proceeds to send the packet to the destination device using one of those.
- The source device sends a [[payload]] with:
	- Data
	- A [[Transport Layer Header]] that uses between:
		- [[TCP]] for a reliable transfer
		- [[UDP]] for a fast transfer
		- A chosen **ephemeral port** to:
			- Are **temporary source ports** assigned by the OS
			- Enable multiple simultaneous connections via **socket pairs**
		- And the **destination [[INTRODUCTION TO PORTS|port]]** which explains the intended protocol to be used.
 - The packet receives the [[IP Addresses|Source IP and a Destination IP Address]]
 - The packet gets forwarded through [[Data Link Frames|frames]], which add a [[Frame header]] with the [[MAC Addresses|destination and source MAC addresses]] and a [[Frame trailer]] which adds error detection.
 

![[Untitled Diagram.drawio.png]]