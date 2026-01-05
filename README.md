# Compiler-Construction-Lab-2025-26

## Overview
This repository contains practical programs for the **Compiler Construction Lab**, developed using **Lex/Flex** and **Yacc/Bison**. These programs demonstrate fundamental concepts of **lexical analysis, syntax analysis, parsing, and intermediate code generation**.
These programs help to understand **how a compiler processes source code step by step**, from tokenization to parsing and code generation.

---

## Tools Required
- **C Compiler** (e.g., GCC)
- **Lex/Flex**
- **Yacc/Bison**
- Terminal/Command Line Interface

---

## List of Practicals

| Practical | Description |
|-----------|-------------|
| **Number Word to Digit Converter** | Converts English words (`zero` to `ten`) to numeric digits using Lex. |
| **Arithmetic Expression Intermediate Code Generator** | Generates 3-address code for arithmetic expressions using Lex & Yacc. |
| **Lexical Analyzer for Keywords and Identifiers** | Counts keywords, identifiers, lines, comments, and spaces in C-like code. |
| **Words Starting with ‘A’ Counter** | Counts words that begin with the letter 'A' in the input. |
| **Case Conversion Program** | Converts lowercase letters to uppercase and vice versa. |
| **Decimal to Hexadecimal Converter** | Converts decimal numbers to hexadecimal using Lex. |
| **Lines Ending with 'com' Detector** | Checks if input lines end with 'com'. |
| **Postfix Expression Evaluator** | Evaluates arithmetic expressions in postfix notation using Lex & Yacc. |
| **Infix Expression Calculator** | Evaluates arithmetic expressions in infix notation with proper operator precedence. |
| **For Loop Syntax Validator** | Validates the syntax of C-style for loops using Lex & Yacc. |

---

## How to Run
1. Install **Flex** and **Bison** on your system.  
2. Open the terminal in the folder containing the program files.  
3. Compile Lex & Yacc files:
   ```bash
   flex program.l        # generates lex.yy.c
   bison -d program.y    # generates program.tab.c and program.tab.h
   gcc lex.yy.c program.tab.c -o program -ll -ly
