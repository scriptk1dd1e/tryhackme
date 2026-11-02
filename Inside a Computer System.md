
# TryHackMe - Inside a Computer System

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Module:** Computer Fundamentals  
**Difficulty:** Beginner  
**Status:** Completed (100%)

---

## Overview

I completed the Inside a Computer System room as part of the TryHackMe Pre Security pathway.

The room covers the main hardware components that make up a computer, how they connect through the motherboard and what happens during the boot process.

Although these are fundamental IT concepts, it's important to keep the underlying hardware and system processes fresh, particularly when building towards more advanced areas of cybersecurity.

## 1. Computer Components

The first section covered the eight main components found in a typical computer system. I went through each component using the interactive static site and reviewed its purpose and how it fits into the overall system.

### CPU - Central Processing Unit

The CPU handles the processing and execution of instructions. It performs calculations, processes data and manages the tasks required by the operating system and applications.

### RAM - Random Access Memory

RAM provides temporary storage for data and instructions that are actively being used by the system.

As volatile memory, its contents are lost when the computer is powered off.

### GPU - Graphics Processing Unit

The GPU is responsible for processing and rendering graphical information. It handles visual workloads such as images, video and other graphics-intensive tasks.

### Network Adapter

The network adapter provides connectivity between the computer and other devices or networks. This can be through a wired Ethernet connection or wireless connectivity such as Wi-Fi.

### Storage - SSD/HDD

Storage devices hold the operating system, applications and user data.

The room covered the two main types:

- **HDD:** Uses magnetic spinning disks to store data.
- **SSD:** Uses flash memory, providing faster read and write performance.

Both are non-volatile, meaning data remains stored when the computer is switched off.

### PSU - Power Supply Unit

The PSU converts incoming AC electricity into the DC power required by the internal hardware. It distributes power to the motherboard and connected components.

### Input/Output (I/O)

Input and output devices allow users to interact with the computer.

Examples include keyboards and mice for input, and monitors, speakers and printers for output.

### Motherboard

The motherboard connects the different hardware components and provides the communication pathways that allow them to work together.

It houses the CPU socket, RAM slots, expansion slots and various connectors used by the system.

## 2. Component Inspection

I worked through the interactive component inspection section, identifying each of the eight components and reviewing their functions.

The exercise provided a visual reference for the hardware rather than relying purely on descriptions.

![Computer Components](images/01-computer-components.png)

Once all eight components had been inspected, the section was marked as complete.

![Components Completed](images/02-components-completed.png)

## 3. Motherboard Exercise

The next exercise involved placing the different hardware components into their correct positions on a motherboard.

I worked through the placement of the CPU, RAM, graphics card, network adapter, storage, PSU and input/output connections.

The exercise was a good way to reinforce the physical layout of a motherboard and where the different components connect.

![Motherboard Exercise](images/03-motherboard-exercise.png)

After correctly positioning the components, the exercise confirmed that everything had been placed correctly.

I was then presented with the completion message and the room flag.

![Exercise Completed and Flag](images/04-exercise-flag.png)

**Flag:**

`THM{4llpccomp0n3nts1d3nt1f13d}`

## 4. What Happens When You Press the Power Button?

The next section focused on the computer boot sequence and the stages involved in getting a system from a powered-off state to a running operating system.

I went through the five stages covered in the room.

### Step 1 - Power Button

When the power button is pressed, a signal is sent to the PSU, allowing power to flow to the computer's components.

This initiates the startup process.

### Step 2 - Firmware Starts

Once power is supplied, the system firmware begins running and starts the hardware initialisation process.

Modern computers generally use UEFI (Unified Extensible Firmware Interface).

The room also covered BIOS (Basic Input/Output System), which is the older firmware standard that UEFI has largely replaced.

### Step 3 - Power-On Self-Test (POST)

POST runs during startup and checks that the essential hardware components are present and functioning correctly.

If an issue is detected, the system may report it through an error message or audible beep codes.

### Step 4 - Select Boot Device

Once the initial checks are complete, UEFI looks for a bootable device based on the configured boot priority.

This could be an internal SSD, HDD, USB device or network boot source.

### Step 5 - Initiate Bootloader

After selecting the boot device, the system starts the bootloader.

The bootloader is responsible for initiating the operating system loading process. Once the OS has been loaded and takes control, it continues starting the services and drivers required for normal operation.

## 5. Final Thoughts

This room was a good refresher on the hardware and processes that sit underneath the operating systems I work with.

The main focus was revisiting component functionality, motherboard connections and the sequence of events involved in booting a computer.

Understanding these processes is relevant beyond basic hardware knowledge. Firmware, bootloaders, storage and memory all have their own considerations when it comes to system security and troubleshooting.

I'll be carrying this knowledge forward as I continue working through the TryHackMe Pre Security pathway.

---

**Room completed: 100%**
