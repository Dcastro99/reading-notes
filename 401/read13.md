# **Message Queues**

> ## Socket.io Chat Example

1. Explain to a non-technical recruiter what the Chat Example (above) does.

- It creates a space where a user can login to and communicate with whom ever is in that space as well in realtime.

2. What proof of life are we getting on the backend from the above app?

- a console log of the connection and disconnection thats happening from user

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

- broadcast

>## Rooms

1. What is a room and how might a room be useful?

- you can emmit or broadcast a something to anyone in a specific room

2. How do you join a room?

```javascript
io.on("connection", (socket) => {
  socket.join("some room");
});
```

3. how do you leave a room?

```javascript
io.on("connection", socket => {
  socket.on("disconnecting", () => {
    console.log(socket.rooms); 
  });
```

>## Namespaces

1. What is a Namespace and what does it allow you to do?

- Namespaces are like endpoints. example:

if route is `localhost://3000` and you have a you have an namespace of `driver` the namespace is now `localhost://3000/driver`

2. Each namespace potentially has its own what? (hint: 3 things)

- event handlers
- rooms
- middlewares

3. Discuss a possible use case for separate namespaces

- If you have many clients and want to directly interact with a client. This would be the way. This allows the user to have access to only the namespace they are in.

## Things I want to know more about