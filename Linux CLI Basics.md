# TryHackMe: Linux Fundamentals

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Module:** Linux Fundamentals  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Linux Fundamentals room as part of my TryHackMe learning journey. It introduced me to the Linux command-line interface (CLI) and helped me practise navigating and interacting with a Linux system.

As I develop my IT and cybersecurity skills, becoming comfortable with Linux is important. It is widely used on servers and in security tools and penetration-testing environments. The practical exercises helped me learn to navigate directories, locate files, read their contents, and gather basic system information.

## 1. Introduction to the Linux Terminal

The room began with an introduction to the Linux terminal and its role in cybersecurity. A terminal is a text-based interface for interacting with an operating system by entering commands rather than using a graphical interface.

Cybersecurity professionals use the terminal to manage files, access command-line tools, and automate repetitive tasks with commands and scripts.

**CLI** stands for **Command-Line Interface**.

## 2. Interacting with the Terminal

The first practical task was to find a file called `mission_brief.txt`.

### Checking the current directory: `pwd`

The `pwd` command stands for **print working directory**. It displays the directory you are currently in.

```bash
pwd
```

The output was:

```text
/home/ubuntu
```

### Listing files and directories: `ls`

The `ls` command lists the contents of the current directory.

```bash
ls
```

The directory contained folders such as `Desktop`, `Documents`, `Downloads`, `Pictures`, `Music`, `Videos`, `logs`, and `projects`.

Useful options include:

```bash
ls -l   # Show detailed file and directory information
ls -al  # Include hidden files in the detailed listing
```

In Linux, hidden files usually begin with a dot (`.`). They are not necessarily secret; they are simply omitted from standard directory listings.

### Navigating directories: `cd`

The `cd` command changes the current directory.

```bash
cd Documents
pwd
```

The resulting path was:

```text
/home/ubuntu/Documents
```

To move up one directory, I used:

```bash
cd ..
```

### Finding a file: `find`

The `find` command searches for files and directories. The `~` symbol represents the current user’s home directory.

```bash
find ~ -name mission_brief.txt
```

The file was located at:

```text
/home/ubuntu/Documents/.research/archive/mission_brief.txt
```

### Reading a file: `cat`

After navigating to the file’s directory, I used `cat` to display its contents:

```bash
cat mission_brief.txt
```

The file contained the flag:

```text
MISSION-FOUND
```

**Answers**

- What does CLI stand for? **Command-Line Interface**
- What is the full path of `mission_brief.txt`? `/home/ubuntu/Documents/.research/archive/mission_brief.txt`
- What is the flag inside `mission_brief.txt`? `MISSION-FOUND`

## 3. Investigating the System

The next task was to collect basic information about the Linux machine, including the current username, kernel version, available disk space, and Linux distribution.

### Checking the current user: `whoami`

The `whoami` command displays the username of the account currently logged in.

```bash
whoami
```

The output was:

```text
ubuntu
```

### Checking system information: `uname`

The `uname -a` command displays detailed information about the operating system and kernel.

```bash
uname -a
```

The information I identified included:

- **Operating system:** Linux
- **Hostname:** `tryhackme`
- **Kernel version:** `6.14.0-1018-aws`
- **Architecture:** `x86_64`

### Checking disk space: `df -h`

The `df -h` command displays filesystem and disk-space information. The `-h` option presents storage sizes in a human-readable format, such as GB and MB.

```bash
df -h
```

The output includes the filesystem, total capacity, used and available space, usage percentage, and mount point. The free disk space reported by the machine was:

```text
58G
```

### Identifying the Linux distribution

The `/etc` directory contains many Linux configuration files. I used `os-release` to identify the distribution:

```bash
cd /etc
cat os-release
```

The output identified the system as:

```text
PRETTY_NAME="Ubuntu 24.04.1 LTS"
NAME="Ubuntu"
VERSION_ID="24.04"
VERSION="24.04.1 LTS (Noble Numbat)"
```

## 4. Final Challenge: End-of-Day Report

For the final task, I was given the filename `day1_report.txt` and had to locate and read it using the commands I had learned.

I searched my home directory:

```bash
find ~ -name day1_report.txt
```

After locating the file, I navigated to its directory and displayed its contents:

```bash
cat day1_report.txt
```

The final message was:

```text
END-OF-DAY1
```

This challenge brought together the commands I had practised and gave me the chance to locate and read a file independently.

**Final challenge answers**

- Username returned by `whoami`: `ubuntu`
- Kernel version shown by `uname -a`: `6.14.0-1018-aws`
- Free disk space reported by `df -h`: `58G`
- Message inside `day1_report.txt`: `END-OF-DAY1`

## 5. Key Takeaways

The main commands and concepts I learned were:

- `pwd` — Displays the current working directory.
- `ls` — Lists files and directories.
- `ls -l` — Displays detailed information about files and directories.
- `ls -al` — Includes hidden files in a detailed listing.
- `cd` — Changes the current directory.
- `cd ..` — Moves up one directory.
- `find` — Searches for files and directories.
- `cat` — Displays the contents of a file.
- `whoami` — Displays the current username.
- `uname -a` — Displays system and kernel information.
- `df -h` — Displays filesystem and disk-space information.
- `/etc/os-release` — Contains information about the Linux distribution.

I also learned about the Linux filesystem, hidden files, directory navigation, and how configuration files can provide useful information about a system.

## 6. Conclusion

Overall, I found this room a useful introduction to Linux and the command-line interface. The practical tasks helped me become more comfortable checking my current location, listing files, navigating directories, searching for files, and reading their contents.

I also gained experience gathering basic system information, including the current username, kernel version, available disk space, and Linux distribution. The final challenge helped reinforce these skills by asking me to locate and read a file independently.

These commands are only the beginning, but they provide a useful foundation for continuing my Linux and cybersecurity learning journey.

**Room status:** Completed  