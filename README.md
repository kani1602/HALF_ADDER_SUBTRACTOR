# EXP3: HALF ADDER AND SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

# AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

# **Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

# **Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

# **Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

# **Truthtable**



![image](https://github.com/user-attachments/assets/d6cb6c4e-7ecc-4567-9b70-db9f23b6e3da)



![image](https://github.com/user-attachments/assets/1b0d4974-e6f6-4551-9518-00fd82a55da8)


# **Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# **Program:**



![Screenshot (19)](https://github.com/user-attachments/assets/434c41a9-298d-4847-974a-2d3d99b9916c)
![Screenshot (20)](https://github.com/user-attachments/assets/a6652948-e6f6-4d51-b813-c2becfd7b630)



/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:kanishka.v   RegisterNumber:24003362

# **RTL Schematic**



![Screenshot (21)](https://github.com/user-attachments/assets/0e19d034-fd15-46ee-a2b8-8c8cc4934fa3)
![Screenshot (22)](https://github.com/user-attachments/assets/8269efbe-bbb3-4f5e-b564-9b37598b6cad)



# **Output/TIMING Waveform**
![Screenshot (23)](https://github.com/user-attachments/assets/30ea3b03-788d-4a14-8da4-1c08c4bca6f3)
![half subtractor](https://github.com/user-attachments/assets/60441f2e-0534-49e3-b40a-7de83668d230)


# **Result:**
 Thus the half adder and half subtractor are studied and the truth table ,logic gates are verified

