# Repository-Entries-Management-With-a-Client-Server-Socket-Principle
A project that manages multiple repositories each containing 2 text files, with each file containing entries destined to be used with a Person structure with attributes : name, last name, phone number. The project uses a menu to give the user the available choices (which are listing a repository given by the user either randomly or while sorting the files and the repository, creating a new repository with a given name, deleting a repository with a given name, deleting a file with a given name and given its repository, searching, modifying or deleting a Person entry with its name as a parameter inside a given repository and given file inside it). The management is assured with a Client/Server model using sockets, as the server starts it sends the menu to the client via a socket, and the client program displays this menu after receiving it and takes the option written by the user and sends it to the server via a socket, and then the server calls for the correspending function and the communication continues using sockets. The server is capable of interacting with multiple clients as I forked the prcoess and used a child socket to communicate with the client, while the parent socket keeps listening in the port.
