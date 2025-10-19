---
date: 2025-10-19
draft: false
---

# Introduction to Operating Systems

## What is a program?

- A program is a set of instructions and data that tell a computer what to do.
- It is static and lives on persistent storage (disk).

## What is an Operating System?

- An OS is a piece of software that makes it easier for us to manage and run multiple programs.
- It aims to make sure the system operates safely, correctly and efficiently.

1. `Virtual Machine`:

- It uses `Virtualisation` to take `physical` resources (CPU, memory, disk) and transform them into
  a more general and `virtual` version of itself.
- Virtualisation allows us to create `illusions` or more `powerful abstractions` of what the raw
  hardware really is such as the `Process (Virtual CPU)` and the `Address Space (Virtual Memory)`.
  The hardware is limited but this abstraction allows us to solve a lot of problems and achieve the
  goals of an ideal OS.

2. `Resource Manager`:

- Virtualisation allows many programs at the same time and so they will share physical resources.
- Therefore, the OS needs to manage resources with a set of policies and mechanisms so that this is
  achieved safely, correctly and efficiently.

3. `Standard Interface`:

- The OS provides an API of system calls that allow application programs to interact with the
  hardware or other processes through a standardised interface.
- This improves portability since programs can now run on various types of hardware as long it runs
  the given OS (or compatible system calls).

## Summary

- The OS uses virtualisation to create the illusion of plentiful, dedicated resources for every
  program, while serving as a strict resource manager to safely coordinate the sharing of physical
  hardware, all accessed by applications through a unified standard interface of system calls.
