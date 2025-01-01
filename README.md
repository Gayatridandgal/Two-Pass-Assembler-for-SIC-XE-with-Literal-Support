# 2-Pass-Assembler-for-SIC-XE-with-Literal-Support

This project implements a two-pass assembler for the **SIC/XE** architecture, with enhanced handling of **literals**. It generates an object program and object code based on input assembly source code, supporting both Pass 1 and Pass 2 of the assembly process.

---

## Features
- Handles literals and their addressing.
- Supports immediate, indirect, and simple addressing modes.
- Processes BYTE, WORD, RESB, and RESW directives.
- Generates modification records and a complete object program.

---
## Folder Structure  

Two-Pass-Assembler/ │ ├── pass1.c
├── pass2.c
├── pass1_input_code.txt
├── pass1_optab.txt
├── pass1_symtab.txt
├── pass1_littab.txt
├── pass1_intermediate_code.txt
├── pass2_object_code.txt
├── pass2_object_program.txt
├── README.md







