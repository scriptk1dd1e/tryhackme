# TryHackMe: Intro to LAN

**Platform:** TryHackMe  
**Room:** Intro to LAN  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I learned about LAN topologies, switches, routers, subnetting, ARP, and DHCP. I also completed an interactive lab and learned how these technologies help devices communicate across local networks.

## 1. Introducing LAN Topologies

I learned that a network topology describes how devices are arranged and connected. The room covered star, bus, and ring topologies, each with different costs, advantages, and points of failure.

A star topology connects devices to a central switch or hub. It is easy to expand, but it can be expensive to set up and maintain. If the central device fails, connected devices may lose network access.

A bus topology connects devices along one backbone cable. It is relatively inexpensive to set up, but traffic can cause bottlenecks, troubleshooting can be difficult, and a break in the backbone can disrupt the network.

A ring topology connects devices in a loop, with data traveling around the ring. It can be easier to troubleshoot and is less prone to bus-style bottlenecks, but a broken cable or device can disrupt the entire network.

<img width="1920" height="923" alt="1" src="https://github.com/user-attachments/assets/6fc7d069-4eaa-4a6b-987b-dea62621a3de" />

**Answers**

- What does “LAN” stand for? **`Local Area Network`**
- What is the verb given to the job that routers perform? **`Routing`**
- What device centrally connects multiple devices on a local network and transmits data to the correct location? **`Switch`**
- What topology is cost-efficient to set up? **`Bus Topology`**
- What topology is expensive to set up and maintain? **`Star Topology`**

## 2. A Primer on Subnetting

I learned that subnetting divides a larger network into smaller networks. It can help organize devices, improve efficiency, and separate groups of devices—for example, keeping a café’s public Wi-Fi separate from its staff and payment devices.

A subnet mask is 32 bits long and is divided into four sections called octets. Subnets use network addresses to identify networks, host addresses to identify devices, and default gateways to send data to other networks.

**Answers**

- What is the technical term for dividing a network into smaller pieces? **`Subnetting`**
- How many bits are in a subnet mask? **`32`**
- What is the range of a section (octet) of a subnet mask? **`0-255`**
- What address is used to identify the start of a network? **`Network Address`**
- What address is used to identify devices within a network? **`Host Address`**
- What is the name used to identify the device responsible for sending data to another network? **`Default Gateway`**

## 3. ARP

I learned that the Address Resolution Protocol (ARP) helps devices associate an IP address with a MAC address on a local network. When a device needs to find the MAC address for an IP address, it broadcasts an ARP request. The device that owns that IP address can respond with an ARP reply, and the mapping can be stored in the requesting device’s ARP cache.

**Answers**

- What does “ARP” stand for? **`Address Resolution Protocol`**
- What category of ARP packet asks whether a device has a specific IP address? **`Request`**
- What address is used as a physical identifier for a device on a network? **`MAC Address`**
- What address is used as a logical identifier for a device on a network? **`IP Address`**

## 4. DHCP

I learned that the Dynamic Host Configuration Protocol (DHCP) can automatically assign an IP address to a device when it joins a network. The process uses four packets: the device sends a DHCP Discover, the server responds with a DHCP Offer, the device sends a DHCP Request, and the server completes the process with a DHCP ACK.

**Answers**

- What type of DHCP packet is used by a device to retrieve an IP address? **`DHCP Discover`**
- What type of DHCP packet does a device send after being offered an IP address by the DHCP server? **`DHCP Request`**
- What is the last DHCP packet sent to a device from a DHCP server? **`DHCP ACK`**

## 5. Practical — LAN Topologies

I completed the interactive lab, which demonstrated how different LAN topologies can be affected by failures.

- Flag: **`THM{TOPOLOGY_FLAWS}`**

## 6. Key Takeaways

- LAN topologies describe how devices are arranged and connected.
- Star, bus, and ring topologies have different costs, benefits, and failure points.
- Switches connect devices on a local network and forward data to the intended destination.
- Routers connect networks and route data between them.
- Subnetting divides a network into smaller parts that can be organized and separated.
- ARP maps IP addresses to MAC addresses on a local network.
- DHCP can automatically assign IP addresses using Discover, Offer, Request, and ACK packets.

## 7. Conclusion

Overall, this room helped me understand several technologies that make local networks work. Learning about topologies, subnetting, ARP, and DHCP gave me a clearer picture of how devices are connected, identified, and assigned network addresses.

**Room status:** Completed
