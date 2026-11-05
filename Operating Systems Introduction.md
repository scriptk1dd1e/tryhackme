# TryHackMe: Operating Systems Introduction

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Module:** Operating Systems  
**Room:** Operating Systems Introduction  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Operating Systems Introduction room as part of my TryHackMe learning journey. It helped me understand what an operating system does behind the scenes and how it manages a computer’s hardware, applications, files, and users.

I also explored a virtual Ubuntu MATE computer. I checked its system information and file system, looked through its user directories, and found a flag in a text file.

## 1. What an Operating System Does

An **operating system (OS)** is the core software that manages a computer’s hardware, applications, and system resources. I found the airport analogy helpful: hardware provides the physical infrastructure, applications are like airlines using it, and the operating system coordinates everything like air traffic control.

Without an OS, applications would have to manage hardware and resources themselves, which could lead to conflicts. The OS helps organize these resources so the computer can run safely and efficiently.

## 2. Kernel Space and User Space

I learned that a computer separates system activity into different privilege levels:

- **Kernel space** is the highly privileged area where the kernel runs. It has direct access to hardware and manages system resources.
- **User space** is where regular applications run with restricted permissions. When an application needs an operation handled by the kernel, it makes a system call.

This separation helps protect the system. Applications do not get unrestricted access to hardware, which helps prevent problems caused by faulty or unsafe software.

**Answers**

- Which OS space has unrestricted access to the computer’s hardware? **Kernel Space**
- Which OS responsibility manages user accounts, authentication, and permissions? **User Management**

## 3. Operating System Responsibilities

I learned that operating systems handle several important responsibilities:

- **Process management** — Creates, schedules, and ends running programs.
- **Memory management** — Allocates memory to applications and keeps their memory separate.
- **File system management** — Organizes files and directories and manages permissions and other file details.
- **User management** — Handles accounts, authentication, and user permissions.
- **Device management** — Helps the OS and applications communicate with hardware through drivers and other interfaces.

The OS also provides security features such as authentication, permissions, process isolation, and protection for important system files.

## 4. Checking the System Information

I opened the **About This Computer** shortcut on the virtual machine’s desktop to inspect its system information. I found the Ubuntu MATE version and checked the Hardware section to see how much memory was allocated to the machine.

**System information**

- **Ubuntu MATE version:** `1.26.2`
- **Allocated memory:** `1.9 GiB`

<img width="1913" height="931" alt="1" src="https://github.com/user-attachments/assets/245ea0df-ff58-4ad4-91eb-ef4aaf7de99c" />

## 5. GUI, CLI, and Operating System Types

I learned that there are two main ways to interact with an operating system:

- A **graphical user interface (GUI)** lets me use windows, icons, and menus.
- A **command-line interface (CLI)** lets me enter text-based commands to control the system.

The room also introduced several operating system categories, including desktop, server, mobile, embedded, and virtual or cloud systems. Each is designed for different needs—for example, desktop systems are made for personal use, while server systems are designed to provide services reliably.

## 6. Exploring the File System

I continued investigating the virtual computer using System Monitor and the Home directory. In the File Systems tab, I checked the `/dev/root` device type. I also looked through the Home directory and found three user directories. Then I opened Alex’s Documents folder to find the flag in `note.txt`.

<img width="1917" height="922" alt="2" src="https://github.com/user-attachments/assets/fb9ec383-2d37-4f9e-b56b-2930fbcf1710" />

**Answers**

- What type is listed for `/dev/root`? **`ext4`**
- How many user directories exist in the Home directory? **3**
- What flag was contained in `note.txt`? **`THM{new_pc_for_free!}`**

## 7. Key Takeaways

The main concepts I learned were:

- **Operating system (OS)** — Manages hardware, applications, and system resources.
- **Kernel space** — The privileged area where the kernel directly manages hardware and resources.
- **User space** — The restricted area where regular applications run.
- **GUI** — A visual interface using windows, icons, and menus.
- **CLI** — A text-based interface controlled by typed commands.
- **System calls** — Requests applications make when they need the OS kernel to perform an operation.

## 8. Conclusion

Overall, I found this room a useful introduction to operating systems and the work they do behind the scenes. I learned how the OS manages resources, separates kernel and user privileges, and provides interfaces for interacting with the computer.

The practical investigation helped me connect those concepts to a real system. I checked the machine’s specifications, explored its file system, and found the flag in Alex’s Documents folder.

**Room status:** Completed
