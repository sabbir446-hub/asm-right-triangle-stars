# 8086 Assembly Nested Loop Star Pattern

A basic 8086 Assembly Language program written in MASM/TASM syntax that demonstrates nested loops, jump-on-non-zero (`JNZ`) conditions, and character pattern printing using DOS interrupts (`INT 21H`).

## 🚀 Project Overview

This program automatically generates a right-angled triangle pattern consisting of stars (`*`) without needing any user input. It handles grid tracking using dual registers (`CL` and `BL`), simulating row and column execution typically seen in higher-level language nested `for` loops.

## 📐 Output Visual

When executed, the program outputs a 5-row pattern where the row number dictates the number of stars printed:

```text
*
**
***
****
*****
