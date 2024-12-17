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

![Screenshot 2024-12-17 112509](https://github.com/user-attachments/assets/558e1e52-7c1e-4db8-8219-e3a4f475e54b)


**Procedure**

**Full Adder:**
1.Open Quartus II and create a new project.
2.Use schematic design entry to draw the full adder circuit. 
3.The circuit consists of XOR, AND, and OR gates. 
4.Compile the design, verify its functionality through simulation. 
5.Implement the design on the target device and program it.

**Full Subtractor:** 
1.Follow the same steps as for the full adder. 
2.Draw the full subtractor circuit using schematic design. 
3.The circuit includes XOR, AND, OR gates to perform subtraction. 
4.Compile, simulate, implement, and program the design similarly to the full adder.




**Program:**

![Screenshot 2024-12-17 112645](https://github.com/user-attachments/assets/a6f955d9-6655-4abc-b90e-541b00b49f2c)

![Screenshot 2024-12-17 112541](https://github.com/user-attachments/assets/728b3446-086e-40e5-93a7-46a47346ef1b)






/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by:kavibharathi.k

RegisterNumber: 24900829
*/

**RTL Schematic**

![Screenshot 2024-12-17 113925](https://github.com/user-attachments/assets/2202b3ca-c673-4dc7-9ef1-271c19c9338d)
![image](https://github.com/user-attachments/assets/9f14363c-6d71-4dba-93d5-0f0f4fd74b5d)





**Output Timing Waveform**
![Screenshot 2024-12-17 111449](https://github.com/user-attachments/assets/38ebaf32-b0a4-4f32-9f7b-f1e8796e540e)
![Screenshot 2024-12-17 112128](https://github.com/user-attachments/assets/7e15c5c6-750c-4140-97b6-467ed9ccbc72)




**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



