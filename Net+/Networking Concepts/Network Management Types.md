# Overview



| In- Band                                                         | Out-of-Band                                                 |
| ---------------------------------------------------------------- | ----------------------------------------------------------- |
| Manages devices using the same [[VLAN\|VLANs]] the devices serve | Uses a separate, dedicated VLAN specifically for management |
| [[SSH]], [[HTTP - HTTPS\|HTTPS]], [[RDP]]                        | "Separation of concerns"                                    |
| Easier to implement, less secure                                 | Serial connection to server, switch, router, etc.           |
