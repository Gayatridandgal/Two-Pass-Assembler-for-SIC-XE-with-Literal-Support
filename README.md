# 2-Pass-Assembler-for-SIC-XE-with-Literal-Support

This project implements a two-pass assembler for the **SIC/XE** architecture, with enhanced handling of **literals**. It generates an object program and object code based on input assembly source code, supporting both Pass 1 and Pass 2 of the assembly process.

---

## Features
- Handles literals and their addressing.
- Supports immediate, indirect, and simple addressing modes.
- Processes BYTE, WORD, RESB, and RESW directives.
- Generates modification records and a complete object program.

---
Two-Pass-Assembler/
pass1.c                     
# Implementation of Pass 1 to generate intermediate files.

pass2.c                     
# Implementation of Pass 2 to generate object code and object program.

pass1_input_code.txt        
# Source code input for Pass 1.

pass1_optab.txt             
# Opcode table for instruction lookup.

pass1_symtab.txt            
# Symbol table generated during Pass 1.

pass1_littab.txt            
# Literal table generated during Pass 1.

pass1_intermediate_code.txt 
# Intermediate code output from Pass 1, used by Pass 2.

pass2_object_code.txt       
# Object code with detailed addresses and instructions.

pass2_object_program.txt    
# Final object program in SIC/XE format.

README.md                   
# Documentation for setup and usage of the assembler.






