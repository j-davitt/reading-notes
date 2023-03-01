# Class 12 notes - Socket.io

## Web Sockets

**What is a Web Socket?**
a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

**Describe the Web Socket request/response handshake and what happens once the connection is established.**
The handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol.

**Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.**
HTTP request

## Socket.io Tutorial

**What does the event handler io.on() do?**
listening for an event

**Describe some possible proof of life or proof that the code works as expected.**
console log that a connection has occured

**What does socket.emit() do?**
it broadcasts an event

## Socket.io vs Web Sockets

**What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).**
WebSocket is the protocol and Socket.io is the library.

**When would you use Socket.IO?**
With broadcasting

**When would you use WebSockets?**
full duplex communications
