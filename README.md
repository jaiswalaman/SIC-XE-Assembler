# SIC-XE-Assembler-
The Objective of the project is to implement a version of two-pass SIC/XE assembler: Pass 1 and Pass 2.
The Assembler we implemented includes all the SIC/XE instructions and supports all four formats 1, 2, 3, 4, addressing modes and program relocation.
It also supports all the machine independent features-
1.	Literals
2.	Symbol Defining Statements 
3.	Expressions
4.	Program Blocks
5.	Control Sections and Program Linking

Input to assembler- Assembler source program using the instruction set of SIC/XE.
Output- Assembler will generate the following files as output-
1.	Pass 1 will generate a Symbol Table.
2.	Pass 1 will also generate Intermediate File for the Pass 2.
3.	Pass 2 will generate a listing file containing the input assembly code and address, block number, object code of each instruction.
4.	Pass 2 will also generate an object program including following type of record: H, D, R, T, M and E types.
5.	An error file is also generated displaying the errors in the assembly program (if any).
6.  A file including symbol table,literal table and table for External definition and External reference is also generated.

Steps to compile and run the program:-
1.run compile.sh script using command ./compile.sh
2.It will  generate an object file named assembler.out in the current directory ,move the assembler.out in the INPUT folder.
3.cd to INPUT folder  and run assembler.out file using ./assembler.out.
4.type the input file name to generate the object file.
