# TryHackMe: Virtualization

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Module:** Virtualization  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Virtualization room as part of my TryHackMe learning journey. It introduced me to how virtualization helps companies use computer hardware more efficiently by running multiple virtual machines on a single physical server.

I learned about hypervisors, virtual machines (VMs), and containers, and how they differ. The practical activities also gave me experience managing VMs, checking host usage, and investigating a virtual machine issue in the Virtualization Manager.

## 1. Why Virtualization Is Useful

Before virtualization became common, companies often followed the rule of “one server = one application.” For example, a company might use separate physical servers for its website, database, email, and internal applications.

I learned that this approach can be expensive and inefficient. Physical servers require hardware, electricity, cooling, maintenance, and data-center space. Many servers also use only a small portion of their available resources, while setting up additional physical servers can take a long time.

Virtualization helps solve these problems by allowing multiple applications and virtual machines to share the resources of one physical server. This can improve hardware utilization, reduce costs, and make it easier to deploy or scale services.

**Answer:** Virtualization enables multiple applications to share a **physical server**.

## 2. Hypervisors and Virtual Machines

A **hypervisor** is the software layer that creates and manages virtual machines. It allocates resources such as CPU, memory, and storage, and manages VM actions like starting, stopping, pausing, cloning, or deleting machines.

I learned about two types of hypervisors:

- **Type 1 hypervisors** run directly on physical hardware. They are commonly used for servers and data centers.
- **Type 2 hypervisors** run within an existing operating system. They are useful for learning, testing, and home labs.

A **virtual machine (VM)** is a virtual computer managed by a hypervisor. It has its own virtual CPU, memory, storage, network, and operating system.

For a personal study lab, a **Type 2 hypervisor** is a suitable choice because it can be installed on an existing computer. Tools such as VirtualBox and VMware Workstation can run VMs for practicing exercises.

**Answers**

- What software manages resources for each lab machine? **Hypervisor**
- Which hypervisor type is suitable for setting up a study lab on a personal machine? **Type 2**

## 3. Containers

A **container** is a lightweight, isolated environment that packages an application with the components it needs to run. Unlike a VM, a container shares the host system’s operating-system kernel rather than running a complete separate operating system.

Because containers share the host kernel, they can start quickly and use fewer resources than VMs. They are useful for development, testing, and deploying applications consistently. Docker is one platform used to build, deploy, and run containers.

I learned that containers are a good fit when a company wants to run several small applications inside a lab machine. Containers remain isolated from one another while sharing the VM’s operating-system resources.

**Answer:** To host multiple small applications in the same lab machine, use **containers**.

## 4. Managing Virtual Machines

In the Virtualization Manager activity, I investigated an issue with the company’s email service. I found that the `Mail-SERVER` VM was in an error state and restarted it using the available action.

**[Insert screenshot: Restarting the `Mail-SERVER` VM]**

After restarting it, I checked its status and confirmed that it was back online and working correctly.

**[Insert screenshot: `Mail-SERVER` back online after restart]**

I then created a VM for the marketing team’s website with these settings:

- **Name:** `Marketing-VM`
- **CPU cores:** 4
- **Memory:** 8 GB
- **Disk size:** 100 GB

**[Insert screenshot: Creating the `Marketing-VM` with its hardware settings]**

After creating the VM, I checked the physical host information. I noted that `HV-PROD-01` had room for more VMs, `HV-PROD-02` was close to full capacity, and `HV-BACKUP-01` was disconnected and hosting no VMs.

**Activity answers**

- Lab machine that had been running for the longest time: `Monitoring-SYS`
- Lab machine using the most memory: `DB-Cluster-01`
- Running VMs after fixing `Mail-SERVER`: **8**
- Physical machine hosting the most VMs: **Not recorded in my notes**

## 5. Key Takeaways

The main concepts I learned were:

- **Virtualization** — Allows one physical computer to act like multiple separate computers.
- **Hypervisor** — Creates and manages virtual machines and their resources.
- **Virtual machine (VM)** — A virtual computer with its own operating system and allocated resources.
- **Type 1 hypervisor** — Runs directly on physical hardware.
- **Type 2 hypervisor** — Runs within an existing operating system and is useful for learning and testing.
- **Container** — An isolated environment for an application that shares the host’s operating-system kernel.
- **Docker** — A platform for building, deploying, and running containers.

I also learned that virtualization can reduce costs, improve resource usage, support safer testing, and make systems easier to deploy, manage, and scale.

## 6. Conclusion

Overall, I found this room a useful introduction to virtualization and how it supports modern IT systems. I learned how hypervisors manage virtual machines, how containers provide a lightweight way to run applications, and why both technologies help organizations use hardware more efficiently.

The Virtualization Manager activities helped me practise restarting a VM, creating a new one, and reviewing physical host capacity. These skills give me a foundation for learning more about cloud computing and other virtualization tools.

**Room status:** Completed
