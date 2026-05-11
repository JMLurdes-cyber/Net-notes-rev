# Concept
- A binary value appended to the [[Data Link Frames|trailer]]  frame to detect errors

# Key Ideas
- The value is calculated from a checksum made from the sent data.
- The value gets calculated once at the source device, and once again at the destination. If they don't match, the data is corrupt.
- Usually used in [[Ethernet]] [[Data Link Frames|frames]] and [[CAN]] bus.


---
[[DATA LINK LAYER]] [[Data Link Frames]] [[Switches]]