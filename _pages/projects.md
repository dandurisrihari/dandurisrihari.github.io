---
permalink: /projects/
title: "Research & Projects"
layout: single
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-bg.jpg
toc: true
toc_label: "Projects"
toc_icon: "code"
---

## Current Research

### Exploring Security Aspects Of Edge AI Accelerators
**Purdue University** | *Aug 2023 - Present*

{: .notice--primary}
**Research Focus:** Analyzing security threats that Edge AI Accelerators pose to Application processors, exploring confused deputy attacks and semantic gaps in AI Accelerator-host communication.

**Key Achievements:**
- Studied the design of Google Coral Dev board, TDA4VM (Texas Instruments), and Tinker Edge R (Asus)
- Analyzed complete flow from application to firmware on accelerator hardware
- Mapped interactions between runtime libraries (TensorflowLite, ONNX), kernel drivers, and accelerator firmware
- **Discovered design-level security vulnerabilities** - currently under investigation by companies

**Technical Stack:** Linux kernel drivers, firmware analysis, AI accelerator hardware, security research

---

## Graduate Research Projects

### Rehosting Embedded Applications As Linux Applications
**Purdue University**

Building on initial research to port embedded applications to Linux for enhanced security analysis.

**Contributions:**
- Developed LLVM passes to optimize the porting pipeline
- Stripped architecture-dependent code from embedded applications
- Implemented MMIO access instrumentation for fuzzing
- Applied various fuzzing techniques to discover security vulnerabilities

**Technologies:** LLVM, Compiler optimization, Fuzzing, Embedded systems

---

### CUDA Implementation of Deep Learning Kernels
**Purdue University**

Series of projects implementing and optimizing GPU kernels for deep learning operations.

#### Convolutional Neural Networks & GEMM
- Implemented optimized convolution CUDA kernels
- Leveraged shared memory and memory coalescing with cache-aligned stride patterns
- Developed and benchmarked GEMM kernels using CUDA memory copies vs unified virtual memory

#### Image Processing Operations
- Built CUDA kernels for noise filtering in images
- Implemented Max, Min, and Average pooling operations
- Optimized memory access patterns for improved performance

#### AlexNet Implementation
- Transformed convolutions into matrix multiply operations
- Implemented fully connected layers
- Assembled complete AlexNet architecture using optimized GEMM building blocks

**Technologies:** CUDA, GPU Computing, Deep Learning, Performance Optimization

---

### LLVM Playground
**Purdue University**

Comprehensive exploration of compiler-based program analysis and instrumentation.

**Implementations:**
1. **Static Analysis:** Data flow analysis to detect divide-by-zero errors
2. **Advanced Analysis:** Extended to handle pointer aliasing and dynamic memory
3. **Dynamic Analysis:** Runtime instrumentation for divide-by-zero detection
4. **Program Monitoring:** Inserted runtime checking and coverage tracking code

**Technologies:** LLVM, Compiler Engineering, Program Analysis

---

### Symbolic Execution Engine
**Purdue University**

Developed a dynamic symbolic execution (DSE) engine for automated test input generation.

**Features:**
- Automatic input generation to explore different program paths efficiently
- LLVM pass to encode C programs into symbolic interpretation API
- Integration with Z3 constraint solver
- Path exploration optimization

**Technologies:** LLVM, Z3 SMT Solver, Symbolic Execution, Automated Testing

---

## Graduate Projects (Arizona State University)

### Linux Kernel Development

#### USB Drivers Analysis & Development
- Comprehensive source code review of USB implementation in Linux kernel v3.19.8
- Analyzed kernel and user-level USB mechanisms
- Developed kernel module demonstrating USB device information extraction
- **Deliverable:** Detailed technical report with implementation analysis

#### HC-SR04 Ultrasonic Sensor Driver
- Developed complete Linux kernel module (v4.19) for HC-SR04 sensors
- Implemented platform driver/device infrastructure
- Created user-space device interface via sysfs
- Built automated testing framework using Bash scripts

#### Generic Netlink Socket & SPI Programming
- Developed multithreaded user-space program for LED matrix control (MAX7219)
- Implemented Generic Netlink Socket communication
- Created asynchronous SPI device driver
- Distance-based LED pattern control system

#### Dynamic Stack Dumping System
- Implemented novel system calls for dynamic kernel stack dumping
- Used Kprobes for dynamic instrumentation without kernel rebuild
- Integrated dump_stack() in pre-handler for runtime debugging

**Technologies:** Linux Kernel, Device Drivers, Platform Drivers, Kprobes, Sysfs

---

### Zephyr RTOS Development

#### Thread Event Tracing Backend
- Developed custom tracing backend for Zephyr RTOS
- Recorded trace data in VCD (Value Change Dump) format
- Built Python analysis scripts for trace visualization
- Performance profiling and debugging capabilities

#### HC-SR04 Sensor Driver
- Implemented sensor driver with standard Zephyr APIs
- Functions: `sensor_sample_fetch_t`, `sensor_channel_get_t`, `sensor_attr_set_t`
- Thread-based sensor reading and processing

**Technologies:** Zephyr RTOS, Embedded C, Real-time Systems, Python

---

### Custom Bootloader Development
**STM32F303RE-NUCLEO Board**

Designed production-ready bootloader for STM32 microcontroller.

**Features:**
- UART-based firmware update mechanism
- Multi-application flash management
- Boot-time application selection
- Secure firmware validation

**Technologies:** Embedded C, ARM Cortex-M4, UART Protocol, Bootloader Design

---

### Message Passing in Multiprocessor OS

Built complete message passing system for multiprocessor operating systems.

**Components Developed from Scratch:**
- Thread Control Block (TCB)
- Semaphore implementation
- Message queues
- Thread scheduling
- Blocking receive / Non-blocking send operations
- Multiple server-client handling

**Technologies:** Operating Systems, Concurrent Programming, Embedded C

---

## Skills Demonstrated Across Projects

**Programming Languages:** C, C++, x86 Assembly, Python, CUDA, Bash

**Systems:** Linux Kernel, Zephyr RTOS, Bare Metal Firmware, BIOS/UEFI

**Tools & Frameworks:** LLVM, MLIR, TensorFlow, PyTorch, Z3, Git, JTAG

**Domains:** System Security, Embedded Systems, GPU Computing, Compiler Engineering, Hardware Security

---

## Publications & Reports

Research publications and detailed technical reports available upon request.

For collaboration opportunities or more information about any project, feel free to [contact me](mailto:ddanduri@purdue.edu).
