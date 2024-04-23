# Week 1 Overview

## Lesson 1: Introduction to Computer Architecture
### Topic Outline
  - **What is a Computer Architecture?**: Understand the fundamental definition and the scope of what encompasses computer architecture.
  - **Key Building Blocks**: Learn about the basic components that make up computer systems such as CPU, RAM, storage, etc.
  - **Von Neumann Architecture**: Study the basic model of computer design based on a processing unit and a single separate storage structure to hold both data and program.
  - **Relationship between Speed, Complexity, and Electronics**: Explore how these factors influence each other in computer architecture.


## Lesson 2: Deep Dive into Processors
### Topic Outline
  - **What is a Processor and What is Computation?**: Define what a processor does, types of processors, and how computation is handled in computer systems.
  - **Limits of Processor Performance**: Identify barriers to performance and methods to mitigate these barriers.
  - **Processor Instructions**: Understand how instructions are formulated and the basics of how they execute programs.

- **Key Foci**
  - Analyze factors limiting processor performance and strategies used in the industry to enhance performance.
  - Thoroughly understand the nature and role of instructions in a processor.

## Lesson 3: Computer Systems and Their Applications
### Topic Outline
  - **General Purpose vs Application-Specific Computers**: Differentiate between computers designed for general tasks vs. those designed for specific applications.
  - **Mainframes and Supercomputers**: Look into what these are and how they differ from typical consumer-grade computers.
  - **Processor Parallelism**: Study how parallel processing works and its benefits in computation.
  - **Influence of Applications on Processor Technology**: Understand how different applications shape the development of processor technologies.

- **Key Foci**
  - Get insights into the specialized use of computers and how this impacts their architecture.
  - Deepen understanding of high-performance computing systems like mainframes and supercomputers.

---
# Concepts
## Von Neumann Architecture Overview
The Von Neumann Architecture, named after mathematician and physicist John Von Neumann, who first described it in 1945, outlines an approach to computer architecture that forms the basis for most digital computer systems. This architecture is also known as the “Von Neumann model” or “stored-program computer.”

### Key Features
1. **Stored-Program Concept**: One of the central ideas of the Von Neumann Architecture is that both data and programs are stored in the computer's memory in the same address space. This was a revolutionary concept, as earlier computers were programmed using predefined hardware configurations or punch cards.

2. **Components of Von Neumann Architecture**:
   - **Central Processing Unit (CPU)**: Acts as the brain of the computer, executing program instructions and managing the operations of other components. The CPU itself can be divided into two main parts:
     - **Control Unit (CU)**: Directs all the processor's operations. It interprets each instruction in the program and generates the necessary signals to operate the computer.
     - **Arithmetic Logic Unit (ALU)**: Responsible for all arithmetic and logical operations.

   - **Memory**: Stores all the information your computer is actively working on, including program instructions (the code) and the data those instructions will act upon. This architecture uses a single memory seamlessly accessible by all parts of the system.

   - **Input/Output (I/O) Mechanisms**: Include devices that can offer input to the machine (like keyboards, mice, and scanners) and output devices that display or transmit the results of its processing (like monitors, printers, and network cards).

   - **Data Bus**: The system within the architecture that allows data to travel between the aforementioned components, carrying data among the CPU, memory, and peripheral devices.

### Operational Cycle
The operation of a Von Neumann architecture-based system can be described in terms of a cycle:
   1. **Fetch**: The control unit retrieves (fetches) program instructions from the memory unit.
   2. **Decode**: The fetched instruction is then decoded to determine what other parts of the computer need to engage to execute the instruction.
   3. **Execute**: The decoded instruction is sent to the appropriate component (often the ALU) to execute the operation.
   4. **Store**: Results of an execution, if any, are sent back to the memory or an output device.

### Limitations and Implications
- **Von Neumann Bottleneck**: A major limitation identified in this architecture is the bottleneck caused by the single data bus that handles both data and instructions. This setup limits the throughput of the system because the memory cannot keep up with the speed of the CPU, causing the CPU to waste time waiting for data and instructions.

- **Security Concerns**: The shared memory and storage for both data and program instructions can pose security risks, such as various forms of malicious exploits that manipulate the execution of a program.

Despite these limitations, Von Neumann Architecture still underpins the general design of most modern computers, although many enhancements and variations have been developed to address its challenges, such as the introduction of cache memory, multiple cores, and parallel processing techniques.

This architecture has truly shaped the development of computing technology, making it a fundamental study area in computer architecture and engineering.