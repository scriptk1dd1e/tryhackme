
# TryHackMe - Inside a Computer System

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Module:** Computer Fundamentals  
**Difficulty:** Beginner  
**Status:** Completed (100%)

---

## Overview

I completed the Inside a Computer System room as part of the TryHackMe Pre Security pathway.

The room covers the main hardware components that make up a computer, how they connect through the motherboard and the processes involved in starting a computer and loading an operating system.

The focus was on revisiting the fundamentals of computer hardware, component functionality and the boot sequence, along with completing practical exercises involving component identification and motherboard placement.

## 1. Computer Components

The first section covered the main components found inside a computer system. I worked through the interactive component inspection exercise, reviewing each component and its role within the system.

### CPU - Central Processing Unit

The CPU is responsible for executing instructions, processing data and performing calculations. It acts as the primary processing unit, handling tasks required by the operating system and installed applications.

### RAM - Random Access Memory

RAM provides temporary, high-speed storage for data and instructions currently being used by the system.

It is volatile memory, meaning its contents are lost when the computer is powered off.

### GPU - Graphics Processing Unit

The GPU handles graphical processing and rendering. It processes visual information such as images, videos and other graphics-intensive workloads.

### Network Adapter

The network adapter allows a computer to communicate with other devices and networks.

Connectivity can be provided through a wired Ethernet connection or wireless technologies such as Wi-Fi.

### Storage - SSD/HDD

Storage devices provide permanent storage for the operating system, applications and user data.

The two main types covered were:

- **HDD (Hard Disk Drive):** Uses magnetic spinning disks to store data.
- **SSD (Solid State Drive):** Uses flash memory and generally provides faster read and write performance.

Unlike RAM, both SSDs and HDDs retain their data when the system is powered off.

### PSU - Power Supply Unit

The PSU converts incoming AC electricity into the DC power required by the computer's internal components.

It distributes power to the motherboard, CPU, storage devices and other connected hardware.

### Input/Output (I/O)

Input and output devices provide the interface between the user and the computer.

Examples include:

- **Input:** Keyboard, mouse and microphone.
- **Output:** Monitor, speakers and printer.

### Motherboard

The motherboard is the main circuit board that connects the different hardware components.

It provides the interfaces, connectors and communication pathways that allow the CPU, RAM, storage, GPU and other devices to operate together.

## 2. Component Inspection

I worked through the interactive component inspection section, identifying the eight main components and reviewing their functions.

The exercise provided a visual reference for the hardware and how each component fits into the overall computer system.

![Computer Components](images/01-computer-components.png)

After reviewing all the components, the inspection section was successfully completed.

![Components Completed](images/02-components-completed.png)

## 3. Motherboard Component Placement

The next exercise involved placing the different hardware components into their correct positions on a motherboard.

I worked through the placement of the CPU, RAM, graphics card, network adapter, storage, PSU and input/output connections.

The exercise reinforced the physical layout of a motherboard and the different connections used by each component.

![Motherboard Exercise](images/03-motherboard-exercise.png)

After correctly positioning the components, the exercise confirmed successful completion and displayed the room flag.

![Exercise Completed](images/04-exercise-completed.png)

**Flag:**

`THM{4llpccomp0n3nts1d3nt1f13d}`

## 4. Computer Boot Sequence

The next section covered the computer boot sequence and the stages involved in getting a system from a powered-off state to a running operating system.

The room broke this process down into five stages.

### Step 1 - Press the Power Button

When the power button is pressed, a signal is sent to the PSU, allowing power to flow to the computer's components.

This initiates the system startup process.

### Step 2 - Firmware Starts

Once power is supplied, the system firmware begins executing and starts the hardware initialisation process.

Modern computers generally use UEFI (Unified Extensible Firmware Interface).

The room also covered BIOS (Basic Input/Output System), which is the older firmware standard that UEFI has largely replaced.

### Step 3 - Power-On Self-Test (POST)

POST is a diagnostic process performed during startup.

It checks that essential hardware components are present and functioning correctly.

If an issue is detected, the system may report it through an error message or audible diagnostic signals.

### Step 4 - Select Boot Device

Once the initial hardware checks are complete, UEFI looks for a bootable device based on the configured boot priority.

Common boot devices include:

- Internal SSD
- Internal HDD
- USB storage device
- Network boot device

### Step 5 - Initiate Bootloader

After the boot device has been selected, the bootloader is started.

The bootloader is responsible for initiating the operating system loading process and transferring control to the OS.

Once the operating system takes over, it continues initialising the necessary drivers, services and user interface required for normal operation.

## 5. Key Takeaways

This room covered several important areas of computer hardware and system startup.

The main points covered were:

- The functions and responsibilities of the main hardware components.
- How components connect and communicate through the motherboard.
- The differences between volatile and non-volatile memory.
- The roles of UEFI and legacy BIOS firmware.
- Hardware validation through the Power-On Self-Test.
- Boot device prioritisation and selection.
- The bootloader's role in operating system initialisation.

These concepts are relevant to understanding operating system behaviour, hardware troubleshooting, system administration and the wider security of computing environments.

## 6. Conclusion

This room was a good opportunity to revisit the hardware and processes that sit underneath the operating systems we use every day.

The practical exercises reinforced component identification and motherboard layouts, while the boot sequence section covered the stages involved in bringing a computer from a powered-off state to a running operating system.

Having a solid understanding of these fundamentals provides useful context as I continue working through the TryHackMe Pre Security pathway and developing my cybersecurity knowledge.

---

**Room Status:** Completed  
**Progress:** 100%
