# Class 13 notes - Message Queues

## Socket.io Chat Example

**Explain to a non-technical recruiter what the Chat Example (above) does.**
its a chat messenger application

**What proof of life are we getting on the backend from the above app?**
listening on port 3000

**Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?**
broadcast

## Rooms

**What is a room and how might a room be useful?**
A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients

**How do you join a room?**
You can call join to subscribe the socket to a given channel

**how do you leave a room?**
Upon disconnection, sockets leave all the channels they were part of automatically, and no special teardown is needed on your part.

## Namespaces

**What is a Namespace and what does it allow you to do?**
A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

**Each namespace potentially has its own what? (hint: 3 things)**
Event handlers, rooms, middlewares

**Discuss a possible use case for separate namespaces.**
To split up logic based on user access needs.
