# -ARITHMETIC-LOGIC-UNIT-ALU-

**COMPANY**: CODTECH IT SOLUTIONS PVT.LTD

**NAME** :SAMYAK MANOJ PATIL

**INTERN ID** :CT06MVO

**DOMAIN** :VLSI

**BATCH DURATIOIN** :January 15th, 2025 to February 15th, 2025

**MENTOR NAME** :NEELA SANTHOSH KUMAR

**DESCRIPTION** :
 # BASIC INFORMATION:
 
ALU stands for Arithmetic and Logical Unit which performs Arithmetic functions like Addition, subtraction, division, etc. it also performs logical commands such as AND , OR & NOt operations .The ALU is a digital circuit inside the CPU that has the capacity to perform billions of operations per second. The ALU in the computer performs arithmetic and logical operations as part of the CPU, and as commanded by the Control Unit.ALU is a fundamental building block of a computer's central processing unit .

# ALU design:
 1)The ALU created supports a 4-bit input and an output result.

 2)The program selects the operation based on a control signal (CS)

 3)Operations include: addition, subtraction, AND, OR, and NOT.

# Applications of ALU**:

ALUs are often used in combination with other components like:
   1) Multipliers and Dividers for more complex operations.
    
   2)Shift Registers for shift operations.
    
   3)Control Units that manage the operation selection (opcode) for the ALU.

# Sources used :
YouTube links: 
https://youtu.be/SlAL_iGgG08?si=l-X3BaJSEoBqJ006
https://youtu.be/H_aoaQYgKT8?si=lNWmhAjGOtR28CnU
https://youtu.be/s24hrgZ8LAM?si=zb0U82tRzswARSRE

Websites used:
circuitcove.com

AI used : 
chat GPT

# Output Generation :
Test Case 1: Addition (4 + 8)

  Inputs: A = 0100 (4), B = 1000 (8), opcode = 000 (Addition)
  Operation: A + B = 4 + 8 = 12, which is 1100 in binary.
  Carry Out: No carry, so carry_out = 0.
  Zero Flag: Since the result is 1100, which is not zero, zero_flag = 0.

Test Case 2: Subtraction (4 - 8)

  Inputs: A = 0100 (4), B = 1000 (8), opcode = 001 (Subtraction)
  Operation: A - B = 4 - 8 = -4 i.e. 8-bit two's complement, which is 1100 in binary.
  Carry Out: No carry beyond 4 bits, so carry_out = 0. ( if 8 bit carry =1)
  Zero Flag: Since the result is 1100, which is not zero, zero_flag = 0.

Test Case 3: AND (4 & 8)

  Inputs: A =  0100 (4), B = 1000 (8), opcode = 010 (AND)
  Operation: A & B = 0100 & 1000 = 0000, which is 0000 in binary.
  Carry Out: No carry, so carry_out = 0.
  Zero Flag: Since the result is 0000, which is not zero, zero_flag = 0.

Test Case 4: OR (4 | 8)

  Inputs: A = 0100 (4), B = 1000 (8), opcode = 011 (OR)
  Operation: A | B = 0101 | 0011 = 1100, which is 1100 in binary.
  Carry Out: No carry, so carry_out = 0.
  Zero Flag: Since the result is 1100, which is not zero, zero_flag = 0.

Test Case 5: NOT (~4)

  Inputs: A = 0100 (4), opcode = 100 (NOT)
  Operation: ~A = ~0100 = 1011, which is 1011 in binary (bitwise NOT operation).
  Carry Out: No carry, so carry_out = 0.
  Zero Flag: Since the result is 1011, which is not zero, zero_flag = 0 

 **OUTPUT OF THE TASK** :<img width="959" alt="Image" src="https://github.com/user-attachments/assets/630af111-f4c0-4f0b-8fb3-928767747114" />

**Conclusion** :

  In this mini project, we have successfully designed and implemented a 4-bit Arithmetic and Logic Unit (ALU) capable of performing basic arithmetic and logical operations, including addition, subtraction, AND, OR, and NOT. The ALU design was based on a control signal (CU) that selects the operation to be performed, with each operation tested through different test cases. 
  
  This ALU is a fundamental building block in digital systems and plays a vital role in the functionality of CPUs. By understanding and implementing the ALU, we gain insight into the internal operations of processors, enabling the design of more sophisticated and efficient computational systems.
  
  The project was supported by multiple learning resources and tools, such as YouTube tutorials, websites, and AI-based assistance. This project was successfully executed in Modelsim app and the ouput was shown via waveforms of different input and outputs
