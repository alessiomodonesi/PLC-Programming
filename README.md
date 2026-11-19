# Siemens Simatic PLC - Industrial Automation Labs

Repository containing source code, exercises, and practical labs for programming **Siemens Simatic PLCs** developed with **TIA Portal**, as part of the Industrial Automation course (University of Padova).

---

## 📌 Table of Contents

- Completed Labs
  - [Lab 1: Block Structure and Operands](./LAB01/)
  - [Lab 2: RLO Operations, Accumulators, and Comparisons](./LAB02/)
  - [Lab 3: Data Blocks (DB) and Memory Management](./LAB03/)
  - [Lab 4: Analogue Signal Acquisition and Scaling](./LAB04/)
  - [Lab 5: Indirect Addressing and Pointers](./LAB05/)
  - [Lab 6: Data Block (DB) Transfer and Control Flow](./LAB06/)

---

## 🏢 Overview

The course provides the practical and theoretical foundations for programming and configuring Siemens Simatic series PLCs (S7-300 / S7-1200 / S7-1500). The goal is to develop structured and modular industrial control logic by managing digital and analogue signals, memory registers, data blocks, indirect addressing, and execution flow manipulation (RLO).

> 💡 **TIA Portal Simulation Tip:** When running simulations in TIA Portal, configure your project using the **CPU 313C-2 DP** (S7-300 series) to ensure full compatibility with Instruction List (STL/AWL) operations, accumulators, and pointer-based indirect addressing.
---

## 📁 Project Structure

```text
.
├── LAB01/          # Exercises on OB, FC, FB, and memory allocation (Byte/Word/DWord)
├── LAB02/          # Boolean operations, Set/Reset, Load/Transfer, and Comparisons
├── LAB03/          # Creation and manipulation of Data Blocks (shared and instance DBs)
├── LAB04/          # Parameterized analogue acquisition (FC6), linear scaling, and error flags
├── LAB05/          # 32-bit/16-bit pointers (P#x.y) and indirect memory/block addressing
├── LAB06/          # Dynamic DB-to-DB transfer (FC8), BEB/CLR instructions, and length checks
└── README.md       # Repository documentation
