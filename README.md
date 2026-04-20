# TCP-IP-Chat-Room-using-C
The TCP/IP Chat Room is a real-time multi-client chat application developed Using Adv C
# TCP/IP Chat Room using C

# Project Overview

The TCP/IP Chat Room is a real-time multi-client chat application developed using Advanced C Programming and Linux Networking concepts.  
This project simulates a messaging platform similar to WhatsApp group chats, where multiple clients can communicate through a centralized server.

The system supports both **single-user messaging** and **group communication**, while maintaining online user notifications and handling graceful termination of clients and server.

---

##  Project Objectives

✔ Build a real-time multi-client chat system  
✔ Support both **Single Chat** and **Group Chat**  
✔ Notify users when others **join** or **leave**  
✔ Handle client termination using signals  
✔ Ensure server crash detection  
✔ Implement secure Login and Registration  
✔ Maintain user database using file storage  

---

## 🛠 Technologies Used

- 💻 Advanced C Programming  
- 🔗 TCP Socket Programming  
- 🧵 POSIX Threads (pthread)  
- 🔒 Mutex Synchronization  
- 📡 Linux System Calls  
- 📂 File Handling  
- 📋 Linked List Data Structure  
- ⚡ Signal Handling  

---

## 🏗 System Architecture

      Client 1
         |
      Client 2
         |
      Client 3
         |
    ----------------
    |    Server    |
    ----------------
         |
 Message Routing

 ## ✨ Features

🔐 Login and Registration System  
👤 Single User Chat  
👥 Group Chat Messaging  
🟢 Online User Notification  
🔴 Offline Notification  
📡 Real-time Message Delivery  
🧵 Multi-client Handling using Threads  
⚙ Signal Handling (Ctrl + C termination)  
💾 File-based User Database  
🚨 Server Crash Detection  

 ## 🔄 Communication Flow

1. Client connects to the server  
2. User selects Login/Register  
3. Server validates credentials  
4. User added to online list  
5. Messages sent to server  
6. Server forwards messages to recipients  
7. Online/Offline notifications are broadcasted  

TCP_CHAT_ROOM/
│
├── client.c
├── client.h
├── server.c
├── server.h
├── server_fun.c
├── users.txt
└── README.md
