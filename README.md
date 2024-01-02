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
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Revanth Palagiri

RegisterNumber:  23002622
program:module mod(sum, carry,a,b);
input a,b;
output sum, carry;
xor sum1 (sum, a,b);
and carry1 (carry,a,b);
endmodule


Logic symbol & Truthtable:
![Image 2024-01-02 at 21 15 41_dfb9263d](https://github.com/Revanth-2717/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152462274/5dd7d208-b0b2-4b2a-9d8e-9044f80006aa)

RTL realization:
![Image 2024-01-02 at 21 17 08_8b64f175](https://github.com/Revanth-2717/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152462274/beed8d69-2587-428b-b846-ee5d83654edf)
Truth table:
![Image 2024-01-02 at 21 18 16_5dde1386](https://github.com/Revanth-2717/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152462274/4e37d1e4-c6ce-480c-bca2-2b3348b6caf8)

### Output:
### RTL
### TIMING DIAGRAM


### TRUTH TABLE 

### Result:
