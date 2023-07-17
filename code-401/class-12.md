# Socket.io

## [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

1. What is a Web Socket?\
A Web Socket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.
2. Describe the Web Socket request/response handshake and what happens once the connection is established.\
The client makes a request through a standard HTTP request to the server. The server modifies the request header to indicate that it wants to switch protocols from HTTP to WebSocket. This is the handshake. After, a duplex connection is established between the client and server via WebSocket.
3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a **request** from a client.

## Socket.io Tutorial

1. What does the event handler io.on() do?\
io.on() is an event handler that listens for events.
2. Describe some possible proof of life or proof that the code works as expected.\
You can use console.log() to see if the code is working as expected.
3. What does socket.emit() do?\
socket.emit() sends an event to the client.

## Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).\
WebSocket is a protocol that defines how communication is established between a client and a server while Socket.IO is a library that enables communication between the browser and the server using the WebSocket protocols.
2. When would you use Socket.IO?\
I would use socket.IO to build an application as this has the components needed to connect WebSocket built.
3. When would you use WebSockets?\
I would use the WebSockets protocol when the application needed functionally to have an open channel of communication.

## OSI Model Explained

1. What are a couple of key takeaways from this video?

## TCP Handshakes Explained

1. Translate the gist of this video to a non-technical friend.
