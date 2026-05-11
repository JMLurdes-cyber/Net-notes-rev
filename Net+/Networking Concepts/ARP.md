# Overview
- Understanding better the routing of [[Network packets]] through the understanding of the gathering of their information.

# Core Ideas
- Also known as **Address Resolution Protocol**
- It resolves the destination [[MAC Addresses|MAC Address]] to an [[IP Addresses|IP Address]], so that it may be routed in a [[LAN]]
- It sends forward an Arp Request in the form of a [[broadcast]] to the switch which gets forwarded in the [[LAN]]. Only the device with a matching MAC Address sends back an answer to the request.
- It stores all the destination MAC Addresses in a cache.

# Known attacks
- [[ARP spoofing]]: The attacker sends fake ARP messages, masking their MAC and impersonating a trusted device of the network.
- [[ARP poisoning]]: The attacker corrups the ARP cache on a network, redirecting them to a wrong MAC address.

---
[[TRANSPORT LAYER]], [[Network Layer]]
