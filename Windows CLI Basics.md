# TryHackMe: Windows CLI Basics

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Room:** Windows CLI Basics  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Windows CLI Basics room as part of my TryHackMe learning journey. It introduced me to using Command Prompt to navigate folders, find and read files, and gather basic information about a Windows computer.

The hands-on tasks helped me get more comfortable using commands instead of relying on the graphical interface.

## 1. Navigating Files and Finding a File

I started by checking my current location with `cd` and listing the contents of the folder with `dir`. I also learned that `dir /a` displays hidden files and folders.

To move between folders, I used `cd` followed by the folder name. When I didn’t know where the brief was stored, I used `dir /s task_brief.txt` to search through the current directory and its subfolders.

**[Insert screenshot: Using `cd` to navigate between folders in Command Prompt]**

After locating the file, I used `type task_brief.txt` to read its contents in Command Prompt.

**[Insert screenshot: Running `dir /s task_brief.txt` to find the file]**

**Useful commands**

- `cd` — Shows the current directory.
- `dir` — Lists files and folders.
- `dir /a` — Lists files and folders, including hidden items.
- `cd <folder_name>` — Moves to a folder.
- `dir /s task_brief.txt` — Searches the current directory and its subfolders for the file.
- `type task_brief.txt` — Displays the file’s contents.

**Answers**

- What is the full path of the `task_brief.txt` found on the system?  
  **`C:\Users\Administrator\Documents\Notes\research_yn6\exports_imv\screenshots\notes_wi6`**
- What message and flag are written inside `task_brief.txt`?  
  **`TASK-BRIEF-FOUND`**

## 2. Gathering System Information

I then used Command Prompt to find out more about the computer. The `whoami` command showed which account I was logged in as, and `hostname` displayed the computer’s name.

**[Insert screenshot: Running `whoami` and `hostname` in Command Prompt]**

I used `systeminfo` to check details about the operating system and `ipconfig` to view the computer’s network configuration.

**[Insert screenshot: Running `ipconfig` and viewing the network information]**

**Useful commands**

- `whoami` — Shows the account currently logged in.
- `hostname` — Displays the computer’s name.
- `systeminfo` — Shows details about the operating system and hardware.
- `ipconfig` — Displays basic network configuration, including the IPv4 address and default gateway.

**Answers**

- What is the computer name shown by `hostname`? **`thmlab`**
- What Windows version is listed in the `systeminfo` output? **`10.0.17763 N/A Build 17763`**

## 3. Key Takeaways

The main commands and skills I learned were:

- Using `cd` and `dir` to navigate and inspect folders.
- Including hidden items in a directory listing with `dir /a`.
- Searching for a file with `dir /s`.
- Reading a text file with `type`.
- Checking the current user with `whoami`.
- Finding the computer name with `hostname`.
- Reviewing Windows and network information with `systeminfo` and `ipconfig`.

## 4. Conclusion

Overall, I found this room a useful introduction to the Windows command line. I practised finding and reading a file without knowing its location, then used built-in commands to gather basic information about the system.

These skills gave me more confidence navigating Windows through Command Prompt and showed me how the CLI can make common troubleshooting and information-gathering tasks quicker.

**Room status:** Completed
