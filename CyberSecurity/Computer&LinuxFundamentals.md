<div align=center>

 # 💻 Computer and Linux Fundamentals
</div>

---
 
# What Is A Computer?

- A computer is an electronic device that stores, processes and produces a meaningful output from given data using a set of instructions. We can even program a computer according to our needs or the specific tasks we want it to perform.
- A Computer operates on a simple IPO(Input-Process-Output) cycle.

## Data, Information and difference bw them

Data and Information are considered same in most cases, but they are not the same.

Data refers to the raw fact that have not been processed yet, they might or might not have a meaning.

<div align="center"> **But** </div>

Information is the processed data that can be understood and has a meaning.

## IPO cycle

Input: The data provided to computer
Process: Converting the provided data to useful information.
Output: Displaying or providing processed data to user


<div align=center>

 >*Note: A computer is not defined by its appearance, any electronic device that is programmable and capable of processing data can be considered a computer.*
</div>

---

# Components of a computer

<br>

## **Hardware** 

The Physical components of a computer that you can touch are known as its hardware.

### CPU(Central Processing Unit)

CPU is known as the brain of a computer, it is responsible for all sorts of processing, executing instructions and coordinating everything.

The CPU performs every instruction in cycles, each cycle performed per unit second is known as the CPU's clock speed,  it is measured in Hertz(Hz).A higher clock speed generally allows a processor to complete more work, but overall performance also depends on other factors like number of CPU cores etc.

### Memory

- Storage: Devices that are used to store data permanently even when computer is turned off.
- RAM(Random Access Memory): It is the computer's faster but short term memory, its contents are lost when computer is powered off.

 ### Buses

 Just like real life buses, computer buses are used to transfer data/information from one place to another.

 ### Input Devices and Output Devices

 Input Devices: The devices that take input from user and send it to the computer are called Input Devices. Example: Keyboard, Mouse etc.
 
 Output Devices: The devices that take processed information/output from computer and presents it to user are called output devices. Example: Monitor, Printer etc.

## **Software:** 

A Software is a set of instructions programmed to complete a specific task. It is mainly divided into 3 types:

* Application Software: It is a type of software designed to complete a specific task, they only gets opened when we open them. Example: MS Word, Instagram, Facebook etc.
  
* Utility Software: Utility Software helps us analyze, optimize and maintain our Computer System. Example: Disk Fragmenter, Antivirus etc.

* System Software: It is a type of software designed to run Computer's hardware and Application Software.
 
### Operating System(OS): 

Operating System is a system software that acts as the interface between user and computer, it is responsible for data management, networking, user management etc. Example: macOS, Windows, Ubuntu(A **distro** of Linux)

>*Note: You will learn about Distro in this file itself.*

Firmware: It is a software that is permanently stored in Motherboard of a computer that is responsible for starting all of the hardwares and checking if all hardware components are working properly.

BIOS(Basic Input Output System) was the basic firmware that was used by older computers and nowadays UEFI(Unified Extensible Firmware Interface) is being used because it offers faster and secure boots.

## **Users:** 

A user is any individual or program that interacts with a computer. Example: Student, Programmer etc.

<br>

---

# Linux


## History 

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

## Linux Basics

As mentioned in the Linux History, Linux is not an operating System, it is a kernel.

>GNU and Linux combined make an operating system that is commonly known as Linux.

Without the kernel, the operating system cannot function.

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

### User Space and Kernel Space

User space and Kernel Space are two different memory areas in Operating Systems, this separation is done for our computer's security and stability. If not separated, an application can delete, read and write anything. 

User Space: It is where normal applications are stored and run, these applications cannot directly access Hardware, they first have to use system call then if kernel accepts the system call, the operation is done

System Call: A system call (syscall) is a request made by a user-space program to the kernel to perform an operation that requires privileged access.

Kernel Space: It is where Linux Kernel runs, it has full access to computer.

---

### Linux Ecosystem

The Linux ecosystem is the collection of all the software, tools, distributions, developers, companies, and communities that work together to develop, support, and use Linux.

#### Linux Distributions (Distro)

A distro is one complete operating system built around Linux Kernel. it Includes: Example — Ubuntu:

- Linux Kernel
- GNU Utilities
- System Libraries
- Shell
- Package Manager
- Software Repositories
- Desktop Environment (optional)
- Applications
- Documentation

Some Popular Distributions are:

1) Ubuntu: It is beginner friendly.
2) Debian
3) Parrot Security OS: All rounder for CyberSecurity
4) Kali Linux: Best for Pentesting

#### Linux Kernel

The Linux Kernel is the core of every Linux Distro. It acts as the intermediary between hardware and software, and provides essential information/services to the running software. It does this through:

- Process management
- Memory management
- Hardware communication
- Device management
- File system management
- Network management
- Security enforcement

Every Linux distribution uses the Linux kernel, although different distributions might use different kernel versions.

#### GNU Utilities

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

#### System Libraries

System Libraries provide reusable code for applications such that they can reuse code from System Libraries instead of writing its own code. Some common libraries are glibc, OpenSSL ,libstdc++.

#### Shell

The Shell is a program that interprets user commands and communicates with the operating system. Popular Linux shells are:

- Bash: Common shell on many distros
- Zsh: Interactive shell with plugins/add-ons
- Fish: Beginner-friendly interactive shell

>Note: Terminal is the interface on which we type commands and shells are the interpreters that communicate with the OS for output.

#### Package Managers

A package manager acts like an app manager for Linux. Instead of downloading and installing software manually, it handles the entire process for you, including any additional software dependencies the application might needs to work properly.

Dependencies are additional software, libraries, or files that a program needs in order to run correctly.

#### Software Repositories

A software repository (repo) is an online collection of software packages maintained by a Linux distribution or a trusted organization. Package managers use these repositories to install and update software.

#### Desktop Environment 

A Desktop Environment is a collection of software that provides the graphical user interface (GUI) of a Linux operating system, allowing users to interact with the system using windows, icons, menus, and a mouse. Example: GNOME, KDE Plasma etc.

---

# Installing Ubuntu

## Why Ubuntu?

You all must me wondering that I already said that Kali Linux is best for Pentesting, Parrot OS is all rounder in CyberSecurity then why must we learn Ubuntu why not just start with them.

The answer is simple, they are not beginner friendly, they are too complicated for a beginner to understand, that's why we will start by learning Ubuntu then move on to Kali Linux or Parrot OS.

## Ways to install Ubuntu

- **Virtual Machine**

A virtual machine allows Ubuntu to run inside your existing operating system. It is safe to experiment, easy to reset and changes nothing in our current system.

- **Dual Boot**

Ubuntu and another operating system (such as Windows) are installed on the same computer, when the computer starts, you can choose which operating system to boot. the only disadvantage is that installation is really complex and mistakes may affect existing OS.

- **Full Installation**

Ubuntu replaces the existing operating system and uses the entire computer.

- **Live USB**

Ubuntu can also run directly from a bootable USB drive without installation.

---

# Common Misconceptions

1) Linux is a Operating System

Linux is a Kernel, not Operating System.

2) Ubuntu is Linux itself

No, Ubuntu is a Distribution of Linux.

3) GNU and Linux are the same thing.

GNU and Linux are separate projects just combined together to build various Distros

4) Linux is only for hackers.

Many Developers, scientists, researchers etc also use linux for various reason not for just hacking.

5) The kernel is the operating system

No, Kernel is a core component of OS but not OS itself.

6) Applications communicate directly with hardware

As explained above, applications communicate with Kernel then kernel communicated with hardware.

7) The operating system starts first

Firmware starts first.

8) Every Linux distribution is completely different

No, every Linux distro contains Linux Kernel and GNU

9) Linux has no graphical interface.

Linux supports many graphical desktop environments.

10) Android is not related to Linux

Android is also built on Linux Kernel
