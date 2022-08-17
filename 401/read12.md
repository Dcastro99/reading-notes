# **Socket.io**

> ## Web Sockets

1. What is a Web Socket?

-  It's a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.

-  is an automated process of negotiation between two participants through the exchange of information that establishes the protocols of a communication link at the start of the communication, before full communication begins. Once this happens, full communication of passing commands can begin.

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

- request

> ## Socket.io Tutorial

1. What does the event handler `io.on()` do?

- The `io.on` event handler handles connection, disconnection, etc., events in it, using the socket object.

2. Describe some possible proof of life or proof that the code works as expected

- run your server and check the terminal. It should read

```A user connected```

3. What does socket.emit() do?

- `socket.emit` allows you to create custom events

> ## Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

- WebSocket is real time

- Socket.io is a library

2. When would you use Socket.IO?

- When you built real time applications, like Group chat Room, video conferencing, multiplayer games etc.

- If you want server to push data by itself without calling from client.

3. When would you use WebSockets?

- real time communication

## VIdeos

> ## OSI Model Explained

1. What are a couple of key takeaways from this video?

- its interesting to see how data is passed along through each layer. Each layer handles different levels of functionality within thoughs layers all to allow a user to send or recieve data.

> ## TCP Handshakes Explained

1. Translate the gist of this video to a non-technical friend

- Basically its communication between client and server.  Lets look at it this way. A communication between a(book) library and a person. A person ask, hey library can I have access to your books? and the server verifies that the person is a member. Library acknowleges their membership and grants access. So on and sofpr

> References

- [What is a web socket](https://en.wikipedia.org/wiki/WebSocket)
- [Handshake](https://en.wikipedia.org/wiki/Handshaking)
- [socket tutorial](https://www.tutorialspoint.com/socket.io/socket.io_hello_world.htm)


## Things I want to know more about