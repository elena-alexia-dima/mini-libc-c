A from-scratch implementation of core C standard library functions, built entirely
using low-level Linux syscalls — no libc dependency.
The project covers string manipulation, memory management, and I/O operations,
giving full visibility into how standard library functions actually work under the hood.

Features:
- String functions: strcpy, strlen, strcmp, strcat
- Memory management: malloc, free, memcpy, memset
- I/O operations: puts, putchar, open, close, read, write
- No external dependencies — pure syscalls only

Technologies:
- Language: C
- System Interface: Linux syscalls (x86/x86-64)
- Tools: GCC, Make, GDB
