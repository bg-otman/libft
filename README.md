# libft.a

## Overview

libft.a is a custom static library that contains a variety of functions written in C. These functions include both re-implementations of existing standard C library functions as well as additional utility functions not present in the standard library. This project was created to deepen the understanding of C programming concepts and to provide a set of tools that can be used across various projects.

## Purpose

The purpose of libft.a is to build a foundational set of functions that can be reused in future C projects. By creating these functions from scratch, I developed a better understanding of how the C standard library operates and how to handle common programming challenges such as memory management, string manipulation, and error handling.

## Compilation

To compile the libft.a library, you can run the provided Makefile:
```bash
make
```
This will generate the libft.a file. Use make clean to remove object files and make fclean to remove the library as well.

## Usage

To use libft.a in your project:

1. Include the libft.h header file in your C source files:
```c
  #include "libft.h"
```
2. Link the libft.a library during the compilation of your project:
```bash
    gcc -o my_program my_program.c -L. -lft
```

## Testing

The library was tested using various test suites and custom test cases to ensure the correctness of each function. Additionally, I used the libftTester by Tripouille to confirm that my implementations meet expected standards.
Contributing

this project was initially created as part of my learning journey, contributions and suggestions are welcome. Feel free to open issues or submit pull requests if you find any potential improvements.

Special thanks to _**@1337 coding school**_ for providing the opportunity to work on this project as part of my programming development.
