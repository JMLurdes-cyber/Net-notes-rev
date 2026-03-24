# Overview
- Understanding what makes [[TCP]] a reliable transfer method through the explanation of its three way handshake.

# Core Ideas
 Whenever [[TCP]] is used to send a packet it will:
1. The source device will send a **Synchronization Request *(SYN)*** to the destination device
2. The destination device will send to the source device a **Synchronization Acknowledgment *(SYN-ACK)***
3. The source will answer once more **acknowledging the answer *(ACK)*** 
	- After those steps the destination device will create a packet with the data requested, which will be broken into pieces and send in pieces to the requesting device.
		- After a threshold, the requesting device will ask once again for an acknowledgment of having received all the data sent.
			- If the acknowledgment is successful the process will continue
			- If the acknowledgment is unsuccessful the destination device will resent whichever data is missing
			- This process is done a few times
	- The maximum amount that a piece of data can have is delimited by the [[RFC]].
4. Once the communication is finished, an **ending request is made (FIN/FIN-ACK/ACK)**
