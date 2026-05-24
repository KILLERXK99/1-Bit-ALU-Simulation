# 1-Bit ALU Design using Discrete Transistor Logic

A transistor-level implementation and simulation of a **1-Bit Arithmetic Logic Unit (ALU)** designed entirely using discrete components in **Proteus**.  
This project focuses on understanding the fundamentals of digital logic design at the hardware level by building logic operations using transistor-based circuitry instead of predefined ICs.

---

# Project Overview

This project demonstrates the design and simulation of a functional **1-Bit ALU** capable of performing fundamental logical and arithmetic operations using:

- Discrete transistor logic
- Resistor-transistor switching networks
- Combinational digital design principles
- Hardware-level signal propagation and control

The complete circuit was designed and simulated in **Proteus Design Suite**.

---

# Features

- Transistor-level digital logic implementation
- Basic arithmetic and logic functionality
- Carry generation mechanism
- Fully simulated in Proteus
- Hardware-oriented digital design approach
- Manual logic gate construction without using logic ICs

---

# Operations Implemented

The ALU supports the following operations:

| Operation | Description |
|---|---|
| AND | Logical AND operation |
| OR | Logical OR operation |
| XOR | Exclusive OR operation |
| NOT | Inversion operation |
| ADD | 1-Bit Addition with Carry |

---

# Circuit Design

The ALU was implemented using:

- Bipolar Junction Transistors (BJTs)
- Resistor biasing networks
- Multi-stage combinational logic structures
- Carry propagation circuitry
- Control signal routing

The design avoids high-level digital IC abstraction and instead builds logic functionality directly from transistor switching behavior.

---

# Circuit Operation

The circuit accepts binary input signals along with control lines that determine the required ALU operation.

## Working Principle

1. Input signals are applied to transistor-based logic stages.
2. Control lines activate specific logic paths.
3. Transistor switching behavior determines output logic levels.
4. The carry generation block computes carry output during arithmetic operations.
5. The final output is routed to the output node depending on the selected operation.

### Logic Flow

- AND and OR operations are implemented using transistor switching networks.
- XOR logic is generated using combined transistor stages.
- Addition functionality is achieved through XOR-based sum generation and carry computation.
- The carry output is independently propagated through dedicated transistor logic.

---

# Simulation

The entire design was simulated in **Proteus** to verify:

- Logic correctness
- Output stability
- Proper transistor switching
- Carry generation behavior
- Signal propagation across stages

---

# What I Learned

This project helped me gain practical understanding of:

## Digital Hardware Design
- Low-level implementation of combinational circuits
- Hardware realization of logic functions
- Signal routing and logic optimization

## Transistor-Level Electronics
- BJT switching behavior
- Biasing and resistor selection
- Logic voltage level management

## Circuit Simulation
- Using Proteus for digital hardware verification
- Debugging logic propagation issues
- Analyzing hardware behavior through simulation

## ALU Architecture
- Fundamental structure of arithmetic logic units
- Carry generation mechanisms
- Arithmetic and logic operation selection

---

# Tools Used

- **Proteus Design Suite**
- Digital Logic Design
- Discrete Transistor Circuits

---

# Project Files

| File | Description |
|---|---|
| `1-Bit_ALU.pdsprj` | Proteus project file |
| `README.md` | Project documentation |

---

# Future Improvements

- Expand to a multi-bit ALU architecture
- Add subtraction and comparison operations
- Optimize transistor count
- Implement FPGA-based equivalent design
- Improve propagation delay performance

---

# Author

**Krrish Sanjay Khavnekar**

Electronics Engineering Undergraduate  
Interested in:
- Embedded Systems
- FPGA Design
- VLSI
- Digital Hardware Design
- Robotics
- Analog Electronics

---
