This project will require you to implement cycle-accurate simulators of a 32-bit RISC-V processor in C++ or
 Python. The skeleton code for the assignment is given in le (NYU_RV32I_6913.cpp or
 NYU_RV32I_6913.py).
 The simulators should take in two les as inputs: imem.text and dmem.txt les
 The simulator should give out the following:
 ● cycle by cycle state of the register le (RFOutput.txt)
 ● Cycle by cycle microarchitectural state of the machine (StateResult.txt)
 ● Resulting dmem data after the execution of the program (DmemResult.txt)
 The imem.txt le is used to initialize the instruction memory and the dmem.txt le is used to initialize the
 data memory of the processor. Each line in the les contain a byte of data on the instruction or the data
 memory and both the instruction and data memory are byte addressable. This means that for a 32 bit
 processor, 4 lines in the imem.txt le makes one instruction. Both instruction and data memory are in
 “Big-Endian” format (the most signi cant byte is stored in the smallest address).
