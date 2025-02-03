TASK 1
1. Downloaded "riscv_workshop" file via provided link : https://forgefunder.com/~kunal/riscv_workshop.vdi 
2. Downloaded virtual box to run the vsd_workshop.
3. Specifications of the virtual machine 
       OS Type: Linux  
       OS Version : Ubuntu 18.0.4 LTS (Bionic Beaver) (64bit)
       base memory : 4096mb    Processors : 4
4. Create the virtual machine of "riscv_workshop" and start
5. Open Leafpad compiler and type a simple C program, ex.finding sum of n numbers
6. Compile and run the code 
7. -O1 and -Ofast obj dump

TASK 2

1.Review spike simulation -O1 and Ofast simulation of a program displaying sequence of cube of first 10 numbers

2.Observing the changes in registers for both compilers -O1 and Ofast

TASK 3

Machine codes and its implementations of first 15 instructions of -Ofast compiler
 1. Instruction: 00021537
Operation: lui a0,0x21
- Opcode (7 bits): 0110111
- rd (5 bits): 00010
- Imm[31:12] (20 bits): 0000000000000010

 2. Instruction: fe010113
Operation: addi sp,sp,-32
- Opcode (7 bits): 0010011
- rd (5 bits): 00010
- funct3 (3 bits): 000
- rs1 (5 bits): 00010
- Imm[11:0] (12 bits): 1111111111100000

 3. Instruction: 00200593
Operation: addi a1,zero,2
- Opcode (7 bits): 0010011
- rd (5 bits): 00011
- funct3 (3 bits): 000
- rs1 (5 bits): 00000
- Imm[11:0] (12 bits): 000000000010

 4. Instruction: 32050513
Operation: addi a0,a0,800
- Opcode (7 bits): 0010011
- rd (5 bits): 00010
- funct3 (3 bits): 000
- rs1 (5 bits): 00010
- Imm[11:0] (12 bits): 000000110010

 5. Instruction: 00813823
Operation: sd ra,8(sp)
- Opcode (7 bits): 0100011
- Imm[11:5] (7 bits): 0010000
- rs2 (5 bits): 00001
- rs1 (5 bits): 00010
- funct3 (3 bits): 011
- Imm[4:0] (5 bits): 00000

 6. Instruction: 00913423
Operation: sd s1,24(sp)
- Opcode (7 bits): 0100011
- Imm[11:5] (7 bits): 0010001
- rs2 (5 bits): 00010
- rs1 (5 bits): 00010
- funct3 (3 bits): 011
- Imm[4:0] (5 bits): 10000

 7. Instruction: 01213023
Operation: sd s0,16(sp)
- Opcode (7 bits): 0100011
- Imm[11:5] (7 bits): 0010010
- rs2 (5 bits): 00000
- rs1 (5 bits): 00010
- funct3 (3 bits): 011
- Imm[4:0] (5 bits): 00000

 8. Instruction: 00113c23
Operation: sd sp,8(sp)
- Opcode (7 bits): 0100011
- Imm[11:5] (7 bits): 0010011
- rs2 (5 bits): 00011
- rs1 (5 bits): 00011
- funct3 (3 bits): 011
- Imm[4:0] (5 bits): 11000

 9. Instruction: 00100413
Operation: addi s0,zero,1
- Opcode (7 bits): 0010011
- rd (5 bits): 01000
- funct3 (3 bits): 000
- rs1 (5 bits): 00000
- Imm[11:0] (12 bits): 000000000001

 10. Instruction: 3ac000ef
Operation: jal ra,940
- Opcode (7 bits): 1101111
- rd (5 bits): 00001
- Imm[19:12] (8 bits): 11101010
- Imm[11] (1 bit): 1
- Imm[10:1] (10 bits): 10111100
- Imm[20] (1 bit): 0

 11. Instruction: 00021937
Operation: lui sp,2
- Opcode (7 bits): 0110111
- rd (5 bits): 00011
- Imm[31:12] (20 bits): 0000000000000010

 12. Instruction: 00600493
Operation: addi s1,zero,6
- Opcode (7 bits): 0010011
- rd (5 bits): 01001
- funct3 (3 bits): 000
- rs1 (5 bits): 00000
- Imm[11:0] (12 bits): 000000000110

 13. Instruction: 00040593
Operation: addi a1,s0,0
- Opcode (7 bits): 0010011
- rd (5 bits): 00011
- funct3 (3 bits): 000
- rs1 (5 bits): 00000
- Imm[11:0] (12 bits): 000000000000

 14. Instruction: 00040513
Operation: addi a0,s0,0
- Opcode (7 bits): 0010011
- rd (5 bits): 00010
- funct3 (3 bits): 000
- rs1 (5 bits): 00000
- Imm[11:0] (12 bits): 000000000000

 15. Instruction: 11c000ef
Operation: jal ra,pc+0x11c
- Opcode (7 bits): 1101111
- rd (5 bits): 00001
- Imm[19:12] (8 bits): 11101011
- Imm[11] (1 bit): 1
- Imm[10:1] (10 bits): 10111100
- Imm[20] (1 bit): 0
