# TryHackMe: Packets & Frames

**Platform:** TryHackMe  
**Room:** Packets & Frames  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I learned how data is divided into packets and frames and sent across networks. I also learned about TCP’s three-way handshake, how UDP differs from TCP, and how ports help direct network traffic to the right applications.

## 1. What Are Packets and Frames?

I learned that packets and frames are pieces of data used at different layers of the OSI model. A packet operates at Layer 3, the Network layer, and includes information such as IP addresses. A frame operates at Layer 2, the Data Link layer, and encapsulates a packet with information such as MAC addresses.

I thought of a frame like an envelope carrying a letter: the frame helps move the packet to another place, and the packet contains the information being delivered. This process is part of encapsulation.

**Answers**

- What is a piece of data called when it has IP addressing information? **`Packet`**
- What is a piece of data called when it does not have IP addressing information? **`Frame`**

## 2. TCP/IP — The Three-Way Handshake

I learned that TCP is a connection-based protocol. Before sending data, two devices establish a connection using a three-way handshake: the client sends a SYN, the server replies with SYN/ACK, and the client responds with ACK.

TCP uses sequence numbers to keep data in order and a checksum to help check data integrity. Once the connection is established, devices can exchange data. A FIN packet can be used to close the connection cleanly.

**Answers**

- What TCP header ensures the integrity of data? **`checksum`**
- What is the order of a normal three-way handshake? **`SYN,SYN/ACK,ACK`**

## 3. Practical — Handshake

I completed the practical by reassembling the TCP handshake in the correct order.

**[Insert screenshot: Task 3 handshake practical showing the completed conversation and flag]**

- Flag: **`[TCP_CHATTER]`**

## 4. UDP/IP

I learned that UDP is a stateless protocol that does not require devices to establish a connection before sending data. Unlike TCP, UDP does not use a handshake or guarantee that data will arrive. This makes it faster and useful for applications such as video calls, where speed can matter more than receiving every packet.

**Answers**

- What does “UDP” stand for? **`User Datagram Protocol`**
- What type of connection is UDP? **`stateless`**
- What protocol would you use to transfer a file? **`TCP`**
- What protocol would you use to have a video call? **`UDP`**

## 5. Ports 101 — Practical

I learned that ports direct network traffic to the appropriate application or service on a device. Port numbers range from 0 to 65535. Some common ports include 21 for FTP, 22 for SSH, 80 for HTTP, and 443 for HTTPS.

I completed the practical challenge by connecting to the specified IP address on port 1234 to retrieve the flag.

**Answers**

- What is the flag received from the challenge? **`THM{YOU_CONNECTED_TO_A_PORT}`**

## 6. Key Takeaways

- Packets operate at the Network layer and include IP addressing information.
- Frames operate at the Data Link layer and can contain packets along with MAC address information.
- TCP establishes a connection with a SYN, SYN/ACK, ACK handshake and helps ensure reliable, ordered delivery.
- UDP is stateless and faster, but it does not guarantee that data will be received.
- Ports help direct traffic to the correct application or service.
- Common protocols are associated with standard ports, though services can be configured to use different ports.

## 7. Conclusion

Overall, this room helped me understand how data is packaged for transmission and how devices use TCP, UDP, and ports to communicate. The practical exercises helped me connect the concepts to how network traffic is handled.

**Room status:** Completed