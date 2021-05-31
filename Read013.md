# Readings: Message Queues

# Review, Research, and Discussion

- What does it mean that web sockets are bidirectional? Why is this useful?

This mean that the connection is directly between the client and the server use TCP no HTTP. Bcause you don’t need to handle every request from client you just use events

- Does socket.io use HTTP? Why?
Yes, it can. Socket.io will try to establish a WebSocket () if possible but if it cannot it will fall back on HTTP

- What happens when a client emits an event?
The client take this emit and respond to it with an action or another emit messages.

- What happens when a server emits an event?
nothing actually that mean the event never been triggered the app will still functions the right way.

- What happens if a client “misses” an event?
Unhandled messages are ignored, behaves as if there is no event listener for the event

- How can we mitigate this?
Can avoid missing an event by always having handlers installed and then deciding in the handlers whether to do anything with the message or no

# Term

- Socket : one endpoint of a two-way communication link between two programs running on the network, a socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to
- Web Socket : WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

- Socket.io : a library that enables real-time, bidirectional, and event-based communication between the browser and the server, consists of a Node.js server and a javascript client library for the browser

- Client :  A Web client typically refers to the Web browser in the user’s machine or mobile device.

- Server : provides function, info, or service back to the client, acts as the main hub for communication

- OSI Model : The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network.

- TCP Model : stands for Transmission Control Protocol/ Internet Protocol. It is specifically designed as a model to offer highly reliable and end-to-end byte stream over an unreliable internetwork..

- TCP : transmission control protocol, one of the main protocols of the internet protocol suite

- UDP : User Datagram Protocol (UDP) – a communications protocol that facilitates the exchange of messages between computing devices in a network. It’s an alternative to the transmission control protocol (TCP).

- Packets : formatted unit of data carried by a packet-switched network, packet consists of control information and user data/payload


## Preparation Materials

- Socket.io Chat example
Sockets have traditionally been the solution around which most real-time chat systems are architected, providing a bi-directional communication channel between a client and a server

- Rooms and Namespaces
Rooms are part of namespaces where each namespace can be divided into several rooms and a very room handles a certain type of sockets (Join & Leave) it basically works by a socket (user) sends a join request to one of the available rooms and the server joins it in the room (it could need authentication or invitation depending on your application).