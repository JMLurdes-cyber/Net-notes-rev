- One of the two main kinds of IPsec operation modes. 
- [[ESP]] adds an *IPsec Header* and *Trailer* to the original packet.
- The original IP header is not encrypted, so any observer can still see the source and destination address of the packet, even though they cannot access the payload.

 ![[ESP_Transport_Mode.png]]