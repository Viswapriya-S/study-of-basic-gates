### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.  

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:VISWAPRIYA.S RegisterNumber:25018876 
 
**Logic symbol & Truthtable**<img width="572" height="788" alt="Screenshot 2025-10-08 102734" src="https://github.com/user-attachments/assets/1c3ff22e-9616-41fc-9953-56401c714dcb" />
<img width="751" height="768" alt="Screenshot 2025-10-08 102748" src="https://github.com/user-attachments/assets/501d45e2-c900-4da6-8702-fcccde998780" />
<img width="738" height="278" alt="Screenshot 2025-10-08 102758" src="https://github.com/user-attachments/assets/615a7fea-bb1d-4d0b-a930-e427f46d26cc" />


**RTL realization Output:** <img width="416" height="282" alt="Screenshot 2025-10-07 193711" src="https://github.com/user-attachments/assets/afaaa79b-3a62-4d98-8063-2352efc1685b" />


**RTL**<img width="1127" height="381" alt="Screenshot 2025-10-07 193434" src="https://github.com/user-attachments/assets/ce8ca8ea-e487-4787-95b2-0141b0ef9269" />


**Result:**Thus the different digital IC's are studied and the truth table for different logic gates are verified


