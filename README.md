# Linux 0.01

This repository contains the Linux 0.01 source tree, the earliest public version of Linux created by Linus Torvalds.

## Overview

Linux 0.01 is a historical snapshot of the kernel's origin. It is useful for studying:

- Early Unix-like kernel design decisions
- Low-level x86 bootstrapping and assembly
- The foundations of process, memory, and filesystem handling in Linux

## Repository Layout

- `boot/`: Early boot code (`boot.s`, `head.s`)
- `init/`: Kernel entry and initialization (`main.c`)
- `kernel/`: Core kernel subsystems (scheduling, syscalls, console, traps)
- `mm/`: Memory management implementation
- `fs/`: Filesystem and file descriptor logic
- `lib/`: Minimal C library support used by the kernel/user boundary
- `include/`: Header files and constants
- `tools/`: Build helper tooling
- `Makefile`: Top-level build rules for this historical tree

## Notes

- This codebase targets very old hardware/software assumptions and is mainly for learning and historical reference.
- Building and running it on modern systems may require an emulator and additional compatibility setup.

## Why This Repo Exists

This mirror provides a clean place to read and navigate the first Linux release while exploring how the kernel began.

## Questions / Support

If you also have an interest in the first version of Linux and would like to discuss something specific, feel free to reach out. I am happy to answer questions and help where I can.

If this repo saved you some time and you feel like fueling more writeups, coffee is always appreciated:
[https://buymeacoffee.com/wg21908](https://buymeacoffee.com/wg21908)
