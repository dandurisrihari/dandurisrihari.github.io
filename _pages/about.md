---
permalink: /about/
title: "About"
layout: single
author_profile: true
---

## Summary

PhD student and researcher with extensive experience in system software development, specializing in low-level software security, drivers, firmware, operating systems, and runtime libraries. My current research focuses on analyzing the design of the latest edge AI systems to understand different design choices and explore their system security aspects.

## Education

**Doctor of Philosophy, Computer Engineering**  
*Purdue University* (Aug 2023 - Present)  
GPA: 3.37

**Master of Science, Computer Engineering - Electrical Engineering (Embedded Systems)**  
*Arizona State University, Tempe, AZ* (Aug 2019 - May 2021)  
GPA: 3.84

**Bachelor of Technology, Electrical Electronics Engineering**  
*GVPCOE, Jawaharlal Nehru Technological University, Kakinada, India* (Aug 2014 - May 2018)

## Experience

### Graduate Research Assistant
**Purdue University** (Aug 2023 - Present)
- Studied the design of Google Coral Dev board, TDA4VM (Texas Instruments), and Tinker Edge R (Asus) Embedded Edge AI accelerators to understand the interaction between the application processor and accelerator hardware
- Analyzed flow from application level to firmware on the accelerator, starting from application to runtime libraries (vendor-specific userspace libraries, and framework runtimes like TensorflowLite, and ONNX), Linux kernel drivers and subsystems, and firmware on accelerator hardware
- Answered research questions like Open Session, Memory Setup, Sending Request, Receive request, and close session
- Investigating if confused deputy attacks are possible, determining whether a malicious application can confuse the accelerator to corrupt the kernel memory or other process memory
- Found some design-level security vulnerabilities and reported them; investigation by companies is under progress

### Silicon Firmware Development Engineer (Firmware Security)
**Intel Corporation** (Jun 2021 - Aug 2023)
- Implemented security hardening features in Intel Boot Guard and Trusted Execution Technology
- Developed various features in BIOS and SINIT ACMs (Intel Authenticated Code Modules), providing BIOS/UEFI security for Intel's silicon products, such as Intel Core processors and PCH chipsets
- Worked closely with Intel silicon design teams and was responsible for ACM software and BIOS-related issues during the program's planning, development, and validation stages
- Addressed customer issues and fixed bugs reported in the Common Vulnerabilities and Exposures (CVE)
- Served as point of contact for some of the critical features (x86 paging) in Client BIOS security
- Ensured validation and mitigation of any risks associated with silicon bugs during the pre-silicon phase
- Actively involved in planning for potential issues, executing system debugging, and ensuring smooth silicon power-on

### Software Development Intern (Firmware Security)
**Intel Corporation** (Jan 2021 - Apr 2021)
- Implemented startup code in X86 Assembly Language (MASM and NASM)
- Re-structured the Build-system to incorporate support for various Compilers and Intel Crypto Libraries
- Investigated and implemented hardening features against stack canary attacks

### Embedded Systems Firmware Intern
**Praan** (May 2020 - Aug 2020)
- Developed prototype firmware on the ST NUCLEO-F303RE development board (ARM 32-bit Cortex-M4)
- Utilized UART, USART, and SPI protocols to collect data from multiple sensors in the RTOS environment
- Lead the board Bring-up stage and contributed to assessing the software/hardware requirements in the design
- Working experience with HAL, CMSIS APIs, and FreeRTOS

### Assistant System Engineer-Trainee
**Tata Consultancy Services (TCS)** (Nov 2018 - Mar 2019)
- Worked for Verizon client in the backend development of IoT products (Oracle DB)

### System Engineer Intern
**Tata Consultancy Services** (Nov 2017 - Apr 2018)
- Worked on the prototype project IOT-Autonomous Garbage / Package Collection System

## Skills

**Programming Languages:** C, C++, x86 Assembly, Python, bash scripting, Java

**Architecture and Protocols:** x86, ARM, SPI, I2C, UART, CAN, PCI, PCIe, BLE

**Tools & Technologies:** GNU toolchains, LLVM, MLIR, CUDA, PyTorch, TensorFlow, TPM, BIOS, platform security, cryptography, Windows Secure Launch, Board bring-up, Tboot, JTAG, SWV, FreeRTOS, Kernel programming, Device drivers, Shell scripting, Bare-metal firmware, debugging and fault analysis, embedded Linux, DMA, Custom Bootloader, Resource management, Intel silicon products, Intel Galileo Gen 2, NUCLEO, Raspberry Pi, cadence virtuoso, HSPICE, Git, JIRA, GitHub

**Relevant Coursework:** Programmable Accelerator Architectures, Holistic Software Security, Real-Time Embedded Systems, Embedded Operating Systems Internals, Computer Architecture-2, Foundations of Algorithms, Digital Systems and Circuits, Distributed and Multiprocessor Operating Systems, Wireless Networks, Artificial Neural Computation, Mobile Systems Architecture

## Selected Projects

### Exploring Security Aspects Of Edge AI Accelerators
*Purdue University*
- Analyzing the security threats Edge AI Accelerators pose to Application processors
- Exploring the possibility of confused deputy attacks and the semantic gap between the AI Accelerator and host communication

### Rehosting Embedded Applications As Linux Applications
*Purdue University*
- Continuing previous work on the initial idea paper
- Wrote LLVM passes, optimized the porting pipeline, and different fuzzing techniques
- Stripping off all architecture-dependent parts of embedded applications and instrumenting the MMIO access followed by fuzzing to find security bugs

### CUDA Implementation of Convolutional Neural Networks and General Matrix Multiply
*Purdue University*
- Implemented convolution CUDA kernels and optimized them by leveraging shared memory, memory coalescing using cache aligned stride patterns
- Implemented and optimized GEMM CUDA kernels using both CUDA memory copies and unified virtual memory to compare performance

### LLVM Playground
*Purdue University*
- Implemented LLVM passes to develop a simple data flow analysis to detect divide-by-zero errors in C code
- Improved analysis to handle pointer aliasing and allocated memory
- Built a dynamic analyzer to catch division-by-zero errors at runtime
- Developed LLVM passes to insert runtime checking and monitoring code

### Symbolic Execution Playground
*Purdue University*
- Implemented a dynamic symbolic execution (DSE) engine that automatically generates inputs to efficiently explore different program paths
- Used an LLVM pass to encode C programs into symbolic interpretation API and Z3 for constraint solving

### USB Drivers in Linux
*Arizona State University*
- Wrote detailed report on USB implementation in Linux kernel (v3.19.8)
- Developed a kernel module that hacks and steals USB device information

### Linux Kernel Device Drivers for HC-SR04 Ultrasonic Distance Sensors
*Arizona State University*
- Developed Linux kernel module to enable user-space device interface for HC-SR04
- Developed platform driver/platform device infrastructure for HC-SR04 sensors
- Tested the sysfs interface with Bash scripts

### Custom Bootloader - STM32F303RE-NUCLEO BOARD
*Arizona State University*
- Designed a custom bootloader for the STM32Nucleo-F303RE board to update on-chip firmware through UART
- Implemented handling of multiple applications and various boot options

## Contact

- **Email:** ddanduri@purdue.edu
- **Phone:** +1 (480) 937-9406
- **Location:** 512 N 5th St #B, Lafayette, IN 47901
- **LinkedIn:** [linkedin.com/in/dandurisrihari](https://linkedin.com/in/dandurisrihari)
- **GitHub:** [github.com/dandurisrihari](https://github.com/dandurisrihari)
