# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![Screenshot 2025-04-23 224714](https://github.com/user-attachments/assets/953d8141-8e6f-49a4-817b-31218720aadd)
![Screenshot 2025-04-23 224755](https://github.com/user-attachments/assets/85614149-4c4c-482f-a88a-cae8ef96079b)

**Procedure**

Write the detailed procedure here

**Program:**
![Screenshot 2025-04-23 224854](https://github.com/user-attachments/assets/0d7c2248-f734-4dcb-a75d-5193400bd767)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: KATHI HASINI  RegisterNumber:212224240074
*/

**RTL Schematic**
![Screenshot 2025-04-23 224948](https://github.com/user-attachments/assets/576c9ff1-bbdd-48ec-8319-dabfcc65f8fd)


**Output Timing Waveform**
![Screenshot 2025-04-23 225458](https://github.com/user-attachments/assets/504540ea-27cc-4315-af06-111525fb4369)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



