# MIPS-Simulator

This project is a simple simulator for a subset of MIPS instruction set as
defined withinin the textbook ‘Computer Organization and Design: The hardware/Software Interface” 5th
Edition, Patterson and Hennessy

The simulator should read the instructions one by one and execute them. Execution of
the instructions means changing the contents of registers and/or memory. Your
simulator should run the program until the end of the file (executable binary), or until
executing a syscall to exit. 

The simulator should run in one of two different modes. The first line of the binary code
is either 0 or 1. if 0, the simulator simulates the program until the end and then print the
contents of the 32 register $0 - $31. If the first line is 1, the simulator prints the contents
of the 32 registers after it executes any instruction. 

