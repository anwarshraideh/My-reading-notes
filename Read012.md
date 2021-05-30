# Readings: Socket.io

# What is the benefit of transforming data into packets?

Packets are intended to transfer data reliably and efficiently. Instead of transferring a large file as a single block of data, sending smaller packets helps ensure each section is transmitted successfully.


# UDP is often refereed to as a connectionless protocol. Why is this?

because No connection needs to be established between the source and destination before you transmit data.

# Can a socket server application have multiple socket connections?
A server socket listens on a single port

# Can a socket connection application be connected to multiple socket servers?
A single client-side server should only connect to one socket server.

# Can an application be both a socket server and a socket connection?
Yes


# Vocabulary Terms

- Observer Pattern :  Observer is a behavioral pattern which means that is concerned about communication      between objects.

- Listener :  a function that listens for an event to occur

- Event Handler : can be used to handle and verify user input, user actions, and browser actions: Things that should be done every time a page loads.

- Driven Programming : programming paradigm in which the flow of the program is determined by events such as user actions, message passing

- Loop : is a programming construct or design pattern that waits for and dispatches events or messages in a program

- Queue : queue where events from an application are held prior to being processed by a receiving program or system

- Call Stack: is a stack data structure that stores information about the active subroutines of a computer program.

- Emit/Raise/Trigger : in event-driven programming, emit sends a message to trigger a response and raise an event

- Subscribe : waiting for the events to take a place in the event loop cycle.

- database : an organized collection of data, generally stored and accessed electronically from a computer system


## WebSocket

- Computer communications protocol, providing full-duplex communication channels over a single TCP connection
- WebSocket protocol enables interaction between a web browser (or other client application) and a web server with lower overhead than half-duplex alternatives such as HTTP polling, facilitating real-time data transfer from and to the server

## Socket.io Tutorial
- Works on every platform, browser, or device
- Built on top of the WebSockets API (Client-side) and Node.js

## Socket.io vs. Web Sockets

- WebSocket is the communication protocol that provides bidirectional communication between the client and the server over a TCP connection
- WebSocket remains open all the time so they allow the real-time data transfer
- When clients trigger the request to the server it does not close the connection, it persists and waits for the client or server to terminate the request

