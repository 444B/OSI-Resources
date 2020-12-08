# OSI Tables 

### Intro and explanation



#### General Overview of OSI Model
| Layer            | Means                                            | PDU                 | Role             |
| :--------------: | :----------------------------------------------: | :---------------------------------------------: | :--------------: | 
| 7 - Application  | API's, Network Services                          | Data                | Scribe           | 
| 6 - Presentation | Reformats, Encrypts/Decrypt, Compress/Decompress | Data     | Translator       |  
| 5 - Session      | Establishes, Manages and Ends Sessions           | Data      | Negotiator       |  
| 4 - Transport    | Segment ID / Assembler                           | Segments   | Middle Manager   |  
| 3 - Network      | IP addressing / Routing                          | Packets  | Mail Room Guy    |  
| 2 - Data Link    | Organizes Bits into Frames                       | [Frames](https://en.wikipedia.org/wiki/Frame_%28networking%29)   | Envelope Stuffer |  
| 1 - Physical     | Movement of Bits                                 | Bits or Data Stream | The Truck        | 
 
 
 []()
 
 
#### Layer: 7 - Application
| Name                                                                  | Port       | RFC                                             | Resource     |
| :-------------------------------------------------------------------: | :--------: | :---------------------------------------------: | :----------: | 
| [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)     |80          | [2616](https://tools.ietf.org/html/rfc2616)     | []()       | 
| [HTTPS/SSL/TLS](https://en.wikipedia.org/wiki/HTTPS)                  | 443        | [2818](https://tools.ietf.org/html/rfc2818)     | []()       | 
| [NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol)  |119         | [3977](https://tools.ietf.org/html/rfc3977)     | []()       |
|  [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol)          |21, 20      | [959](https://tools.ietf.org/html/rfc959)       | []()       |
| [Telnet](https://en.wikipedia.org/wiki/Telnet)                        |23          | [854](https://tools.ietf.org/html/rfc854)       | []()       |
| [SSH](https://en.wikipedia.org/wiki/SSH_(Secure_Shell))               | 22         | [4251 - Transport layer](https://tools.ietf.org/html/rfc4251), [4252 - User Authentication layer](https://tools.ietf.org/html/rfc4252), [4254 - Connection Layer ](https://tools.ietf.org/html/rfc4254)      | []()       |
|  [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol)           |   110       | [1939](https://tools.ietf.org/html/rfc1939), [2449 - Extention](https://tools.ietf.org/html/rfc2449), [1734 - Authentication](https://tools.ietf.org/html/rfc1734)       | []()       
| [IMAP4](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol)           |      143    | []()       | []()       |
|   [SMTP]()          |      25    | []()       | []()       |
|  [DNS]()            | 53         | []()       | []()       |
|  [TFTP]()           |   69       | []()       | []()       | 
|  [DHCP]()           |     67, 68     | []()       | []()       |
|  [SNMP]()           |  162, 161    | []()       | []()       |
|  [NTP]()          |   123       | []()       | []()       |
|  [Syslog]()         |    514      | []()       | []()       |


 
#### Layer: 6 - Presentation
| Name                                                                  | Port       | RFC                                             | Resource     |
| :-------------------------------------------------------------------: | :--------: | :---------------------------------------------: | :----------: | 
|  [JPEG]()           | []()            | []()       | []()       | 
|   [MIDI]()          | []()            | []()       | []()       |
|  [MPEG]()           | []()            | []()       | []()       |
|  [PICT]()           | []()            | []()       | []()       |
|  [TIFF]()           | []()            | []()       | []()       | 
|  [ASCII]()          | []()            | []()       | []()       |
 
#### Layer: 5 - Session
| Name                                                                  | Port       | RFC                                             | Resource     |
| :-------------------------------------------------------------------: | :--------: | :---------------------------------------------: | :----------: | 
|  [NetBIOS]()        | []()            | []()       | []()       | 
|  [NFS]()            | []()            | []()       | []()       |
|  [PAP]()            | []()            | []()       | []()       |
|  [SCP]()            | []()            | []()       | []()       | 
|  [SQL]()            | []()            | []()       | []()       |
| [ZIP]()             | []()            | []()       | []()       |
 
 
#### Layer: 4 - Transport
| Name                                                                  | Port       | RFC                                             | Resource     |
| :-------------------------------------------------------------------: | :--------: | :---------------------------------------------: | :----------: | 
|  [TCP]()            | []()            | []()       | []()       |
|  [UDP]()            | []()            | []()       | []()       |
 
 
#### Layer: 3 - Network
| Name                                                                  | Port       | RFC                                             | Resource     |
| :-------------------------------------------------------------------: | :--------: | :---------------------------------------------: | :----------: | 
| [ICMP]()            | []()            | []()       | []()       | 
|  [IGMP]()           | []()            | []()       | []()       | 
|  [IPsec]()          | []()            | []()       | []()       | 
| [IPv4]()            | []()            | []()       | []()       | 
|  [IPv6]()           | []()            | []()       | []()       | 
|  [IPX]()            | []()            | []()       | []()       | 
|  [RIP]()            | []()            | []()       | []()       |
 
 
#### Layer: 2 - Data Link
| Name                                                                  | Port       | RFC                                             | Resource     |
| :-------------------------------------------------------------------: | :--------: | :---------------------------------------------: | :----------: | 
|  [ARP]()            | []()            | []()       | []()       | 
|  [ATM]()            | []()            | []()       | []()       | 
|  [CDP]()            | []()            | []()       | []()       |
|  [FDDI]()           | []()            | []()       | []()       | 
| [Frame Relay]()     | []()            | []()       | []()       |
| [HDLC]()            | []()            | []()       | []()       | 
| [MPLS]()            | []()            | []()       | []()       |
| [PPP]()             | []()            | []()       | []()       |
| [STP]()             | []()            | []()       | []()       | 
| [Token Ring]()      | []()            | []()       | []()       |
 
 
#### Layer: 1 - Physical
| Name                                                                  | Port       | RFC                                             | Resource     |
| :-------------------------------------------------------------------: | :--------: | :---------------------------------------------: | :----------: | 
| [Bluetooth]()       | []()            | []()       | []()       |
| [Ethernet]()        | []()            | []()       | []()       | 
| [DSP]()             | []()            | []()       | []()       | 
| [ISDN]()            | []()            | []()       | []()       | 
| [WIFI]()            | []()            | []()       | []()       |





##### Resources list:
https://en.wikipedia.org
https://tools.ietf.org/html/

