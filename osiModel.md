---
title: OSI Model
---

## OSI Model
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
  - Provies the control functions neccesary to establish, manage, and terminate, the connections as requried to satisfy the user request



- Presentation
  - Protocol Converstion, data translation
  - ASCII, JPEG
  - Accepts and structures the message for the application. It translates the messsage from one code to another, if necesary this layer is responsible for the data compression and encryption.

- Application
  - Support for Applications
  - HTTP, FTP, SMTP (email)
  - interacts with the application programs that incorporate a communication component such as your internet browser and email. This layer is resposible for logging the message in, interpretaing the request, and determining what informmaiton is needed to support the request.




Standardization of layers of labs for how a network should be set up.

framework that ensure compatability between networks.

nit card works at the physical layer.
Physical layer is everything you can touch.
Hub is at the physical

Datalink works for mac addresses
switch is at the data link layer.

Network
Ip sits there

transport 
Ensures stuff gets there ok.
Unreliable or Reliable
will it go back to where it was at when it disconnected

Session 
establishing how long you're talking with another network. If you're trying to connect to another network. Buffering and time outs

Presentation
Translates the standard data into other types of files. So internet speak into ascii or Jpeg

Application
these are the protocols that show how things are going to. 



