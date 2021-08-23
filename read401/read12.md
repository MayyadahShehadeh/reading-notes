## Socket.io

### 1. What is the benefit of transforming data into packets?
TDM-based networks must transform into packet-based networks to meet the demands of pervasive data-centric applications and services. Packet-based networks not only enable new innovations, services, and business opportunities, they are also the most cost-effective, efficient, and scalable networks for content delivery.

### 2. UDP is often refereed to as a connectionless protocol. Why is this?
UDP is a connectionless protocol. It is known as a datagram protocol because it is analogous to sending a letter where you don't acknowledge receipt.



### 3. Can a socket server application have multiple socket connections?
Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.

### 4. Can a socket connection application be connected to multiple socket servers?
A connected socket is assigned to a new (dedicated) port, so it means that the number of concurrent connections is limited by the number of ports, unless multiple sockets can share the same port.



--------------
### Terms:

**Observer Pattern:** 
The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

**Listener:** 
The listener is programmed to react to an input or signal by calling the event's handler.

**Event Handler:**
is a callback routine that operates asynchronously and handles inputs received into a program (events)

**Event Loop:**
 A programming structure that continually tests for external events and calls the appropriate routines to handle them. An event loop is often the main loop in a program that typically waits for the user to trigger something. 



 
