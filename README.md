# cheatsheets
## all cheatsheets put together

### Local Area Network - Windows

| **Lan-Win**              |                                                                                                    |                      |                                                                                           |
|--------------------------|----------------------------------------------------------------------------------------------------|--------------------- |-------------------------------------------------------------------------------------------|
| **Kommand**              | **Anwendung /   Beschreibung**                                                                     | **Kommand Beispiel** | **Option**                                                                                |
| ipconfig                 | Netzwerk   Informationen, wie IP-Adressen                                                          | ipconfig /a          | /a /renew /release                                                                        |
| arp                      | Alle   Adress Resolution Protokoll instances, bzw.       Alle Gespeicherten MAC-Adressen anschauen | arp -a               | [-a] [-g] [-v] [-d]   [-s]                                                                |
| getmac                   | Alle MAC-Adressen   anzeigen, die mit deinem Gerät verbunden sind / waren                          | getmac               | /s /u /p /fo /nh v                                                                        |
| ping                     | überprüfen ob ein   Host/Server erreichbar ist über Layer 3                                        | ping 10.80.4.120     | [-t]   [-a] [-n count] [-l size] [-f] [-i TTL] [-v TOS]  [-w timeout] [-R] [-p] [-4] [-6] |
| route                    | mit dem Route Command   kannst du deine Network Routing Tables anschauen oder manuell editieren    | route print          | add print delete   change [-4] [-6]                                                       |

### Wide Area Network - Windows

| **WAN - Win** |                                                                                                                                          |                      |                                                                                                                |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------------------------------------------------------------------------------------------------|
| **Kommand**                 | **Anwendung /   Beschreibung**                                                                                                               | **Kommand Beispiel**     | Option                                                                                                         |
| tracert                 | Zeigt alle   verschiedene Netzwerkgeräte, durch die es durchdringen musste, um zum Ziel   zugelangen                                     | tracert google.com   | [-d] [-h Max. Hops]   [-j Hostliste] [-w Zeitlimit] [-R] [-S Quelladresse] [-4] [-6]                           |
| pathping                | Zeigt   alle verschiedene Netzwerkgeräte,       durch die es durchdringen musste, um zum Ziel zugelangen, mit weniger   Informationen    | pathping google.com  | [-g Hostliste] [-h   max. Hops] [-i Adresse] [-n] [-p Zeitraum]    [-q Abfrageanzahl] [-w Zeitlimit] [-4] [-6] |
| route                   | mit dem Route Command   kannst du deine Network Routing Tables anschauen oder manuell editieren                                          | route print          | add print delete   change [-4] [-6]                                                                            |
| netstat                 | mit   hilfe von einem immer aktualisierenden Fenster, kann man alle verbindungen   die dein Laptop bekommt oder anfragt angezeigt werden | netstat              | [-a] [-b] [-e] [-f]   [-n] [-o] [-p Protokoll] [-r] [-s] [-t] [-x] [-y] [Intervall]                            |
| telnet                  | überprüfen ob ein   Port lauft                                                                                                           | telnet google.com 80 | [-a] [-e] [-f] [-l]   [-t] host port                                                                           |
| ping                    | überprüfen ob ein   Host/Server erreichbar ist über Layer 3                                                                              | ping 10.80.4.120     | [-t]   [-a] [-n count] [-l size] [-f] [-i TTL] [-v TOS]  [-w timeout] [-R] [-p] [-4] [-6]                      |
| nslookup                | Name Service   anfragen, und Infos erhalten                                                                                              | nslookup google.com  | minus pt                                                                                                       |
