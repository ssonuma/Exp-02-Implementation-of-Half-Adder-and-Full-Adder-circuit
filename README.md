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
### 
Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: SONU S
RegisterNumber:  23005566

## CODING:
### HALF ADDER:
![Exp3 ha code](https://github.com/ssonuma/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150653312/3d0daae4-7d29-4ab8-950c-2e8e4cb48742)
### FULL ADDER:
![Exp3 fa code](https://github.com/ssonuma/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150653312/742fa16c-32aa-4e38-8123-c48a6efc48b0)



### Output:
### RTL:
### HALF ADDER:
![Exp3 ha RTL diagram](https://github.com/ssonuma/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150653312/595854cf-028e-4ebb-bd95-ec6dd8dcf2cb)

### FULL ADDER:
![Exp3 fa RTL diagram](https://github.com/ssonuma/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150653312/243a1b15-260d-464c-b7a3-8a01c6eda4f3)

### TIMING DIAGRAM:
### HALF ADDER:
![exp3 ha wave](https://github.com/ssonuma/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150653312/a53cfe26-0dfd-4195-9aa5-3e760a86e343)

### FULL ADDER:
![exp 3 fa wave](https://github.com/ssonuma/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150653312/d6d0d031-2208-4e7d-a696-9a4c3d7beed2)

### TRUTH TABLE:
### HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/ssonuma/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150653312/d538364b-7c1c-4955-978b-06f13d8881ef)

### FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/ssonuma/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150653312/4b9f2884-c349-4abc-8218-0bf7a1897e98)

### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming.
