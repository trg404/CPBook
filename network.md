---
title: Network
---


# network and security


## Lesson 1

- Protocol
  - Set of rules established for users to exchange information.


### Network Topologies
#### Physical Topologies
- *Types*
  - Star
    - All computers are connected to one switch or hub. 
  - Ring
    - All computers are connected to two others in a giant circle, usually done in dual rings these days
  - Bus
    - computers form a line with one coax running between them. they include breaks and terminators
  - Mesh
    - all computers are directly connect to every other computer
      - Full mesh all connects to all
        - n(n-1) / 2 formula to figure out how many conections you need. 
      - Partial Mesh they only connect to some.


#### Logical Topology
How information in a network flows.


Which kind of cable?
- Crossover Cable
  - Same Same (same kind of devices)
  - crossover - same same - Router
- STUD
  - Straight through unlike devices
  - Not the same kind of device


### OSI Model
_*Open Systems Interconnection*_


7. Application
6. Presenation
5. Session
4. Transport
3. Network
2. Data Link
1. Physical


- Physical 
  - Signals and media 
  - provides the electrical and mechanical connection to the network.
  - Examples, Twisted Pair Cable, Fiber, Nics, Electronic Industries Alliance/ Telecommunications Industry Association (EIA/TIA) - related technologies, UTP, FIber, and newtwrok interface cards (NICs)

- Data Link
  - Provies for the flow of data
    - Handles error recover, flow control (syncronization), and sequencing (which terminlals are sending and which are recieving). it is considered the "media access control layer" and is where media access control (MAC) addressing is defined. The Ethernet 802.3 standard is defined in this area, which is why the MAC address is sometimes called the ethernet address. 
   - Examples MAC adddresses

- Network
  - Provides routing decision
  - Examples, IP IPX (internet protocol, interwork packet exchange)
  - accepts outgoing messages and combines messages or segments into packets, adding a header that includes routing information. it acts as the network controller. 

- Transport 
  - ensures error free packets 
  - Examples, TCP UDP (Transmission Control Protocolm and User Datagram protocol) 
  - is concerned with message integrity between source and destination. it also segments/ reassembles (the packets) and handles flow control.
 
- Session 
  - Establishes, manages, and terminates sessions. 
  - NFS, SQL (Network file system, Structured Query Language) 
  - Provies the control functions neccesary to establish, manage, and terminate, the connections as requried to satisfy the user request.
 
- Presentation
  - Protocol Converstion, data translation
  - ASCII, JPEG
  - Accepts and structures the message for the application. It translates the messsage from one code to another, if necesary this layer is responsible for the data compression and encryption. 
  
- Application
  - Support for Applications
  - HTTP, FTP, SMTP (email) 
  - interacts with the application programs that incorporate a communication component such as your internet browser and email. This layer is resposible for logging the message in, interpretaing the request, and determining what informmaiton is needed to support the request. 
    
    
    
### Ethernet LAN

- Frame
  - Data over an ethernet
  - Header
    - Preamble
    - Start Frame Delimiter
    - Destination MAC address and source
    - Mac Address
    - Length/Type
  - Data
    - Pad (data added to bring up to minumum)
  - Trailer
    - Frame Check Sequnce


### Home Networking
 802.11 
  - A, 54Mbps 75 ft, 5GHZ
  - b, 11 Mbps 100-150 ft, 2.4Ghz
  - g 54 Mbps 150Ft 2.4Ghz
  - N 4x 802.11g (200+Mbps) 2.4ghz or 5 Ghz
  - AC  1.3 Gpbs 5hz

- Switch
  - Estabishes a direct connection from the sender to the destination without passing the data trafic to other networking devices.
- Router
  - Connects two ore more networks using a single connection to the ISP
- Access Point
  - Interconnects wireless devices and provides a connection to the wired lan
- GateWay
  - provides high speed data access via a cable or telephone company's DSL connection.



### Assembling Office LAN

- 10Base2
  - 10Mbps, over Coaxial Cable up to 185 m, also called thinnet
- 10Base5
  - 10 Mpbs over coaxial cable up to 500 m, also called Thicknet
- 10BaseT
  - 10Mpbs over twisted pair
- 10BaseF 
  - 10Mpbs over multimode Fiber optic cable
- 10BaseFL
  - 10 Mbps over 850 nm multimode fiberoptic cable
- 100BaseT
  - 100Mbps over twister-pair also called fast ethernet
- 100baseFX
  - 100Mpbs over Fiber
- 1000baseT
  - 1000Mpbs over twisted pair
- 1000baseFX
  -1000Mbps over fiber
- 1000BaseLS
  - 1000Mpbs over fiber
- 1000baseSX
  - 1000MBPS over fiber
- 1000baseLX
  - 1000Mpbs over fiber
- 10GE 
  - 10GB (10GBaseT) ethernet


### testing and troubleshooting LAN

use the ping command.


## lesson 4



## Lesson 10


## Lesson 12

## Lesson 13



