# TryHackMe: Data Encoding

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Room:** Data Encoding  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Data Encoding room as part of my TryHackMe Pre Security learning journey. I learned how computers represent text as numbers and how character encodings map those numbers to letters, punctuation, and other symbols.

The room covered ASCII, its limitations, and how Unicode and UTF encodings support text from languages around the world, as well as symbols and emojis.

## 1. Introduction

I learned that computers store data as bits and numbers, while an **encoding** is an agreed mapping between numbers and meanings. For text, each character is assigned a numeric code, so a string becomes a sequence of numbers that a computer can store and process.

I also learned that mismatched encodings can cause text to appear as garbled characters. Understanding encoding is useful when reading files and logs, and when considering how different systems interpret text.

## 2. ASCII

I learned that ASCII stands for **American Standard Code for Information Interchange**. It is an early character encoding that uses codes from 0 to 127 to represent English letters, digits, punctuation, and control characters.

ASCII uses seven bits. Some codes represent actions rather than printable symbols—for example, code 10 is LF, which represents a line feed. The room showed how the text `TryHackMe` can be represented as a sequence of ASCII bytes in binary, hexadecimal, octal, or decimal.

**[Insert screenshot: ASCII web activity]**

**Answers**

- What is the ASCII code in decimal for the character `@`? **`64`**
- What character has the ASCII code `35` in decimal? **`#`**
- What is the abbreviated name of the control character with ASCII code `7`? **`BEL`**

## 3. Unicode and UTF

I learned that ASCII is limited, especially when representing languages that use characters outside the English alphabet. The ISO/IEC 8859 standards supported additional European characters, but different standards covered different language groups. Reading a file using the wrong encoding can therefore display some characters incorrectly.

Unicode provides a way to represent characters from languages around the world, along with symbols such as chess pieces and emojis. The room introduced UTF-8, UTF-16, and UTF-32 as Unicode encoding standards.

**[Insert screenshot: Unicode web activity]**

## 4. Key Takeaways

The main concepts I learned were:

- An encoding maps numbers to characters and other meanings.
- ASCII represents English letters, digits, punctuation, and control characters using codes from 0 to 127.
- Different encodings can represent text differently, which may cause garbled characters when they do not match.
- Unicode supports a much broader range of languages, symbols, and emojis.
- UTF-8, UTF-16, and UTF-32 are encoding standards used with Unicode.

## 5. Conclusion

Overall, I found this room helpful for understanding how text is stored as numbers and why the encoding used to save and read a file matters. Learning about ASCII, Unicode, and UTF encodings gave me a clearer picture of how computers handle text from different languages and symbol sets.

**Room status:** Completed
