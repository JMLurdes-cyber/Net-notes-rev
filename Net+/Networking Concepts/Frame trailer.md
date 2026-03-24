[[Cyclic Redundancy Check]]
# Overview
- A piece of data added to the [[Network Layer Header|Packet]] during the process of [[Data Link Frames|data link layer encapsulation]], alongside the [[Frame header|header]]

# Core Ideas
- Usually two bits of information are added:
	- **Frame Check Sequence (FCS/[[Cyclic Redundancy Check|CRC]] (Checksum))**: A (usually) 4 bytes mathematical number calculated by the sender based on the message. This number gets calculated twice, and if the results don't match the frame is considered "faulty", and discarded.
	- **End-of-Frame Flag (Optional)**: Some protocols specify the end of the frame.

