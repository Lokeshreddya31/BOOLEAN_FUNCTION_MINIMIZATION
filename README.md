# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Lokesh reddy A
RegisterNumber:212223040104

## program
## module combinationalcircuit(A,B,C,D,F1);
## input A,B,C,D;
## output F1;
## wire x1,x2,x3,x4,x5;
## assign x1=(~A)&(~B)&(~C)&(~D);
## assign x2=(A)&(~C)&(~D);
## assign x3=(~B)&(C)&(~D);
## assign x4=(~A)&(B)&(C)&(D);
## assign x5=(B)&(~C)&(D);
## assign F1=x1|x2|x3|x4|x5;
## endmodule 


## RTL realization
![Screenshot 2024-03-22 134043](https://github.com/Lokeshreddya31/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870682/57edece0-d380-4eb4-b5a9-2f3bf3e00b50)

## Truth table
![Screenshot 2024-03-22 134053](https://github.com/Lokeshreddya31/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870682/fa14206b-e5b1-4ce5-8196-ca3abd951b40)

## Timing Diagram
![Screenshot 2024-03-22 134101](https://github.com/Lokeshreddya31/BOOLEAN_FUNCTION_MINIMIZATION/assets/144870682/b33adc48-94c5-480d-9a52-5beab9b2a569)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

