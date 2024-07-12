# Simple C++ Compiler

## Overview
This project implements a basic C++ compiler capable of analyzing and understanding a simplified subset of C++ code. It focuses on two essential tasks in compiler construction: lexical analysis and syntax analysis.

## Features
- **Tokenization**: The compiler breaks down the input C++ code into meaningful units called tokens. These tokens include reserved words (like `int`, `while`), identifiers (variable names), numbers, strings, and symbols (such as arithmetic operators).
  
- **Parsing**: Once tokens are identified, the compiler verifies the syntax of the code. It constructs a hierarchical structure called a parse tree, which represents the syntactic relationships between different parts of the code. For example, it identifies how statements are organized within functions or loops.

- **Parse Tree Visualization**: The parse tree is then printed to provide a clear visual representation of how the code is structured. This helps in understanding the flow and organization of statements and expressions within the source code.

## Usage
To use the compiler:
1. Input your C++ source code as a string.
2. The compiler processes this string to tokenize the code, identifying and categorizing each part (tokens).
3. It then checks the arrangement of these tokens against the expected syntax rules to ensure correctness.
4. Finally, it generates a parse tree, which can be printed out to visually inspect how different components of the code relate to each other.

## Purpose
This project serves as an educational tool to understand the fundamental steps involved in converting human-readable code into a format that a computer can execute. It emphasizes the importance of structured analysis in ensuring that programs are not only correct but also efficient and maintainable.
