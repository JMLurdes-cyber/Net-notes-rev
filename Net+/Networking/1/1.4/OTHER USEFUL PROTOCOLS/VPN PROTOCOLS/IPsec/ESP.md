- ESP a.k.a. **Encapsulation Security Payload** is a protocol that provides confidentiality, integrity and authentication for IP packets through encryption.
- It uses the hash algotithms MD5, SHA-1, SHA-2 for *hashing*.
- It uses the encryption algorithms 3DES or AES for *encryption*.
- To perform the encryption, it adds a header and a trailer that encapsulate the packet.
- It adds an Integrity Check Value that verifies both the packet's integrity and authenticity.

![[ESP.png]]