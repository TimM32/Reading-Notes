# Reading Notes Class 12

- What is a Web Socket? The WebSocket API is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server. With this API, you can send messages to a server and receive event-driven responses without having to poll the server for a reply.
- Describe the Web Socket request/response handshake and what happens once the connection is established. The handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol.
- Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client. WebSockets is an advanced technology that enables bidirectional real-time interactive communication between a client and a server. It is achieved by defining a standardized mechanism for the server to send data to the client without the client first making a request.

- What does the event handler io.on() do? The event handler io.on() in Socket.IO is used to listen for incoming events from clients or other sources. It allows you to define a callback function that will be executed when a specific event occurs. This event handler is typically used on the server-side to handle events triggered by clients.
- Describe some possible proof of life or proof that the code works as expected. Connection is established, event handling, and there is some logging and debugging.
- What does socket.emit() do? emit() to send a message to all the connected clients. This code will notify when a user connects to the server.

- What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0). Differences between WebSocket and Socket.IO. The main advantages of Socket.IO over WebSockets are: Unlike WebSocket, Socket.IO allows you to broadcast a message to all the connected clients.
- When would you use Socket.IO? As we have explored, Socket.IO is a great tool for developers wanting to set up bi-directional socket connections between client and server. This makes simple applications such as live chat much simpler to implement.
- When would you use WebSockets? When to use WebSockets. Use WebSockets when you want two-way communication between two networked systems, for example when building a chat application. WebSockets are also very useful for data visualization dashboards or maps that need to reflect real-time data values.

## Additional Information
