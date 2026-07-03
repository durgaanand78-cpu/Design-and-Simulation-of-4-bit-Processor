# Design and Simulation of 4-bit Processor using Verilog HDL

## Project Overview
This project presents the design and simulation of a simple 4-bit processor using Verilog HDL. The processor executes a custom instruction set and performs arithmetic and logical operations using a 4-bit ALU.

## Objective
To design a basic processor architecture and understand the working of digital blocks such as ALU, register file, control unit, program counter, and program memory.

## Main Components
- 4-bit ALU
- Register File
- Control Unit
- Program Counter
- Program Memory
- Instruction Decoder
- Testbench

## Instruction Set
| Opcode | Operation |
|---|---|
| 0000 | Load immediate value to R0 |
| 0001 | Load immediate value to R1 |
| 0010 | Load immediate value to R2 |
| 0011 | Load immediate value to R3 |
| 0100 | Addition: R0 = R0 + R1 |
| 0101 | Subtraction: R0 = R0 - R1 |
| 0110 | AND operation |
| 0111 | OR operation |
| 1000 | XOR operation |
| 1001 | NOT operation |
| 1010 | Shift left |
| 1011 | Shift right |
| 1111 | Halt |

## Tools Used
- Verilog HDL
- EDA Playground
- Icarus Verilog
- EPWave

## Simulation Result
The processor was simulated using EDA Playground. The waveform verifies the operation of the clock, reset, program counter, instruction output, ALU result, and register outputs.

## Conclusion
The 4-bit processor was successfully designed and simulated using Verilog HDL. This project helped in understanding processor architecture, instruction execution, ALU operations, register file design, and waveform-based verification.
