# miniCPU
<img width="1264" alt="Screenshot 2024-04-11 at 9 46 07 PM" src="https://github.com/kayvandharsee/Mini-Mips_CPU_Project/assets/135669229/379f7eba-d1e3-4426-9929-b32790412229">

### Overview
This repository contains my Mini-MIPS CPU project for the COMP 273 course at McGill University. The goal of this project is to design and implement a simplified version of a MIPS CPU using Logisim Evolution. My Mini-MIPS executes only one instruction per CPU execution cycle, simplifying the architecture while retaining the essence of the MIPS pipeline CPU. This project was undertaken by a team of 2, adhering to the guidelines specified for such teams.

### Project Details
- Course: COMP 273
- Institution: McGill University
- Date for Completion: April 14, 2024
- Team Members: Kayvan Dharsee, Alex Groiser

### Objective
The main objectives of this project are:

- To understand the functioning of Pipeline CPUs.
- To familiarize ourselves with wiring instructions as microcode.
- To comprehend how the Control Unit coordinates the different machines that make up the CPU.

### Implementation
Our Mini-MIPS CPU is built using Logisim Evolution and follows the pipeline CPU architecture closely. The CPU is capable of executing a set of predefined instructions, including LOAD, SAVE, ADD, SUB, and HALT, with all data represented as nibbles (4-bits). Although it resembles a pipeline CPU in its four-stage process, it is akin to a classical CPU in terms of executing instructions atomically.

### Components
For this project, the following components were implemented:

- A clock.
- The Program Counter which points to the next instruction.
- The Instruction Register which stores the current instruction.
- The Register Block with General Registers R0 and R1.
- The Control Unit (CU) that controls everything inside the CPU.
- The ALU that performs arithmetic and logical operations.
- The Status Register to monitor the outcome of the ALU
- Instruction RAM that stores 8 nibbles of data.
- Data RAM that stores 2 nibbles of data.

### Execution
Our CPU circuit is capable of executing algorithms that involve loading two numbers, performing an ALU operation, and then saving the solution. Additionally, it can handle a program that contains only the HALT instruction.

### Acknowledgements
I would like to thank Professor Vybihal and the teaching assistants of the COMP 273 course for their guidance and support throughout this project. Out of respect for the course, I will not be sharing the code of this project publicly. Please message me to see the code.

