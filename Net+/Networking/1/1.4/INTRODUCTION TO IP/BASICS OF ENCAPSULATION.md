Data  is not sent as a whole through the internet because this would be too inefficient, hard to route and difficult to recover if something fails.

Instead computers break down data (or in computing terms, payload) into smaller, more manageable data, to be able to optimally send, manage, reroute and resend if needed. Then each layer of the [[UNDERSTANDING THE OSI MODEL|OSI model]] gives the data a header that wraps the payload and lets it know where and how to be sent. This process is known as **encapsulation**.

**Encapsulation** happens in *descending order* of the [[UNDERSTANDING THE OSI MODEL| OSI model]] when it is being *sent*
 and **decapsulation** happens in *ascending* when it is being *received*. The process goes as follows:

## [[TRANSPORT LAYER|Layer 4: Transport layer]]
- Depending on the kind of transfer, this layer chooses a [[TCP AND UDP|TCP]] header for reliable transfers and [[TCP AND UDP|UDP]] header for faster transfers. 
- This header takes carries the source [[INTRODUCTION TO PORTS|port]] and device and the destination [[INTRODUCTION TO PORTS|port]] and device.

## [[NETWORK LAYER|Layer 3: Network Layer]]
- This layer gives the payload an **IP Header**.
- This header carries the source and destination's [[IP addresses]] and routing specifications, like [[TTL]].

## [[DATA LINK LAYER|Layer 2: Data Link Layer]]
- This layer gives the payload a **Ethernet header and trailer**
- The header  carries information about the source and destination's [[MAC Adresses]].
- The trailer handles error detection and correction.

---
[[INTRODUCTION TO IP]]
#Layer2 #Layer3 #Layer4  #ports-and-protocols #TCP #UDP 