---

---
Whenever a transfer is being made over the network/internet, one of the two main transfer protocols of the [[TRANSPORT LAYER|transport layer]] are picked:**[[TCP]]** or **[[UDP]]**. They have different strengths and weaknesses:

|                    | TCP                                                                                                                                             | UDP                                                             |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| TYPE OF CONNECTION | Connection-oriented, there is a formal beginning and end of communications                                                                      | Connectionless, it sends without verifying start or end         |
| CONTROL FLOW       | It uses acknowledgments to verify if data needs to be resent or not, and to know the state of communications to slow down/send faster as needed | Sends data without getting an answer nor stopping/slowing down. |
| SPEED              | Slower due to overhead                                                                                                                          | Faster due to no overhead                                       |
| USE CASES          | Downloading a PDF or an image                                                                                                                   | Video streaming, voice calls over internet.                     |



---
[[INTRODUCTION TO IP]]
#ports-and-protocols #Layer4 #TCP #UDP #network-troubleshooting 