# Overview
- One of the main kinds of network communication.

# Core Ideas
- One-to-many communication type.
- Multiple recipients will get the sent information at once.
- Not used between different networks
- Usually found in the Class D range (224.0.0.0 - 239.0.0.0)
# [[IPv4 Addressing|IPv4]] vs [[IPv6 addressing|IPv6]]
- IPv4 can only multicast within an organization
- IPv6 can multicast over the internet

# Use Cases
- Commonly used in Data Centers to send information between main center and backup  server.
	- Performs this task sending many encrypted packets through the use of [[Generic Routing Encapsulation (GRE)]].


![[multicast.png]]

---
[[NETWORK COMMUNICATION]]