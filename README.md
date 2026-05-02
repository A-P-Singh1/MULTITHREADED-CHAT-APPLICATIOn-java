# MULTITHREADED-CHAT-APPLICATION-java




COMPANY : CODTECH IT SOLUTIONS

NAME : ADITYA PRATAP SINGH

INTERN ID : CTIS8188

DOMAIN : JAVA PROGRAMMING

DURATION : 6 WEEKS

MENTOR : NEELA SANTHOSH KUMAR









This project focuses on building a real-time multithreaded chat application using Java, where multiple users (clients) can communicate simultaneously through a centralized server. The main objective is to understand how network programming (sockets) and multithreading work together to enable efficient, concurrent communication between multiple clients in a distributed system.
The entire application is designed using Java, leveraging its built-in libraries for networking (java.net) and multithreading (java.lang.Thread). The development was carried out in an IDE like Visual Studio Code, along with Java extensions that provide features such as syntax highlighting, debugging, and smooth execution.

Overview of the System
The chat system follows a client-server architecture, where:


The Server acts as the central hub that manages all client connections.


Multiple Clients connect to the server and exchange messages.


Each client runs on a separate thread, allowing simultaneous communication.


This ensures that the application supports real-time messaging without delays, even when many users are connected.

Key Features and Functionalities Implemented
1. Server Setup and Socket Programming
A server program was created using Java sockets to listen for incoming client connections on a specific port. Once a client connects, the server accepts the connection and establishes a communication channel using input and output streams.
The server runs continuously, ensuring that new clients can join the chat at any time without interrupting existing users.

2. Multithreading for Multiple Clients
To handle multiple users efficiently, multithreading was implemented:


Each connected client is assigned a separate thread.


This allows the server to manage multiple clients simultaneously.


Messages sent by one client are processed independently without blocking others.


This is the core feature that enables concurrent communication, making the system scalable and efficient.

3. Client-Server Communication
Each client application connects to the server using sockets and can:


Send messages to the server


Receive messages from other connected clients


The server acts as a message broadcaster, forwarding messages from one client to all others in real time.

4. Message Broadcasting System
A broadcasting mechanism was implemented where:


When a client sends a message, the server receives it.


The server then distributes (broadcasts) that message to all connected clients.


This ensures that all users stay updated in real time.



5. Input and Output Handling
Efficient input/output stream handling was used to:


Read messages from clients


Send messages back to clients


Maintain continuous communication without interruption


This ensures smooth data transfer between server and clients.

6. User-Friendly Interaction
A simple console-based interface was provided for clients, allowing users to:


Enter messages


View incoming messages instantly


This simulates a real-time chat environment similar to messaging applications.

Development Environment
The project was developed using Java in Visual Studio Code. The following tools and extensions were used:


Java Extension Pack for coding support and debugging


Integrated terminal for compiling and running the application


Built-in debugging tools for identifying and fixing errors


This setup provided a smooth and efficient development workflow.

Working of the Application


The server starts and waits for client connections.


Multiple clients connect to the server using sockets.


Each client is handled in a separate thread.


When a client sends a message:


The server receives it


The server broadcasts it to all other clients




All clients receive and display the message instantly.



Conclusion
This project provided a strong understanding of multithreading and socket programming in Java. By building a real-time chat system, I learned how concurrent processes are managed efficiently and how multiple users can interact within a single application without performance issues.
The implementation demonstrates how multithreading improves responsiveness and scalability in network-based applications. The concepts learned in this project are highly applicable in developing real-world systems such as messaging apps, online collaboration tools, and distributed systems.




INPUT :<img width="446" height="145" alt="Screenshot 2026-04-12 014932" src="https://github.com/user-attachments/assets/4e7bc01b-394f-45b8-9605-5aeaf742c43d" />

OUTPUT :<img width="464" height="196" alt="Screenshot 2026-04-12 014959" src="https://github.com/user-attachments/assets/06496942-5633-4c1c-85e6-15dfca31c3f6" />
