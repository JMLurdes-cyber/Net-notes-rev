
- IKE, a.k.a. **Internet Key Exchange** is a protocol that ensures that both source and destination devices of a communication agree on the encryption and decryption keys.
- The actual secret key agreed upon is never transmitted through the net, making the transmission more secure.
- The agreement is known as a *Security Association (SA)*.
- The SA is formed by two phases:
	- **Phase 1** - Uses [[Diffie-Hellman]] to create a secret key shared through [[UDP]] 500. This process is also known as **ISAKMP** (Internet Security Association and Key Management Protocol)![[IKE.png]]
	- **Phase 2** - Coordinates the ciphers and key sizes and  confirms the SA for [[IPSec]].![[IKE_P2.png]]
	

