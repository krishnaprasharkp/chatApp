# Chat Application

A real-time console-based **Chat Application** developed using C++ that enables users to exchange messages through a simple client-server communication model. The project demonstrates networking fundamentals, message handling, and real-time communication concepts.

---

##  Overview

This Chat Application is designed to simulate real-world messaging systems where users can send and receive messages instantly. The project focuses on implementing the core logic behind communication systems while strengthening concepts of socket programming, networking, and system-level communication.

---

##  Features

-  Real-time message exchange
-  Multi-user communication support
-  Client-Server architecture
-  Instant message delivery
-  Socket-based communication
-  Console-based interface
-  Structured communication flow

---

##  Tech Stack

| Technology | Purpose |
|------------|----------|
| C++ | Core application development |
| Socket Programming | Network communication |
| OOP Concepts | Application structure |
| TCP/IP Protocols | Reliable message transfer |
| File Handling (if used) | Message storage |

---

##  Project Structure

```bash
chatApp/
│
├── server.cpp          # Handles server-side communication
├── client.cpp          # Handles client-side communication
├── messages/           # Stores chat data (if implemented)
├── assets/             # Screenshots or resources
└── README.md           # Project documentation
```

---

##  Working Flow

```text
Start Server
      |
      v
Wait for Client Connection
      |
      v
Client Connects to Server
      |
      v
Establish Communication Channel
      |
      v
Send / Receive Messages
      |
      v
Display Messages in Real-Time
      |
      v
Terminate Connection
```

---

##  Concepts Used

- Socket Programming
- Client-Server Architecture
- TCP/IP Networking
- Object-Oriented Programming
- Message Handling
- Input/Output Streams
- Process Communication
- Real-Time Data Transfer

---

##  Learning Objectives

This project was built to understand:

- How real-time chat systems work
- Network communication fundamentals
- Client-server interaction
- Message transmission protocols
- Building communication-based applications
- Practical implementation of socket programming

---

##  Core Functionalities

### Server Module
- Accepts client connections
- Manages communication sessions
- Handles message transfer

### Client Module
- Connects to server
- Sends messages
- Receives messages in real time

### Communication Layer
- Establishes network connection
- Transfers messages reliably
- Maintains active communication session

---

##  Future Enhancements

- GUI-based interface
- Group chat support
- User authentication system
- End-to-end encryption
- Media and file sharing
- Chat history storage
- Online user status
- Multi-client support
- Database integration

---

##  How to Run

### Compile Server

```bash
g++ server.cpp -o server
```

### Run Server

```bash
./server
```

### Compile Client

```bash
g++ client.cpp -o client
```

### Run Client

```bash
./client
```

---

##  Learning Outcomes

Through this project, I gained hands-on experience in:

- Computer Networks
- Socket Programming
- Real-Time Communication Systems
- C++ Application Development
- Client-Server Design
- Networking Fundamentals

---

##  Author

**Krishna Prashar**  
B.Tech Computer Science & Engineering  
Guru Nanak Dev University, Amritsar

GitHub: https://github.com/krishnaprasharkp

---

## ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.
