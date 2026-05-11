# Overview
- An explanation of how clouds are regulated through the use of **Security Groups** and **Security Lists**.

# Core Ideas.
- **Security lists** refer to a set of rules that apply to a virtual [[subnets|subnet]]. They are:
	- A set of whitelists/blacklists that filter connections based on [[Common Ports|ports]], [[INTRODUCTION TO PORTS|protocols]], ranges or rules
	- Usually set up in a virtual [[Firewalls|firewall]]
	- Stateless
- **Security groups** refer to a set of rules that apply to individual (or a group of) virtual devices. They are:
	- Stateful

# Examples
- A Security List could block all incoming access to [[RDP]] within a [[VLAN]].
- A Security Group could be made to block some devices from connecting to [[HTTP - HTTPS]].


---
[[DESIGNING THE CLOUD]]
#ports-and-protocols #cloud-computing 
