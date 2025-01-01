# Two-Pass-Assembler-for-SIC-XE-with-Literal-Support

This project implements a two-pass assembler for the **SIC/XE** architecture, with enhanced handling of **literals**. It generates an object program and object code based on input assembly source code, supporting both Pass 1 and Pass 2 of the assembly process.

---

## Features
- Handles literals and their addressing.
- Supports immediate, indirect, and simple addressing modes.
- Processes BYTE, WORD, RESB, and RESW directives.
- Generates modification records and a complete object program.

---
## Folder Structure
Two-Pass-Assembler/
├── pass1.c                          # Pass 1 implementation
├── pass2.c                          # Pass 2 implementation with literal support
├── pass1_input_code.txt             # Input source code for Pass 1
├── pass1_optab.txt                  # Opcode table for Pass 1
├── pass1_symtab.txt                 # Symbol table output from Pass 1
├── pass1_littab.txt                 # Literal table output from Pass 1
├── pass1_intermediate_code.txt      # Intermediate code output from Pass 1 (input for Pass 2)
├── pass2_object_code.txt            # Generated object code from Pass 2
├── pass2_object_program.txt         # Final object program output from Pass 2
├── README.md                        # Documentation and usage instructions


