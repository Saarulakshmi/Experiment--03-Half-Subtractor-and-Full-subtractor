# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:

##half subractor

![exp 4 prg](https://github.com/Saarulakshmi/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155513241/8f24f5a8-d4a2-44b3-a744-c7c2aa63abff)

##full subractor

![exp 4 prg 2](https://github.com/Saarulakshmi/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155513241/ffd89d7c-7a1e-474a-80a3-87d4b9614857)

##rtl

![exp 4 rtl 1](https://github.com/Saarulakshmi/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155513241/4609cf85-3255-4830-b91d-5e8b9ab02609)



![exp 4 rtl 2](https://github.com/Saarulakshmi/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155513241/2f91350c-9f3b-4fa3-ba06-19d70100d3a6)


##truth table


![tt 4 1](https://github.com/Saarulakshmi/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155513241/1aa1dabb-656e-410c-b63a-d8799781eb93)




![tt 4 2](https://github.com/Saarulakshmi/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155513241/3caa1974-307e-47fc-a30d-856c7269ec37)



##output

![op 4 1](https://github.com/Saarulakshmi/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155513241/ddfcd493-c329-4a3a-85f6-3257980b8ffc)



![op 4 2](https://github.com/Saarulakshmi/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/155513241/677be9d6-64f9-45c3-9874-2bc891801473)









/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: saaru lakshmi
RegisterNumber:  23008458
*/



## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
