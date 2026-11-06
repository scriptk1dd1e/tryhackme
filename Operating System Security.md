# TryHackMe: Operating System Security

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Room:** Operating System Security  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Operating System Security room as part of my TryHackMe Pre Security learning journey. It introduced the confidentiality, integrity, and availability principles, along with common operating system security weaknesses such as weak passwords, weak file permissions, and malicious programs.

In the practical task, I used SSH to access a Linux lab machine and practised basic commands for checking my account, listing files, reading a text file, and viewing command history.

## 1. Introduction to Operating System Security

I learned that an operating system sits between computer hardware and the applications that use it. The room also introduced the three main security principles:

- **Confidentiality:** Information should only be accessible to the people who are meant to see it.
- **Integrity:** Files and information should not be changed without authorization.
- **Availability:** Systems and data should be accessible when needed.

**Answer**

- Which option is not an operating system? **`Thunderbird`** — it is an email client.

## 2. Common Examples of OS Security

I reviewed three common areas of operating system security: authentication and weak passwords, file permissions, and malicious programs. I learned that passwords based on common words or keyboard patterns are easier to guess, while weak file permissions can let people access or modify files they should not. Malicious programs can affect confidentiality, integrity, and availability. For example, ransomware can make files unavailable by encrypting them.

**Answer**

- Which listed password is hardest to guess based on the top 20 list? **`LearnM00r`**

## 3. Practical Example of OS Security

I connected to the lab machine over SSH using the provided Sammie account and password. After logging in, I used `whoami` to confirm which account I was using, `ls` to list files, and `cat` to read a text file. I also learned that `history` displays commands entered by the current user.

**[Insert screenshot: Logging into Sammie over SSH]**

The exercise then had me try the room’s password list for Johnny. After logging in as Johnny, I used the command history to find the root password, switched to the root account, and read the flag file.

**[Insert screenshot: Cracking Johnny’s password and logging in]**

**Useful commands**

- `ssh <username>@<IP_address>` — Connects to a remote machine over SSH.
- `whoami` — Shows the current username.
- `ls` — Lists files in a directory.
- `cat <filename>` — Displays a text file’s contents.
- `history` — Shows commands entered in the current shell.
- `su - root` — Switches to the root account when authorized and provided the correct password.

**Answers**

- Which password from the first seven opens Johnny’s account? **`abc123`**
- What is the root password shown in Johnny’s command history? **`happyHack!NG`**
- What is the content of `/root/flag.txt`? **`THM{YouGotRoot}`**

## 4. Key Takeaways

The main concepts and skills I learned were:

- The roles of confidentiality, integrity, and availability in system security.
- Why weak or reused passwords can put accounts at risk.
- How file permissions relate to the principle of least privilege.
- How to connect to a Linux machine over SSH.
- How to check the current user, list files, read a text file, and review shell history.

## 5. Conclusion

Overall, I found this room a useful introduction to operating system security and basic Linux access. The practical exercise showed how weak passwords and exposed command history can create security risks, while also giving me practice with common Linux commands.

**Room status:** Completed
