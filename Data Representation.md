# TryHackMe: Data Representation

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Room:** Data Representation  
**Difficulty:** Beginner  
**Status:** Completed

## Overview

I completed the Data Representation room as part of my TryHackMe Pre Security learning journey. I learned how computers represent colors and numbers using binary, decimal, hexadecimal, and octal systems.

The exercises helped me practise converting values between number systems and understand how RGB values combine to represent colors.

## 1. Introduction

I learned that people commonly use the decimal system, which has ten digits, while computers represent information using binary, which has two digits: `0` and `1`.

The room also explained how binary and hexadecimal are useful when working with computer data. For example, hexadecimal values can make raw bytes easier to read.

## 2. Representing Colors

I learned that a color on a computer screen can be represented using red, green, and blue (RGB) values. In a 24-bit color representation, each color channel uses one byte, allowing 256 possible values for red, green, and blue.

The three values together can represent more than 16 million color combinations. Hexadecimal makes these values easier to write: each pair of hex digits represents one byte, and each hex digit corresponds to four binary bits.

**Answers**

- What does the color `#3BC81E` appear to be? **Green**
- What is the binary representation of `#EB0037`? **`11101011 00000000 00110111`**
- What is the decimal representation of `#D4D8DF`? **`212 216 223`**

## 3. Number Systems

I practised converting values between decimal, binary, and hexadecimal. I learned that hexadecimal uses the digits `0` to `9` and the letters `A` to `F`. Each hexadecimal digit represents four binary bits.

The room also introduced octal, a base-8 system where each digit represents three binary bits.

<img width="1920" height="917" alt="1" src="https://github.com/user-attachments/assets/cf3c6471-28bc-401f-806a-abe5418a61d9" />
<img width="1913" height="892" alt="2" src="https://github.com/user-attachments/assets/195e3b53-f715-4d53-86b3-8482a00bd64b" />
<img width="1920" height="922" alt="3" src="https://github.com/user-attachments/assets/2b371ce2-8266-4e37-8f6d-4d00a2087509" />

**Answers**

- What is the hexadecimal `FF` in binary? **`1111 1111`**
- What is the hexadecimal `AB` in decimal? **`171`**
- Convert `FFFFFF` to decimal as one number, then round to the nearest million. How many millions is that? **17 million** (`16,777,215` rounds to `17,000,000`)

## 4. Key Takeaways

The main concepts I learned were:

- Binary uses `0` and `1` to represent values.
- A byte consists of 8 bits.
- Hexadecimal uses digits from `0` to `9` and letters from `A` to `F`.
- RGB colors use values for red, green, and blue.
- Binary, decimal, and hexadecimal values can be converted between one another.

## 5. Conclusion

Overall, I found this room a useful introduction to how computers represent colors and numbers. Practising conversions between binary, decimal, and hexadecimal helped me understand values I may encounter when working with computer data.

**Room status:** Completed
