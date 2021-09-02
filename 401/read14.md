What’s the difference between a FIFO and a standard queue?
Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue.


How can the server be assured a message was properly received?
by recieving a req from the client


What classic design pattern is best represented by event driven programming?

observer pattern.

How do you test an event driven system?
Basically, an event-driven application architecture is one in which services (aka functions) within an application input data and output data via messages that are stored in a message queue. This differs from a synchronous architecture, in which data is passed straight to a service by making a direct call‏/

FIFO Queue
A FIFO queue is a queue that operates on a first-in, first-out (FIFO) principle. This means that the request (like a customer in a store or a print job sent to a printer) is processed in the order in which it arrives.

Pub/Sub

![img](https://images.ctfassets.net/ee3ypdtck0rk/5pLjHrKms2t73sDD8yheBv/83513ecb96bd0e9a0160f552e84dc926/pub-sub-pattern-architecture-at-scale.png)

In software architecture, publish–subscribe is a messaging pattern where senders of messages, called publishers, do not program the messages to be sent directly to specific receivers, called subscribers, but instead categorize published messages into classes without knowledge of which subscribers, if any, there may be. Similarly, subscribers express interest in one or more classes and only receive messages that are of interest, without knowledge of which publishers, if any, there are.

