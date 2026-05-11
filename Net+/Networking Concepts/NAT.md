# Concept
Takes a [[Private IP Addresses|private IP address]] and translates it to a [[Public IP Addresses|public IP address]] allowing for networks to connect to the Internet without requiring a large amount of public IP addresses for a local device.

# Key Ideas
- Allows for outbound communications from local IPs, such as a house, to the Internet.
- Found in most [[Routers|routers]] by default.
- Creates a Table that stores the values of both the internal and external IPs to be able to translate between the private and the public IPs
-   The NAT table has inside and outside spots dedicated to : Sournce and Destination IPs and Source and destination ports. These are found on both internal and external NAT tables.
- 