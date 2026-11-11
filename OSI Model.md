# TryHackMe: OSI Model

**Platform:** TryHackMe  
**Room:** OSI Model  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I learned how the seven layers of the OSI model work together to help networked devices send, receive, and interpret data. I also learned about encapsulation, the role of each layer, and how TCP and UDP are used to transfer data.

## 1. What Is the OSI Model?

I learned that the OSI model provides a framework for how networked devices communicate. As data travels through the layers, information is added to it through a process called encapsulation.

**Answers**

- What does “OSI” stand for? **`Open Systems Interconnection`**
- How many layers does the OSI model have? **`7`**
- What is the term for adding information to data? **`Encapsulation`**

## 2. Layer 1 — Physical

I learned that the physical layer covers the hardware used to connect devices and transmit data. Devices use electrical signals to send data as binary values: 1s and 0s.

**Answers**

- What is the name of Layer 1? **`Physical`**
- What numbering system uses 0s and 1s? **`Binary`**
- What cables are used to connect devices? **`Ethernet Cables`**

## 3. Layer 2 — Data Link

I learned that the data link layer handles physical addressing and formats data for transmission. It uses MAC addresses to identify network interfaces, which are part of a device’s Network Interface Card (NIC).

**Answers**

- What is the name of Layer 2? **`Data Link`**
- What hardware do networked devices use to connect to a network? **`Network Interface Card`**

## 4. Layer 3 — Network

I learned that the network layer uses IP addresses and determines routes for packets to travel across a network. Routing can take factors such as distance, reliability, and connection speed into account.

**Answers**

- What is the name of Layer 3? **`Network`**
- Do packets take an optimal route across a network? **`Y`**
- What does “OSPF” stand for? **`Open Shortest Path First`**
- What does “RIP” stand for? **`Routing Information Protocol`**
- What type of addresses are used at this layer? **`IP Addresses`**

## 5. Layer 4 — Transport

I learned that the transport layer uses TCP or UDP to send data between devices. TCP prioritizes reliability: it checks that data arrives and is reassembled in the correct order. This makes it useful for activities such as browsing the Internet, sending email, and downloading files.

UDP is faster and does not guarantee that data will arrive. It can be useful for video streaming, where losing a small part of the data may be preferable to slowing down the stream.

**Answers**

- What is the name of Layer 4? **`Transport`**
- What does “TCP” stand for? **`Transmission Control Protocol`**
- What does “UDP” stand for? **`User Datagram Protocol`**
- What protocol guarantees the accuracy of data? **`TCP`**
- What protocol does not guarantee that data is received? **`UDP`**
- What protocol would an email client use? **`TCP`**
- What protocol would an application that downloads files use? **`TCP`**
- What protocol would an application that streams video use? **`UDP`**

## 6. Layer 5 — Session

I learned that the session layer establishes and maintains connections between computers. It can also close inactive or lost connections and use checkpoints to help resume data transfers without resending everything.

**Answers**

- What is the name of Layer 5? **`Session`**
- What is a connection called once it has been successfully established? **`Session`**

## 7. Layer 6 — Presentation

I learned that the presentation layer acts as a translator between the application layer and the data. It helps make sure data can be understood across different software, and it is associated with encryption.

**Answers**

- What is the name of Layer 6? **`Presentation`**
- What is the layer’s main purpose? **`Translator`**

## 8. Layer 7 — Application

I learned that the application layer is where users interact with network services through software such as email clients and web browsers. These applications provide a Graphical User Interface (GUI).

**Answers**

- What is the name of Layer 7? **`Application`**
- What is the term for the interface users interact with? **`Graphical User Interface`**

## 9. Practical — OSI Game

I started the OSI game, which tests how well I can identify the layers and put them in the correct order.

<img width="1920" height="936" alt="1" src="https://github.com/user-attachments/assets/4ac71af7-e383-4503-a614-0ae8c9b58b87" />

After completing the game, I reached the end and got the flag.

<img width="1920" height="976" alt="2" src="https://github.com/user-attachments/assets/43ecb213-1712-4cbb-ace5-91be25977b22" />

- Flag: **`[Add flag]`**

## 10. Key Takeaways

- The OSI model has seven layers that describe how networked devices communicate.
- Encapsulation adds information to data as it moves through the layers.
- The physical, data link, and network layers handle hardware, MAC addresses, and IP routing.
- The session and presentation layers manage connections and help make data understandable.
- The transport layer uses TCP for reliable delivery and UDP when speed is more important than guaranteed delivery.
- The application layer supports the software users interact with.

## 11. Conclusion

Overall, this room helped me understand how the OSI model organizes network communication. Learning what each layer does made it easier to see how data moves between devices and why different protocols are used for different tasks.

**Room status:** Completed
