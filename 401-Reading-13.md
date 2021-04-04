
Reading Note 13

# What does it mean that web sockets are bidirectional? Why is this useful?
-	It means that you may efficiently push data from the server to the client. ... It must be handled both client-side and server-side. Of course that implies that both software be updated (old browsers and old servers can't handle websockets).

-	Socket bidirectional is useful . Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time. In the context of networked AV and control systems, this allows devices to send and receive continuous streams of data to and from any point on the network.

# Does socket.io use HTTP? Why?
- Yes the socket.io uses HTTP server so it can serve its own client code through /socket.io/socket.io.js .

- It seems that Socket.IO is always dependent on a http server, to the point that it will create one for you


# What happens when a client emits an event?
- Whenever client emits an event the server will call this function every time it receives an HTTP request. All it has to do to is invoke, or “emit”. 

# What happens when a server emits an event?
- Every time we click that button, that event is emitted and our callback fires ... We're using an array because there could be more than one subscriber for each event. ... When it happen, we'll use event name we're storing ( emit("event") ) ... specific environment. so it'll work in both the browser and the server.

# What happens if a client “misses” an event?
- Each event has a sequence number, and the client can tell, based on the event sequence number, if any event is missing in the sequence. ... The problem is that the client regularly receives only portions of the event sequence. In fact, there is a regular pattern to this. For every 250 events there is a large gap.


## Vocabulary Term
- Socket in JavaScript is a library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for Node. js. Both components have a nearly identical API.

- The WebSocket API is an advanced technology that makes it possible to open a two-way interactive communication session between the user's

- The Clients interface provides access to Client objects. Access it via self. Clients within a service worker. Client applications run in a browser, such as Netscape Navigator, and server applications run on a server, such as Netscape Enterprise Server

- A server is a computer that provides data to other computers. It may serve data to systems on a local area network (LAN) or a wide area network (WAN) over the Internet. Many types of servers exist, including web servers, mail servers, and file servers. Each type runs software specific to the purpose of the server.

- OSI Model is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a

- TCP  is a standard that defines how to establish and maintain a network conversation through which application programs can exchange data. TCP works with the Internet Protocol (IP), which defines how computers send packets of data to each other.

- UDP is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. It speeds up transmissions by enabling the transfer of data before an agreement is provided by the receiving party.

- Packets is a small amount of data sent over a network, such as a LAN or the Internet. Similar to a real-life package, each packet includes a source and destination as well as the content (or data) being transferred.
 
# reference 
https://www.google.com/ 
https://www.w3schools.com/
https://stackoverflow.com/
javascript & jquery textbook

