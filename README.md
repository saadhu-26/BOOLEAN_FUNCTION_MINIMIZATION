# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**<br>
<img width="720" height="968" alt="image" src="https://github.com/user-attachments/assets/8efc781c-5350-4345-867b-3f5f04b81047" /><br>
<img width="684" height="710" alt="image" src="https://github.com/user-attachments/assets/09aa0baa-0034-47dd-bf12-96206b7b1827" /><br>
<img width="667" height="658" alt="image" src="https://github.com/user-attachments/assets/a0ceda8a-34e0-439a-b2f1-e7ca47adf1a5" /><br>
<img width="669" height="318" alt="image" src="https://github.com/user-attachments/assets/a5e402ad-3377-4ed2-8a0a-3fb7feb9a402" /><br>
**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/<br>
25018432<br>

MINIMIZATION OF BOOLEAN FUNCTION
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule <br>
**RTL realization**<br>

**Output:** <br>
<img width="643" height="699" alt="image" src="https://github.com/user-attachments/assets/296dd802-4aa5-4a60-a479-23f3bf311601" /><br>
**RTL** <br>

**Timing Diagram** <br>
<img width="717" height="572" alt="image" src="https://github.com/user-attachments/assets/3e5915b2-52b5-44f7-b7a5-45fe839e1ad8" /><br>

**Result:**<br>
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

