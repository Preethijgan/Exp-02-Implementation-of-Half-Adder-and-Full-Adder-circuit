# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Preethi Jagan 
RegisterNumber: 23008364  
*/
Logic symbol & Truthtable
RTL realization

### Program

### Half Hadder

![image](https://github.com/Preethijgan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870652/05132f57-c9de-4795-b9fe-9ff036cf9471)

### Full Hadder

![image](https://github.com/Preethijgan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870652/ff1347f2-e11d-450d-a535-c1d05af912ea)

### Truth Table

### Half Hadder

![image](https://github.com/Preethijgan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870652/6cfd9abd-4056-43c5-b4e3-12e65abf8a89)

### Full Hadder

![image](https://github.com/Preethijgan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870652/ec4945e3-e890-4848-8a28-47e5e61477d0)

### RTL Diagram

### Half Hadder

![image](https://github.com/Preethijgan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870652/c9fd586e-4ad0-4f5e-8fd5-d3ca24c84e85)

### Full Hadder

![image](https://github.com/Preethijgan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870652/ab1e7947-de6a-4c0b-beaf-5fa7629e22aa)

### Timing Diagram

### Half Hadder

![image](https://github.com/Preethijgan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870652/985089ba-2bea-49b9-8dcb-5d9d4082502b)

### Full Hadder

![image](https://github.com/Preethijgan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870652/d5804976-bdd4-4f82-b6d5-9ebb39b1e931)

### Result:

Thus, the half adder and full adder circuits are designed and the truth tables is verified using quartus software.
