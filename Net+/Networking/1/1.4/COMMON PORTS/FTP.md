## Un-encrypted
- **File Transfer Protocol** (a.k.a. FTP) is used for mainly two things: transferal of data over intranet/internet, or file management between client and a server.
- FTP sends data in plaintext, making it unsafe on public networks.

## Port number
- Depending on the function it can use one of two ports:
	- [[TCP]] 20 for transferal on [[active mode|active mode]].
	- It uses [[INTRODUCTION TO PORTS|non-ephemeral ports]] on [[Passive mode|passive mode]].
	- [[TCP]] 21 for file management.
## Encrypted
- [[SFTP]] runs over [[SSH]], sharing most of the functionality of FTP over an encrypted port.
- [[FTPS]] runs over FTP over [[TLS]] encryption.

| FUNCTION | **PLAINTEXT** | **ENCRYPTED** |
| :------: | :-----------: | :-----------: |
|   DATA   |  [[TCP]] 20   |               |
| CONTROL  |  [[TCP]] 21   |               |

---
[[COMMON PORTS]]
#ports-and-protocols 