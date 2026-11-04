# TryHackMe: Client-Server Basics

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Room:** Client-Server Basics  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Client-Server Basics room as part of my TryHackMe learning journey. It helped me understand how devices request services from one another over a network.

I learned about the client-server model and the roles of clients, servers, ports, protocols, and DNS. I also explored how a browser sends an HTTP request and receives a response from a web server.

## 1. The Client-Server Model

I learned that a **client** is the system that starts a request, while a **server** provides a service and sends back a response. For example, when I visit a website, my browser acts as the client and requests a webpage from the server hosting it.

The room used ordering a pizza as an analogy: the customer makes an order, the takeaway prepares it, and the order is delivered back. In a similar way, a browser requests a resource from a server, which then returns a response.

A request needs to be understood by both sides. If it is incorrectly formatted or the requested resource is unavailable, the server may return an error instead of the requested resource.

**Key point:** The client is the one that **initiates the request**.

## 2. Protocols, Ports, and DNS

A **protocol** sets the rules that clients and servers use to communicate. It defines things such as which methods they understand, how requests are structured, and what responses to return.

A **port** identifies a particular service running on a system. A server can provide several services at once, with each service using a different port.

I also learned how **DNS** helps clients find servers. It translates a human-readable domain name into an IP address, which identifies the server’s location on the network.

**Answers**

- What do we use to identify a specific service on a server? **Port**
- What do we call the address of a server? **Internet Protocol address**

## 3. HTTP and Web Requests

I learned that **HTTP** and **HTTPS** are protocols used for communication on the web. HTTP is stateless, which means each request is handled independently. Websites can maintain a user’s session across requests using mechanisms such as cookies or tokens.

HTTP uses methods to describe the type of request. The room introduced methods such as `GET`, `POST`, `PUT`, `DELETE`, and `PATCH`. I focused on **GET**, which is used to retrieve a resource from a server.

In the lab, I opened the webpage and used Firefox Developer Tools to inspect its network activity. The Network tab showed the requests made by the browser and details such as the scheme, host, requested file, server address, and status. The example request returned **200 OK**, indicating it was successful.

<img width="1918" height="980" alt="3" src="https://github.com/user-attachments/assets/b6cb638a-ea03-44ed-82d2-b4ccb9d20edd" />

The server’s response has two main parts: a **response header**, which contains metadata, and a **response body**, which contains the requested content. I opened the Response section to view the webpage’s HTML.

<img width="1912" height="982" alt="4" src="https://github.com/user-attachments/assets/cbaa4990-e192-4549-a491-f5f09abaa652" />

**Answers**

- What would be the host in `https://www.iamlearning.thm/contact`? **`www.iamlearning.thm`**
- What would be the scheme in `https://www.iamlearning.thm/contact`? **`https`**

## 4. Key Takeaways

The main concepts I learned were:

- **Client** — Starts a request for a service or resource.
- **Server** — Provides a service and responds to client requests.
- **Protocol** — Defines the rules for communication between systems.
- **Port** — Identifies a specific service running on a system.
- **DNS** — Resolves a domain name to an IP address.
- **HTTP/HTTPS** — Protocols used for communication on the web.
- **GET** — An HTTP method used to retrieve a resource.

## 5. Conclusion

Overall, I found this room a helpful introduction to how devices communicate over a network. I learned how clients make requests, how servers respond, and how protocols, ports, and DNS help make that communication possible.

Inspecting a real web request in Developer Tools made the concepts easier to understand. I could see the GET request, check its details, and view the HTML returned in the response.

**Room status:** Completed
