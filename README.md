## Thirukumaran.G
## 23010217

## Experiment--03-Half-Subtractor-and-Full-subtractor
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
  ![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png`


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
Write the detailed procedure here 


## Program:
 

## Half subtractor:


![WhatsApp Image 2023-12-18 at 15 49 16_031577e6](https://github.com/23010217/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154016053/dc3623de-8f29-4d3a-8547-bc4ff8b6ab95)

## Full subtractor:


![WhatsApp Image 2023-12-18 at 15 49 16_ac7d35bd](https://github.com/23010217/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154016053/ff455f73-5cd1-4b94-8b13-1cab5a8c389c)


## truth table:


## half subtarctor:

![286511396-8e10cf55-5b1a-4089-b750-49f6acdad175](https://github.com/23010217/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154016053/4ebd1000-21e9-493c-97aa-fce7dff4d71f)







## full subtractor:



![dd4f6c7b-177e-4325-b279-4b661ec0b734](https://github.com/23010217/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154016053/5a261251-f062-4811-9fbf-1b632fcf8b12)




##  RTL realization:



## Half subtractor:


![291159722-c4b05717-c38c-402f-ae56-aab9da4e65d1](https://github.com/23010217/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154016053/d1fa8040-f6ac-4186-ba64-ea05932d00ae)



## Full subtractor:


![c634113c-b4f9-45a3-8d45-c533891d187e](https://github.com/23010217/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154016053/88dc45f1-692e-4929-af90-5bd82fcd6d19)


## Timing diagram:



## Half subtractor:


![286511423-7b10a3ee-8c3b-49a4-88c2-95059ef32a3e](https://github.com/23010217/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154016053/89d79d23-ae51-40bf-b2b9-954e405c12e6)




## Full subtractor:


![ea854b7e-45bd-4699-8d4f-06b431c3dd53](https://github.com/23010217/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/154016053/b6e45c11-e74a-49e5-a07e-2ebad5cfcc7c)






## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
