# Overview
Understanding attacks used on [[VLAN|VLANs]] and their possible contrameasures.

# Purpose
- Manipulation of switching architecture to be able to move between VLANs.
- Eavesdropping, data theft

# Techniques
- Switch spoofing: advertise false trunk port.
- Double tagging: Insert false VLAN tags.

# Mitigation
- Disable Dynamic Trunking Protocol (DTS)
- Lock down access ports to VLANs (network segmentation)

---
[[Network Attacks]]