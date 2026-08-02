# PicoBlaze Research Report

This repository contains a research report examining the structure, features, and use cases of the Xilinx PicoBlaze microcontroller.
PicoBlaze is a low-resource 8-bit processor used for embedded control applications in FPGA designs.

## 📂 Content

### 1. What is PicoBlaze?
- An 8-bit RISC-based microcontroller developed by Xilinx
- Optimized for embedded control operations within FPGAs
- Embedded into FPGAs using hardware description languages (VHDL, Verilog)

### 2. Architecture
- 8-bit processor core
- 1K x 18-bit program memory
- 64 bytes of data memory
- 16 general-purpose registers
- Interrupt support
- Fast, sequential instruction execution (each instruction runs in 2 clock cycles)

### 3. Instruction Set
- 8-bit data operations
- Assignment, arithmetic, and logical operations
- Decision structures (conditional branching)
- Input/output (I/O) operations
- Program flow control (CALL, RETURN, etc.)

### 4. Programming and Usage
- Programs for PicoBlaze are written using KCPSM (Ken Chapman's PicoBlaze Assembler)
- Embedded into FPGA designs to work alongside custom hardware
- Its low resource usage makes it well-suited for small, fast projects

### 5. Use Cases
- Embedded control systems
- Sensor data processing
- Serial communication protocols
- Small helper-processor tasks on FPGAs

## 📄 Report File

📄 `picoblaze-report.pdf` — Contains all detailed explanations and examples.

## 📚 References

- Official Xilinx PicoBlaze documentation
- FPGA design examples
- Academic papers

## 👤 Author

**Sedanur Peker**
Submission date: 01.01.2025
