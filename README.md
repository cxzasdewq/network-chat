Command ```run``` ```ServerLauncher``` → ```run``` ```Client```.

A network chat with basic functionality. 
The project consists of two main parts: server and client. 
The client does not have a GUI and all interaction occurs through the console. 
The relationship between client and server is implemented using sockets.

--- 
Server functionality: 
- [x] Setting the port for connecting clients via a settings file;
- [x] Ability to connect to chat at any time;
- [x] Sending new messages to clients;
- [x] Logging of all messages sent through the server.

Client functionality:
- [x] Selecting a name to participate in the chat;
- [x] Reading application settings from a file;
- [x] Connect to the server specified in the settings;
- [x] Exit chat using the exit command → ```/exit```;
- [x] Logging of all customer messages with saving chat history.