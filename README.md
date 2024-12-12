
**NAME: DEVASAHRI S**

**REF NO: 24001806**

# EXPIREMENT NO: 3 HALF ADDER SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**HALF ADDER:**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**HALF SUBTRACTOR:**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**TRUTHTABLE:**

![WhatsApp Image 2024-12-03 at 22 45 42_2836de0e](https://github.com/user-attachments/assets/fe749a8a-a647-4cdb-9fe4-e992b0ae78c4)

**PROCEDURE:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM:**

![Screenshot 2024-12-04 093440](https://github.com/user-attachments/assets/d28f9438-0767-48b6-82b5-8b01919fc90f)


**RTL SCHEMATIC:**
![WhatsApp Image 2024-12-03 at 22 45 42_465c63ae](https://github.com/user-attachments/assets/87332ab7-b73f-4f0f-a660-b8c3ea6e9316)

**OUTPUT/TIMING WAVEFORM:**

![WhatsApp Image 2024-12-03 at 22 45 43_cf10f04d](https://github.com/user-attachments/assets/199a2f58-1792-43b3-bfd5-33d1597052a9)



**RESULT:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
