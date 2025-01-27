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
### Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:SUMAN.G

RegisterNumber:23014256
# Half Adder
![image](https://github.com/sumanguna/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146914442/6a95a978-f915-4e9c-b4bc-d0eae66e77bc)
# Full Adder
![image](https://github.com/sumanguna/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146914442/3eb001f0-e1d4-4e13-beeb-88140c49a02f)



Logic symbol & Truthtable
RTL realization

### Output:
### RTL
# Half Adder
![Screenshot 2023-12-04 115712](https://github.com/sumanguna/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146914442/d12dc2d0-5c1a-4858-883b-006ed5c81330)

# Full Adder
![Screenshot 2023-12-04 115734](https://github.com/sumanguna/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146914442/3c65a4f5-1cd8-4949-be0d-9e3a6ed197bb)

### TIMING DIAGRAM
# Half Adder
![Screenshot 2023-12-04 115758](https://github.com/sumanguna/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146914442/d3535443-9e2a-457d-abad-7ec968737ab9)

# Full Adder
![Screenshot 2023-12-04 115814](https://github.com/sumanguna/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146914442/c4fa8f14-fbdb-4329-ae3c-623b14f3bbf7)

### TRUTH TABLE 
# Half Adder
![Screenshot 2023-12-04 115829](https://github.com/sumanguna/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146914442/122771ad-9a09-446f-8f8d-efdcb7d14f6b)

# Full Adder
![Screenshot 2023-12-04 115839](https://github.com/sumanguna/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/146914442/ed4b614a-73df-4cfd-ba57-afc1f16f9321)

### Result:
       Thus, the half adder and full adder circuits are designed and the truth tables is verified using quartus software.
