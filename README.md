
The TCP/IP Chat Room is a real-time multi-client chat application developed Using Adv C
# TCP/IP Chat Room using C

<img width="1600" height="780" alt="image" src="https://github.com/user-attachments/assets/14282d7e-7916-4e2c-a29b-fcd29c42c973" />

<img width="1600" height="780" alt="image" src="https://github.com/user-attachments/assets/fe6c7ca6-8e71-4712-a20d-02d52b026237" />

<img width="1600" height="780" alt="image" src="https://github.com/user-attachments/assets/485dfb5c-c5c5-40d6-a839-3fde6435f5b8" />

<img width="1600" height="780" alt="image" src="https://github.com/user-attachments/assets/94e47284-5dac-4d7f-b4e1-e3e33e6ef84d" />

<img width="1600" height="780" alt="image" src="https://github.com/user-attachments/assets/3cecf111-0e40-40dd-a884-1074d18e3183" />



https://github.com/user-attachments/assets/76b72bc3-1fa5-4ad1-b277-6fc12614676d




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
