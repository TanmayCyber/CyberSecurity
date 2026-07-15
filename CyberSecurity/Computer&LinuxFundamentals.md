<div align=center>

 # 💻 Computer and Linux Fundamentals
</div>

---
 
## What Is A Computer?

- A computer is an electronic device that stores, processes and produces a meaningful output from given data using a set of instructions. We can even program a computer according to our needs or the specific tasks we want it to perform.
- A Computer operates on a simple IPO(Input-Process-Output) cycle.
<div align=center>

 >*Note: A computer is not defined by its appearance, any electronic device that is programmable and capable of processing data can be considered a computer.*
</div>

---

## Components of a computer

- **Hardware:** The Physical components of a computer are known as its hardware.
  * Example: CPU(Central Processing Unit), Keyboard, Monitor etc.
- **Users:** A user is any individual or program that interacts with a computer.
    * Example: Student, Programmer etc.
- **Software:** Software is a set of instructions programmed to complete a specific task. It is mainly divided into 3 types:
  
  * Application Software: It is a type of software designed to complete a specific task.
      * Example: MS Word, Instagram, Facebook etc.
  
  * Utility Software: Utility Software helps us analyze, optimize and maintain our Computer System.
      * Example: Disk Fragmenter, Antivirus etc.
  
  * System Software: It is a type of software designed to run Computer's hardware and Application Software.
      * Operating System(OS): Operating System is a system software that acts as the interface between user and computer.
          * Example: macOS, Windows, Ubuntu(A **distro** of Linux)
>*Note: You will learn about Distro in this file itself.*

<br>

---

## History Of Linux


- **1950s–60s:** Computers were large, expensive, and mainly used by governments, universities, and large corporations.
- As computers grew more powerful, new problems emerged: multiple users needed to share one machine, developers wanted a standardized way to write software, and manual file management became impractical.
- **1969:** Researchers at Bell Labs developed **UNIX**, solving these problems by introducing multiuser support, multitasking, and other key features.
- Early operating systems were written in assembly language, making them hard to maintain or port to new hardware. **Dennis Ritchie** developed the **C programming language**, and much of UNIX was rewritten in C — making it portable across different hardware.
- **1983:** **Richard Stallman** launched the **GNU Project** (*GNU's Not UNIX*), aiming to build a system that was free to use, modify, and distribute, and compatible with UNIX.
> A **kernel** is system software that acts as a bridge between a computer's hardware and the software (applications) running on it.
- GNU had nearly everything needed for a full OS — except a working kernel. Its own kernel project, **GNU Hurd**, began in 1990 but progressed slowly.
- Around the same time, **Andrew S. Tanenbaum** developed **MINIX**, a small UNIX-like OS built for teaching — not for production use, but it inspired many students.
- **1991:** A Finnish computer science student, **Linus Torvalds**, began building a new kernel as a personal hobby project. On **25 August 1991**, he announced it on the Usenet newsgroup `comp.os.minix`, describing it as just a hobby that wouldn't be "big and professional" like GNU.
- This kernel became known as **Linux**.

---

# Linux

As mentioned in the Linux History, Linux is not an operating System, it is a kernel.

>GNU and Linux combined make an operating system that is commonly known as Linux.

Without the kernel, the operating system cannot function.

---

## Why Linux?

Linux has become one of the most important Operating Systems at present because it is:

- **Free:** Most of the Distros of Linux are available for free at their official websites.
- **Open Source:** Source Code of Linux is available to us and we are free to use, edit, and share it.
- **Secure:** Linux is more secure because of its strong permission system and open-source development reduces the risk of unauthorized access and malware.
- **Stable:** Linux is more stable because its efficient resource management and process isolation allows it to run reliably for long periods without crashing.
- **Flexible:** We can customize Linux according to our preference and requirements.

Cybersecurity professionals work with operating systems daily, tasks such as system administration, network analysis, log analysis, etc., are commonly performed on Linux systems.

Most cybersecurity tools are developed primarily for Linux because it offers powerful command-line utilities, scripting capabilities, and fine-grained control over system resources.


A strong Linux foundation makes advanced cybersecurity topics significantly easier to understand.

Linux is used almost everywhere: Mobile Devices(Android is also based on Linux), Supercomputers, Cloud Computing, and of course Cybersecurity. That is also the reason why Linux is important for Cybersecurity.

---

## Linux Ecosystem

The Linux Ecosystem is the broader collection of projects, tools, and communities 
that different distros draw from. Each layer has multiple competing options:

- **Kernel:** Linux Kernel (the one constant across all distros)
- **Core utilities:** GNU Utilities, BusyBox (lighter alternative)
- **Shells:** bash, zsh, fish
- **Package Managers:** APT (Debian/Ubuntu), DNF (Fedora), Pacman (Arch)
- **Desktop Environments:** GNOME, KDE Plasma, XFCE
- **Software Repositories:** distro-specific repos, Flatpak, Snap

## Linux Distributions (Distro)
A distro is one complete, assembled operating system built by picking specific 
options from the ecosystem above. Example — Ubuntu:

- Linux Kernel
- GNU Utilities
- System Libraries
- Shell
- Package Manager
- Software Repositories
- Desktop Environment (optional)
- Applications
- Documentation

## Linux Kernel

The Linux Kernel is the core of every Linux Distro. It acts as the intermediary between hardware and software, and provides essential information/services to the running software. It does this through:

- Process management
- Memory management
- Hardware communication
- Device management
- File system management
- Network management
- Security enforcement

Every Linux distribution uses the Linux kernel, although different distributions might use different kernel versions.

## GNU Utilities

GNU provides many commands that we will use daily in the future, examples include:

- `ls`
- `cp`
- `mv`
- `rm`
- `mkdir`
- `cat`
- `grep`
- `chmod`
- `chown`
- `bash`

Without GNU utilities, Linux would only provide the kernel, making it difficult for users to interact with the system.

## System Libraries

Libraries provide reusable code that applications use. Instead of calling the same command repeatedly, applications call library functions. Some common libraries are:

- glibc
- OpenSSL
- libstdc++

## Shell

The Shell is a program that interprets user commands and communicates with the operating system. Popular Linux shells are:

- Bash: Common shell on many distros
- Zsh: Interactive shell with plugins/add-ons
- Fish: Beginner-friendly interactive shell

>Note: Terminal is the interface on which we type commands and shells are the interpreters that communicate with the OS for output.
