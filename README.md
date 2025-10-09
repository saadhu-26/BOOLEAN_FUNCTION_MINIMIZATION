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
<img width="720" height="968" alt="image" src="https://github.com/user-attachments/assets/3d88591c-ef97-4ecc-af40-db9f8d010c65" /><br>
<img width="684" height="710" alt="image" src="https://github.com/user-attachments/assets/8ae68595-5075-4e82-89dc-432f48071fe5" /><br>
<img width="667" height="658" alt="image" src="https://github.com/user-attachments/assets/a6c06489-6bfe-417f-a621-eff79082a722" /><br>
<img width="669" height="318" alt="image" src="https://github.com/user-attachments/assets/4f0e92a9-cee7-4833-b3c4-121a4c31fda6" /><br>
**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/
<br>25018432<br>
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
endmodule<br>
**RTL realization** <br>

**Output:** <br>
<img width="643" height="699" alt="image" src="https://github.com/user-attachments/assets/bd381781-70a0-47b8-8e9c-12e6b4474774" /><br>
**RTL**

**Timing Diagram**<br>
<img width="717" height="572" alt="image" src="https://github.com/user-attachments/assets/62f6747d-9045-42ee-9cf9-7d6c5a5f0150" /><br>

**Result:** <br>
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

