## 


### 1. What does it mean that web sockets are bidirectional? Why is this useful?
BIDIRECTIONAL. Whereas HTTP relies on a client request to receive a response from the server for every exchange,
WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates
asynchronously, without requiring the client to submit a request each time. In the context of networked AV and control
systems, this allows devices to send and receive continuous streams of data to and from any point on the networ

### 2. Does socket.io use HTTP? Why?
a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js .

### 3. What happens when a client emits an event?
it will recieve the actions that inside the socket event from the server
### 4. What happens when a server emits an event?
it will recieve the actions that inside the socket event to the clients. 

### 5. What happens if a client “misses” an event?
he will recieve when he connect.

----------------------------

### Terms:

**Socket:** is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. An endpoint is a combination of an IP address and a port number.

**Web Socket:**
is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

**Socket.io:**
is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

