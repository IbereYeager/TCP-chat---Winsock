# TCP-chat---Winsock
This is a simple TCP server project written in C++ -  Winsock API (Windows) 

Code Structure:
Winsock Startup: Kicks off the Winsock library with WSAStartup, and sets up the server socket.
Setup & Binding: Sets the IP and port, and binds them to the socket so the server knows where to listen.
Connection Handling: Waits for a client to connect, then prints out some info about the client (like IP and port).
Sending Thread: Runs a separate thread that lets the server send messages to the client without blocking.
Receiving Loop: Keeps listening for incoming messages from the client and prints them out when they arrive.
Cleanup: Closes the sockets and shuts down Winsock properly when everything's done.

FYI: To actually test this, you'll need a client. I used PuTTY for testing...
