- One of the two main kinds of IPSec tunnels used nowadays. 
- It creates an *IPSec Header* and *Trailer*.
- Even though it encrypts the data, it doesn't encrypt the IP Header, so any interceptor can see where the packet is headed, even though they may not access the data.!

 ![[ESP_Transport_Mode.png]]