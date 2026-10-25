# 💻 Computer and Linux Fundamentals

---

# What Is A Computer?

A computer is an electronic device. It stores, processes and outputs meaningful information by following some instructions. We can program it to do things we need it to.

Computers follow an IPO(Input-Process-Output) cycle.

## Data and Information

In most cases data and information are considered the same but they are not.

Data is raw facts that have not been processed yet. They may or may not have any meaning.

But

Information is processed data which can be understood and has meaning.

## IPO Cycle

Input: Data given to the computer.

Process: Data is converted into useful information.

Output: Processed data is shown to the user.

> Note: A computer can be anything that can be programmed and can process data.

---

# Components Of A Computer

## Hardware

This is the physical parts of the computer.

### CPU (Central Processing Unit)

The CPU is the brains of the computer. It handles processing, executing instructions and organising everything.

Every instruction is processed in cycles. How many cycles are completed per unit second is known as the clock speed of a CPU. This is measured in hertz (Hz). The higher the clock speed the better the processor can do. However there are other factors such as how many CPU cores.

### Memory

Storage: Devices used to store data permanently.

RAM (Random Access Memory): This is the fast memory of the computer. It is short term memory so the data is lost when the computer is switched off.

### Buses

Like buses in real life, computer buses transfer data/information.

### Input Devices

These are the devices used to get input from the user and pass it to the computer. e.g Keyboard, Mouse etc.

### Output Devices

These are the devices used to give processed information/output from the computer to the user. e.g Monitor, Printer etc.

## Software

Software is a set of instructions that have been programmed to help complete certain tasks. There are mainly three types of software.

Application Software: This is software that is designed to do certain tasks. It isn't opened unless you open it. e.g MS Word, Instagram, Facebook etc.

Utility Software: This helps analyse, improve and manage our computer system. e.g Disk Fragmenter, Antivirus etc.

System Software: This is software designed to help the computer's hardware and application software.

### Operating System (OS):

An Operating System is a system software that is the link between the user and computer. It handles data management, networking and user management. e.g macOS, Windows, Ubuntu (A distro of Linux).

> Note: You will learn about Distro in this file.

Firmware: This is software that is stored permanently on the motherboard of a computer. It is responsible for powering up all of the hardwares and checking everything is working correctly.

Older computers used BIOS (Basic Input Output System) as basic firmware. They now use UEFI (Unified Extensible Firmware Interface) as it allows faster and secured boots.

## Users

Users are individuals or programs that interact with a computer. e.g Student, Programmer etc.

---

# Linux

## History

Computers in the 1950s-60s were large and expensive. They were mainly used by governments, universities or large corporations.

As computers became more powerful new issues arose. Multiple users were trying to share one computer. Developers wanted a standardised way of developing software. Manually managing files became impractical.

In 1969 Researchers in Bell Labs created UNIX. This solved the issues by adding multi-user support, multi-tasking and other vital features.

Early operating systems were created using assembly language. This made them difficult to manage and transfer to new hardware. Dennis Ritchie created the C programming language. Much of UNIX was written in C to make it transferrable between different hardware.

In 1983 Richard Stallman started the GNU Project (GNU's Not UNIX) to create a system that could be freely used, modified and distributed and be compatible with UNIX.

> A kernel is system software that is used as a bridge between the hardware and software (applications) of a computer.

GNU had nearly everything needed for a full OS however they didn't have a working kernel. Their own kernel project GNU Hurd started in 1990 but progress was slow.

Around the same time Andrew S. Tanenbaum created MINIX. This was a small UNIX like operating system. It wasn't meant to be used but inspired many students.

In 1991 a Finnish computer science student named Linus Torvalds started creating a new kernel. On 25 August 1991 he posted to the Usenet newsgroup comp.os.minix stating "Just a hobby, not big and professional like GNU." He was creating a new kernel.

This kernel became known as Linux.

---

## Linux Basics

As stated in the Linux history Linux is not an operating System. It is a kernel.

> GNU and Linux combined make an Operating System known as Linux.

Without the kernel the Operating System won't work.

Linux is one of the most important Operating Systems now as it is:

Free: Most Distros of Linux can be downloaded for free from their official websites.

Open Source: We can view the source code of Linux. We can use, modify and share it.

Secure: Linux is more secure due to the security permissions and being open source reduces the risk of unauthorised access and Malware.

Stable: Linux is more stable due to it having efficient resource management and processes.

Flexible: We can customise Linux to our liking.

Cybersecurity professionals will work with Operating Systems daily. Tasks such as administration, network analysis, log analysis etc are often carried out on Linux.

Most Cybersecurity tools are developed for Linux as it has powerful command line tools.

Having knowledge of Linux makes it much easier to understand advanced Cybersecurity topics.

Linux is used nearly everywhere. Mobile Devices (Android is also based on Linux), Supercomputers, Cloud Computing and Cybersecurity. This is why it is important for Cybersecurity.

---

### User Space And Kernel Space

User Space and Kernel Space are two different areas of memory in Operating Systems. This is to keep our computer secure and stable. Without this an application could delete, read and write anything.

User Space: This is where normal applications live. These apps cannot directly access any hardware. They have to make a system call. If the kernel agrees to the system call then the operation will be carried out.

System Call: A system call (syscall) is when a user space program requests the kernel to complete an operation.

Kernel Space: This is where Linux Kernel lives. It has full access to the computer.

---

### Linux Ecosystem

The Linux ecosystem is all the software, tools, distributions, developers, companies and communities involved in developing, supporting and using Linux.

#### Linux Distributions (Distro)

A distro is a complete Operating System based on the Linux Kernel. It includes: Example: Ubuntu:

Linux Kernel

GNU Utilities

System Libraries

Shell

Package Manager

Software Repositories

Desktop Environment (optional)

Applications

Documentation

Some popular distributions are:

Ubuntu: Great for beginners.

Debian

Parrot Security OS: All rounder for CyberSecurity.

Kali Linux: Best for Pentesting.

#### Linux Kernel

The Linux Kernel is the core of every Linux Distro. It is used as an intermediary between hardware and software. It gives essential information/services to software while running. It does this by:

Process Management

Memory Management

Hardware Communication

Device Management

File System Management

Network Management

Security

Every Linux distribution uses the Linux kernel. Different distributions may use different versions of kernels.

#### GNU Utilities

There are many commands provided by GNU that we will use regularly in the future. Examples include:

ls

cp

mv

rm

mkdir

cat

grep

chmod

chown

bash

Without GNU utilities Linux would only provide the kernel.

#### System Libraries

System Libraries allow code to be reused in applications. Some common ones are glibc, OpenSSL ,libstdc++.

#### Shell

Shell is a program that translates commands from the user. Some popular shells are:

Bash: Common shell for many distros.

Zsh: Interactive shell with plugins/add-ons.

Fish: Beginner friendly interactive shell.

> Note: Terminal is where we type our commands. Shells are the translators that talk to the OS.

#### Package Managers

A package manager is like an app manager. It will manage the whole process of downloading and installing software. It will also manage any extra software that the application may require.

Dependencies are extra software, libraries or files that will be required for a program to work.

#### Software Repositories

A software repository (repo) is an online collection of software managed by a Linux distro or trusted organisation. Package managers will use these to install/update software.

#### Desktop Environment

A Desktop Environment is a collection of software that provides a GUI for a Linux OS. Example: GNOME, KDE Plasma etc.

---

# Installing Ubuntu

## Why Ubuntu?

You may be wondering why we should learn Ubuntu when I have said that Kali Linux is best for Pentesting and Parrot OS is the all rounder for CyberSecurity.

The answer to this is simple. They are not beginner friendly. They are very complicated for beginners to understand. We will start with learning Ubuntu and then move onto Kali Linux/Parrot OS.

## Ways To Install Ubuntu

Virtual Machine

This allows you to run Ubuntu within your current operating system. It is safe to try things out, easy to reset and doesn't change anything.

Dual Boot

Ubuntu and another operating system (Windows) can be installed onto your computer. When you start up your computer you can choose what OS to use. The downside to this is that it can be very complicated to install and mistakes can effect your existing OS.

Full Installation

This will replace your operating system with Ubuntu.

Live USB

Ubuntu can be ran from a bootable USB.

---

## Common Misconceptions

1) Linux is an Operating System.

Linux is a Kernel.

2) Ubuntu is Linux.

No, Ubuntu is a Distribution of Linux.

3) GNU and Linux are the same.

They are two separate projects that have been combined to create various Distros.

4) Linux is only for hackers.

Many Developers, Scientists, Researchers etc use linux for various reasons.

5) The kernel is the operating system.

No, the kernel is a core part of the OS.

6) Applications talk directly to hardware.

As explained above applications talk to the Kernel which then talks to the hardware.

7) The operating system starts first.

The firmware starts first.

8) All Linux distributions are completely different.

No, all Linux distros have the Linux Kernel and GNU.

9) Linux doesn't have a graphical interface.

Linux supports many graphical desktop environments.

10) Android isn't related to Linux.

Android is also built on the Linux Kernel.
