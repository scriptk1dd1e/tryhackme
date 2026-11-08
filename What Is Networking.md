# TryHackMe: What Is Networking?

**Platform:** TryHackMe  
**Room:** What Is Networking?  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I learned the basics of computer networking, how the Internet connects smaller networks, and how devices identify and communicate with one another. I also practiced using `ping` to check connectivity and completed an interactive lab about network access.

## 1. What Is Networking?

I learned that a network is a group of connected devices. Networks can include anything from a couple of computers to billions of devices, such as phones, laptops, cameras, and traffic systems.

**Answer**

- What is the key term for devices that are connected together? **`Network`**

## 2. What Is the Internet?

I learned that the Internet is a large network made up of many smaller networks. Private networks connect to public networks, allowing devices around the world to communicate.

I also learned that Tim Berners-Lee invented the World Wide Web.

**Answer**

- Who invented the World Wide Web? **`Tim Berners-Lee`**

## 3. Identifying Devices on a Network

I learned that devices use IP and MAC addresses as identifiers. An IP address can change and identifies a device on a network, while a MAC address is associated with a device’s network interface. MAC addresses can be spoofed, which can undermine security systems that rely on them as proof of identity.

I also completed the interactive Wi-Fi lab and learned how a network might use MAC address controls to manage access.

**[Insert screenshot: MAC address task]**

**Answers**

- What does “IP” stand for? **`Internet Protocol`**
- What is each section of an IP address called? **`Octet`**
- How many sections does an IPv4 address have? **`4`**
- What does “MAC” stand for? **`Media Access Control`**
- What flag did I get in the interactive lab? **`THM{YOU_GOT_ON_TRYHACKME}`**

## 4. Ping (ICMP)

I learned that `ping` uses ICMP packets to test whether a device is reachable and to measure how long a response takes. I used the task’s deployable website to ping an address and retrieve the flag.

**[Insert screenshot: Ping task]**

**Answers**

- What protocol does `ping` use? **`ICMP`**
- What is the syntax to ping `10.10.10.10`? **`ping 10.10.10.10`**
- What flag did I get when I pinged `8.8.8.8`? **`THM{I_PINGED_THE_SERVER}`**

## 5. Key Takeaways

- A network is a group of connected devices.
- The Internet connects many smaller networks.
- IP addresses and MAC addresses help identify devices on networks.
- IPv4 addresses have four sections called octets.
- `ping` uses ICMP to test connectivity and measure response time.

## 6. Conclusion

Overall, this room gave me a useful introduction to networking. I learned how networks and the Internet are structured, how devices are identified, and how `ping` can help test a connection.

**Room status:** Completed
