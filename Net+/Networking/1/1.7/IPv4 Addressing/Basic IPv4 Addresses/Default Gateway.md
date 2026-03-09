## Concept
- The router that handles traffic going outside of the local subnet.

## Key ideas
- It is in an [[IP Addresses| IP address]] on the local subnet.
- Only used when the destination IP is outside of the local subnet.
- The gateway corresponds to the **default route** in the [[routing table]], if there are specific routes set up it may go unused.
- Before receiving traffic, the host must learn it's [[MAC Addresses|MAC Address]] using the  [[ARP|Address Resolution Protocol]] .
- Some devices that act as gateways include: [[Routers]], [[Switches|Layer 3 switches]], [[Firewalls]] and an [[ISP Modem]].

---
[[IPv4 Addressing]]
#Layer2 #Layer3 