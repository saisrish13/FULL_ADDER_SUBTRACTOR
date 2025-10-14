<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/dfb5dcad-545a-435f-ad00-a021e5efaaa2" /># FULL_ADDER_SUBTRACTOR

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

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
<img width="911" height="352" alt="FULL ADDER RTL VIEWER 1" src="https://github.com/user-attachments/assets/b23a3565-4471-4e31-bf80-242c4469e59d" />
<img width="862" height="356" alt="LOGIC DIAGRAM FULL SUBTRACTOR" src="https://github.com/user-attachments/assets/92dedd85-4531-48fa-b95f-c4db32b431b5" />



**Output Timing Waveform**
<img width="1137" height="152" alt="FULL ADDER STATE DIAGRAM" src="https://github.com/user-attachments/assets/e1462517-e080-49c9-87cb-54c42a6b41fb" />
<img width="1142" height="141" alt="FULL SUBTRACTOR STATE DIAGRAM" src="https://github.com/user-attachments/assets/53efece5-d177-4716-bc11-dad599b369b9" />


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



