# Recursive Descent Disassembler (x86 – Educational Project)

This project is a Python-based recursive descent disassembler created as part of a university course on binary analysis and reverse engineering.

## Overview
The goal of this project was to incrementally build an x86 disassembler capable of:
- Parsing raw binary input
- Decoding instructions byte-by-byte
- Handling ModRM and SIB addressing modes
- Managing instruction state and control flow
- Gracefully handling malformed or incomplete binaries

The project evolved through multiple iterations as requirements became clearer, requiring frequent refactoring and refinement of instruction parsing logic.

## What This Demonstrates
- Low-level binary parsing
- State management and pointer tracking
- Understanding of x86 instruction encoding
- Debugging complex, ambiguous specifications
- Iterative problem-solving and refinement

## Notes
This is an educational project and not intended to replace production disassembly tools (e.g., Capstone). The focus was on understanding how disassemblers work internally.
