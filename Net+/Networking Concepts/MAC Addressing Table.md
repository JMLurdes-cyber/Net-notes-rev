## Concept
 - [[Switches]] keep tabs of all connected devices, and the ports where they are connected. Through observation of [[MAC Addresses|source and destination addresses]] it learns the exact "positions" of those connections, saving them into a table.

## Functions
- If the address **is in the table**, it will forward the data through the respective port.
- If the address is **not in the table**, several things happen:
	- The switch sends the data to every connected device (except the sender)
	- Every device that doesn't has the required address drops it.
	- The intended device sends an answer to the switch, which adds the device into the table.
	- Then the answer gets sent back to the sender device

## [[Framing Data Flow]]




---
[[Switches]]
[[DATA LINK LAYER]]
