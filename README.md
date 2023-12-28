# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

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
### Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
## Developed by: Harini.N
## RegisterNumber:212223050019  
*
### 1.program to design a half adder:
![image](https://github.com/Hariniselvan21/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155089072/4d0b8b42-9d87-48f1-a24e-c645f61e0a54)

### 1.program to design a full adder:
![image](https://github.com/Hariniselvan21/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155089072/6bf3e2e7-f37e-4adf-954d-92575ea498c4)

### Output:
### RTL realization:
### HALF ADDER:
![image](https://github.com/Hariniselvan21/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155089072/15ddef19-b2da-4857-a648-c75eeb573de9)

### FULL ADDER:
![image](https://github.com/Hariniselvan21/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155089072/5d5c4fe2-ebb5-406a-a53c-f569577aa1f7)

### TIMING DIAGRAM
### HALF ADDER:
![image](https://github.com/Hariniselvan21/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155089072/a5d270be-d687-47e8-ab66-550a89eee50c)

### FULL ADDER:
![image](https://github.com/Hariniselvan21/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155089072/90936974-8ba6-461f-870f-f171311439cb)

### TRUTH TABLE:
### HALF ADDER:
![image](https://github.com/Hariniselvan21/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155089072/e4f4cdb5-006a-4c99-b167-bdc350bfc145)

### FULL ADDER
![image](https://github.com/Hariniselvan21/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155089072/672e5cc5-8b0f-4d36-aad8-2ef28bed595b)

### Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.
