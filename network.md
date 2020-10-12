---
title: Network
---


# network and security


## Lesson 1

- Protocol
  - Set of rules established for users to exchange information.
m 

### Network Topologies
#### Physical Topologies
- clear
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
- Data Link
  - Provies for the flow of data
    - Handles error recover, flow control (syncronization), and sequencing (which terminlals are sending and which are recieving). it is considered the "media access control layer" and is where media access control (MAC) addressing is defined. The Ethernet 802.3 standard is defined in this area, which is why the MAC address is sometimes called the ethernet address.
   - Examples MAC adddresses  - Examples, IP IPX (internet protocol, interwork packet exchange)
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


## lesson 4 Wireless Networking
### the IEEE 802.11 wireless LAN standard

wireless lans create ad hoc networks when put a bunch together you get a wireless mesh netowrk

802.11 N can use MIMO (Multiple Input Multiple Output) it splits the signal over different wavelengths
 
802.11 AC uses 5 ghz and can have mulitple users using MIMO
 
- DSSS
  - Direct Sequence Spread Specturm
  - Spreading over 14 channels over a GHZ frequency
- OFDM
  - Orthogonal Frequency Division Multiplexing
  - uses invertion math to make sure you're not on the same wavelength as another band


802.11
- a
  - this standard can provide data transfer raties up to 54 mpbs and an oeprating range of up to 75 feet. it operates at 5 ghz and uses OFDM
- b
  - This standard can provide data transfer rates up to 11 mbps and an operating range up to 150 feet. it operates at 2.4 ghz and uses DSSS or OFDM
- g
  - this standard can provide data transfer rates up to 54 mbps and an operating range up to 150 feet. it operates at 2.4 ghz and uses DSSS or OFDM
- N 
  - This highspeed wireless connectivity promises data transfer rates over 200 mbps. it operates at 2.4 ghz and 5ghz and uses DSSS or OFDM 
- i 
  - This standard for WLANs provides improved data encryption for netowrks that use A B and G standards 
- r 
  - this standard is designed to speed handoffs between access points or cells in WLAN. this standard is critical addition to 802.11 WLANS if voice traffic is become widely deployed
- ac
  - this is the next generation of high speed wireless connectivity. This technology promiese data rates up to 1 GPbps and operates over the 5ghz band.
 
 
 

### 802.11 wireless networking

- SSID
  - service set identifier

- CAPWAP
  - configuraiton and provisioning of wireless access points

### Bluetooth, WiMAX, RFID, and Mobile Communications
#### Bluetooth
Bluetooth connects in a piconet
a pico net can hold up to 8 devices
a piconet works as a star topology with the others being slaves.

#### WiMax

WorldWide Interoperability for Microwave Access
Broadband Wireless access (BWA) 

802.16e holds a lot of promise as a mobil air interface.

#### RFID
Radio Frequency Identification


RFID tags catagories
- Passive
  - provided to a passive tag by rectifiying the RF energy transmitted from the read, that strikes the RF tag attena. 
- Semi-active
  - with semi active tags, a battery powers the electronivs on a tag but the tag uses back scatter to transmit informaiotn back ot the reader.
- active
  - with avtive tags, a better powers the tag and transmits a signal back ot the reader. Basically this is a radio transmitter. new active RFID tags are inrocporating wireless ethernet, the 802.11 b wifi connectivity. 
    
Frequency Opperations
- low frequency tags
  - lf tags typically use frequency shift keying between 125 khz and 134 khz. they're suitable for iniaml identification. 
- high frequency tags
  - HF tags oeprate in the 13.56 Mhz industrial band, high frequency tags have been availbly commercially since 1995. the range is aproximately 1 meter
- Ultra high frequency tags
  - UHF tags work at the 860-960 Mhz and at 2.4 Ghz. the data rates for these tags can be 50-150 kpbs and great. the tags are popular for trancking inventory the read rang for passive uHF tags is 2.6 meters which amke sthem a good choice for reading pallet tags. however if an active tag is used a read range up to 100 meters is possibe.


#### Mobile Communications
-CDMA
  - Code Division Multple Access
  - communicaiotns system in which spread spectum techniques are used to multiplex more than one signal within a single channel, in this case each device uses a different binary sequence to muldate the carrier, spread the spectrum of the wave form. the signals are seperaed at the reciever by a correlator that accepts only the signals from the seleced binary sequence. 
- LTE/4g
  - Long Tem Evolution is a 4g wireless communication standard. it is designed to provide speeds up to 10x those of 3g networkds. 
- HSPA+
  - evolved high speed packet access provides netowrk speeds comparable to those of LTE networks. theoretical speeds are 168 mpbs for download and 22mbps uplink
- 3g/4g
  - developed to provide boradband network wireless service. the stndard degining 3g wireless is called International Mobile OCmmunicaiotn or IMT200 4g is it's sucessors and has download speeds up to 100mpbs
- Edge
  - Enhanced Data GSM evolution provudes download speeds of 384 kbps
- NFC
  - a concept related to mobile communicaiton and smartphones is NFC, Near Field COmmunications. they can communicate with one naother if they're withing 4 cm of one another. 
    



Cohotrt 1 video


WEP + AES best encryption for wireless


Cohort 2 

Firewall
DMZ - semi protected computer that is halfway into the network, it's behind firewall but more easily accessible than full into the network.



Data rates for T lines
t1 - 1.544 Mpbs
t2 - 6.312 Mpbs
t3 - 44.736 Mpbs
t4 - 274.176 MPbs

E1 - 2.048 Mbps
E3 - 34.368 Mbps

