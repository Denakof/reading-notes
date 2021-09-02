# read13
What does it mean that web sockets are bidirectional? Why is this useful?

Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.

Does socket.io use HTTP? Why?
Even when websockets can be used, the initial connection setup it done over HTTP. Also, a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js .

What happens when a client emits an event?
will run the event in server that was listinig for this event


What happens when a server emits an event?
each time a peer connects to it.

What happens if a client “misses” an event?
The client will be disconnected.


How can we mitigate this?
We should consider a reconnect.

Socket
A socket is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. An endpoint is a combination of an IP address and a port number

Web Socket
is an advanced technology that makes it possible to open a two-way interactive communication session between the user’s browser and a server. With this API, you can send messages to a server and receive event-driven responses without having to poll the server for a reply.


Client: a computer hardware device or software that accesses a service made available by a server.

Server: is a physical computer dedicated to run services to serve the needs of other computers. Depending on the service that is running, it could be a file server, database server, home media server, print server, or web server.

OSI Model :
 (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software.


A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients:


![img](https://socket.io/images/rooms.png)


In networking, a packet is a small segment of a larger message. Data sent over computer networks*, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them.
