[https://www.youtube.com/watch?app=desktop&v=Jk7Ul2hKqxs&t=118s]
[https://www.youtube.com/watch?v=Ps0JFsyX2fU]
# ARM vs X86-64 vs RISC-V
- `x86` -> follows CISC CPU design
  - `CISC` -> Complex Instruction Set Computing
  - `closed ISA` Instruction Set Architecture -> Intel and Amd have license
  - complex instructions -> multiple instructions in a single statement
  - can `manipulate memory directly`

- `ARM` -> Advanced RISC Machine -> follows RISC CPU design
  - `RISC` -> Reduced Instructions Set Computing
  - `closed ISA` -> Arm limited has license 
  - simpler instruction set -> power efficiency
  - requires `seperate load and store instructions for memory manipulation`

[https://www.youtube.com/watch?v=9s8hPmCZ0mk]
- `RISC-V` -> follows RISC CPU design
  - `open ISA` -> no license needed
  - at the moment most relevant for embedded - but debian 13 will support it

# General
[https://developer.arm.com/documentation/ddi0602/2024-06/Base-Instructions]
- opcodes -> 8 bit numbers -> represent the mnemonic instructions for the cpu
- syntax dialects
  - Windows	masm
  - Cross-platform	nasm, fasm
  - C/C++	gcc, clang	AT&T

# x86 (AT&T/GAS)
- `Directives` or Pseudo-Op's -> start with .
  - .ascii          -> String
  - .asciz          -> Null-terminated String
  - .byte           -> 1B
  - .hword/.short   -> 2B
  - .int/.long      -> 4B
  - .quad           -> 8B
  - .octa           -> 16B
  - .float/.single  -> Float
  - .double         -> Double Float

- 3 Types of opperands: Immediate, Register, Memory
  - memory, memory  -> not allowed
  - symbol          -> load memory at adress
  - $symbol         -> immediate address (pointer)

[https://c9x.me/x86/]
- instructions
  -suffixes: b, w, l, q

# x86 intel-style
- data declaration
  - in .section .data
    - db, dw, dd, dq, dt
  - in .section .bss
    - resd, resw, resd, resq, rest

# ARM






