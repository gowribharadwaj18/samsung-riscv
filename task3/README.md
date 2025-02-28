 Understanding RISC-V and Its Instruction Formats

### About RISC-V:
RISC-V is an open-source Instruction Set Architecture (ISA) rooted in RISC principles, designed to optimize processors for specific applications.

- As the fifth generation of RISC-based ISAs, RISC-V offers a flexible, free alternative to proprietary processor technologies.
- With its open and license-free nature, RISC-V empowers developers to create customized processors without the burden of licensing fees.
- RISC-V’s open-source model fosters innovation and broadens the hardware development ecosystem, making it a compelling choice for modern processor design.

# RISC-V Instruction Analysis  

Reviewed the **RISC-V software documentation** to gain a comprehensive understanding of the **R, I, S, B, U, and J** instruction formats. These formats define the structure of different types of **RISC-V instructions** and how their **opcode, function codes, and register fields** are arranged within a **32-bit instruction word**.  

After understanding these formats, I analyzed the **riscv-objdump** output of my application code to extract **15 unique RISC-V instructions**. For each of these instructions, I carefully examined their **binary representation** and determined their exact **32-bit instruction codes** according to their respective instruction formats.  

## Process Involved:  

1. **Identifying the opcode, function fields, and register operands** for each instruction.  
2. **Matching each instruction** to its respective format (**R, I, S, B, U, or J**).  
3. **Decoding the 32-bit binary representation** to understand how different fields are structured within each instruction.  


