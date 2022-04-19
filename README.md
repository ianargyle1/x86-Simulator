# x86 Simulator

This code impliments the requirements from assignment 1 of CS 4400 (Computer Systems) of the University of Utah. The objective of this assignment it to implement a simulator for a simplified x86 processor; the task is made easier by supporting only 32-bit ("l") instructions with a machine code representation of instructions fixed to the 32-bit size.

- simulator.c — My solution code.
- instruction.h — This header file provides some useful definitions for representing instructions.
- tests — This directory contains simple, moderate, and complex tests for your simulator.  The tests themselves are machine code programs that your simulator should be able to input and run.
- run_tests.sh — This bash script runs all of the tests and reports the results.
- assembler — This file is a pre-compiled executable that can be used to generate a simulator input machine code file given an assembly file.  (You do not need to use this executable, but it may be useful for testing if you want to modify or write your own assembly test programs.)
