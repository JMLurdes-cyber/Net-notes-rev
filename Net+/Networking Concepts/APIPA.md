- APIPA a.k.a. Automatic Private IP Addressing
- Known as a [[Link-local addresses|link-local address]], since it can only communicate with local devices, it cannot forward by routers.
- APIPA has a range of reserved IPs: **169.254.0.0/16**.
	- However, since the first and last 256 addresses are blocked, the functional range is:   **169.254.1.0 - 169.254.254.255**.
- Uses [[ARP]] to automatically confirm that the address isn't in use.
- It is used instead of the [[Default Gateway]] when there is a fault with the network (misconfigurations, the [[DHCP]] is down...).

---
[[IPv4 Addressing]]