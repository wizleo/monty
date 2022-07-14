In this project we are tasked to create an interpreter for monty ByteCode files. These files will have commands per line to manipulate the data structure given.

What you should learn from this project:
What do LIFO and FIFO mean
What is a stack, and when to use it
What is a queue, and when to use it
What are the common implementations of stacks and queues
What are the most common use cases of stacks and queues
What is the proper way to use global variables
How to work with git submodules

Instructions
Compile with:

gcc -Wall -Werror -Wextra -pedantic *.c -o monty

Files
monty.c
Contains the main function that takes in the file and runs the parser.
monty.h
Header file.
parse.c
Functions that parses the file from main, then parses the lines. While parsing, data is stored into structs to be passed onto other functions.
verify.c
Contains functions that checks arguments from lines of the file. Checks for if push function is in the file line.
match.c
Our get operations function that matches the aruguments with what opcode function we need to run.
opcodes_1.c
Contains push, pall, free_stack, and nop.
opcodes_2.c
Contains pint, pop, swap, pchar, and pstr.
opcodes_3.c
Contains rotl, rotr, qpush.
opcodes_math.c
Contains add, sub, div, mul, mod.
opcodes_mode.c
Contains stack and queue.
