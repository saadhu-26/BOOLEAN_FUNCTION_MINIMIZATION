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
<img width="720" height="968" alt="image" src="https://github.com/user-attachments/assets/ceaa617a-d36a-4a87-9cfc-ecd3aa2866be" /><br>
<img width="684" height="710" alt="image" src="https://github.com/user-attachments/assets/4040a22c-060e-48b8-a068-98f4f6764723" /><br>
<img width="667" height="658" alt="image" src="https://github.com/user-attachments/assets/4560e444-4ce9-495d-951c-8877c4c7cb0b" /><br>
<img width="669" height="318" alt="image" src="https://github.com/user-attachments/assets/1057bbc1-39b3-433d-a281-08a87bd0a271" /><br>
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
MINIMIZATION OF BOOLEAN FUNCTION<br>
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
<br>
ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule<br>

**Output:** <br>
<img width="643" height="699" alt="image" src="https://github.com/user-attachments/assets/bf9b6a0c-4d65-4618-b18e-76231f510590" /><br>

**Timing Diagram**<br>
<img width="717" height="572" alt="image" src="https://github.com/user-attachments/assets/da22ed3b-4c27-479b-a4a6-ef780782f142" /><br>

**Result:**<br>

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

