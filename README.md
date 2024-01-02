# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
# Theory
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
# Program:
/*
#Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
~~~
#Developed by: Dhanusya K
~~~
#RegisterNumber: 23006651 
# HALF ADDER:
![Screenshot 2024-01-02 195255](https://github.com/Dhanu654/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514965/4571a969-d436-4346-a8bb-eb06dc18b929)
# FULL ADDER:
![Screenshot 2024-01-02 195219](https://github.com/Dhanu654/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514965/3b253355-ade2-41ec-a12f-5788a1cd8a3f)

*/
# Logic symbol & Truthtable:
# HALF ADDER CIRCUIT:
![Screenshot 2024-01-02 195351](https://github.com/Dhanu654/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514965/6dd64fb7-2ac5-45b6-a3ae-db61bd9cee9f)
# FULL ADDER CIRCUIT:
![Screenshot 2024-01-02 195337](https://github.com/Dhanu654/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514965/54c70d10-92da-48c6-bc99-e09a45893c77)


# RTL realization:
# Half adder:
![Screenshot 2024-01-02 195235](https://github.com/Dhanu654/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514965/2f49d343-9eda-4762-b06b-fd9441c4a999)
# Full adder:
![Screenshot 2024-01-02 195235](https://github.com/Dhanu654/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514965/23a47742-ff0f-40cb-a15b-40ffd815daf6)

### TIMING DIAGRAM
# HALF ADDER:
![image](https://github.com/Dhanu654/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514965/cc605c0d-027a-415f-9edc-87c93f04baa7)

# FULL ADDER:
![Screenshot 2024-01-02 195523](https://github.com/Dhanu654/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514965/6c2bf331-80c3-45c0-a063-b6c58935039e)


### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
