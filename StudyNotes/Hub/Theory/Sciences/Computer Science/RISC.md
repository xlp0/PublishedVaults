---
Aliases: RISC, Reduced Instruction Set Computer
---
#RISC

RISC (Reduced Instruction Set Computer) is a computer architecture design philosophy that emphasizes simplicity and efficiency in instruction execution. It was developed as a response to complex and slower CISC (Complex Instruction Set Computer) architectures.

In RISC architecture, the instruction set is designed to have a small number of simple and basic instructions. These instructions are typically executed in a single clock cycle, which enables faster processing. The goal of RISC is to execute instructions quickly by using a pipeline approach, where each stage of the pipeline performs a specific operation on the instruction.

RISC architecture focuses on the following key principles:

1. Simplicity: The instruction set is kept simple with fewer addressing modes and formats. This reduces the complexity of decoding and executing instructions.

2. Load-store architecture: RISC machines use a load-store architecture, where data must be loaded from memory into registers before any operations can be performed on it. This simplifies instruction decoding and execution.

3. Register-based operations: RISC machines heavily rely on registers for performing operations instead of memory. This reduces memory access time, resulting in faster execution.

4. Fixed-length instructions: Instructions in RISC architectures are typically of fixed length, making them easier to decode and execute quickly.

5. Pipelining: RISC processors often use pipelining techniques to improve performance by allowing multiple instructions to be processed simultaneously in different stages of the pipeline.

6. Compiler optimization: RISC architectures require compilers to optimize code generation for efficient execution by utilizing available registers effectively and minimizing memory access.

Advantages of RISC architecture include improved performance due to simplified instruction execution, reduced power consumption, better compiler optimization opportunities, and easier scalability for future advancements in technology.

However, there are also some limitations of RISC architecture such as increased code size due to simple individual instructions, reliance on compilers for efficient code generation, and potential limitations when executing complex algorithms that require more complex instructions found in CISC architectures.

## What are the more well-known RISC architectures

Some well-known RISC architectures include:

1. [[ARM]] (Advanced RISC Machines) - Widely used in smartphones, tablets, and other embedded devices.
2. MIPS (Microprocessor without Interlocked Pipeline Stages) - Used in various applications such as networking devices, consumer electronics, and gaming consoles.
3. PowerPC - Originally developed by IBM, used in Apple Macintosh computers until 2006 and still in use in some embedded systems.
4. SPARC (Scalable Processor Architecture) - Developed by Sun Microsystems, used primarily in servers and workstations.
5. [[RISC-V]] (RISC Five) - An open-source architecture that is gaining popularity due to its simplicity and flexibility.

These architectures have different features and are optimized for specific applications or target markets.

# Conclusion
Overall, RISC architecture prioritizes simplicity, efficiency, and faster execution of instructions, making it a popular choice for many modern processors and embedded systems.

# References

[[@johncooganThisBritishCompany2023]]