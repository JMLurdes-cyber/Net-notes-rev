- ESP a.k.a. **Encapsulation Security Payload** is a protocol used to encrypt packets.
- It uses the formats MD5, SHA-1, SHA-2 for *hashing*.
- It uses the formats 3DES or AES for *encryption*.
- To perform the encryption, it adds a header and a trailer that encapsule the packet.
- It adds an Integrity Check Value that double-checks that the received packet has the expected hash.

![[ESP.png]]