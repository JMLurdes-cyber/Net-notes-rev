# Overview
- One of the two added pieces of data that encapsulates a [[Network Layer Header|packet]], alongside the [[Frame trailer|trailer]], when a packet travels through a [[LAN]]

# Core Ideas
- It adds  several pieces of information that are used during forwarding.
- Some of those pieces of information are:
	- **Destination [[MAC Addresses|MAC Address]]**: The pysical address of the computer or device that is supposed to receive the frame
	- **Source [[MAC Addresses|MAC Address]]**: They  physical address of the device that sent the frame
	- **[[Data Link Frames|Frame]] type**: Tells the computer the kind of data that is being sent so the computer knows where to send it to. Some examples include [[ARP]], [[IPv4 Addressing|IPv4]], [[IPv6 addressing|IPv6]].
	- **Flags/Syncronization (Preamble/SFD)**: Bits that tell the receiving computer to get ready to receive a transmission.
	- **[[VLAN]] Tag (Optional)**: Tells the switch if the frame belongs ot an specific virtual network
	- **Maximum Transmission Unit (MTU)**: delimits and gives a maximum size to the data sent through the Ethernet. It can be edited, but it shouldn't be as long as there isn't a good reason.