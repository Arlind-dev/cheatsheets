### Local Area Network - Windows

| Kommand                  | usage                                                                                              | example              | Option                                                                                    |
|--------------------------|----------------------------------------------------------------------------------------------------|--------------------- |-------------------------------------------------------------------------------------------|
| ipconfig                 | get network information                                                                            | ipconfig /a          | /a /renew /release                                                                        |
| arp                      | see all Adress Resolution Protokoll instances                                                      | arp -a               | [-a] [-g] [-v] [-d]   [-s]                                                                |
| getmac                   | see all mac addresses that were connected to this device                                           | getmac               | /s /u /p /fo /nh v                                                                        |
| ping                     | check if a server is reachable over layer 3                                                        | ping 10.80.4.120     | [-t]   [-a] [-n count] [-l size] [-f] [-i TTL] [-v TOS]  [-w timeout] [-R] [-p] [-4] [-6] |
| route                    | See through which network devices and IPs you had to go through before reaching the destination    | route print          | add print delete   change [-4] [-6]                                                       |
