# Message Queues

## [Socket.io Chat Example](https://socket.io/get-started/chat/)

1. Explain to a non-technical recruiter what the Chat Example (above) does.\
The chat example is a simple way of sending chat messages using socket.io, which allows virtually instant communication between multiple clients since socket.io establishes a duplex connection between the client and server.
2. What proof of life are we getting on the backend from the above app?\
A couple of things, we are getting users are connecting/disconnecint, as well as getting the message sent displayed.
3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?\
Use add `io.broadcast.emit()`

## [Rooms](https://socket.io/docs/v4/rooms)

1. What is a room and how might a room be useful?\
Rooms are virtual channels which holds info sockets that join it. From there, you can send messages to all sockets in the room.
2. How do you join a room?\
You send an emit from the client with the trigger in the server to join the room, then call socket.join(room) in server.
3. how do you leave a room?\
You send an emit from the client with the trigger in the server to leave the room, then call socket.leave(room) in server.

## [Namespaces](https://socket.io/docs/v4/namespaces/)

1. What is a Namespace and what does it allow you to do?\
Namespaces are a way to separate your server address into different paths. This allows you to have different endpoints for different purposes.
2. Each namespace potentially has its own what? (hint: 3 things)\
 `/` endpoint, clients, and rooms.
3. Discuss a possible use case for separate namespaces\
If you application needs separate endpoints to sell different products, you can use namespaces to separate the endpoints then use rooms to separate the clients if needed.
