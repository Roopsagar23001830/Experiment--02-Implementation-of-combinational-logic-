# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming. F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D F2=xy’z+x’y’z+w’xy+wx’y+wxy
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 
/*Developed by: ROOP SAGAR S L
RegisterNumber:  212223040175

## Logic Diagram
## Procedure
## Program:

module exp2(a,b,c,d,f1);
input a,b,c,d;
output f1;
wire x1,x2,x3,x4,x5;
assign x1=(~a)&(~b)&(~c)&(~d);
assign x2=(a)&(~c)&(~d);
assign x3=(~b)&(c)&(~d);
assign x4=(~a)&(b)&(c)&(d);
assign x5=(b)&(~c)&(d);
assign f1=x1|x2|x3|x4|x5;
endmodule

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

*/
Truthtable :

![Screenshot 2023-12-25 133949](https://github.com/Roopsagar23001830/Experiment--02-Implementation-of-combinational-logic-/assets/145972515/87b6ab2a-0204-4d5f-9834-dc70ae7a4916)

## RTL
## RTL realization

![Screenshot 2023-12-25 132252](https://github.com/Roopsagar23001830/Experiment--02-Implementation-of-combinational-logic-/assets/145972515/7186a427-735a-43c6-95c9-dd3640fce2d6)

## Output:

![Screenshot 2023-12-25 132550](https://github.com/Roopsagar23001830/Experiment--02-Implementation-of-combinational-logic-/assets/145972515/ae2b98ab-31d0-4e7c-b797-b14574cde812)

## Timing Diagram
## Result:
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
