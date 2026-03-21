**Vivid OS  README**

*Welcome to Vivid OS! A brand new, free, and open-source 64-bit x86 operating system currently in early development. Let's get into the details*


**SCOPE**

Goal: A 64-bit x86 kernel written in C.

Features for version 0.1: Displaying text on the screen (VGA driver), reading keyboard input, and crashing the computer cleanly (kernel panic).

What it (initially) CANNOT do: Graphical user interface (mouse, windows), internet connection, or hard drive access.


**Architecture and tools**

Bootloader:(Not decided yet)

Kernel: C

Build system: Makefile

Emulator: QEMU





## Roadmap
- [Done] Set up a GitHub repository (folder structure, .gitignore) 
- [] Configure a bootloader (e.g., Limine)
- [] First C kernel: Display "Hello World" on the screen
- [] Configure interrupts (GDT and IDT)
- [] Write a keyboard driver

**you can also look at issues for more infos on plans**