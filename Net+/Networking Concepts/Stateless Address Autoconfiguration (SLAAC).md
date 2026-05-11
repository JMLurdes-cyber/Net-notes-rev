# Overview
Understanding how [[IPv6 addressing|IPv6 Addresses]] are automatically configured to be able to be fully operational without the need of human input


# Core Ideas
- **Stateless Address Autoconfiguration** a.k.a. **SLAAC** automatically configures IPv6 Addresses to devices without needing to use [[DHCP]]
- It is used in combination with the [[Neighbor Discovery Protocol (NDP)]] to discover the network prefix and gateway, and grant an IPv6 address to a device without the risk of repeating the address with another device.