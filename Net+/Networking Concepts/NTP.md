# Overview
- Used to synchronize the time all over the network with the atomic time server

# Core Ideas
- NTP a.k.a. **Network Time Protocol**
- Not only it ensures that the time is correct all over the network, but it is useful for time-dependent protocols/functions, like logging.
- Usually uses the time from a NTP server
- The main server is used in UTC, adding or subtracting time based  on Time Zones
- Used in [[SSO|SSOs]] or in [[Kerberos]].
- [[NTS]] adds cryptographic protection to the NTP data, preventing tampering of data.
## Port Used.
- [[UDP]] 121

---
[[Common Ports]]
#ports-and-protocols 
