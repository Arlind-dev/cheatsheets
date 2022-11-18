# Local Area Network - Windows

| **Lan-Win**              |                                                                                                    |                      |                                                                                           |
|--------------------------|----------------------------------------------------------------------------------------------------|--------------------- |-------------------------------------------------------------------------------------------|
| **Kommand**              | **Anwendung /   Beschreibung**                                                                     | **Kommand Beispiel** | **Option**                                                                                |
| ipconfig                 | Netzwerk   Informationen, wie IP-Adressen                                                          | ipconfig /a          | /a /renew /release                                                                        |
| arp                      | Alle   Adress Resolution Protokoll instances, bzw.       Alle Gespeicherten MAC-Adressen anschauen | arp -a               | [-a] [-g] [-v] [-d]   [-s]                                                                |
| getmac                   | Alle MAC-Adressen   anzeigen, die mit deinem Gerät verbunden sind / waren                          | getmac               | /s /u /p /fo /nh v                                                                        |
| ping                     | überprüfen ob ein   Host/Server erreichbar ist über Layer 3                                        | ping 10.80.4.120     | [-t]   [-a] [-n count] [-l size] [-f] [-i TTL] [-v TOS]  [-w timeout] [-R] [-p] [-4] [-6] |
| route                    | mit dem Route Command   kannst du deine Network Routing Tables anschauen oder manuell editieren    | route print          | add print delete   change [-4] [-6]                                                       |
