### study-of-basic-gates
**DATE:** 12-03-2025

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

 **Developed by:R N Somnath** 
 **RegisterNumber:212224240158** 
 
**Logic symbol & Truthtable**
# Not gate
![image](https://github.com/user-attachments/assets/eed5a6db-293a-441d-a2cf-1b55b9c0b5c1)
# AND GATE
![image](https://github.com/user-attachments/assets/d1fc38db-1354-4e5e-8a1b-dc261c07dbfb)
# OR GATE
![image](https://github.com/user-attachments/assets/a25ab05e-4fee-42ce-80b0-168f0a4b0620)
# NAND GATE
![image](https://github.com/user-attachments/assets/270eaeb9-7252-406f-9b59-06ed964b8f45)
# NOR GATE
![image](https://github.com/user-attachments/assets/ce443822-9809-4211-b21d-c58c30c21076)
# EX-OR GATE
![image](https://github.com/user-attachments/assets/3386f751-7176-4939-a0ad-5333fb42547f)

# EX-NOR GATE
![image](https://github.com/user-attachments/assets/b56f5529-f87d-4b9e-98f1-6f1649555a7f)


**RTL realization Output:**
![Screenshot 2025-03-19 090314](https://github.com/user-attachments/assets/15e4f381-c926-4a81-af8c-44895e0e700f)


**RTL**
![image](https://github.com/user-attachments/assets/3d6c8898-9a72-422f-b374-63b466aaab10)


**Result:**
 Thus the Basic digital ICs and the verification of truth tables for different logic gates were studied and successfully realized using Verilog.

