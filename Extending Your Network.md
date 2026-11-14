# TryHackMe: Extending Your Network

**Platform:** TryHackMe  
**Room:** Extending Your Network  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I learned about technologies that extend networks and control how devices communicate. The room covered port forwarding, firewalls, VPNs, routers, switches, and VLANs. I also completed practical exercises using a firewall and a network simulator.

## 1. Introduction to Port Forwarding

I learned that port forwarding allows services on a private network to be accessed from the Internet. For example, a web server on a local network can be made available to public users through the network’s public IP address and a forwarded port. Port forwarding is configured on the router.

**Answers**

- What device is used to configure port forwarding? **`router`**

## 2. Firewalls 101

I learned that firewalls inspect network traffic and determine whether it should be allowed or blocked. They can use details such as the traffic’s source, destination, port, and protocol to apply rules.

A stateful firewall considers the behavior of an entire connection, while a stateless firewall evaluates individual packets against a set of rules. Firewalls operate at OSI Layers 3 and 4.

**Answers**

- What layers of the OSI model do firewalls operate at? **`3 & 4`**
- What category of firewall inspects the entire connection? **`stateful`**
- What category of firewall inspects individual packets? **`stateless`**

## 3. Practical — Firewall

I completed the firewall practical by configuring rules to prevent malicious traffic from reaching the web server.

<img width="1918" height="912" alt="1" src="https://github.com/user-attachments/assets/e422b56e-188d-4a8b-a0ab-f944f6990bc0" />
<img width="1920" height="927" alt="2" src="https://github.com/user-attachments/assets/b82cd521-c1bd-46e7-9c6f-640aac1f7806" />

- Flag: **`THM{FIREWALLS_RULE}`**

## 4. VPN Basics

I learned that a Virtual Private Network (VPN) can create a private, encrypted tunnel between devices or networks over the Internet. This can let devices in separate locations communicate as if they were connected to the same private network.

The room also covered PPP, PPTP, and IPsec. PPP provides authentication and encryption, PPTP allows PPP data to travel across networks, and IPsec encrypts data using the IP framework.

**Answers**

- What VPN technology only encrypts and provides authentication of data? **`PPP`**
- What VPN technology uses the IP framework? **`IPSec`**

## 5. LAN Networking Devices

I learned that routers connect networks and route data between them. Routers operate at Layer 3 of the OSI model and can provide configuration options such as port forwarding and firewall rules.

Switches connect devices on a network. Layer 2 switches forward frames using MAC addresses, while Layer 3 switches can also route packets between networks using IP addresses. VLANs can separate groups of devices on the same network, helping control how those groups communicate.

**Answers**

- What is the verb for the action that a router does? **`routing`**
- What are the two different layers of switches? **`Layer 2,Layer 3`**

## 6. Practical — Network Simulator

I used the network simulator to follow the steps a packet takes as it travels between devices. I sent a TCP packet from computer1 to computer3 and checked the network log.

<img width="1912" height="933" alt="3" src="https://github.com/user-attachments/assets/c740f4a8-b495-4da1-8292-88f8c4202c3e" />

**Answers**

- What is the flag from the network simulator? **`THM{YOU'VE_GOT_DATA}`**
- How many HANDSHAKE entries are there in the Network Log? **`5`**

## 7. Key Takeaways

- Port forwarding is configured on a router and allows external access to selected services on a private network.
- Firewalls inspect traffic and apply rules to allow or block it.
- Stateful firewalls inspect connection behavior, while stateless firewalls inspect individual packets.
- VPNs can create encrypted tunnels between devices or networks.
- Routers connect networks, while switches connect devices within a network.
- Layer 3 switches can route packets, and VLANs can separate groups of devices.
- A network simulator can show the steps packets take as they move between devices.

## 8. Conclusion

Overall, this room helped me understand how networks can be extended and managed using port forwarding, firewalls, VPNs, routers, and switches. The practical exercises helped me see how firewall rules affect traffic and how packets travel through a network.

**Room status:** Completed
