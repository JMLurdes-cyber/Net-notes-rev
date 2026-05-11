Safest protocol right now. 
Uses 192 bit encryption + Added integrity to the handshake


# Overview
Latest standard in Wi-Fi security.

# Core Ideas
- Uses a process called SAE to block off [[Dictionary Attacks]], which were a known vulnerability of [[Wi-Fi Protected Access Version 2|WPA2]].
- Encrypts the connection between the device and the [[Access Points|Access Point]], even in environments without password authentication.
- Uses "Forward secrecy", which ensures that each session is protected by an unique key that is deleted after the communication. This ensures that there are no logs of past conversations.
- Allows the connection through the scanning of a QR code sent to the device.