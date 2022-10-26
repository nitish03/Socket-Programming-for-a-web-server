# Socket-Programming-for-a-web-server
The project is about performing socket programming for TCP connections using python programming. 
TCP is a connection-oriented protocol, which means before the client and server start to send data to each other they first need to handshake and established a connection. The client socket address and server socket address associate with each other to create a TCP connection. The socket address consists of the host and port.
In the program, serverSocket creates a new socket during the three-way handshake that is a welcoming door for the client-server. serverHost is the IP address and serverPort is the port number. I am using my computer’s IP address and the port is 7000. serverSocket.listen listens for the client. 
The parameter in the listen code defines that the maximum number of the queued connections is at least 1. The accept() method is initiated when listen() method notifies there is a connection then accept() method creates a new connection. This is where the client and server complete the handshake and create a TCP connection.
I have a file name server.html that has a message. When the server is running, and the client tries to make a connection with the server and the message is displayed. If there is no file, it displays 404 Not Found.
